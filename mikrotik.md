#  Mikrotīkls SIA!

## ¿Quienes son MikroTik ?
Es una empresa letona fundada en 1996 para desarrollar enrutadores y sistemas de ISP inalámbricos. MikroTik ahora ofrece hardware y software para la conectividad a Internet en la mayoría de los países del mundo. su experiencia en el uso de hardware de PC estándar de la industria y los sistemas de enrutamiento completos les  permitió en 1997 crear el sistema de software RouterOS que proporciona una gran estabilidad, controles y flexibilidad para todo tipo de interfaces de datos y enrutamiento. En 2002 decidieron  hacer su propio hardware, y nació la marca RouterBOARD. Tienen  revendedores en la mayor parte del mundo y clientes en todos los países del planeta. La empresa está ubicada en Riga, la capital de Letonia y cuenta con más de 140 empleados

##   ¿Qué Es Mikrotik RouterOS?
MilkroTik RouterOS es un sistema operativo basado en el kernel de Linux 2.6 usado en el ardware de los Microtik RouterBOARD que es la división de hardware de la marca Mikrotik. Se caracteriza por poseer su propio S.O de fácil configuración. Estos dispositivos poseen la ventaja de tener una relación costo /beneficio muy alta.

Ahora, lo que hace interesante a un RouterOS es que puede ser instalado en una computadora, convirtiéndola en un router con todas las características necesarias: firewall, routing, punto de acceso wireless, administración de ancho de banda, servidor VPN y más


# Configuración

RouterOS soporta varios métodos de configuración

- Acceso local vía teclado y monitor
- Consola serial con una terminal
- Acceso vía Telnet y SSH vía una red
- Una interfaz gráfica llamada WinBox
- Una API para el desarrollo de aplicaciones propias para la configuración
- En caso de no contar con acceso local y existe un problema con las direcciones IP RouterOS soporta una conexión basada en direcciones MAC usando las herramientas customizadas Mac-Telnet y herramientas de Winbox

A Partir de su versión RouterOS v4 agrega el lenguaje de Scripting Lua, que expande las posibilidades para programar y automatizar el sistema.

Vamos a ver ahora todos los features que nos brinda RouterOS, ya sea que lo usemos en un RouterBoard o en una PC.

#### Firewall

El firewall integrado implementa el filtrado de paquetes y provee funciones de seguridad que son usadas para el manejo del flujo de datos desde y hacia el router. Junto con el NAT, previene el acceso no autorizado a una red conectada directamente. Puede filtrar por direcciones IP, tuerto TCP/UDP, rango de puertos, protocolos, entre otros parámetros. Soporta además lista de direcciones estáticas y dinámicas y puede interceptar paquetes con un patrón definido. Cuenta además con soporte para IPv6.

##### Routing

RouterOS soporta rutas estáticas y varios protocolos de rutas dinámicas.

- Para IPv4 soporta RIP v1 y v2, OSPF v2, BGP v4
- Para IPv6 soporta RIPng, OSPFV v3 y BGP

También soporta VRF, políticas basadas en rutas, rutas basadas en interfaz y ECMP. Se puede utilizar el Firewall para marcar los paquetes que lleguen desde una conexión determinada y que estos salgan por un proveedor distinto.Create files and folders

#### MPLS

MPLS (Multiprotocol Label Switching), puede ser utilizado para reemplazar los paquetes IP salientes, la decisión del reenvío ya no se realiza en base al header IP o tabla de enrutamiento, sino en etiquetas adjuntadas al paquete. Este acercamiento acelera el reenvío del paquete porque la búsqueda del destino es más simple que la búsqueda del  enrutamiento. La Eficiencia en el proceso de reenvío es el mayor beneficio de MPLS.

Algunos de los features de MPLS soportados son:

## Aplicaciones de seguridad de Mikrotik RouterOS

- **Seguridad Wireless.** La seguridad siempre ha de ser una prioridad en Internet, para ti como proveedor de servicio hacia tus suscriptores y para que ellos tengan la garantía de que están trabajando con una empresa seria. *Mikrotik RouterOS* te ofrece las máximas posibilidades en este campo.

-   **Firewall NAT.** Evidentemente Mikrotik te ofrece aplicaciones de última tecnología para impedir que alguien pueda entrar en tu red.


## Aplicaciones de seguridad de gestión y control de Mikrotik RouterOS

- **Servidor de VPN.** Consiguiendo que todas tus sucursales funcionen como una red única.

-  **Control de prioridad P2P.** Para que nunca tengas problemas en tu red esta aplicación te permitirá controlar el tráfico P2P.

-  **Tareas programadas.** El software de Mikrotik te permite programas todas las tareas básicas de mantenimiento en determinados horarios, lo que te da la tranquilidad de saber que todos los equipos son controlados puntualmente.


## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions




## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

| Tipo / Caracteristicas |RB951G-2HnD |RB951Ui-2HnD-03                |
|----------------|-------------------------|----------------------|
|Producto |![](http://www.mikrotik-mexico.com.mx/wp-content/uploads/2017/07/RB951G-2HnD.jpg)            |![](http://www.mikrotik-mexico.com.mx/wp-content/uploads/2017/07/RB951G-2HnD.jpg)            |
|10/100/1000 Ethernet ports          |`'10/100'` 5             |    5            |
|802.11b          |`Yes`|Yes|
|802.11g          |`Yes`|Yes|
|802.11n          |`Yes`|Yes|
|Antenna gain          |`2.5`|2.5|
|CPU          |`AR9344`|AR9344|
|CPU core count     |1|1|
|CPU nominal frequency |`	600 MHz`|	600 MHz|


##  Enrutadores Ethernet 

|  Tipo / Caracteristicas |hEX lite |  RB2011iLS-IN  | CCR1036-12G-4S-EM|
|----------------|-------------------|-----------------------------|------|
|Imagen |![](https://img.routerboard.com//mimg/1040_m.png)          |![](https://img.routerboard.com//mimg/1106_m.png)    | ![](https://img.routerboard.com//mimg/1307_m.png)  |
|CPU  | 850MHz  |   600MHz   | 36 núcleos x CPU de 1.2GHz|
|RAM      |64MB| 64MB | 16GB |
|RouterOS   |RouterOS L4|RouterOS L4| RouterOS L6 |
|Otros         |5x Ethernet, caja de plástico pequeña| Carcasa metálica de escritorio, 5xEthernet, 5xGigabit Ethernet, jaula SFP, PoE out en el puerto 10 | 1U rackmount, 12x Gigabit Ethernet, 4xSFP jaulas, LCD,24 mpps fastpath, Hasta 16 Gbit / s de rendimiento|

