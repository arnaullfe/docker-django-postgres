# docker-django-postgres

START PROJECT:

    1-
      docker-compose run web django-admin startproject app .
      
    2-
      sudo chown -R $USER:$USER .
      
    3-
      docker-compose up
      
    4-
      docker run -it (id container) bash
      
    5-
      pip install mysqlclient
      
    6-
      python manage.py startapp api
  
    7- 
      Add in app/setting.py inside INSTALLED_APP YOUR APP
    
  
