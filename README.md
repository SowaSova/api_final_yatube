# API модуль для социальной сети [YaTube](https://github.com/SowaSova/hw05_final)

### Функционал:

* Подписка и отписка от авторизованного пользователя;
* Авторизованный пользователь просматривает посты, создавёт новые, удаляет и изменяет их;
* Просмотр сообществ;
* Комментирование, просмотр, удаление и обновление комментариев;
* Фльтрация по полям.

### Технологии:

- Python 3.8 
- Django 2.2.19
- Django Rest Framework 3.12.4

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/SowaSova/api_final_yatube.git
```

```
cd yatube_api/
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

[Документация после запуска проекта](http://localhost:8000/redoc/)

