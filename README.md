# JwtAuthDemo
Proyecto de autenticación JWT de .Net Core.

La autenticación es el proceso que ayuda a identificar quiénes son los usuarios. Por otro lado, la autorización es el proceso de determinar qué puede hacer un usuario. Para la autorización de trabajo, el usuario será autenticado primero.

Necesitamos la identidad del usuario para identificar el rol de un usuario y actuar en consecuencia.

#JWT, o JSON Web Token, es un estándar abierto que se utiliza para compartir información de seguridad entre dos partes: un cliente y un servidor. Cada JWT contiene objetos JSON codificados, incluido un conjunto de notificaciones. Los JWT se firman con un algoritmo criptográfico para garantizar que los reclamos no se puedan modificar después de que se emita el token.

Una forma común de usar JWT es como tokens portadores de OAuth. El método de autenticación crea un JWT a petición de un cliente y lo firma para que ninguna otra parte pueda modificarlo. Luego, el cliente enviará este JWT con su solicitud a una API REST. La API REST verificará que la firma del JWT coincida con su carga útil y encabezado para determinar que el JWT es válido. Cuando la API REST ha verificado el JWT, puede usar las notificaciones para conceder o denegar la solicitud del cliente.
