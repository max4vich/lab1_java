# Lab1_Java

Створіть клас згідно вашого варіанту з списку нижче З використанням бібліотеки lombok слід реалізувати set і get методи, конструктори з аргументами, конструктор по замочуванню та перевизначений метод toString() Написаний клас має містити публічний статичний метод getInstance(), та поле статичне поле instance, значення якого буде повертати метод getInstance В класі також слід наисати main метод, в якому слід сворити масив об'єктів класу з використанням:

конструктора по замовчуванню
конструктора, який отримує всі параметри
2 обєкти, отримані при виклику методу getInstance
Вивести в консоль ідентифікатори всіх об'єктів з масиву з використанням циклу з передумовою

Задача лабораторної має міститись у пакеті ua.lviv.iot.algo.part1.lab1 Реалізацію задачі слід розмістити в репозиторії Github. Для цього слід створити окрему гілку (branch), додати ваші класи (commit, push) та створити Pull Request Важливо: при створенні репозиторію в Github слід вибрати .gitignore для мови Java Післі додавання коду в репозиторій варто переконатись, що у реопзиторії знаходяться лише ваш файл з реалізацією (файл з розширенням java) Файл лабораторної роботи має міститись у папці ua/lviv/iot/algo/part1/lab1, яка відповідає назві пакету Написаний код має відповідати прийнятим вимогам у мові Java (Java code conventions)

Створіть клас Plate, який буде мати наступні поля: diameter: діаметр тарілки; material: матеріал, з якого виготовлена тарілка; color: колір тарілки; isClean: прапорець, що позначає чи є тарілка чистою, по замовчуванню значення "false". hasFood: прапорець, що позначає чи є на тарілці їжа, по замовчуванню значення "false"

Клас Plate має мати такі публічні методи: wash(): метод, який миє тарілку та встановлює прапорець isClean в значення "true"; dirty(): метод, який позначає тарілку як брудну (встановлює прапорець isClean в значення "false"); eat(): метод, який скидає прапорець hasFood та позначає тарілку, як брудну addFood(): метод, який встановлює прапорець hasFood у значення true
