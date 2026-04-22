## Fase 6. Relación con OSI, TCP/IP y encapsulamiento

| Evento observado | Protocolo | Capa OSI | Capa TCP/IP | ¿Usa puerto? | ¿Qué función cumple? |
|---|---|---|---|---|---|
| Resolución MAC antes del ping | ARP | Capa 2  Enlace de datos | Acceso a la red | No | Resuelve una IP en la dirección MAC para poder entregar la trama físicamente en la red local |
| Prueba de conectividad | ICMP | Capa 3  Red | Internet | No | Verifica si un host está activo enviando Echo Request y recibiendo Echo Reply |
| Entrega automática de IP | DHCP | Capa 7  Aplicación | Aplicación | Sí  Puerto 67/68 | Asigna automáticamente IP, máscara, gateway y DNS a los dispositivos de la red de soporte |
| Consulta de nombre | DNS | Capa 7  Aplicación | Aplicación | Sí  Puerto 53 | Traduce el nombre intranet.betek.local a la IP del servidor web |
| Acceso al sitio interno | HTTP | Capa 7  Aplicación | Aplicación | Sí  Puerto 80 | Permite cargar la página web del servidor interno desde el navegador  |