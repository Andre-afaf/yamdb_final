![Yamdb Workflow Status](https://github.com/Andre-afaf/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg?branch=master&event=push)
# YaMDB
## Учебный проект рейтингового сайта
Проект должен был быть доступен тут http://84.201.173.57:8000/, но web контейнер не запускается по непонятной причине


### Технологии
- Python 
- Django 
- DjangoRest Framework

### Запуск
- Создайте и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
' pip install -r requirements.txt '
- выполните миграции:
 1) ' python3 manage.py makemigrations '
 2) ' python3 manage.py migrate '
- наполните базу данных:
 python manage.py import_csv
- В папке с файлом manage.py выполните команду:
' python3 manage.py runserver ' 

### Авторы
Nikita Feyuk
Igor Polyakov
Andrey Rodin