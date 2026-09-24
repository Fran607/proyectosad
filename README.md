# Proyecto SAD
 
## Autor
 
Francisco Cervantes López
 
## Descripción
 
Infraestructura virtualizada desarrollada con Vagrant para la asignatura Seguridad y Alta Disponibilidad.
 
La infraestructura incluye:
 
- gw
- proxy
- www
- idp
- adminpc
- empleadopc
 
## Redes
 
- DMZ: 172.1.1.0/24
- LAN Empleados: 172.2.1.0/24
- LAN Gestión: 172.3.1.0/24
 
## Comandos básicos
 
Levantar la infraestructura:
 
```bash
vagrant up
```
 
Recargar configuración:
 
```bash
vagrant reload --provision
```
 
Acceder a una máquina:
 
```bash
vagrant ssh nombre_maquina
```
 
Apagar máquinas:
 
```bash
vagrant halt
```
 
Destruir infraestructura:
 
```bash
vagrant destroy -f
```