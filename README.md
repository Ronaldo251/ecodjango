Passo a passo para funcionar o código:

git clone https://github.com/ronaldo251/ecodjango 

cd django-simple-ecommerce    

python -m venv venv

venv\Scripts\activate

python -m pip install --upgrade pip setuptools wheel --user

python -m pip install django django-debug-toolbar django-crispy-forms pillow

python manage.py migrate

