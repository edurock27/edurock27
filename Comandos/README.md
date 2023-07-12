# Iniciar o projeto Django
python -m venv venv
. venv/Scripts/activate
pip install django
django-admin startproject project .
python manage.py runserver
python manage.py startapp contact

# Iniciar o Git
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem't
git remote add origin URL_DO_GIT
