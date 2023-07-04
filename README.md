# Итоговое задание по модулю Е6


Проект состоит из клиента на JavaScript и бэкенда на Django Rest Framework, обмен информацией через WebSocket.

Реализован базовый мессенжер со следующими функциями:

Отправка и получение сообщений;
Создание, редактирование и удаление групповых чатов и переписка в них (управление чатами по REST API,
а переписка так же, как в обычных чатах, но с использованием на сервере идеологии «комнат»);
Редактирование личной информации пользователя (имя и аватар);
Просмотр списка других пользователей с переходом на отправку им сообщений.
Для запуска сервера необходим IDE (я использую PyCharm), в котором установить фреймворк Django
и следующие библиотеки:

pip install django==4.2.2

pip install djangorestframework==3.14.0

pip install daphne==4.0.0

pip install channels==4.0.0

pip install channels-redis==4.1.0

Для авторизации пользователя :pip install django-allauth==0.54.0

Для работы с ImageField: pip install Pillow

Или установить все нужные библиотеки командой:
pip install -r requirements.txt

Запуск сервера:
python manage.py runserver