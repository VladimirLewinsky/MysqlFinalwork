1. Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека)

cat > HomePets.txt
cat > AnotherPets.txt 
cat HomePets.txt AnotherPets.txt >> HumanFriends.txt
![image](https://github.com/user-attachments/assets/021abf11-6698-479a-8deb-9117df005d48)

2. Создать директорию, переместить файл туда

mkdir FinalWork
mv HumanFriends.txt ./FinalWork
![image](https://github.com/user-attachments/assets/fc297523-3e51-4c20-adc6-1f74172bf7f7)

3. Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.

sudo apt-install mysql-server
![image](https://github.com/user-attachments/assets/917d5b2b-3ba2-44c8-8214-8ad93e9a5139)

![image](https://github.com/user-attachments/assets/e111a348-01d4-40ae-913d-eed37a2e2981)
sudo wget название пакета 
sudo dpkg -i название пакета

4.Установить и удалить deb-пакет с помощью dpkg.
sudo dpkg -i название пакета
![image](https://github.com/user-attachments/assets/ac15449e-fbd0-4dda-a04f-3a6aa0562cdd)

sudo dpkg -r cromium

5.Выложить историю команд в терминале ubuntu
history 50

![image](https://github.com/user-attachments/assets/ae8fe709-e363-4388-a90a-64e4b97851bb)

6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).
![Диаграмма](https://github.com/user-attachments/assets/a699c80d-3585-4765-b552-cf858eee9f94)

7. В подключенном MySQL репозитории создать базу данных “Друзья
человека”
CREATE_DATABASE Human_friends;

8.Создать таблицы с иерархией из диаграммы в БД
![image](https://github.com/user-attachments/assets/d64d7c87-b8c1-4c7f-8eec-429acfc1d1ce)

9.Заполнить низкоуровневые таблицы именами(животных), командами которые они выполняют и датами рождения
![image](https://github.com/user-attachments/assets/d5a3b1ff-de60-4ae4-b883-361a12ac4263)
![image](https://github.com/user-attachments/assets/c805ba7e-0cb3-4c3e-9574-d92188d68e7e)

10.Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.
![image](https://github.com/user-attachments/assets/9c700e89-fa6c-4797-97ee-cd483d9669c3)

11.Создать новую таблицу “молодые животные” в которую попадут все животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице

![image](https://github.com/user-attachments/assets/e8f63db8-b532-4b1b-b82f-21a43cba5141)

12.Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.
![image](https://github.com/user-attachments/assets/a21c40cd-2d33-4900-851c-7851cbc28cab)


13. Создать класс с Инкапсуляцией методов и наследованием по диаграмме.
Classes








