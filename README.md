# Итоговая работа по блоку специализация

<a href="task/Итоговая%20аттестация.pdf" target="_blank">Файл задания</a>

# Ход выполнения

## Linux

### Задание 1 
Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).

Создание файлов

![](test/image1.png)
![](test/image8.png)
![](test/image9.png)

Объединение, переименование файлов

![](more_image/image30.png)


### Задание 2

Создать директорию, переместить файл туда. 

![](test/image3.png)
![](test/image4.png)
![](test/image5.png)
![](test/image7.png)

### Задание 3 

Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.

![](test/image4.png)

### Задание 4

Установить и удалить deb-пакет с помощью dpkg. 

![](test/image5.png)

### Задание 5

Выложить историю команд в терминале ubuntu

![](test/image6.png)

### Задание 6 

Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).

![](image/img_007.png)

### Задание 6

В подключенном MySQL репозитории создать базу данных “Друзья
человека”

![](image/img_008.png)

![](image/img_009.png)

### Задание 8

Создать таблицы с иерархией из диаграммы в БД

![](image/img_010.png)

![](image/img_011.png)

<a href="data/Animals.SQL" target="_blank">SQL дамп создания БД</a>.

### Задание 9

Заполнить низкоуровневые таблицы именами(животных), командами
которые они выполняют и датами рождения

![](image/img_012.png)

![](image/img_013.png)


### Задание 10

Удалить из таблицы верблюдов, т.к. верблюдов решили перевезти в другой
питомник на зимовку. 

```sql
DELETE FROM camel;
```

![](image/img_014.png)

Объединить таблицы лошади, и ослы в одну таблицу.

![](image/img_015.png)

### Задача 11

Создать новую таблицу “молодые животные” в которую попадут все
животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью
до месяца подсчитать возраст животных в новой таблице

![](image/img_016.png)

![](image/img_017.png)

![](image/img_018.png)

### Задача 12

Объединить все таблицы в одну, при этом сохраняя поля, указывающие на
прошлую принадлежность к старым таблицам.

![](image/img_019.png)

## Программная реализация

Скриншоты выполнения

![](image/img_020.png)

![](image/img_021.png)

![](image/img_022.png)

![](image/img_023.png)
