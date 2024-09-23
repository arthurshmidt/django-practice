# install a virtual environment
1. mkdir <project_dir>
2. cd <project_dir>
3. python -m venv .venv
4. source .venv/bin/activate

# install core packages & setup base project
(.venv) $ python -m pip install django black
(.venv) $ django-admin startproject <project_name> .
(.venv) $ python manage.py startapp pages
