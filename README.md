# NutriLab é uma aplicação usando Python e Django 4
##Um app desenvolvido para Nutricionistas gerenciarem seus pacientes.

## Tecnologias utilizadas para o desenvolvimento

- Python
- Django 4
- SQLite
- Arquitetura MVT

## Funcionalidades

- Autenticação de usuário, Cadastro e Login
- Gestão de Pacientes, Dados Laboratoriais e Planos Alimentares

envio de emails html
ativação de conta por email
Models do django
Banco de dados


IMAGENS


## COMANDOS USADOS

### PIP
```
pip list --outdate
python -m pip install --upgrade pip
python -m pip install --upgrade setuptools
```

### Para windows > virtualenv 
```
python -m venv env
env\Scripts\activate.bat
env\Scripts\deactivate.bat
```

### Instalar bibliotecas, gravar/instalar requerimentos
```
(env) pip install Django
(env) pip install Pillow

(env) pip freeze > requirements.txt
(env) pip install -r requirements.txt
```

### Criar projeto
```
(env) django-admin startproject nutrilab .
```

### Criar apps
```
(env) python manage.py startapp autenticacao
(env) python manage.py startapp plataforma
```

### Migrations
```
(env) python manage.py makemigrations
(env) python manage.py migrate
```

### Executar projeto
```
(env) python manage.py runserver
```























