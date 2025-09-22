# CI-CD


[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![Version](https://img.shields.io/badge/version-0.1.0-orange)]()

---
# Содержание
- [О проекте](#О-проекте)
- [Демо / Скриншоты]()
- [Особенности](#Особенности)
- [Технологии](#Технологии)
- [Установка](#Установка)
- [Быстрый старт](#Быстрый-старт)
- [Использование](#Использование)
- [Конфигурация]()
- [Архитектура]()
- [API / Интерфейсы](#API-Интерфейсы)
- [Тесты](#Тесты)
- [CI / CD](https://github.com/KayaAkd/CI-CD)
- [Безопасность]()
- [Как внести вклад]()
- [Лицензия]()
- [Контакты]()
- [TODO / Roadmap]()
- [История изменений]()


## О проекте
Проект - микросервис для доставки сообщений по WebSocket

## Демо / Скриншоты
screenshot.png

## Особенности 
Поддержка большинства ОС, легкая интеграция

## Технологии
Python 3.1, SQLite 3

## Установка
python -m venv .venv
- source  .venv/bin/actvate
- pip install -r requirements.txt

## Быстрый старт
python app/main.py

## Использование
from client import Client
- c = Client(api_key="YOUR_KEY")
- c.send("Hello")

## API / Интерфейсы
POST /api/auth
GET /api/items

## Тесты
pytest tests/
