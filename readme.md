# API de envío de correos

## Nombre del Webservice
Servicio de Envío de Correos Electrónicos

## Descripción
Este servicio permite a los usuarios enviar correos electrónicos a través de una solicitud HTTP utilizando el método POST. El servicio está diseñado para recibir datos en formato JSON y enviar un correo electrónico al administrador web.

## Instalación
Para instalar y configurar este servicio, sigue los siguientes pasos

    Clona el repositorio del servicio
    git clone https://github.com/usuario/repositorio.git

    Accede al directorio del proyecto
    cd repositorio

    Instala las dependencias necesarias
    npm install 

    Inicia el servicio
    npm start

## Uso
### Parametros   
La solicitud debe ser de tipo POST y el cuerpo debe estar en formato JSON. Los parámetros que debe incluir son:

    name: Nombre del remitente.
    email: Correo electrónico del remitente.
    message: Mensaje a enviar.

### Endpoint

    POST http://localhost/api/v1/endpoint-webservice/


## Ejemplo de la solicitud
La solicitud debe ser de tipo POST y el cuerpo debe estar en formato JSON.


    POST http://localhost/api/v1/endpoint-webservice/
    Content-Type: "application/json"

    {
        "name": "Nombre del remitente",
        "email": "Correo electrónico del remitente",
        "message": "Mensaje"
    }
