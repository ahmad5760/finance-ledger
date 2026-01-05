# Django Ledger ERP

Accounting-focused ERP built with Django.

## Setup

1) Create and activate a virtual environment.
2) Install dependencies:

```bash
pip install -r requirements.txt
```

3) Run migrations:

```bash
python manage.py migrate
```

4) Start the server:

```bash
python manage.py runserver
```

## Notes

- Default settings use SQLite (`db.sqlite3`) for local development.
