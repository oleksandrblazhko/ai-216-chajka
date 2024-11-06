##Основи керування файлами у файловій системі Unixподібних ОС

Встановити програмне забезпечення Oracle VM Virtual Box

Отримати з інтернету ISO-образ для 32-бітної ОС Server Linux Ubuntu 14.04.6.

Створити віртуальну машину, використовуючи графічний інтерфейс та враховуючи наступні значення параметрів: 
	назва = «Linux of Surname», де Surname – ваше прізвище транслітерацією, наприклад 
«Linux of Blazhko»; 
	файл ISO-образу = ubuntu-14.04.6-server-i386.iso; 
	розмір оперативної пам’яті (Мб) = 10 * group +  var, де group – номер вашої групи, 
var – номер вашого варіанту, наприклад, 10 * 221 + 5 = 2215 Мб; 
	кількість ядер процесору = 1; 
	розмір жорсткого диску (Мб) = 40 * group, наприклад, 40 * 221 = 8840 Мб = 8,84 Гб;

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.1.1.jpg)

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.1.2.jpg)

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.1.3.jpg)

Запустити віртуальну машину, створену у пункті 2.1.3, та виконати інсталяцію віртуальної ОС, враховуючи параметри: 
	hostname = os-surname, наприклад, os-blazhko; 
	user account = surname, наприклад, blazhko; 
	time zone = Kiev; 
	Software = OpenSSH server;

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.4.jpg)

Після інсталяції та перезапуску віртуальної машини виконати вхід до віртуальної ОС, використовуючи створений обліковий запис.

Отримати значення мережевої IP-адреси віртуальної ОС

В програмі Oracle VM Virtual Box для запущенної віртуальної машини додати правило Port Forwarding на першу мережеву карту, яке буде перенаправляти мережеві пакети для з’єднання через SSH-протокол із guest-ОС (IP-address=10.0.2.15, SSH-port=22) на IPадресу=127.0.0.1 з використанням SSH-port=1234

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.5.jpg)

Запустити псевдотермінал Git Bash та перевірити наявність мережевого з`єднання між host-ОС та guest-ОС з віртуальною ОС Linux, яка має мережеву адресу з IP = 127.0.0.1

Встановити з’єднання з віртуальної ОС через SSH-протокол

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.1.8.jpg)

###Основи керування віртуальними ОС

Створити ще одну віртуальну машину, використовуючи інтерфейс командного 
рядку та враховуючи наступні значення параметрів: 
	назва = «Linux of Surname 2», де Surname – ваше прізвище транслітерацією, 
наприклад «Linux of Blazhko»; 
	розмір оперативної пам’яті (Мб) = 10 * group +  var, де group – номер вашої групи, 
var – номер вашого варіанту, наприклад, 10 * 221 + 5 = 2215 Мб; 
	кількість ядер процесору = 1; 
	розмір оперативної пам’яті графічної карти (Мб) = 100 + group2, останні дві цифри 
номеру групи, наприклад, 100 + 21 = 121 Мб; 
	перша мережева карта з конфігурацією NAT; 
	правило Port Forwarding на першу мережеву карту, яке буде перенаправляти мережеві пакети для взаємодії через SSH-протокол між guest-ОС (IP-address=10.0.2.15, SSHport=22) та host-ОС (IP-адреса=127.0.0.1, SSH-port=1234); 
	контролер IntelAHCI з інтерфейсом sata-типу за назвою SurnameSATA, Surname – ваше прізвище транслітерацією, наприклад «BlazhkoSATA»; 
	контролер PIIX4 з інтерфейсом ide-типу за назвою SurnameIDE, де Surname – ваше прізвище транслітерацією, наприклад «BlazhkoIDE»; 
	віртуальне сховище даних, розміщене у файлі з назвою DiskSurname.vdi, наприклад, 
DiskBlazhko.vdi, та розміром (Мб) = 40 * group, наприклад, 40 * 221 = 8840 Мб; 
	ISO-файл ubuntu-14.04.6-server-i386.iso з інсталяцією ОС Linux 

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.2.1.1.jpg)

![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.2.1.jpg)

Перебуваючи на першому екрані процесу інсталяції віртуальної ОС, призупинити роботу віртуальної машини.
Повторно запустити призупинену віртуальну машину,
Зупинити віртуальну машину
Зняти з реєстрації віртуальну машину та видалити всі пов’язані з нею файли. 


![image](https://github.com/oleksandrblazhko/ai-216-chajka/blob/Laboratory-work-5/Laboratory-work-5/2.2.2.jpg)
