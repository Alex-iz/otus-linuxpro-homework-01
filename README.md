# otus-linuxpro-homework-01
Курс "Administrator Linux. Professional". Домашнее задание №1.

Версия ядра после установки ОС:

Команда
uname -r

Ответ
6.8.0-79-generic

<img width="192" height="64" alt="image" src="https://github.com/user-attachments/assets/988e5e79-8019-4b05-86a9-948811913f77" />

Скачал файлы:

Источник
https://kernel.ubuntu.com/mainline/v6.17-rc6/amd64/

Команды
wget https://kernel.ubuntu.com/mainline/v6.17-rc6/amd64/linux-headers-6.17.0-061700rc6-generic_6.17.0-061700rc6.202509142238_amd64.deb
wget https://kernel.ubuntu.com/mainline/v6.17-rc6/amd64/linux-headers-6.17.0-061700rc6_6.17.0-061700rc6.202509142238_all.deb
wget https://kernel.ubuntu.com/mainline/v6.17-rc6/amd64/linux-image-unsigned-6.17.0-061700rc6-generic_6.17.0-061700rc6.202509142238_amd64.deb
wget https://kernel.ubuntu.com/mainline/v6.17-rc6/amd64/linux-modules-6.17.0-061700rc6-generic_6.17.0-061700rc6.202509142238_amd64.deb

<img width="1236" height="832" alt="image" src="https://github.com/user-attachments/assets/ff8eb4a6-3a7f-4d73-93e3-9bd64ef7afca" />

Проверил наличие скаченных файлов:

<img width="977" height="513" alt="image" src="https://github.com/user-attachments/assets/6425b095-1886-446a-b563-fafc8eb6c01e" />

Установил скаченные пакеты

Команда
sudo dpkg -i linux-headers* linux-image* linux-modules*


<img width="891" height="580" alt="image" src="https://github.com/user-attachments/assets/a9d020d7-227f-4ebf-99ba-9b068012593e" />
