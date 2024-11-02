# Описание

API для учебного проекта YaTube.

Социальная сеть с возможностью регистрации, публикации и комментирования постов.

# Установка:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/<username>/api_final_yatube.git
```

```
cd api_final_yatube
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

# Примеры запросов

http://127.0.0.1:8000/redoc/