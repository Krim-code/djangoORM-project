### Clone Repository
```
https://github.com/Krim-code/djangoORM-project.git
```

```
сd django_ORM
```

### Set Database
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'hr',
        'USER': 'root',
        'PASSWORD': '',
        'HOST':'localhost',
        'PORT':'3306',
    }
}
```
### Make Venv
```
python -m venv venv
```
### Install Requirements 
```
pip install -r requirements.txt
```

### Migrate Database
```
python manage.py migrate
```

### Load Data 
```
python manage.py loaddata data.json
```

