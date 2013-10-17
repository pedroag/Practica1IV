# Práctica 1 de Infraestructura Virtual

Pasos a seguir:
---------------

* Me he registrado en Openshift y desde allí creo la aplicación, que en mi caso se va a llamar "prueba", y la voy crear
en PHP, por lo tanto eligo PHP 5.3.

* Una vez creada, me la descargo con:


git clone ssh://525bc537e0b8cdbcf2000146@prueba-pedroag.rhcloud.com/~/git/prueba.git/


* Añado a la carpeta del proyecto los archivos php, que previamente ya tenía hechos, ya que se trata de una práctica
del año pasado, y seguidamente hago:

git add .
git commit -a -m "Añadidos los archivos"
git push

* La aplicación ya esta funcionando, salvo la parte de bases de datos. Para ello le añado los Cartridges necesarios para su
manejo: MySQL 5.1 y myphpadmin 4.0, todo esto desde la propia web de openshift. Modifico los datos de conexión de mi sitio web
y creo las tablas necesarias desde https://prueba-pedroag.rhcloud.com/phpmyadmin/

* Aplicación completa y accesible desde https://prueba-pedroag.rhcloud.com



