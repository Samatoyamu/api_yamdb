# api_yamdb

### Описание
Проект представляет собой агрегатор произведений.
Отличительной особенностью является реализованное API для работы со всеми функциями проекта.
>Примечание: для использования всех функций API ползователь должен быть авторизован


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:rakikz/api_yamdb-1.git
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pi
pip install -r requirements.txt
```

Выполнить миграции: `python3 manage.py migrate`

Запустить проект: `python3 manage.py runserver`

### Примеры запросов API
`GET api/v1/titles` - Получаем список всех произведений.
`POST api/v1/titles/{title_id}/reviews/` - Добавление нового отзыва в коллекцию произведений. Анонимные запросы запрещены.

### Использованные технологии:
- Django - 3.2
- djangorestframework - 3.12.4
- djangorestframework-simplejwt - 5.2.2

#### Об авторах:
- имя: Савелий Худяк
- имя: Роман Петушков
- имя: Андрей Мелешкин

студенты ЯндексПрактикума 51 когорты
