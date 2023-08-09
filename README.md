# SO-
Comandos Utiles

Comandos Básicos de Ubuntu:

sudo apt update: Actualiza la lista de paquetes disponibles en los repositorios.
sudo apt upgrade: Actualiza los paquetes instalados en el sistema.
sudo apt install apache2: Instala el servidor web Apache en el sistema.
cd /var/www/html: Cambia el directorio actual al directorio de contenido web de Apache.
ls: Lista los archivos y directorios en el directorio actual.
sudo rm index.html: Elimina el archivo index.html en el directorio web de Apache.
sudo nano index.html: Abre el archivo index.html en el editor de texto Nano.
sudo chmod 777 -R: Otorga permisos de lectura, escritura y ejecución a todos los usuarios en todos los archivos y directorios.
mkdir prueba: Crea un nuevo directorio llamado "prueba".
Comandos de Docker:

sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common: Instala paquetes necesarios para manejar fuentes de software seguras.
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -: Descarga y añade la clave GPG para verificar los paquetes de Docker.
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable": Agrega el repositorio de Docker a la lista de fuentes de software.
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose: Instala Docker y sus componentes relacionados.
sudo usermod -aG docker ${USER}: Agrega al usuario actual al grupo "docker" para ejecutar comandos Docker sin "sudo".
sudo systemctl start docker: Inicia el servicio de Docker.
sudo systemctl enable docker: Configura Docker para que se inicie automáticamente al arrancar el sistema.
sudo docker pull ubuntu: Descarga la imagen de Ubuntu desde Docker Hub.
sudo docker pull wordpress: Descarga la imagen de WordPress desde Docker Hub.
sudo docker pull tutum/lamp: Descarga la imagen de LAMP (Linux, Apache, MySQL, PHP) desde Docker Hub.
sudo docker ps -a: Lista todos los contenedores, incluidos los detenidos.
sudo docker rm Ubuntu2: Elimina el contenedor con el nombre "Ubuntu2".
sudo docker search ubuntu: Busca imágenes de Docker relacionadas con Ubuntu en Docker Hub.
docker build -t mi_contenedor_personalizado .: Construye una imagen Docker a partir de un Dockerfile en el directorio actual, etiquetada como "mi_contenedor_personalizado".
docker run mi_contenedor_personalizado: Ejecuta un contenedor a partir de la imagen "mi_contenedor_personalizado".
docker stop mi_contenedor_personalizado: Detiene un contenedor con el nombre "mi_contenedor_personalizado".
docker ps: Lista los contenedores en ejecución.
docker ps -a: Lista todos los contenedores, incluidos los detenidos.
docker exec -it mi_contenedor_personalizado bash: Ejecuta un shell interactivo en un contenedor en ejecución llamado "mi_contenedor_personalizado".
docker volume create portainer_data: Crea un volumen Docker llamado "portainer_data".
docker run -d -p 8000:8000 -p 9000:9000 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce: Ejecuta el contenedor de Portainer para gestionar Docker.
sudo apt-get install -y docker.io: Instala Docker en el sistema.
sudo systemctl start docker: Inicia el servicio de Docker.
sudo systemctl enable docker: Configura Docker para que se inicie automáticamente al arrancar el sistema.
docker --version: Muestra la versión de Docker instalada.
Comandos Básicos de Linux Mint:

ip a: Muestra la información de la dirección IP y la configuración de red.
clear: Limpia la pantalla de la terminal.
pwd: Muestra el directorio de trabajo actual.
ls: Lista los archivos y carpetas en el directorio actual.
ls -l: Lista los archivos y carpetas en formato detallado.
ls -a: Lista los archivos y carpetas, incluidos los ocultos.
man: Muestra el manual del comando especificado.
sudo apt install: Instala paquetes de software utilizando el sistema de administración de paquetes APT.
su root: Inicia sesión como el usuario root.
sudo passwd root: Cambia la contraseña del usuario root.
whoami: Muestra el nombre del usuario actual.
history: Muestra la lista de comandos utilizados anteriormente en la terminal.
nano: Editor de texto en la terminal.
cat: Muestra el contenido de un archivo.
mkdir: Crea una nueva carpeta.
cd: Cambia de directorio.
rm: Elimina un archivo.
cp: Copia archivos o carpetas.
mv: Mueve archivos o cambia su nombre.
Comandos de Lubuntu:

