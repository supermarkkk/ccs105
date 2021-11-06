# Steps to install

## 1. Delete dbsqllite3
## 2. activate env folder
- env/script/activate
## 3. navigate to ovs folder
- cd ovs
## 4. install dependencies 
- pip install requirements.txt
## 5. create db 
- py manage.py makemigrations
- py manage.py migrate
## 4. create superuser 
- py manage.py createsuperuser
## 6. run application
- py manage.py runserver
