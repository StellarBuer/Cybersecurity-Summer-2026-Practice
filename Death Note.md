Death Note

За допомогою netdiscover шукаємо віртульну машину
<img width="1337" height="548" alt="image" src="https://github.com/user-attachments/assets/50551d74-ff55-4fbc-b252-3beb612a13e8" />
<img width="845" height="367" alt="image" src="https://github.com/user-attachments/assets/2d14fc58-2451-4b47-a425-307fb3638f05" />
MAC-address : 08:00:27:c2:bc:08 імовірно належить потрібній віртуальній машині

За допомогою nmap скануємо відкриті порти
<img width="1197" height="511" alt="image" src="https://github.com/user-attachments/assets/cdc4aefa-c5af-476e-b173-7e4621bc388b" />

Потрапляємо на сайт 
<img width="2192" height="1250" alt="image" src="https://github.com/user-attachments/assets/2f01980f-232e-4137-9b9d-02c2f033d029" />

Декілька шляхів знайдених через dirsearch
<img width="1267" height="848" alt="image" src="https://github.com/user-attachments/assets/179f1491-5896-42b5-a780-cb55a8b10e26" />

У robots.txt
<img width="1402" height="412" alt="image" src="https://github.com/user-attachments/assets/8f3da21e-9799-4f27-ba50-aa524f8901f0" />

За цим шляхом знаходиться
<img width="1347" height="452" alt="image" src="https://github.com/user-attachments/assets/15dfa82e-5927-4a97-9600-8f43d9455efc" />

У підказках кажуть знайти notes.txt
На сайті у папках wp-content/uploads присутні ці два файли
<img width="1908" height="1190" alt="image" src="https://github.com/user-attachments/assets/9df5a0b1-2a2e-4bfc-b402-a0106710f3fe" />

Запускаю брутфорс на ssh
<img width="1932" height="742" alt="image" src="https://github.com/user-attachments/assets/d4370bd9-be3e-4ec3-86de-4edbe9ef58df" />

З'єднуюся за знайденим паролем через ssh
<img width="1530" height="750" alt="image" src="https://github.com/user-attachments/assets/9e23909c-d28c-4d72-bd14-fa65394fa4f8" />

Присутній файл 
<img width="2270" height="621" alt="image" src="https://github.com/user-attachments/assets/d0942172-d544-4fad-ac32-9d07e152d768" />
декодовуючи з brain#uck: i think u got the shell , but you wont be able to kill me -kira

Знайдені файли з 'kira'
<img width="1470" height="367" alt="image" src="https://github.com/user-attachments/assets/746bcf54-6540-4ec9-8369-c3145ceeec51" />

Ось знайдене
<img width="1168" height="838" alt="image" src="https://github.com/user-attachments/assets/4b0995a9-347c-4f97-8dbc-64c4dddef847" />
<img width="1013" height="517" alt="image" src="https://github.com/user-attachments/assets/44a4ca62-2a71-45d5-9a0c-2f896212770f" />

Знаходжу файл та декодую
<img width="2087" height="950" alt="image" src="https://github.com/user-attachments/assets/0649ba08-467b-476c-baff-57d98f257860" />
![Uploading image.png…]()

Захожу під користувача kira та від його імені перехожу до root папки
![Uploading image.png…]()
 
Завдання виконане
