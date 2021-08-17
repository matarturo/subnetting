Autor: Arturo Mata <arturo.mata@gmail.com>
Script: ping.py
Version: 1.0.0
Repositorio: https://github.com/matarturo/
Released under the GNU General Public License WITHOUT ANY WARRANTY.
See LICENSE.TXT for details.

# Este script escrito en Python, analiza segmentos red para validar los hosts activos

Es importante el mantenimiento periódico de estos equipos ya que los archivos logs del entorno GNU/Linux DebianOS 
crecen rápidamente y se pueden llenar los discos duros generando problemas de almacenamiento de información.

# Requisitos 

Nmap => apt install nmap
Python => apt install python3
Pip Python => pip install python-nmap

# Descarga e instalación del script
Para correr este script se requiere ingresar al equipo con credenciales de usuario < root >

$ cd /var/log
$ sudo git clone https://github.com/matarturo/scan_subnet.git
$ cd scan_subnet
$ sudo cp ping.py /var/log
$ cd /var/log

#Para editar el script
$ sudo nano ping.py  

# Ejecución del script
$ sudo python3 ping.py 

#Detener el proceso de busqueda.
Pulsar simultaneamente las teclas CRTL+C

#Una vez obtenido el reporte de hosts activos, se detener el programa 
$ exit
