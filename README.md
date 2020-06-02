# RPCenum

Herramienta en Bash ideal para efectuar una enumeración básica y extraer la información más relevante de un dominio vía rpcclient. 

Esta utilidad nos permitirá obtener la siguiente información de un dominio:

* Usuarios del dominio
* Usuarios del dominio con información
* Usuarios administradores del dominio
* Grupos del dominio

¿Cómo funciona?
======
La ejecución de la herramienta mostrará el siguiente panel de ayuda:

<p align="center">
	<img src="images/image1.png"
		alt="Panel de ayuda"
	style="float: left; margin-right: 10px;" />
</p>

Para su correcta ejecución, es necesario especificar el modo de enumeración a usar, siendo los representados en la imagen adjunta.

El modo de enumeración **DUsers**, nos permitirá obtener un listado de los usuarios existentes en el dominio (siempre y cuando el **Null Session** esté habilitado):

<p align="center">
	<img src="images/image2.png"
		alt="DUsers"
	style="float: left; margin-right: 10px;" />
</p>
