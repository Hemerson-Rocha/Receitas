# Receitas

Você pode se cadastrar, logar e criar suas proprias receitas!

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.


### 📋 Pré-requisitos

Você precisa para instalar: 

Python 3.


### 🔧 Como instalar:

```
git clone https://github.com/Hemerson-Rocha/Receitas.git
```
No terminal powershell:

Instalar e ativar a venv
```
python -m venv venv
.\venv\Scripts\Activate.ps1
```

Instalar as dependencias e abrir o banco de dados
```
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
```

Rodar o projeto
```
python manage.py runserver
```

Depois acesse o link gerado 
