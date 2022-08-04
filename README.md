# REST API для проекта Yatube

Бэкенд для проекта Yatube реализован по ссылке:

>*https://github.com/airatns/hw05_final_yatube*

## **Стек технологий**

Python, Django, Django REST Framework, Simple JWT, Djoser, SQLite3

## **Как запустить проект:**

Клонировать репозиторий и перейти в него в командной строке:

>*git clone git@github.com:airatns/api_final_yatube1.git*

Cоздать и активировать виртуальное окружение:

>*python -m venv env*

>*source env/scripts/activate*

Установить зависимости из файла requirements.txt:

>*python -m pip install --upgrade pip*

>*pip install -r requirements.txt*

Выполнить миграции:

>*python manage.py migrate*

Запустить проект:

>*python manage.py runserver*

Полное описание можно найти по ссылке после запуска проекта - <a href="http://127.0.0.1:8000/redoc" target="_blank">Redoc</a>

## **Примеры**

### **Получение публикации**

![Post](https://user-images.githubusercontent.com/96816183/182833690-a20e5733-139d-458f-90bb-4142e45edcc3.png)

### **Создание комментария**

![comment](https://user-images.githubusercontent.com/96816183/182833743-8790520a-6939-4adb-8258-90c6b585e8c0.png)

### **Получение JWT-токена**

![Tokrn](https://user-images.githubusercontent.com/96816183/182833559-e1997753-5311-40c7-b71a-b1dbf477ef29.png)
