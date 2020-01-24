# Redes de SuperEmpresa S.L

Las redes de esta empresa han sido ideadas utilizando la cantidad mínima de recursos.

La empresa contiene 7 oficinas con un ordenador cada una.
Estos están configurados con una IP's estáticas que van desde la 192.168.1.3 hasta la 192.168.1.9.

Además, en el mismo edificio hay una sala de reuniones, a la que los trabajadores llevan sus portátiles y los conectan a un punto de acceso Wi-Fi.
A los dispositivos conectados a este punto de acceso se les asigna automáticamente una IP mediante
un servidor DHCP, el cual les asigna IP's a partir de 192.168.1.10.

Estas dos salas están conectadas físicamente mediante un switch el cual lleva al Gateway, un router.

Este router permitirá conectar con una red de servidores propiedad de la empresa en otra localización.

Estos servidores incluyen; un servidor HTTP (que aloja la página web de la empresa, <http://www.superempresa.com>) y con ip 192.168.0.3, un servidor DNS que contiene la dirección de el servidor HTTP con ip 192.168.0.2 y varios servidores adicionales con usos varios para la empresa.
