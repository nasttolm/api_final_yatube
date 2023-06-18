<h1 align="center"> Проект «API для Yatube» </h1>

<h2 align="center"> Как запустить проект? </h2>

<h3> Клонировать репозиторий и перейти в него в командной строке: </h3>

git clone https://github.com/yandex-praktikum/kittygram.git

cd kittygram

<h3> Cоздать и активировать виртуальное окружение: </h3>

python3 -m venv env

source env/bin/activate

<h3> Установить зависимости из файла requirements.txt: </h3>

python3 -m pip install --upgrade pip

pip install -r requirements.txt

<h3> Выполнить миграции: </h3>

python3 manage.py migrate

<h3> Запустить проект: </h3>

python3 manage.py runserver

<h2 align="center"> Примеры </h2>

<h3> Некоторые примеры запросов к API: </h3>

GET/api/v1/posts/

POST/api/v1/posts/{post_id}/comments/

<h2 align="center"> ###Документация к API проекта Yatube (v1): </h2>

http://127.0.0.1:8000/redoc/
