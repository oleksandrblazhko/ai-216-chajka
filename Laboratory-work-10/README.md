## Основи програмного керування процесами в Unix-подібних ОС

### Створити C-програму з назвою за шаблоном «ваше прізвище_process_info.c», наприклад, blazhko_process_info.c яка виводить на екран таку інформацію: 
	ідентифікатор групи процесів, до якої належить процес; 
	ідентифікатор процесу, що викликав цю функцію; 
	ідентифікатор parent-процесу; 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-10/Laboratory-work-10/2.1.1.jpg)
### Запустити дві копії програми у двох режимах за прикладами з рисунку 4
	паралельне виконання двох процесів;  конвеєрне виконання двох процесів
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-10/Laboratory-work-10/2.1.2.jpg)
### Створити C-програму, яка породжує процес та замінює образ процесу на команду у відповідності із варіантом з таблиці 3. Назва програми повинна співпадати з назвою команди з таблиці 3, але з додатком у вигляді транслітерації вашого прізвища, наприклад, touch_blazhko.c
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-10/Laboratory-work-10/2.2.1.jpg)
### Створити C-програму з назвою «ваше прізвище_get_signal», в якій процес очікує отримання сигналу SIGUSR2 та виводить повідомлення типу «Process of Students` Surname got signal» після отримання сигналу, де  замість слова Students` Surname в повідомленні повинно бути ваше прізвище в транслітерації.  

### Скомпілювати програму та запустити її. 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-10/Laboratory-work-10/2.3.1.jpg)