Los comandos son los mismos que los comandos básicos de Linux Mint.
Comandos de Manjaro Linux:

sudo pacman-mirrors --fasttrack && sudo pacman -Syuu: Actualiza los repositorios y los paquetes en Manjaro Linux.
flameshot screen -n 1 -c --region 1367x765+80+50: Captura una captura de pantalla con Flameshot en Manjaro Linux.
sudo nano /etc/network/interfaces: Edita la configuración de red en Manjaro Linux.
sudo nano /etc/pacman.conf: Edita la configuración de Pacman, el administrador de paquetes en Manjaro Linux.
sudo systemctl start NetworkManager: Inicia el administrador de red en Manjaro Linux.
sudo systemctl enable NetworkManager: Habilita el administrador de red para que se inicie automáticamente al arrancar el sistema en Manjaro Linux.
sudo pacman -Syyu: Actualiza los repositorios y los paquetes en Manjaro Linux.
sudo pacman -S package_name: Instala un paquete específico en Manjaro Linux.
sudo pacman -R package_name: Desinstala un paquete específico en Manjaro Linux.
sudo pamac install package_name: Instala un paquete utilizando Pamac, una interfaz gráfica para administrar paquetes en Manjaro Linux.

Comandos Básicos:

ubuntu-ls: Lista los archivos y carpetas en el directorio actual.
ubuntu-ls -l: Lista los archivos y carpetas en formato detallado.
ubuntu-ls -a: Lista los archivos y carpetas, incluidos los ocultos.
ubuntu-pwd: Muestra el directorio de trabajo actual.
ubuntu-cd: Cambia de directorio.
ubuntu-cd ~: Cambia al directorio de inicio del usuario.
ubuntu-mkdir: Crea una nueva carpeta.
ubuntu-touch archivo.txt: Crea un nuevo archivo de texto.
ubuntu-rm archivo.txt: Elimina un archivo.
ubuntu-rmdir carpeta: Elimina una carpeta vacía.
ubuntu-rmdir -rf carpeta: Elimina una carpeta y su contenido de manera recursiva.
ubuntu-cp origen destino: Copia un archivo o carpeta a un destino.
ubuntu-mv origen destino: Mueve un archivo o carpeta a un destino.
ubuntu-cat archivo.txt: Muestra el contenido de un archivo.
ubuntu-less archivo.txt: Muestra el contenido de un archivo de manera interactiva.
ubuntu-chmod permisos archivo: Cambia los permisos de un archivo.
ubuntu-chown usuario:grupo archivo: Cambia el propietario y el grupo de un archivo.
ubuntu-man comando: Muestra el manual de un comando.
ubuntu-history: Muestra el historial de comandos utilizados anteriormente.
ubuntu-echo "Hola, Mundo!": Muestra un mensaje en la terminal.
ubuntu-clear: Limpia la pantalla de la terminal.
ubuntu-whoami: Muestra el nombre del usuario actual.
ubuntu-sudo comando: Ejecuta un comando con privilegios de superusuario.
ubuntu-su: Inicia sesión como el usuario root.
ubuntu-su usuario: Inicia sesión como otro usuario.
ubuntu-ps: Muestra la lista de procesos en ejecución.
ubuntu-top: Muestra una lista de procesos en ejecución y su uso de recursos.
ubuntu-kill PID: Finaliza un proceso por su identificador de proceso (PID).
ubuntu-killall proceso: Finaliza todos los procesos con el nombre especificado.
ubuntu-ping dominio: Verifica la conectividad de red a un dominio.
Comandos Avanzados:

