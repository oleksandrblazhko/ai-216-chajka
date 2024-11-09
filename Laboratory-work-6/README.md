##Основи операційного керування процесами в Unix-подібних ОС
###Перезавантажити віртуальну ОС та перейти до роботи Boot Loader GRUB

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.2.1.jpg)

###Для одного з пінктів меню «Advanced options for Ubuntu» змінити параметри конфігурації, які дозволяють запустити ОС з підключенням розділу диску в режимі запису (Read Write) в єдиному терміналі з оболонкою bash.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.2.2.jpg)

###Перезавантажити GRUB та дочекатися завершення завантаження віртуальної ОС на рівні single user та безпарольного підключення до терміналу від імені користувача root 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.2.3.jpg)

###У командному рядку виконати команду passwd зміни пароля користувача root на будь-який пароль. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.2.4.jpg)

###Отримати ієрархію процесів у вигляді дерева, враховуючи наступне: 
	імена користувачів, які запустили процеси; 
	PID процесів. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.1.jpg)

###Отримати на екран назви запущених процесів ОС.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.2.jpg)

###Отримати таблицю процесів, враховуючи наступне (за необхідністю використати утиліту sed): 
	процеси запущені від імені вашого користувача; 
	таблиця процесів має розширений набір стовпчиків;

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.3.jpg)

###Отримати таблицю процесів, враховуючи наступне (за необхідністю використати утиліту grep):  
таблиця процесів містить лише стовпчики: TTY, USER, PID, STIME, CMD

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.4.jpg)

###Отримати таблицю процесів, враховуючи наступне (за необхідністю 
використати утиліту grep): 
	процеси знаходяться у стані сну; 
	процеси не мають псевдотерміналу. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.5.jpg)

###Використовуючи команду TOP, отримати список процесів, відсортованих за % використання оперативної пам’яті.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.6.jpg)

###Встановити у віртуальній ОС утиліту HTOP.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.7.jpg)

###Представити перегляд процесів з використанням дерева виклику (Tree), використовуючи утиліту HTOP.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.3.8.jpg)

###У поточному (1-му) псевдотерміналі виконати команду ping localhost у фоновому режимі.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.1.jpg)

###Запустити 2-й псевдотермінал роботи із віртуальною ОС.

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.2.jpg)

###У 2-му псевдотерміналі: 
	для команди ping отримати таблицю її процесу (стовпчики PID, STAT, CMD); 
	призупинити виконання процесу команди ping; 
	переглянути процес призупиненої команди, враховуючи background-режим; 
	отримати таблицю процесу команди ping; 
	відновити виконання призупиненого процесу ping. 
	остаточно завершити роботу процесу команди ping. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.3.1.jpg)

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.3.2.jpg)

###У 1-му псевдотерміналі запустити команду ping localhost у режимі «background without hanging up». 
У другому псевдотерміналі для команди ping отримати таблицю її процесу (стовпчики PID, PPID, TTY, STAT, CMD) для вашого поточного користувача. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.4.jpg)

###Закрити перший псевдотермінал. 
У 2-му псевдотерміналі для команди ping отримати таблицю її процесу (стовпчики PID, PPID, TTY, STAT, CMD) для вашого поточного користувача. 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.4.5.jpg)
