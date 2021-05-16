# Simple CURD API IN DJANGO

## Quick Starter

<br>

Install and create virtual environment

**_Windows_**

```console
py -m pip install --user virtualenv
py -m venv env
```

**_Mac and Linux_**

```console
python3 -m pip install --user virtualenv
python3 -m venv env
```

Activate Virtual environment

**_Windows_**

```console
.\env\Scripts\activate
```

**_Mac and Linux_**

```console
source env/bin/activate
```

Install packages in virtual environment

```console
pip install -r requirements.txt
```

Run Django server

```console
cd curd_api
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

_In case of mac of linux use sudo_

## To use the api check the methods of main.py in app
