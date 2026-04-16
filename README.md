# Laboratorio 4 - Redes

En este laboratorio se configura y verifica el funcionamiento de distintos **protocolos de enrutamiento dinámico** en varias topologías de red, trabajando con **IPv4 e IPv6** en **Cisco Packet Tracer**.

## Objetivo

El laboratorio busca comprender el rol de los protocolos de enrutamiento dinámico y sus diferencias, además de implementar escenarios prácticos con routers Cisco. Entre los objetivos se incluyen la configuración de **RIP**, **OSPF** y distintas formas de enrutamiento en **IPv6**. :contentReference[oaicite:1]{index=1}

## Contenido del laboratorio

El trabajo se divide en tres topologías principales:

- **Topología 1:** RIPv1 y OSPF
- **Topología 2:** BGP
- **Topología 3:** RIPng y OSPFv3 

## Protocolos trabajados

### RIPv1
Protocolo de enrutamiento de **vector-distancia** que utiliza el **número de saltos** como métrica. Es una versión **con clase**, por lo que no envía máscara de subred en sus actualizaciones.

### OSPF
Protocolo de **estado de enlace** que calcula la mejor ruta con base en el **costo**, asociado al ancho de banda. Se usa ampliamente en redes más complejas por su mejor convergencia.

### BGP
Protocolo utilizado para el enrutamiento entre **sistemas autónomos**. En este laboratorio se trabaja como parte de la Topología 2. 

### RIPng
Versión de RIP para **IPv6**, basada en RIPv2, usada en la Topología 3. 

### OSPFv3
Versión de OSPF para **IPv6**, también trabajada en la Topología 3. 

## Herramientas

- Cisco Packet Tracer
- CLI de routers Cisco
- Wireshark 
