# The "API for Yatube" project
Yandex educational project. Python Developer course (backend).

### Running a project

- Clone the repository and go to it on the command line:
```
git clone git@github.com:nasttolm/api_final_yatube.git
```
cd kittygram

- Install and activate the virtual environment
```
python3 -m venv env
```
source env/bin/activate
```
- Install dependencies from requirements.txt file
```
python3 -m pip install --upgrade pip
```
pip install -r requirements.txt
```
- Run migrations:
```
python3 manage.py migrate
```
- In the folder with the manage.py file, run the command:
```
python3 manage.py runserver
```
### Examples

#### Some examples of API requests

GET/api/v1/posts/

POST/api/v1/posts/{post_id}/comments/

### Technologies
Python 3.9.10

Django 3.2.16

djangorestframework 3.12.4

djangorestframework-simplejwt 4.7.2

### Documentation for the Yatube project API (v1):

http://127.0.0.1:8000/redoc/
