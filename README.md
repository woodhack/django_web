# Portfolio site

**Creating site**

cd portfolio

virtualenv venv -p python3

`source venv/bin/activate` or `deactivate`

pip3 install Django

[django-admin](http://django-admin.py/) startproject portfolio

**Run project** 

cd portfolio

`python3 manage.py runserver`

[http://127.0.0.1:8000](http://127.0.0.1:8000/)

**Migrations**

python3 [manage.py](http://manage.py/) migrate

**Users**

python3 manage.py createsuperuser

**Bootstrap**

`pip3 install django-bootstrap-v5`

**Requirments.txt**

pip3 freeze > requirements.txt

pip3 install -r requirements.txt

**Run project**

`source venv/bin/activate`

cd portfolio

`python3 manage.py runserver`

[http://127.0.0.1:8000](http://127.0.0.1:8000/)

**Create app**

`python3 manage.py startapp`
