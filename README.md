# IT-Sysadmin
Básico-intermedio de administración Linux, redes, LDAP, certificados, scripting y reportería para aplicar a trabajos IT/Sysadmin.

# Primera Semana Linux + Redes (incluye Firewalls)
## Linux
La realidad es que me dedico al Hacking ético, por lo que, practicaré Linux haciendo mis pruebas de concepto (PoC)

![image](https://github.com/user-attachments/assets/fde315b9-638e-4af8-939a-a3004edf8858)
##
### Comando Linux más usados por un Hacker
|Comando  |Descripción  |
|---------|-------------|
|cat      |Muestra el contenido de uno o varios archivos concatenados.|
|df -h    |Se usa para mostrar el uso del espacio en disco de manera legible para humanos.|
|rm -rf   |Se usa para eliminar archivos y directorios de forma recursiva y forzada, sin pedir confirmación.|
|mv       |Se utiliza para mover o renombrar archivos y directorios.|  
|mkdir    |Se usa para crear uno o más directorios (carpetas).|
|unzip    |Se usa para extraer archivos de un archivo comprimido .zip|
|bash     |Se utiliza para ejecutar comandos, scripts y automatizar tareas.|
|Ctrl + Shift + R         |Abrir una nueva terminal dividida al costado (split terminal).
|Ctrl + Shift + T         |Abre una nueva pestaña en la terminal.
|ip a    |Se usa para mostrar las direcciones IP y detalles de las interfaces de red en tu sistema.
|docker ps   |Lista de contenedores corriendo con su ID, nombres, estado, puertos, etc.|
|docker ps -a |Muestra todos los contenedores, incluyendo los detenidos (parados) y activos.|
|docker stop [NAMES or IDs] |Detiene uno o más contenedores en ejecución.|
|docker rm [NAMES or IDs] |Solo puedes eliminar contenedores que estén detenidos (para eliminar uno en ejecución, primero hay que detenerlo).|
|nmap|Nmap (Network Mapper) es una herramienta de código abierto utilizada para explorar redes y llevar a cabo auditorías de seguridad. Su uso principal consiste en escanear redes para descubrir dispositivos activos, detectar puertos abiertos en esos dispositivos, identificar los servicios y versiones que se ejecutan en dichos puertos, y también en detectar el sistema operativo que utiliza cada equipo.|
---
## Redes
Los protocolos como TCP/IP facilitan la comunicación efectiva.
### Software de Red
Cisco IOS

Juniper Junos

Cumulus Linux

### Herramientas de análisis
Ofrecen insides profundos del tráfico de red:

Wireshark

TCPDUMP

### Plataformas de monitoreo
Permiten mantener el rendimiento y seguridad de la red.

Nagios

ZABBIX

OpenNMS

### Tipos de redes

### PAN 
![image](https://github.com/user-attachments/assets/be712989-5950-4974-8d94-0ed30dc69688)

Bluetooth: Permite la transmisión de datos a corta distancia

![image](https://github.com/user-attachments/assets/ea3d506b-59c1-46a5-9ac5-7dc1762509ed)


NFC: Se usa para transacciones rápidas, como pagos móviles, al tocar dos dispositivos.

![image](https://github.com/user-attachments/assets/ff7b1df1-36ec-4280-a4eb-e04b3fcf114f)

### MAN

DQDB (Distributed queue dual bus)

![image](https://github.com/user-attachments/assets/036ef015-888c-4d6f-8341-71d7cfa6a129)

SMDS (Switched multimegabit data service)

### WAN

MPLS (Multiprotocol label switching)

![image](https://github.com/user-attachments/assets/35bb2139-53a0-4ecf-b3e8-2a5030d1eade)

VPN (Virtual Private Network)

![image](https://github.com/user-attachments/assets/be803dd3-ef9a-43cc-9d4b-06214a77895c)

## Firewall
