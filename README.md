# Examen_Redes

Tenemos 3 redes, de las cuales 1 de ellas son 2 subredes VLSM. Una soporta 6 host y otra 25. Las 2 subredes estan aisladas del resto de las redes, ademas cada una de ellas tiene 2 ordenadores conectados

Tenemos 2 routers que forman 2 redes:

La primera (192.168.2.0) contiene 3 ordenadores con IP fijas y 2 ordenadores con DHCP
La segunda (192.168.3.0) contiene 2 ordenadores con ip fijas y 2 con DHCP

Ademas en la red 192.168.3.0 hay conectados 3 servidores, 1 de ellos es el servidor DNS con la ip 192.168.3.100 el cual contiene las web de los otros dos servidores (www.web01.es y www.web02.es)
Al acceder al servidor de la web01 se nos muestra el mensaje 'web01', al acceder al servidor de la web02 se nos muestra el mensaje 'web02'
