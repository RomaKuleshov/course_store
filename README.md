# Магазин курсов на Django

Простой проект интернет-магазина по продаже курсов, созданный на Django.

## Описание

Приложение представляет собой магазин, где можно просматривать и покупать курсы.
Реализованы основные функции Django-приложения: маршрутизация, представления и модели.


## Установка

1. Клонировать репозиторий:

```bash
git clone https://github.com/RomaKuleshov/course_store
cd <имя_проекта>
```

2. Создать и активировать виртуальное окружение:

```bash
python -m venv venv
source venv/bin/activate       # Linux / macOS
venv\Scripts\activate          # Windows
```

3. Установить зависимости:

```bash
pip install -r requirements.txt
```

4. Применить миграции:

```bash
python manage.py migrate
```

5. Запустить сервер:

```bash
python manage.py runserver
```

Проект будет доступен по адресу [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

