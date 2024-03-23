# entrega_final

##Pasos Tener instalado

django 5.0.3
python 3.11
vsc 1.87.0
Pillow
Comentario: Se ha creado el archivo mediante django, con startproyect, pararse en la carpeta correspondiente con el cd PE_3 y luego con colocar la App a través de python manage.py startapp Se ha tomato un template de start bootstrap. Para los templates, se a usado el padre para crear herencia para las otras plantillas. Arrastrar la carpeta al vsc y comenzamos:

python manage.py makemigrations para poder crear las tablas de las class en la db
Luego se hace el python manage.py migrate
Instalar un visor de sqlite Viewer
ir a la terminal y correr el python manage.py runserver para ver el server
ctrl+C para cerrar el server

Cuando se ingresa a la pagina por primera vez, se puede ingresar a los botones de about me, descargar, intagram y demas, pero no al resto de los botones.
La unica forma de acceder a todos estos es iniciando sesion. 
