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


## IMAGENS
![registrar](https://user-images.githubusercontent.com/54272286/179042841-a059fcdd-3a3f-44df-a6c7-506179417dfe.png)
![login](https://user-images.githubusercontent.com/54272286/179043172-c1af6c89-17ba-4e9f-9ac1-f7e0262a9df5.png)
![pacientes](https://user-images.githubusercontent.com/54272286/179043228-b94a0dbe-c65e-4810-9973-90a62c63316a.png)
![cadastrar_pacientes](https://user-images.githubusercontent.com/54272286/179043299-86291afd-4f86-49c8-8783-21c34eb5a637.png)
![add_dados_pacientes](https://user-images.githubusercontent.com/54272286/179043359-60b2afa8-d3b4-4f82-ae3b-2040fae96181.png)
![dados_pacientes](https://user-images.githubusercontent.com/54272286/179043425-966e2858-47a6-41d0-a08e-e08256a16b05.png)
![plano_alimentar](https://user-images.githubusercontent.com/54272286/179043478-73045a0b-8d13-4a39-a5c7-86fd486e06e1.png)
![django](https://user-images.githubusercontent.com/54272286/179044305-4a225fd1-efad-4f1f-8b2c-8a30a894d8f8.png)


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























