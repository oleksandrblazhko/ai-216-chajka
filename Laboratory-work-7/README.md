## Основи керування файлами у файловій системі Unix-подібних ОС

### Скопіювати 5-ть файлів на віддалений Linux-сервер до каталогу «Laboratorywork-7» Git-репозиторія, враховуючи наступні типи по одному файлу: 
	текстовий файл, наприклад README.md; 
	текстовий html-файл, наприклад, index.html; 
	бінарний pdf-файл з вашим WebAR-буклетом; 
	будь-який бінарний файл-зображення; 
	будь-який бінарний аудіо-файл. 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.2.2.jpg)
### Знаходячись на віддаленому Linux-серверу, перейти до каталогу «Laboratory-work-7», в якому вже знаходяться 5-ть скопійованих раніше файлів
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.2.3.jpg)
### Для кожного із вказаних файлів виконайте команду визначення їх типів.
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.2.6.jpg)
### Для 	html-файлу 	створити 	два 	жорсткі 	зв`язки 	з 	назвами транслітація_вашого_прізвища + hard_link_1, транслітація_вашого_прізвища +  hard_link_2, наприклад, Blazhko_hard_link_1 та Blazhko_hard_link_2
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-6/Laboratory-work-6/2.2.1.jpg)
### Для 	html-файлу 	створити 	файл 	символічного 	зв`язку 	з 	назвою транслітація_вашого_прізвища + sym_link_1, наприклад, Blazhko_sym_link_1 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.2.7.jpg)
### Переглянути повноваження доступу до створених файлів жорсткого та символічного зв`язків. 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.3.1.jpg)
### Надати 	символьні 	повноваження 	доступу 	до 	файлу 	з 	назвою транслітація_вашого_прізвища + hard_link_1: 
	варіант взяти зі стовпчика «Повноваження доступу 1» таблиці 6; 
	у таблиці вказано лише повноваження, які необхідно встановити, та не вказано повноваження, які необхідно зняти; 
	тип файлу не повинен протирічити визначеним повноваженням, наприклад, якщо використовується звичайний текстовий файл, тоді він не може мати повноваження на виконання; 
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.3.2.jpg)
### Надати числові десяткові повноваження доступу до файлу з назвою транслітація_вашого_прізвища + hard_link_2: 
	варіант взяти зі стовпчика «Повноваження доступу 2» таблиці 6; 
	у таблиці вказано лише повноваження, які необхідно встановити, та не вказано повноваження, які необхідно зняти; 
	тип файлу не повинен протирічити визначеним правам, наприклад, якщо використовується звичайний текстовий файл, тоді він не може мати повноваження на виконання; 

### Створити новий каталог з назвою «Dark Directory» та скопіювати до каталогу один текстовий файл
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.3.4.jpg)
### Перетворити каталог «Dark Directory» на «темний» каталог, виконавши відповідні команди зміни повноважень доступу до цього каталогу.
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.3.5.jpg)
### Отримати на екран список файлів «темного» каталогу. Для «темного» каталогу ця операція повинна завершитися помилкою
![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-7/Laboratory-work-7/2.3.6.jpg)
