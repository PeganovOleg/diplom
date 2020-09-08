# diplom
PSW-9, финальный проект

Локальный запуск проекта:
Скопировать даный репозиторий.
Установить зависимости из requirements.txt: pip install -r requirements.txt.
Создать миграции: python manage.py makemigrations.
Провести миграции БД: python manage.py migrate
Создать суперпользователя: python manage.py createsuperuser
Создать свои опросы под админом 
Запустить сервер: python manage.py runserver
Сайт будет доступен по адресу: http://127.0.0.1:8000

В БД пользователи: admin - 123456 (администратор); user22 - oleg352510 (пользователь)
Можно создать своих пользователей с помощью панели администрирования
Опросы с вопросами создаются админом/персоналом через панель администрирования.

Работа выложена на Heroku: https://whispering-thicket-32549.herokuapp.com
