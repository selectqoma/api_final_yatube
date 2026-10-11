# YaTube API

A Django REST Framework API for posts, groups, comments and follows, with JWT authentication.

## Run locally

From the repository root:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd yatube_api
python manage.py migrate
python manage.py runserver
```

API: http://127.0.0.1:8000/api/v1/. Documentation: http://127.0.0.1:8000/redoc/.
