# Playbook_sencillo
En este Playbook escrito en yaml, vamos a realizar diversas operaciones sencillas. Las operaciones que vamos a realizar son las siguientes:

* Crear un usuario en el servidor remoto que tenga tu nombre.
* Descarga el fichero desde la url https://wordpress.org/latest.zip.
* Descomprime ese fichero en el home del usuario creado anteriormente.
* Instala el paquete mariadb.
* Crea una base de datos que se llame tunombre_wordpress.
* Crea un usuario que se llame my_nombre que tenga privilegios sobre la base de datos.
* Clona el repositorio: https://github.com/josedom24/ansible_ejemplos.git en el home del usuario que hemos creado en el primer punto.

La salida del comando no debe de dar ningun fallo al ejecutarlo con el comando **ansible-playbook playbook_sencillo.yaml**.

<img src="/img/salidacomando.png" alt="Salida del comando"/> 

