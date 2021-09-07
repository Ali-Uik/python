Python 3.9.2
Django - 3.2.6
Python -V - проверка версии Python
python -m django --version - проверка версии django
.\venv\Scripts\activate – активация виртуальной среды
deactivate – деактивация виртуальной  среды
pip list – список установленных доп. пакетов 
pip install Django – установка Django 
django-admin – список команд в Django
django-admin startproject “имя проекта” – создание проекта
python manage.py runserver – старт проекта
python manage.py startapp 'имя' - создание нового модуля(приложения)
Mark directory as -> source root
Типы полей django - https://django.fun/docs/django/ru/3.1/ref/models/fields/
python manage.py makemigrations - создание миграции
python manage.py migrate - выполнение миграции
python manage.py shell - командная среда django
from news.models import News
News.objects.all() - получение всех записей в таблице News
News.objects.order_by('id')
News.objects.create(title='Новость ', content='Контент новости ') - запись в базу данных
News.objects.filter(title='News5') -
news.save() - сохранить запись








ЛИТЕРАТУРЫ
https://djbook.ru/
https://django.fun/docs/django/ru/3.2/topics/db/queries/ - Работа с запросами

