# Protocolos

Cuando intente seguir el TCP Stream del paquete 4 me aparecieron muchos datos cifrados, por lo que podemos darnos cuenta que el sitio utiliza HTTPS, si fuera HTTP entonces podriamos ver cosas en lenguaje que podriamos entender. Tambien podemos ver protocolos como Internet Protocol y Transmission Control Protocol, por otro lado este paquete tambien tiene TLS que es Transport Layer Security, que evoluciono sobre el protocolo SSL Secure Socket Layer, basicamente TLS permite dar mas pivacidad y encriptar informacion en sitios web

# Extra

Habia leido acerca de los flags en las comunicaciones y el modelo OSI basicamente cada flag podia indicar ciertas cosas, tenemos las siguientes flags: 

SYN: Sincronizacion
FIN: Fin
ACK: Acknowledgment - No se que significa acuerdo o algo asi
PSH: Push 
URG: Urgent
CHK: Checksum
RST: Reset
informe
# Encapsulamiento

En el paquete numero 4 podemos ver que tenemos el apartador Ethernet II y este nos brinda un receptor y un emisor. Tambien se nos da una IPv4. 

Esta IPv4 envia informacion a una ip y la informacion pasa por el protocolo TCP.

Aqui se evidencia el encapsulamiento, esto es cuando los datos pasan por todas las capas del modelo OSI. Tenemos 7 capas.

Ahora con el tema del encapsulamiento la informacion primero pasa por la aplicacion creo que era la primer capa del modelo osi, aqui se le da una cabecera(header) luego este se pasa a la siguiente capa, en donde se le aplican los protocolos necesarios y se le agrega otra cabecera indicando informacion relevante.

Importante recalcar que esta la encapsulacion y des encapsulacion. En ambos procesos la informacion solamente pasa por las capas necesarias del modelo OSI es decir no necesita pasar por las 7 capas estrictamentes.