ubuntu-grep patrón archivo.txt: Busca un patrón en un archivo de texto.
ubuntu-find / -name archivo.txt: Busca un archivo en todo el sistema.
ubuntu-locate archivo.txt: Encuentra la ubicación de un archivo.
ubuntu-which comando: Muestra la ruta completa de un comando.
ubuntu-du -h carpeta: Muestra el uso de espacio en disco de una carpeta.
ubuntu-df -h: Muestra el uso de espacio en disco del sistema de archivos.
ubuntu-free -h: Muestra el uso de memoria del sistema.
ubuntu-top -c: Muestra los procesos con sus comandos completos.
ubuntu-htop: Muestra una lista de procesos en ejecución con una interfaz interactiva.
ubuntu-iostat: Muestra estadísticas de uso de CPU y dispositivos de E/S.
ubuntu-netstat -tuln: Muestra las conexiones de red y los puertos abiertos.
ubuntu-ifconfig: Muestra la configuración de red de las interfaces.
ubuntu-ssh usuario@host: Inicia una sesión SSH en un servidor remoto.
ubuntu-scp archivo.txt usuario@host:/ruta: Copia un archivo a través de SSH.
ubuntu-tar -cvf archivo.tar carpeta: Crea un archivo tar de una carpeta.
ubuntu-tar -xvf archivo.tar: Extrae un archivo tar.
ubuntu-gzip archivo.txt: Comprime un archivo en formato gzip.
ubuntu-gunzip archivo.txt.gz: Descomprime un archivo gzip.
ubuntu-service servicio start: Inicia un servicio del sistema.
ubuntu-service servicio stop: Detiene un servicio del sistema.
ubuntu-service servicio restart: Reinicia un servicio del sistema.
ubuntu-ps aux | grep proceso: Filtra los procesos que coinciden con un nombre.
ubuntu-kill -9 PID: Fuerza la finalización de un proceso por su PID.
ubuntu-htop -u usuario: Muestra los procesos en ejecución de un usuario específico.
ubuntu-lsof -i: Lista los archivos abiertos y los puertos de red.
ubuntu-iptables -L: Muestra las reglas del firewall iptables.
ubuntu-useradd nuevo_usuario: Agrega un nuevo usuario al sistema.
ubuntu-userdel usuario: Elimina un usuario del sistema.
ubuntu-adduser nuevo_usuario: Interfaz interactiva para agregar un usuario.
ubuntu-deluser usuario: Interfaz interactiva para eliminar un usuario.
ubuntu-addgroup nuevo_grupo: Agrega un nuevo grupo al sistema.
ubuntu-delgroup grupo: Elimina un grupo del sistema.
ubuntu-visudo: Edita el archivo sudoers para configurar los permisos de sudo.
ubuntu-mount dispositivo punto_de_montaje: Monta un dispositivo en un punto de montaje.
ubuntu-umount punto_de_montaje: Desmonta un dispositivo montado.
Comandos Específicos de Ubuntu:

ubuntu-apt update: Actualiza la lista de paquetes disponibles en los repositorios.
ubuntu-apt upgrade: Actualiza los paquetes instalados en el sistema.
ubuntu-apt install paquete: Instala un paquete de software.
ubuntu-apt remove paquete: Desinstala un paquete de software.
ubuntu-apt search término: Busca paquetes en los repositorios.
ubuntu-apt-cache show paquete: Muestra información detallada sobre un paquete.
ubuntu-apt-get autoremove: Elimina los paquetes no utilizados y sus dependencias.
ubuntu-apt-get clean: Limpia la caché de paquetes descargados.
ubuntu-apt-get purge paquete: Desinstala un paquete y sus archivos de configuración.
ubuntu-aptitude: Interfaz avanzada para gestionar paquetes.
ubuntu-add-apt-repository repositorio: Agrega un repositorio PPA al sistema.
ubuntu-ppa-purge ppa: Elimina un repositorio PPA y sus paquetes.
ubuntu-apt-file search archivo: Busca paquetes que contienen un archivo específico.
ubuntu-ufw enable: Habilita el firewall Uncomplicated Firewall (UFW).
ubuntu-ufw disable: Deshabilita el firewall UFW.
Comandos Específicos de Lubuntu:

lubuntu-pcmanfm: Abre el administrador de archivos PCManFM.
lubuntu-lxterminal: Abre la terminal LX.
lubuntu-openbox-settings: Abre la configuración de Openbox.
lubuntu-leafpad: Abre el editor de texto Leafpad.
lubuntu-logout: Cierra la sesión actual.
Comandos Específicos de Linux Mint:

