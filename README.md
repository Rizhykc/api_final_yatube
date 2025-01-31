## Проект Yatube - социальная сеть для авторов.

***Здесь вы можете создавать свои записи, добавлять их в сообщества, подписываться на авторов и комментировать их записи.***

### Возможности проекта:
- Регистрация с расширенным профилем и управление им (переопределение модели User с помощью AbstractUser).
- Публикация записей с изображениями.
- Публикация записей в сообщества.
- Комментарии к записям других авторов.
- Подписка на других авторов.
- Лента с записями, на которых оформлена подписка.
- Template tags, отображающие самые обсуждаемые записи, последние записи и пр.

### Возможности API:
- Получение, создание, обновление, удаление записей.
- Получение, создание, обновление, удаление комментариев.
- Получение списка сообществ и их информации.
- Получение списка подписок и создание подписки на авторов.
- Получение, обновление и проверка токена авторизации (JWT).

## Технологии
![Python](https://img.shields.io/badge/Python-3.9.13-%23254F72?style=flat-square&logo=python&logoColor=yellow&labelColor=254f72)
![Django](https://img.shields.io/badge/Django-3.2-0C4B33?style=flat-square&logo=django&logoColor=white&labelColor=0C4B33)
![Django](https://img.shields.io/badge/Django%20REST-3.12.4-802D2D?style=flat-square&logo=django&logoColor=white&labelColor=802D2D)

### Как запустить проект:

1.Клонировать репозиторий и перейти в папку **api_yatube**:
```
git clone https://github.com/Rizhykc/api_yatube.git
```
```
cd api_yatube
```

2.Cоздать и активировать виртуальное окружение:
```
py -3.9 -m venv venv
```
```
source venv/Scripts/activate
```
3.Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
5.Перейти в папку проекта **yatube_api** и запустить его:
```
cd yatube_api
```
```
./manage.py migrate
```
```
./manage.py runserver
```
6.Перейти на локальный сервер:
```
http://127.0.0.1:8000/api/v1
```

### Автор проекта:
Рижук Сергей [Github](https://github.com/Rizhykc)