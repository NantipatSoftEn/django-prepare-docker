# Devcontainer test project
### Django related command list
#### Create django python 
```
django-admin startproject startweb .
```
- Change database info
#### Create super user
```
python manage.py createsuperuser
```
#### Start server
``` 
python manage.py runserver 0.0.0.0:8000
```


## [Error migration fix](https://stackoverflow.com/questions/43718536/django-python-manage-py-migrate-does-nothing-at-all)

```python
python manage.py makemigrations
python manage.py migrate
```