mint-update: Abre la herramienta de actualización de Linux Mint.
mint-install: Abre el administrador de software de Linux Mint.
mint-welcome: Abre la ventana de bienvenida de Linux Mint.
mint-backup: Abre la herramienta de copia de seguridad de Linux Mint.
mint-nm-applet: Abre el applet de administración de red de Linux Mint.
mint-screenshot: Abre la herramienta de captura de pantalla de Linux Mint.
mint-locale: Abre la configuración regional y de idioma de Linux Mint.
Comandos Específicos de Manjaro Linux:

manjaro-pacman-mirrors: Actualiza los repositorios de Manjaro Linux.
manjaro-pacman -Syu: Actualiza el sistema y los paquetes.
manjaro-pacman -S paquete: Instala un paquete en Manjaro Linux.
manjaro-pacman -R paquete: Desinstala un paquete en Manjaro Linux.
manjaro-pacman -Q: Muestra la lista de paquetes instalados.
manjaro-pamac: Abre la interfaz gráfica de Pamac, el administrador de paquetes.
manjaro-mhwd: Configura los controladores de hardware en Manjaro.
manjaro-architect: Abre la herramienta de instalación personalizada de Manjaro.
manjaro-mhwd-kernel: Instala o cambia el kernel en Manjaro Linux.
manjaro-xfce-settings: Abre las configuraciones del entorno de escritorio XFCE.
manjaro-kde-settings: Abre las configuraciones del entorno de escritorio KDE.
manjaro-i3-settings: Abre las configuraciones del entorno de escritorio i3.
manjaro-system: Abre las herramientas del sistema de Manjaro.
Comandos del Sistema:

manjaro-systemctl enable servicio: Habilita un servicio para que se inicie automáticamente al arrancar el sistema.
manjaro-systemctl start servicio: Inicia un servicio.
manjaro-systemctl stop servicio: Detiene un servicio.
manjaro-systemctl restart servicio: Reinicia un servicio.
manjaro-systemctl status servicio: Muestra el estado de un servicio.
manjaro-systemctl --failed: Muestra los servicios que han fallado.
manjaro-journalctl -xe: Muestra el registro del sistema.
manjaro-timedatectl: Muestra y configura la fecha y hora del sistema.
manjaro-reboot: Reinicia el sistema.
manjaro-poweroff: Apaga el sistema.
manjaro-shutdown: Apaga y cierra el sistema.
manjaro-mkdir: Crea un nuevo directorio.
manjaro-rmdir: Elimina un directorio vacío.
manjaro-rmdir -rf: Elimina un directorio y su contenido de manera recursiva.
manjaro-touch: Crea un nuevo archivo vacío.
manjaro-echo: Muestra un mensaje en la terminal.
Comandos de Paquetes y Repositorios:

manjaro-pacman -U paquete.tar.xz: Instala un paquete local en Manjaro.
manjaro-pacman -Qs paquete: Busca información sobre un paquete instalado.
manjaro-pacman -Ql paquete: Lista los archivos instalados por un paquete.
manjaro-pacman -Qii paquete: Muestra información detallada sobre un paquete instalado.
manjaro-pacman -Qdt: Lista paquetes huérfanos (sin dependencias).
manjaro-pacman -Rns paquete: Desinstala un paquete y sus dependencias no utilizadas.
manjaro-pacman-mirrors: Configura los espejos de los repositorios.
manjaro-pacman -U URL_del_paquete: Instala un paquete desde una URL remota.
manjaro-pacman -U https://ruta-del-archivo/paquete.tar.xz: Instala un paquete desde una URL.
manjaro-pacman -Syyu: Actualiza el sistema y los paquetes.
manjaro-pacman -Syu --ignore paquete: Ignora un paquete durante la actualización.
manjaro-pacman -S paquete: Instala un paquete desde los repositorios.
manjaro-pacman -Syy: Actualiza la base de datos de paquetes.
manjaro-pacman -Sc: Limpia la caché de paquetes.
manjaro-pacman -Scc: Limpia la caché de paquetes y las firmas.
manjaro-pacman -Ss término: Busca paquetes en los repositorios.
Comandos de Controladores de Hardware:

manjaro-mhwd --list: Lista los controladores de hardware disponibles.
manjaro-mhwd --install controlador: Instala un controlador de hardware.
manjaro-mhwd --remove controlador: Elimina un controlador de hardware.
manjaro-mhwd --auto-configure: Configura automáticamente los controladores de hardware.
Comandos del Gestor de Pantalla:

