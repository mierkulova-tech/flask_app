# Simple Flask App

Простое веб-приложение на Flask.

## Установка

1. Клонировать репозиторий:
   git clone https://github.com/mierkulova-tech/flask_app.git
   cd flask_app

2. Создать виртуальное окружение и активировать:
   python -m venv .venv
   source .venv/Scripts/activate  # Windows PowerShell
   # или source .venv/bin/activate  # Linux/Mac

3. Установить Flask:
   pip install flask

4. Запустить приложение:
   python main.py

## Маршруты

- `/` → Hello, Flask!
- `/user/<name>` → Привет, <name>!
