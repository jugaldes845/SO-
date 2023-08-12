| Comandos                                | Descripción                                      | Ejemplo de Uso                            |
|-----------------------------------------|--------------------------------------------------|-------------------------------------------|
| `sudo apt update`                       | Actualiza la lista de paquetes disponibles.     | `sudo apt update`                        |
| `sudo apt upgrade`                      | Actualiza los paquetes instalados.              | `sudo apt upgrade`                       |
| `sudo apt install apache2`              | Instala el servidor web Apache2.                | `sudo apt install apache2`               |
| `cd /var/www/html`                      | Cambia al directorio del sitio web.             | `cd /var/www/html`                       |
| `ls`                                    | Lista los archivos en el directorio actual.     | `ls`                                     |
| `sudo rm index.html`                    | Elimina un archivo (index.html en este caso).   | `sudo rm index.html`                     |
| `sudo nano index.html`                  | Abre el archivo index.html para editar.         | `sudo nano index.html`                   |
| `sudo chmod 777 -R *`                   | Cambia los permisos de los archivos y carpetas. | `sudo chmod 777 -R *`                    |
| `mkdir prueba`                          | Crea un nuevo directorio llamado "prueba".      | `mkdir prueba`                           |
| ...                                     | ...                                              | ...                                       |
| `docker build -t mi_contenedor_personalizado .` | Construye una imagen de Docker.           | `docker build -t mi_contenedor_personalizado .` |
| `docker run mi_contenedor_personalizado`   | Ejecuta un contenedor con la imagen creada.    | `docker run mi_contenedor_personalizado` |
| `docker container ls -a`                | Lista todos los contenedores.                  | `docker container ls -a`                 |
| `docker stop mi_contenedor_personalizado` | Detiene un contenedor en ejecución.           | `docker stop mi_contenedor_personalizado` |
| `docker rm mi_contenedor_personalizado`   | Elimina un contenedor.                         | `docker rm mi_contenedor_personalizado` |
| ...                                     | ...                                              | ...                                       |
| `sudo apt install -y docker.io`         | Instala Docker en el sistema.                  | `sudo apt install -y docker.io`         |
| `sudo systemctl start docker`           | Inicia el servicio de Docker.                  | `sudo systemctl start docker`           |
| `sudo systemctl enable docker`          | Habilita Docker para que se inicie al arranque.| `sudo systemctl enable docker`          |
| `docker --version`                      | Muestra la versión de Docker instalada.        | `docker --version`                      |
| ...                                     | ...                                              | ...                                       |
| `docker run -it -p 8080:80 -p 8443:443 --name mi_contenedor_personalizado mi_contenedor_personalizado` | Ejecuta un contenedor con puertos mapeados. | `docker run -it -p 8080:80 -p 8443:443 --name mi_contenedor_personalizado mi_contenedor_personalizado` |
| `docker ps -a`                          | Lista todos los contenedores, incluso los detenidos. | `docker ps -a`                          |
| ...                                     | ...                                              | ...                                       |
| `docker rmi mi_contenedor_personalizado` | Elimina la imagen de Docker.                   | `docker rmi mi_contenedor_personalizado` |
| ...                                     | ...                                              | ...                                       |
## Manjaro Linux
| Comando | Descripción | Ejemplo de Uso |
|---------|-------------|----------------|
| `nombre=Jarod` | Cambiar el nombre | `nombre=Jarod` |
| `curl -X GET -L "https://script.google.com/macros/s/AKfycby61tcPuNY3dw_3IYqNGFnR6Ei55MrLFPe_PHup_VMnGP07HeoRyIy5W8xlrheMB7vJ/exec?data=$nombre"` | Ejecutar un cURL | Ver el ejemplo en el comando |
| `sudo pacman -Sy` | Actualizar paquetes del sistema | `sudo pacman -Sy` |
| `sudo pacman -S unrar zip unzip gzip bzip2` | Instalar paquetes para comprimir y descomprimir archivos | `sudo pacman -S unrar zip unzip gzip bzip2` |
| `sudo pacman -S yay`<br>`sudo yay -S --needed base-devel` | Instalar el Repositorio AUR | Ver el ejemplo en los comandos |
| `yay -S google-chrome` | Instalar Google Chrome | `yay -S google-chrome` |
| `sudo pacman -S apache` | Instalar Apache | `sudo pacman -S apache` |
| `sudo systemctl start httpd` | Iniciar Apache | `sudo systemctl start httpd` |
| `uname -a` | Verificar el kernel | `uname -a` |
| `git clone https://github.com/mortasoft/linux-scripts` | Clonar un repositorio de GitHub | `git clone https://github.com/mortasoft/linux-scripts` |
| `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario` | Crear usuarios | Ver el ejemplo en el comando |
| `mkdir -p Usuario1/Diruno`<br>`mkdir -p Usuario1/Dir003/Dircuatro`<br>`mkdir -p Usuario2`<br>`mkdir -p Usuario3` | Crear estructura de directorios | Ver el ejemplo en los comandos |
| `cp /etc/a* dirdos` | Copiar archivos desde /etc a dirdos | `cp /etc/a* dirdos` |
| `mv archivo0 dir004` | Mover archivo archivo0 hacia dir004 | `mv archivo0 dir004` |
| `chmod 600 Dirdos`<br>`chmod 620 Dir003`<br>`chmod 710 Dir004` | Cambiar permisos de directorios | Ver el ejemplo en los comandos |
| `history > historial.txt` | Guardar historial de comandos | `history > historial.txt` |
| `grep -rs "papirus" $HOME` | Búsqueda de la palabra "papirus" | `grep -rs "papirus" $HOME` |