manjaro-lightdm-settings: Abre las configuraciones de LightDM, el gestor de pantalla.
manjaro-lightdm-webkit-theme: Instala y configura temas webkit para LightDM.
manjaro-lxdm-settings: Abre las configuraciones de LXDM, otro gestor de pantalla.
Comandos de Red y Conectividad:

manjaro-ip a: Muestra información de la configuración de red.
manjaro-ping dominio: Prueba la conectividad a un dominio.
manjaro-ifconfig: Muestra la configuración de red de las interfaces.
manjaro-nmcli: Interfaz de línea de comandos para administrar conexiones de red.
Comandos de Audio y Multimedia:

manjaro-pulseaudio --start: Inicia el servidor de sonido PulseAudio.
manjaro-pavucontrol: Abre el control de volumen de PulseAudio.
manjaro-mpris2: Controla la reproducción de multimedia con MPRIS.
Comandos de Hardware y Energía:

manjaro-acpi: Muestra información sobre el estado de la batería y la temperatura.
manjaro-lsusb: Lista los dispositivos USB conectados.
manjaro-lspci: Lista los dispositivos PCI conectados.

l libnet-ssleay-perl libauthen-pam-perl libio-pty-perl apt-show-versions sudo apt-get install webmin sudo rebootResetear el password de Root
1: Reiniciar el equipo
2: Abrir el GRUB y seleccionar "Opciones Avanzadas"
3: Presionar 'e'
4: Buscar la linea que inicia con 'ro' y cambielo a 'rw'
5: Agregue init=/bin/bash al final de la linea
6: Presione F10
7: Monte su sistema de archivos con el comando mount -n -o remount,rw /
8: Resetea la contraseña con passwd root
9: Digite exec /sbin/init para salir

Lista los discos duros y sus particiones
lsblk

Grabar la pantalla desde la terminal
sudo apt-get install libav-tools
avconv -f x11grab -s 1024x768 -r 25 -i :0.0 -qscale 0 screen.mp4

Desbloquear con BlueTooth
# http://blog.desdelinux.net/blueproximity-o-como-bloquear-tu-pc-al-alejarte-con-tu-telefono-movil/
sudo apt-get install blueproximity

Crear un Servidor multimedia DLNA
sudo apt-get install mediatomb

Obtener la fecha de instalación del sistema
ls -lct /etc | tail -1 | awk '{print $6, $7, $8}' 

Respaldar Paquetes instalados
dpkg --get-selections > listadepaquetesdebinstalados
#Restaurando los paquetes
dpkg --set-selections < listadepaqueresdebinstalados
apt-get update
apt-get dselect-upgrade
apt-get dist-upgrade

Recuperar discos duros dañados
badblocks -s -v -n -f /dev/sdb
# NTFS No se monta
sudo ntfsfix /dev/sdXY

Para monitorear el ancho de banda
# g para ver una grafica
# d para estadisticas detalladas
sudo apt-get install bmon
# Para ver el consumo de ancho de banda por aplicacion
sudo apt-get install nethogs
#Limitar el ancho de banda
sudo wondershaper eth0 1024 512 
# El ejemplo anterior limita la conexión a 1024kbps de bajada y 512kbps de subida

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
# Elimina los archivos
fdupes -d /home/$USER/Desktop/tecmint

Parches a archivos de texto
## Crear:
diff -u archivo.antiguo archivo.nuevo >archivo.patch
## Aplicar
patch -p0 archivo.viejo <archivo.patch

Monta una carpeta remota por SSH
# sudo apt-get install sshfs
sshfs user@www.dominio.com:/home/user /mnt/carpeta
# El usuario debe tener permisos de escritura sobre /mnt/carpeta
sudo modprobe fuse
ssh-keygen en cliente
ssh-copy-id -i $HOME/.ssh/id_rsa.pub usuario@servidor

Desproteger PDF
qpdf --decrypt protected.pdf unprotected.pdf
# Si el archivo PDF está protegido con un password
qpdf --decrypt --password prueba1234 protected.pdf unprotected.pdf

