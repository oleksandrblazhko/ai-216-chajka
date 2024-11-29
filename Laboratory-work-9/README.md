## Основи використання скриптової мови інтерпретатору оболонки командного рядку Unix-подібних ОС

### Створити скрипт-файл на скриптовій мові програмування Bash з назвою за шаблоном Прізвище транслітерацією + osparam, наприклад, blazhkoosparam.sh, який виводить на екран лише окремі дані про параметри поточного стану ОС з віртуальної файлової системи Procfs (подробиці у лабораторній роботі №7) у відповідності із варіантом, представленим у стовпчику «Параметр пам`яті або процесору»  таблиці 3
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-9/Laboratory-work-9/2.1.1.jpg)
### Створити скрипт-файл на скриптовій мові програмування Bash: 
	my_create_empty_file – створити порожній файл (команда touch файл); 
	my_create_file – створити файл через перенаправлення (команда echo “” > файл); 
	my_create_slink  – створити символічний зв’язок (команда ln –s файл файл-зв’язок); 
	my_create_hlink  – створити жорсткий зв’язок (команда ln файл файл-зв’язок); 
	my_create_directory – створити каталог (команда mkdir каталог); 
	my_change_directory – змінити назву каталогу (команда mv каталог1 каталог2); 
	my_change_file – змінити назву файлу (команда mv файл1 файл2); 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-9/Laboratory-work-9/2.2.1.jpg)
### Створити скрипт-файл на скриптовій мові програмування Bash з назвою за шаблоном Прізвище транслітерацією + osobjectgenerator, наприклад, blazhkoosgenerator.sh, який у циклі for автоматично створить (30+n) об’єктів ОС у відповідності із варіантом таблиці 4 (n – номер варіанту)
користувач 	user 	файл /etc/passwd 	1,5
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-9/Laboratory-work-9/2.3.1.jpg)
### Використовуючи утиліту AWK та відповідні команди одного командного рядку, обробити потік даних у відповідності із варіантом таблиці 4:
користувач 	user 	файл /etc/passwd 	1,5.
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-9/Laboratory-work-9/2.4.1.jpg)
