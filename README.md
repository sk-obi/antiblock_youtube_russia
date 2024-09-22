# antiblock_youtube_russia
Обход блокировок youtube в России


Используемая инфраструтктура:

1. роутер Xiaomi Роутер Mi 4С - https://www.ozon.ru/product/xiaomi-router-mi-router-4c-179052675/?asb=zNMJJSfEBnzPjSD1kUeP2kiqZfKBHpMJ%252Fvv64GdW6R4%253D&asb2=xvcOh1iki42p_uZ4mDc-aHGBqNaLuE_Wj5dTamO8ZcQV4CoMT6btJzy3tOi3Oqvh&avtc=1&avte=1&avts=1727012234&keywords=xiaomi+4css,
на прошивке OpenWRT OpenWrt 23.05.4
2. VDS в России на Debian 11 (либо сервер в домашней сети с белым ip)
3. VDS за границей на Debian 11


Установка OpenWRT на роутер:

Нам потребуется тачка на Linux в домашней сети 

1. Скачать https://github.com/acecilia/OpenWRTInvasion
2. Перейти в скачанную директорию и выполнить установку
# pip3 install -r requirements.txt
3. Запустить скрипт
# python3 remote_command_execution_vulnerability.py
Спросит ip роутера и его сток 
![image](https://github.com/user-attachments/assets/f7eceb0f-ed8e-4eab-9b5f-a0d897368a0e)
