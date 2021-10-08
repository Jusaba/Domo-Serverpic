# Domo-Serverpic# SISTEMA DOMÓTICO
## Introduccióm
Est proyecto se inicia con la intención de diseñar un sistema domótico a medida.
Se pretende conseguir un sistema abierto, flexible, económico y accesible a cualquier persona con conocimientos básicos de electrónica y programación lo que, permitirá, que cada ususario pueda diseñar los elementos segun sun necesidades.

En la siguiente figura se observa una distribución general del sistema

![](https://s3.amazonaws.com/bucket.jusaba.imagenes/bFgSkh9RVSBGasMFZbNa_InstalacionDomoticaNew.png)

El sistema está formado por:

**Sensores**.- Dsipositivos que se encargan de leer las magnitudes físicas del entorno y trasladarlas al sistema.
**Actuadores**.- Dispositivos que se encargan de convertir ordenes recibidas desde el sistema en procecesos fisicos.
**Interfaces**. Puntos desde donde se puede establecer comunicación entre el sistema y los usuarios.
**Centralita**.- Dsipositivo encargado de gestionar la información entre sensores, actuadores e interfaces.

Aunque existen varias soluciones para la comunicacion entre los componentes ( cada una con sus pros y sus contras ), se ha optado por la comunicacion WIFI. Montar una infraestructura WIFI es sencillo y económico y, aunque tiene ciertos inconvenientes, es la opción elegida, aunque esto no significa que no puedan utilizarse conexiones cableadas, por radio e incluso por GSM.

Como centralita se ha optado por utilizar un servidor propio ( ServerPic ) que puede correr en  cualquier sistema que sea capaz de manejar JAVA.

Para soluciones locales, la opción más aconsejable es utilizar un servidor en una raspberry ubicada en la instalación que se desea domotizar.

Esta opción tiene el inconveniente de la dependencia del hardware utilizado, si falla, el sistema deja de funcionar.

Existe la posibilidad de utilizar una red  de servidores en la nube con reparto de carga de forma que, si uno de ellos falla, cualquier otro de la red puede asumir el trabajo del 'caído'. Los servidores en  red puede ser hosts comerciales pero también, varios domicilios pueden compartir su hardware para crear una red de servidores.

Para sensores y actuadores, aunque hay muchas posibilidades se ha optado por desarrollarlos en torno al modulo ESP8266 lo que no impide utilizar cualquiere otra solución distinta.

Aunque ya se han diseñado varios sensores y actuadores, como se ha comentado, no es un sistema cerrado, la descripción del software permitirá diseñar nuevos elementos en función de las necesidades y la electrónica disponible. **Se trata pues de proporcionar herramientas y conocimientos para poder desarrollar unos módulos lo más simples y económicos posibles que puedan iteractuar entre ellos y puedan ser telecontrolados desde internet**.

Este proyecto es una apuesta personal que viene ya de hace unos cuantos años segun se describe en el apartado [[Un poco de historia|Serverpic/Historia]], si no te apetece conocer la historia del proyecto, puedes ir directamente a la sección [[Serverpic|Serverpic]]




