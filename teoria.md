# Servicios de Red DNS y LDAP

## Servicios de red implicados en el despliegue de aplicaciones web

Se estudian 2 servicios red para el despliegue de aplicaciones web: 
- DNS (Servicio de Nombres de Dominio).
- Servicio de directorio LDAP.

Son importantes para hacerla de forma mas amigable para el usuario y ayudar a la gestión de los accesos a los servicios.


- DNS: sirve para traducir nombres de dominio legibles por los humanos en direcciones IP numéricas.
- Servicio de directorio LDAP: és una plataforma que organiza y almacena información de manera jerárquica, facilitando la gestión centralizada y el acceso eficiente a datos de usuarios, dispositivos y recursos en una red.


## Servicio DNS (Domain Name System)

### Introducción

El sistema de nombres de dominio DNS es un mecanismo eficaz para llevar a cabo la resolución de nombres de dominio (por ejemplo, www.gva.es) a direcciones IP (por ejemplo, 193.144.127.85). También permite la resolución inversa. Es decir, a partir de una IP averiguar el nombre de dominio.

El servicio DNS proporciona independencia del nombre de dominio respecto a la IP. Así un dominio puede cambiar de IP de forma transparente para los usuarios del dominio. Es usual que un dominio se identifique con más de una IP como medida de redundancia contra la caída del sistema o como balanceo de cargas. 

Otros servicios proporcionados por el DNS son la identificación de los servidores de correo de un dominio, de cada uno de los hosts que pertenecen a la red, servidores de impresión, etc.


### Sistemas de nombres planos y jerárquicos

