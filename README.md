# api_final
api final

### Описание
Учебный проект для отработки API

### Технологии
Django 2.2
Django Rest Framework
Python 3.7
Pytest
Simple-JWT
SQLite3

### Документация
Доступна по адресу ```/redoc/```

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:ivditm/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Source/activate
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
