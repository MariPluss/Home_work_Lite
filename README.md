# Home_work_Lite — Books REST API

Учебный проект на Django REST Framework для управления книгами через REST API.

## Возможности

- GET — получение списка книг и информации об отдельной книге.
- POST — добавление новой книги.
- PUT — полное обновление информации о книге.
- PATCH — частичное обновление информации о книге.
- DELETE — удаление книги.

## Используемые технологии

- Python
- Django
- Django REST Framework
- drf-spectacular
- SQLite

## Установка и запуск

1. Создать и активировать виртуальное окружение.
2. Установить зависимости:

   `pip install -r requirements.txt`

3. Применить миграции:

   `python manage.py migrate`

4. Запустить сервер:

   `python manage.py runserver`

## Документация API

После запуска сервера открыть:

http://127.0.0.1:8000/api/docs/

Основные адреса API:

- `GET /api/books/`
- `POST /api/books/`
- `GET /api/books/{id}/`
- `PUT /api/books/{id}/`
- `PATCH /api/books/{id}/`
- `DELETE /api/books/{id}/`

## Проверка

Операции создания, просмотра, изменения и удаления книг протестированы через Swagger UI.