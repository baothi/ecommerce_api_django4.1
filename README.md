python3.10 -m venv django_env
source django_env/bin/activate
python3.10 --version
pip freeze > requirements.txt

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
python3.10 manage.py dumpdata inventory.category --indent 4 > new.json

pytest -m "not selenium" -rP
pytest -m "not selenium and not dbfixture" -rP

python3.10 manage.py load-fixtures
https://factoryboy.readthedocs.io/en/stable/orms.html

# E-commerce V2

# Pytest
```
pytest -m "not selenium" -rP
```

## Creating custom fields 
```
cas = models.CharField(max_length=11, validators=[RegexValidator(r'^\d\d-\d\d-\d\d-\d\d$')])
```

## PowerShell - Prepare fixtures
```
$topicsjson = import-csv .\db_product_inventory.csv | ConvertTo-Json
$topicsjson | Add-Content -Path "mydata.json"
```

## Make Password Fixture
---
```
./manage.py shell

from django.contrib.auth.hashers import make_password
make_password('password')
```

## Load fixture
```
manage.py loaddata xyz.json
manage.py dumpdata auth.user --indent 2 > user.json 
```

## Docs
```
\docs>make html
```
```
https://django-ecommerce-project-v2.readthedocs.io/en/latest/
```
## ElesticSearch





