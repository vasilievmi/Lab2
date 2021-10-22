# lab3

![питон](https://static.tildacdn.com/tild3665-3161-4135-b731-356635633937/s1200.jpg)
## Python tasks in linux compiler
### TASK 1

    d = 4; print (d); #вывод значения

4
***
### TASK 2

    print ('Васильев Марат Ильдарович\nР20Б1\n31.07.2002');

Васильев Марат Ильдарович

Р20Б1

31.07.2002
***
### TASK 3
    print ('Город рождения - Астрахань\nДостопримечательности:Астраханский кремль\nНабережная Волги\nБелая мечеть')

Город рождения - Астрахань

Достопримечательности:Астраханский кремль

Набережная Волги

Белая мечеть
***
### TASK 4
    print ('22 июня 1941 года'); 
    print('ЯПОНИЯ,США,СССР,ГЕРМАНИЯ,ВЕЛИКОБРИТАНИЯ'); 
    print (); 
    print ('9 мая 1945 года\nСтрана победитель - СССР');

22 июня 1941 года

ЯПОНИЯ,США,СССР,ГЕРМАНИЯ,ВЕЛИКОБРИТАНИЯ

9 мая 1945 года

Страна победитель - СССР
***
### TASK 5
    print ('Как вы относитесь ко 2 учебной смене?:'); 
    t = input()

Как вы относитесь ко 2 учебной смене?:
Положительно
***
### TASK 6
    j = input(); 
    print (':))')


:))
***
### TASK 7
    print ('Физ-ра\tОПД\tМатанализ\n5\t4\t5')

Физ-ра ОПД Матанализ
5       4       5
***
### TASK 8
    a = ('Стас'); 
    b = ('Умар'); 
    c = ('Кирилл'); 
    print ('Я', a , b, c, 'любим играть в Genshin Impact')

Я Стас Умар Кирилл любим играть в Genshin Impact
***
### TASK 9
    orange_stocks = 1051; 
    print ('Запасы апельсин на складе -', orange_stocks)

Запасы апельсин на складе - 1051
***
## Writing a script using linux,python and vim
    apt install python3.8 
    cd/home
    touch hel.py
    vim hel.py

>IN VIM: press i to go to insert mode
>then add code : 
    print ('22 июня 1941 года'); 
    print ('ЯПОНИЯ,США,СССР,ГЕРМАНИЯ,ВЕЛИКОБРИТАНИЯ');
    print ();print ('9 мая 1945 года');
    print ('Страна победитель - СССР')
>then press *esc* button, type **:wq** and press *enter* to save script.
    
    chmod 777 hel.py
    python 3.8 hel.py