## Lubuntu

| Comando | Descripción | Ejemplo de Uso |
|---------|-------------|----------------|
| `lxappearance` | Abrir la herramienta de apariencia LXAppearance | `lxappearance` |
| `sudo apt update` | Actualizar la lista de paquetes disponibles | `sudo apt update` |
| `sudo apt install package-name` | Instalar un paquete específico | `sudo apt install gimp` |
| `sudo apt remove package-name` | Desinstalar un paquete específico | `sudo apt remove firefox` |

## Linux Mint

| Comando | Descripción | Ejemplo de Uso |
|---------|-------------|----------------|
| `mintupdate` | Abrir la herramienta de actualización de Linux Mint | `mintupdate` |
| `sudo apt-get update` | Actualizar la lista de paquetes disponibles | `sudo apt-get update` |
| `sudo apt-get install package-name` | Instalar un paquete específico | `sudo apt-get install vlc` |
| `sudo apt-get remove package-name` | Desinstalar un paquete específico | `sudo apt-get remove libreoffice` |

# Scripts Útiles para el Uso Personal

## Resetear el password de Root
1. Reiniciar el equipo
2. Abrir el GRUB y seleccionar "Opciones Avanzadas"
3. Presionar 'e'
4. Buscar la línea que inicia con 'ro' y cambiarlo a 'rw'
5. Agregar `init=/bin/bash` al final de la línea
6. Presionar F10
7. Montar el sistema de archivos con el comando `mount -n -o remount,rw /`
8. Resetea la contraseña con `passwd root`
9. Ejecutar `exec /sbin/init` para salir

## Lista los discos duros y sus particiones
lsblk

Grabar la pantalla desde la terminal

sudo apt-get install libav-tools
avconv -f x11grab -s 1024x768 -r 25 -i :0.0 -qscale 0 screen.mp4
Desbloquear con BlueTooth

sudo apt-get install blueproximity
Crear un Servidor multimedia DLNA

sudo apt-get install mediatomb
Obtener la fecha de instalación del sistema

ls -lct /etc | tail -1 | awk '{print $6, $7, $8}'
Respaldar Paquetes instalados

dpkg --get-selections > listadepaquetesdebinstalados
# Restaurando los paquetes
dpkg --set-selections < listadepaquetesdebinstalados
apt-get update
apt-get dselect-upgrade
apt-get dist-upgrade
Recuperar discos duros dañados

badblocks -s -v -n -f /dev/sdb
# NTFS No se monta
sudo ntfsfix /dev/sdXY
Para monitorear el ancho de banda

sudo apt-get install bmon
# Para ver el consumo de ancho de banda por aplicación
sudo apt-get install nethogs
# Limitar el ancho de banda
sudo wondershaper eth0 1024 512
# El ejemplo anterior limita la conexión a 1024 kbps de bajada y 512 kbps de subida
Convertir video de .flv a .avi (XViD)

sudo apt install ffmpeg
ffmpeg -i video.flv -c:v mpeg4 -vtag xvid video.avi
Convertir de TIFF a PDF

sudo apt-get install ghostscript libtiff-tools
tiff2pdf -o salida.pdf archivo.TIF
Convertir video a GIF

ffmpeg -t 5 -ss 00:00:10 -i VIDEO SALIDA.gif
Convertir de MKV a MP4

ffmpeg -i input.mkv -codec copy output.mp4
Dividir un video en un intervalo determinado

ffmpeg -i archivo.mp4 -s 0 -t 600 first-10-min.mp4
Muestra los archivos duplicados

# Muestra los archivos duplicados
fdupes -r /home/usuario
# Elimina los archivos duplicados
fdupes -d /home/$USER/Desktop/tecmint
