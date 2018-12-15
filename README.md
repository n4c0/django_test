# django_test
Creación de entorno virtual Django

Instalación Django

1.- Descargar libreria de Pyton y Virtual Enviorment
# apt install python-pip virtualenv

2.- Crear carpeta django e ingresar a ella.
# mkdir django
# cd django

3.- Habilitar el entorno virtual dentro de la carpeta creada.
# virtual env .

4.- Activar entorno virtual.
# source bin/activate

5.- Instalar dentro del entorno virtual django.
# pip install django

6.- Crear el sitio a levantar.
# django-admin startproject mysite

7.- Ejecutar el servidor de acuerdo al sitio generado, dentro de la carpeta mysite.
# cd mysite
# python manage.py runserver

8.- Migrar la base de datos del sitio.
# python manage.py migrate

9.- Ejecutar el sitio y validar su funcionamiento.
# python manage.py startapp prueba

10.- Ir a github.com para crear una repo
www.github.com

11.- Clonar la repo en Github
# git clone urlquetienelarepo

12.- Agregar el projecto en la carpeta en la url, en este caso sería la carpeta completa del sitio "Django".
# cd..
# cd /django
# git add.

13.- Subir los archivos a Github.
# git commit -m "Subiendo Archivos"

14.- Aplicar un push
# git push
