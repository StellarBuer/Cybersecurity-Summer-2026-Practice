Juice Shop solution

Перший етап знайти посилання до score-board у доступному нам коді через консоль розробника
<img width="2230" height="1022" alt="image" src="https://github.com/user-attachments/assets/0d2b025c-bc31-49ac-889f-17261e2bc05d" />

DOM-XSS
Можливий XSS через те що сервер надсилає нам тіж дані які ми йому на діслали без філтрів чи пеервірок
<img width="2238" height="896" alt="image" src="https://github.com/user-attachments/assets/b7c34001-2f42-40b9-aef9-9fb9d4c803f7" />

Ще один XSS у якому відбувається перехід на інший сайт за завантажним нами посиланням
<img width="2213" height="786" alt="image" src="https://github.com/user-attachments/assets/80a65031-749f-4609-a056-eba15edcb47d" />

Пошук можливо прихованих папок через перебір
<img width="1762" height="1092" alt="image" src="https://github.com/user-attachments/assets/ef58fc8b-0975-4d9f-96eb-cab635bdcfe1" />

Наприклад папка FTP
<img width="1853" height="737" alt="image" src="https://github.com/user-attachments/assets/91a87a8f-803b-4aa8-80fc-3c42d927e4a5" />

Але у папці є достуа лише до файлів типу .md та .pdf
<img width="2161" height="830" alt="image" src="https://github.com/user-attachments/assets/3b4d73e2-feeb-4228-955b-5fa820d60291" />

Додаюч до кінця файлу %2500.md або .pdf можна отримати до нього доступ
<img width="1872" height="977" alt="image" src="https://github.com/user-attachments/assets/27940450-9c06-4aca-969f-e69d48bb9499" />

Далі використовуючи SQL ін'єкцію можна потрапити на акаунт адміна
<img width="1740" height="1052" alt="image" src="https://github.com/user-attachments/assets/fdfc669c-7150-418e-8c6f-b963bb1b71ad" />
<img width="1398" height="1025" alt="image" src="https://github.com/user-attachments/assets/da2c4530-cfc9-454c-ae5d-4e81124be854" />
