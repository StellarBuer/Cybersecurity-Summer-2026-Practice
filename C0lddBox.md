C0lddBox challange

ip адреса пристрою 192.168.62.239
<img width="1107" height="762" alt="image" src="https://github.com/user-attachments/assets/a255996d-7b78-424d-b8a8-3e33a215110a" />

Сканую відкриті порти за допомогою nmap
<img width="950" height="478" alt="image" src="https://github.com/user-attachments/assets/beb7a809-4982-49d9-be83-bda9b84b3e01" />

На 80 порту запущений веб сервер
<img width="1641" height="708" alt="Знімок екрана 2026-07-25 090235" src="https://github.com/user-attachments/assets/99e19536-157b-4a81-99a5-d90db2119aa8" />

Знайдені доступні шляхи
<img width="1015" height="535" alt="Знімок екрана 2026-07-25 090755" src="https://github.com/user-attachments/assets/3a70160a-4e05-4be5-b409-5848e35ad15a" />
<img width="1063" height="508" alt="image" src="https://github.com/user-attachments/assets/27f4e853-3691-4ecf-92c0-75fb7a700a80" />
<img width="1798" height="277" alt="image" src="https://github.com/user-attachments/assets/0d712a32-5b13-4dea-a343-06641025767b" />
Можна припустити що Hugo c0ldd, hugo, philip - логіни

Результати wp-scan
<img width="1040" height="627" alt="image" src="https://github.com/user-attachments/assets/1763e1ff-be40-454b-8602-d0da1425eb60" />
<img width="1061" height="712" alt="image" src="https://github.com/user-attachments/assets/499a4519-360e-4cb6-b216-c5b2dcc2cc94" />
Знайдений пароль до c0ldd - 9876543210

Входимо в акаунт, в реадкторі змінюємо футер для впровадження реверс-шелу,редагуємо код реверс шелу підставляючи свою адресу та порт для слухання
<img width="1602" height="767" alt="image" src="https://github.com/user-attachments/assets/f1ed4437-e8ed-49b4-b8e7-71517751d424" />

Прослуховуєсо признаачений порт, налаштовуєсо нормальну оболонку
<img width="1147" height="315" alt="image" src="https://github.com/user-attachments/assets/a4cd7d8c-895e-4e29-a838-737df93d9512" />


Знаходимо логін пароль якогось користувача від бд можливо вони існує користувач системи з такимиж параметрами
<img width="1090" height="775" alt="image" src="https://github.com/user-attachments/assets/cd12e22f-5efb-4c1d-a2e7-8fd31880d737" />

Шукаємо файли даного користувача та його доступи
<img width="1050" height="582" alt="image" src="https://github.com/user-attachments/assets/e91cb50f-dc63-46bc-8353-b772874edd99" />

Використання chmod для отримання файла 
<img width="1108" height="763" alt="image" src="https://github.com/user-attachments/assets/e197d507-78d7-4b29-b659-10b5d8b9b4b5" />

Отримання root-шелу задопомогою vim -c '!/bin/bash'
<img width="780" height="327" alt="image" src="https://github.com/user-attachments/assets/36288473-c9bf-4976-85e0-9b306f674521" />







