
Yatube - социальная сеть. В Yatube реализована
авторизация на Django, работа с БД, создание индивидуальных страниц
пользователей, постов, их оценка и возможность добавлять комментарии.

Поддерживает методы GET, POST, PUT, PATCH, DELETE.

Предоставляет данные в формате JSON.

### Запуск проекта:

Клонировать репозиторий и перейти в него в командной строке:
```
cd api_yatube
```
Cоздать и активировать виртуальное окружение:

Для Windows:
```
python -m venv env
```
Для Linux:
```
source venv/bin/activate
```
Обновить менеджер пакетов:
```
python -m pip install --upgrade pip
```
Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
Выполнить миграции:
```
python manage.py migrate
```
Запустить проект:
```
python manage.py runserver
```