Sustituir caracteres por otro en un documento masivamente
## Reemplaza la palabra paco por Francisco
sed -i 's/paco/Francisco/g' *.txt

Unir PDF
pdfunite ejemplo2.pdf ejemplo3.pdf ejemplo4.pdf ejemplo5.pdf resultado.pdf
## Separar PDF
## Separa un pdf en archivos diferentes
## -f Pagina Inicial
## -l Pagina Final
pdfseparate -f 2 -l 32 documento.pdf resultado_%d.pdf

Convertir PDF a JPG
convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0 archivo.pdf salida.jpg
## Script para hacerlo masivo

#/bin/bash
for file in *.pdf;do 
	convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0 $file $file.jpg
done

Crear archivo aleatorio
# En este caso se utiliza /dev/urandom como fuente de entropía,
# la cual se volcara en el archivo de pruebas llamado archivo.bin.
# En este ejemplo se quiso generar un archivo con un tamaño de 256 MB
# y como /dev/urandom tiene una salida de 512 bytes se utiliza la opción count=500000
dd if=/dev/urandom of=archivo.bin count=500000

Ejecutar un script desde internet
wget -q -O - https://raw.githubusercontent.com/mortasoft/scripts/master/13.%20Crear%20Ventanas.sh | bash /dev/stdin

Imagen a Texto
# Fuente: http://geekland.eu/extraer-texto-imagen-con-ocrfeeder/
sudo apt-get install ocrfeeder tesseract-ocr tesseract-ocr-spa tesseract-ocr-eng gocr cuneiform ocropusocrad
ocrfeeder

Buscar texto
# mydomain.com 
grep -r "mydomain.com" /etc/apache2/

# Buscar archivo y quitar los mensajes de error
find / -name foo 2>/dev/null

Reiniciar Cinnamon
killall -HUP cinnamon-session

Respaldo Rsync
#Respaldo RSYNC
rsync -r -t -v --progress -s mortasoft@koala:/datos/Soporte /home/mortasoft/Koala

Flush Rules
iptables -F
iptables -X
iptables -Z
iptables -t nat -F

Listar Archivos de una carpeta a un archivo
for f in *;do echo $f>>archivo.txt;done

Docker
sudo usermod -aG docker $(whoami)
docker pull ubuntu
docker run ubuntu
#Da un shell interactivo
docker run -it ubuntu
# docker commit -m "Primera Imagen" -a "mortasoft" 7100a984f6f7 mortasoft/ubuntu1
# docker stop container-id

Ataque DDOS
sudo hping3 192.232.217.2 --flood -V

Disable Cups Service
sudo systemctl disable cups.service

Importar certificado OpenVPN en Kubuntu
sudo nmcli connection import type openvpn file Zenbook.ovpn

Instalar Megasync en Kali Linux
wget --inet4-only -O- https://mega.nz/linux/repo/Debian_testing/Release.key | gpg --dearmor | sudo tee /usr/share/keyrings/megasync-archive-keyring.gpg
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/megasync-archive-keyring.gpg] https://mega.nz/linux/repo/Debian_testing ./" | sudo tee /etc/apt/sources.list.d/megasync.list
sudo apt update && sudo apt -y full-upgrade && sudo apt autoremove
sudo apt install megasync
sudo apt install nautilus-megasync

Kali Linux Multiple Eth Adapters
sudo nano /etc/network/interfaces:
# This file describes the network interfaces available on your system
# and how to activate them. For more information, see interfaces(5).

# The loopback network interface
auto lo
iface lo inet loopback

# The primary network interface
allow-hotplug eth0
iface eth0 inet dhcp

allow-hotplug eth1
iface eth1 inet dhcp

Actualizar repositorios en Manjaro
sudo pacman-mirrors --fasttrack && sudo pacman -Syuu

Comando para tomar screenshots CEH
flameshot screen -n 1 -c --region 1367x765+80+50

Comando para instlar Webmin
echo "deb http://download.webmin.com/download/repository sarge contrib" | sudo tee /etc/apt/sources.list.d/webmin.list cd ~/ wget http://www.webmin.com/jcameron-key.asc sudo apt-key add jcameron-key.asc rm jcameron-key.asc sudo apt-get update sudo apt-get install libapt-pkg-per


