# Django Ledger ERP

Accounting-focused ERP built with Django.

## Setup

1) Clone the repository:

```bash
git clone https://github.com/ahmad5760/finance-ledger.git
cd finance-ledger
```

2) Create and activate a virtual environment named `virtual`:

```bash
Windows:
python -m venv virtual
.\virtual\Scripts\activate

macOS/Linux:
python -m venv virtual
source virtual/bin/activate
```

3) Install dependencies:

```bash
pip install -r requirements.txt
```

4) Run migrations:

```bash
python manage.py migrate
```

5) Create a superuser for the admin site:

```bash
python manage.py createsuperuser
```

6) Start the server:

```bash
python manage.py runserver
```

## Notes

- Default settings use SQLite (`db.sqlite3`) for local development.
- The Django admin is available at `http://127.0.0.1:8000/admin/`.
