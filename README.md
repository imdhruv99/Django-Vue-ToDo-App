# Django-Vue-ToDo-App

- Task App Implementation using Django as BackEnd and Vue.js as FrontEnd.

### Django Modules

- django
- djangorestframework
- django-cors-headers
- To install this use ```pip install <module-name>```.

### Running Server

- Inside the mysite directory and fire below command
- ```python manage.py runserver```
- This will start server on default ```8000``` port.
- To change the port use port number behind runserver
- ```python manage.py runserver 8080```
- To change IP use below command
- ```python manage.py runserver 0.0.0.0:8080```
- To migrate the Models
- ```python manage.py makemigrations```
- ```python manage.py migrate```
- To Create Superuser
- ```python manage.py createsuperuser```

### Create Vue Client 
- Create Vue client using vue cli
- ```vue create client```
- Choose 'Manually Select Features'
- Select 'babel', 'Router', 'Css-PreProcessor'
- Choose SASS/SCSS (node-scss)
- Choose package.json
- and this will create you vue client

### Vue Packages
- axios
- bulma [CSS Framework]
- To install dependancies use ``` npm install <package-name> ```

### Running Vue Client
- To run Vue client use
- ```vue run serve```

### Thank You!