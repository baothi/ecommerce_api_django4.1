python3.10 -m venv django_env
source django_env/bin/activate
python3.10 --version

pip install Django==4.1
pip install --upgrade pip
pip install Django==4.1
pip install pytest
pip install pytest-django
pip install pytest-factoryboy
pip install pytest-selenium
pip freeze > requirements.txt
python3.10 manage.py startapp dashboard
django-admin startapp dashboard
https://chromedriver.chromium.org/downloads