# REST API для проекта Yatube

Бэкенд для проекта Yatube реализован по ссылке:

>*https://github.com/airatns/hw05_final*

## **Стек технологий**

Python, Django, Django REST Framework, Simple JWT, Djoser, SQLite3

## **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:

>*git clone git@github.com:airatns/api_final_yatube1.git*

Cоздать и активировать виртуальное окружение:

>*python3 -m venv env*

>*source env/scripts/activate*

Установить зависимости из файла requirements.txt:

>*python3 -m pip install --upgrade pip*

>*pip install -r requirements.txt*

Выполнить миграции:

>*python3 manage.py migrate*

Запустить проект:

>*python3 manage.py runserver*


## **Примеры**

### **Создание публикации**

>*http://127.0.0.1:8000/api/v1/posts/*

*Request*

>*"text": "купил котенка",*

>*"group": "1"*

*Response*

>*"id": "1"*

>*"author": "tiger"*

>*"text": "купил котенка"*

>*"pub_date": "01-04-2022 14:00:01"*

>*"group": "1"*

### **Получение комментариев**

>*http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/*

*Request*

>*"post_id": "1",*

*Response*

>*"id": "1"*

>*"author": "leo"*

>*"text": "покажи фотку"*

>*"created": "01-04-2022 16:00:01"*

>*"post": "1"*

### **Получение JWT-токена**

>*http://127.0.0.1:8000/api/v1/jwt/create/*

*Request*

>*"username": "kitten",*

>*"password": "kitten1",*

*Response*

>*"refresh": "eysfaq05"*

>*"access": "eyfdsgsfdg08"*
