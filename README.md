# Intermodular-Redes-Locales-
# 1. Análisis de necesidades de red

## Cuántos equipos informáticos tiene la empresa
La empresa cuenta con 3 ordenadores:
- Dos equipos destinados a la gestión de recepción y atención al cliente.
- Un equipo destinado a la administración de la empresa.

## Qué tipo de dispositivos existen
Los dispositivos existentes en la empresa son:
- 3 ordenadores
- 1 impresora

## Qué servicios de red necesitan
La empresa necesita un servicio de red local para permitir la comunicación entre los distintos dispositivos.

## Si necesitan acceso a internet
Sí, la empresa necesita acceso a internet para:
- Consultar páginas web.
- Utilizar aplicaciones ofimáticas como Word y Excel.
- Enviar y recibir información.

## Si necesitan compartir archivos o impresoras
Sí, será necesario que los equipos estén conectados entre sí para:
- Compartir archivos entre los ordenadores.
- Utilizar la impresora desde cualquier equipo de la empresa.



# 2. Diseño de la red

La red estará formada por:
- Un router principal encargado de proporcionar acceso a internet.
- Tres ordenadores conectados a la red local.
- Una impresora conectada a la red para su uso compartido.

Todos los dispositivos estarán conectados dentro de la misma red local para facilitar la comunicación y el intercambio de recursos.


# 3. Plan de direccionamiento IP

| Dispositivo | Dirección IP |
|---|---|
| Red | 192.168.0.0/24 |
| Router | 192.168.0.1 |
| PC1 | 192.168.0.2 |
| PC2 | 192.168.0.3 |
| PC3 | 192.168.0.4 |
| Impresora | 192.168.0.5 |



# 4. Servicios de red básicos

## Compartición de archivos
En el sistema se instalará un servidor de compartición de archivos que permitirá guardar toda la documentación e información de la empresa en una ubicación común accesible desde todos los equipos.

## Compartición de impresoras
Se utilizará un sistema de compartición de impresoras para que todos los ordenadores puedan enviar documentos e imprimir de forma centralizada, facilitando el trabajo y mejorando la productividad de los trabajadores.

## Acceso a internet
El acceso a internet será gestionado por el router, permitiendo a los equipos conectarse a la red pública para:
- Consultar información.
- Enviar y recibir correos electrónicos.
- Utilizar aplicaciones empresariales y ofimáticas.

## Usuarios en red
Cada trabajador dispondrá de un usuario y contraseña propios, mejorando así la seguridad del sistema y permitiendo controlar los accesos y permisos de cada usuario.

## Copias de seguridad en red
El sistema de copias de seguridad permitirá proteger la información de la empresa frente a fallos o pérdidas de datos mediante:
- Copias automáticas.
- Discos duros externos.
- Servicios de almacenamiento en la nube.



# 5. Simulación o explicación de funcionamiento

## Configuración del router
La configuración de la red comenzará con el router, al que se le asignará la dirección IP principal de la red:

- Dirección de red: `192.168.0.0/24`
- Dirección del router: `192.168.0.1`

## Configuración de los PCs
Las direcciones IP de los ordenadores se configurarán manualmente mediante direccionamiento estático.

El rango de direcciones utilizado será:
- `192.168.0.2`
- `192.168.0.3`
- `192.168.0.4`

Asignación:
- PC1 → `192.168.0.2`
- PC2 → `192.168.0.3`
- PC3 → `192.168.0.4`

## Configuración de la impresora
La impresora se configurará mediante conexión FastEthernet utilizando direccionamiento estático.

- Dirección IP de la impresora: `192.168.0.5`

## Comprobación de conectividad entre equipos
Para comprobar el correcto funcionamiento de la red se realizarán pruebas de conectividad mediante el comando `ping`.

Ejemplo:
- Ping desde PC1 (`192.168.0.2`) hacia PC2 (`192.168.0.3`).

Estas pruebas permitirán verificar que todos los dispositivos pueden comunicarse correctamente dentro de la red local.
