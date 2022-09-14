# **Workshop01 - Anibal Castro Ponce - ISW-811**
### Implementación de una aplicación LAMP (Linux, Apache, MySQL, PHP).


## Recursos utilizados:
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/)

## Como instalar VirtualBox:
Ingresar al enlace que se encuentra arriba, empezar a descargar VirtualBox, a la hora de la instalacion solo es de presionar el boton siguiente y siguiente. El se instalara solo.

## Como instalar Vagrant:
Ingresar al enlance de Vagrant, una vez iniciada la descarga depende de la calidad del internet tardara un poco, a la hora de instalar el programa, ejecutar el boton siguiente hasta finalizar la instalacion del mismo.

## Notas importantes:
- A nivel de BIOS para la maquina es importante tener activa la virtualizacion.
- Tambien es necesario desactivar Secure Boot.
- Todo lo realizado, se implementara en consola de su preferencia.

## Procedimiento:
- Una vez descargados VirtualBox y Vangrant, se debe realizar una carpeta en donde se van a almacenar las maquinas virtuales.
- En nuestro caso se nombrara el equipo como webserver, por lo cual es necesario crear una carpeta con dicho nombre.
- Una vez creada la carpeta, ingresamos a la carpeta por medio del comando `cd` y el nombre de la carpeta.
- Seguidamente ingresamos el comando `vagrant init debian/bullseye64`.
- Una vez creada la maquina, se le debe asignar una IP, obtaremos por conveniencia asignarle una IP privada, se le asigna la direccion que sea necesaria, en nuestro caso le asignaremos la dirección: **192.168.74.12**
- **Paso importante:** En el caso que utilice un sistema operativo Windows, ingresar a la direccion `c:\Windows\System32\drivers\etc\host`, si el sistema operativos es Linux o MacOX es `/etc/hosts/`.
- Seguidamente se escribe el siguiente comando en consola: `vagrant up`.


## Comandos una vez inicialicen la maquina:
1- `apt -get update` comando para actualizar la lista de los paquetes disponibles.

2- `sudo apt -get install vim vim-nox curl git apache mariadb-server mariabdb-client php7.4 php7.4-bcmath php7.4-curl php7.4-json php7.4-mbstring php7.4-mysql php7.4-xml` comando mas importante para instalar todo lo necesario.

## Comprobacion de que la máquina se configuró exitosamente:
En su navegador web de preferencia, y colocan en el buscador ya sea la IP que ingresaron a la maquina, o en nuestro caso le colocamos webserver entonces ingresamos: `*www.webserver.com*` y nos debe aparecer como resultado lo siguiente:


![alt text](https://howtoforge.es/media/instalar-la-plataforma-de-aprendizaje-electronico-moodle-en-debian-9/upload-1.jpg "Debian Default Page")


#### **WORKSHOP REALIZADO POR:** Anibal Jafeth Castro Ponce
#### **FECHA:** 12 de Setiembre del 2022
#### **CURSO:** Aplicaciones Web Utilizando Software Libre
#### **CÓDIGO:** ISW-811


