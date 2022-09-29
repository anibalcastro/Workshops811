# Workshop02 - Anibal Castro Ponce - ISW811

### Iniciar maquina LAMP y publicacion de un sitio.

## Creación de la maquina debian con Vagrant:
1) Crear una carpeta VMs con el comando:  ```$ mkdir VMs ```
2) Crear otra carpeta en donde se instalara la maquina debian/bullseye64 ```$ mkdir WebServer```
3) Ingresamos a la carpeta con el comando ```$ cd WebServer```.
4) Estando en la carpeta WebServer ejecutamos el comando ``` $ vagrant init debian/bullseye64 ```
5) En dado caso que tengan instalado Visual estudio ejecutan ``` $ code Vagrantfile ``` sino utilizan ``` $ notepad Vagrantfile ``` y descomentan la linea numero 35 y se guarda el archivo.
6) Una vez hecho el paso anterior podemos iniciar la maquina con el comando ```$ vagrant up```
7) Para iniciar sesión en la maquina virtual se ejecuta el comando ``` $ vagrant ssh ```.
