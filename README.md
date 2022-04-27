# Biolerplate for Django with Vuejs

Welcome to the Django Vuejs boilerplate. Now you can simply clone the repo and start using Vue js in Django in couple of minutes.

I have used Django 3.2 with Vue js 2

# Steps to clone and run the project

## First clone the Project

```shell
git clone https://github.com/Prabin619/django-vuejs-boilerplate.git
```

## Open two terminals one for Django App and another for Vuejs App

### In Django Terminal

> First install virtual environment

```shell
python3 -m venv <virtual_env_name>
```

> Activate Virtual environment

```shell
source <virtual_env_name>/bin/activate
```

> Install required packages

```shell
pip install -r requirements.txt
```

> Run Python Server

```shell
python manage.py runserver
```

## In Vuejs Terminal

> Change directory to frontend and install node modules

```shell
cd frontend/
npm install
```

> Run npm in development mode

```shell
npm run dev
     or 
npm run watch

Both will keep server runnning. However, watch will automatically reload your screen when any vue file is updated, unlike dev.
```

> Build npm for Production mode

```shell
npm run build
```
