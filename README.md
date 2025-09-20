# CivicConnect

CivicConnect is a web platform that connects citizens with local government for reporting and tracking civic issues (photos + location, tracking, dashboards, AI prioritization).

## Quick features
- Issue reporting (photo + location)
- Real-time tracking & role-based dashboards
- AI prioritization & semantic deduplication

## Tech stack
- Frontend: HTML, CSS, JavaScript (Django templates)
- Backend: Python, Django, Django REST Framework
- DB: PostgreSQL
- ML: TensorFlow (saved model under `/ml/`)

## How to run (local)
1. Create virtualenv: `python -m venv venv`  
2. Activate: `source venv/bin/activate` (Windows: `venv\Scripts\activate`)  
3. Install: `pip install -r requirements.txt`  
4. Create `.env` (see sample) and update DB creds  
5. Run migrations: `python manage.py migrate`  
6. Create superuser: `python manage.py createsuperuser`  
7. Run server: `python manage.py runserver`


