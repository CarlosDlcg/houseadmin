## Notas
python3 manage.py runserver -- Para iniciar el webserver
python3 manage.py startapp <app_name> -- Para crear una app
La app creada debe colocarse en settings.py de la carpeta central
Se crea la carpeta templates y se le indica en settings.py de la carpeta central
python3 manage.py makemigrations es para stagear las migraciones que se quieran
python3 manage.py migrate es para realizar esas migraciones
python3 manage.py createsuperuser para crear el usuario admin
En admin.py se coloca el modelo para que aparezca en el panel de admin
Para implementar CRUD intervienen views.py, urls.py y los templates
Revisar la parte de autenticación

3:01:30 https://www.youtube.com/watch?v=PtQiiknWUcI&t=6854s