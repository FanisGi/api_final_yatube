### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:FanisGi/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Примеры запросов API:

После запуска проекта переходите на 

```
http://127.0.0.1:8000/redoc/
```

Там будут все примеры запросов и даже больше

### Технологии:

Python 3.7.9
Django==2.2.16
pytest==6.2.4
pytest-pythonpath==0.7.3
pytest-django==4.4.0
djangorestframework==3.12.4
djangorestframework-simplejwt==4.7.2
Pillow==8.3.1
PyJWT==2.1.0
requests==2.26.0
djoser==2.1.0

### Гений-создатель:

FanisGi