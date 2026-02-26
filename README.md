# unicloud_backend

Django backend project scaffold with a starter `core` application.

## Project structure

- `manage.py` — Django management entrypoint
- `unicloud_backend/` — project package (`settings.py`, `urls.py`, `asgi.py`, `wsgi.py`)
- `core/` — starter Django app
- `requirements.txt` — Python dependencies

## Local setup

1. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Run Django checks and migrations:

   ```bash
   python manage.py check
   python manage.py migrate
   ```

4. Start the development server:

   ```bash
   python manage.py runserver
   ```
