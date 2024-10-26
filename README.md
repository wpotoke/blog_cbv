# Blog CBV

**Blog CBV** — это система управления контентом для блогов, разработанная с использованием Django и представлений на основе классов (CBV). Проект поддерживает создание и категоризацию контента, а также включает такие функции, как теги, аутентификация пользователей и многое другое. Проект создан в учебных целях для изучения Django.

## Содержание

- [Технологии](#%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D0%B8)
- [Функционал](#%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB)
- [Начало работы](#%D0%BD%D0%B0%D1%87%D0%B0%D0%BB%D0%BE-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B)
- [To Do](#to-do)
- [Команда проекта](#%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%B0-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)

## Технологии

- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- Django MPTT
- [Django Taggit](https://github.com/jazzband/django-taggit)
- [Django Debug Toolbar](https://django-debug-toolbar.readthedocs.io/)
- [Django Summernote](https://github.com/summernote/django-summernote)
- [Pillow](https://python-pillow.org/)

## Функционал

- Аутентификация пользователей
- Категоризация и тегирование постов
- Редактирование текста с помощью Summernote
- Социальная аутентификация (через Google, GitHub)
- reCAPTCHA для защиты форм
- Загрузка и хранение изображений

## Начало работы

### Клонирование репозитория:

bash

Копировать код

`git clone https://github.com/wpotoke/blog_cbv.git cd blog_cbv`

### Установка зависимостей:

bash

Копировать код

`pip install -r requirements.txt`

### Настройка переменных окружения

Создайте файл `.env` и добавьте необходимые ключи для reCAPTCHA, социальной аутентификации и других секретных данных.

### Применение миграций базы данных:

bash

Копировать код

`python manage.py migrate`

### Запуск сервера разработки:

bash

Копировать код

`python manage.py runserver`

Перейдите по адресу `http://127.0.0.1:8000` в вашем браузере для использования приложения.

## To Do

- Добавить функционал комментариев к постам
- Настроить CI/CD для автоматического развертывания
- Добавить дополнительные социальные методы аутентификации
- Реализовать рекомендации постов на основе тегов

## Команда проекта

- [Морозов Данила](https://t.me/amigos_mixtapes) — Разработчик
