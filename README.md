# Linux_vm
Las máquinas virtuales (VM) de Azure se pueden crear a través de Azure Portal. Azure Portal es una interfaz de usuario basada en explorador para crear recursos de Azure. Este inicio rápido muestra cómo usar Azure Portal para implementar una máquina virtual (VM) Linux que ejecuta Ubuntu 20.04 LTS. Para ver la máquina virtual en acción, también debe SSH a la máquina virtual e instalar mobaxterm
## Pasos
Descargar previo el programa Mobaxterm
https://mobaxterm.mobatek.net/download-home-edition.html

-- Ingresemos al root
1. sudo su
-- Actualizamos la lista de paquetes disponibles y sus versiones
2. apt-get update 
-- Instalamos
3. apt-get install ubuntu-desktop 
4. apt-get install --reinstall ubuntu-desktop
5. nano script1.sh
6. chmod +x script1.sh
-- Copiamos el script
7. ./script1.sh
8. apt install xfce4 slim
9. service slim start
-- Reiniciamos
10. reboot
11. Cerramos mobaxterm
12. Añadimos una regla de puerto de entrada -> RDP
13. Iniciamos una nueva sesion de tipo RDP con la IP Publica
