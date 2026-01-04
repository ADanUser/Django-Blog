# Django Blog

Simple blog app built with Django. It includes a post feed, post detail pages (via slug), authenticated post creation with image upload, and basic user auth (register, login, logout). Static files and media are configured.

## Features
- Post feed and post detail (slug)
- Create post (login required)
- Image upload for post banner
- Basic user auth (register, login, logout)
- Admin panel

## Requirements
- Python 3.13+
- Django
- Pillow (for ImageField)

## Setup
```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows

pip install django pillow
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```

## Run
```bash
python manage.py runserver
```


