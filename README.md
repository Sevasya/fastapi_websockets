# FastAPI WebSocket Чат

Реализация реального времени чата на FastAPI с WebSocket соединениями.

## Функциональность

- ✅ Аутентификация пользователей
- ✅ WebSocket для реального времени
- ✅ Личные сообщения между пользователями

## Технологии

- FastAPI
- WebSocket
- SQLite/PostgreSQL
- JWT аутентификация
- HTML/CSS/JavaScript

## Установка и запуск

В корне проекта создайте файл .env, в него добавьте:

```bash
SECRET_KEY=YOUR_SECRET_KEY
ALGORITHM=YOUR_ALGORITHM
```

Пример алгоритма: HS256

```bash
# Установка зависимостей
pip install -r requirements.txt

# Запуск сервера
uvicorn main:app --reload
```