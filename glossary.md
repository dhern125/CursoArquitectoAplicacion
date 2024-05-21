# Glosario de Terminología sobre APIs

## A

### API (Application Programming Interface)
Una interfaz que permite que dos aplicaciones se comuniquen entre sí. Proporciona un conjunto de funciones y procedimientos para que otras aplicaciones puedan acceder a las características o datos de un sistema operativo, aplicación u otro servicio.

### API Key
Una clave única utilizada para autenticar una aplicación al acceder a una API. Es similar a un nombre de usuario y contraseña, proporcionando acceso a los recursos de la API.

### Asynchronous API
Una API que permite que las solicitudes y respuestas se procesen de manera no secuencial, lo que significa que una aplicación puede continuar ejecutándose sin esperar a que se completen las solicitudes de la API.

## B

### Backend
La parte del sistema de software que se encarga de la lógica del servidor, la base de datos y la aplicación. Las APIs a menudo se comunican con el backend para obtener datos o realizar operaciones.

### Base URL
La dirección común de la API que precede a los endpoints específicos. Por ejemplo, en la API `https://api.ejemplo.com/v1/users`, `https://api.ejemplo.com/v1` es la base URL.

## C

### CORS (Cross-Origin Resource Sharing)
Un mecanismo de seguridad que permite que los recursos de una página web se soliciten desde otro dominio fuera del dominio desde el que se sirvió la página.

### CRUD (Create, Read, Update, Delete)
Un acrónimo que describe las cuatro operaciones básicas de persistencia en una base de datos: Crear, Leer, Actualizar y Eliminar.

## D

### Documentation
La descripción detallada de cómo usar una API, incluidos ejemplos de solicitudes y respuestas, explicaciones de endpoints, parámetros, códigos de estado y errores.

## E

### Endpoint
Una URL específica en una API donde se pueden realizar ciertas operaciones. Por ejemplo, `https://api.ejemplo.com/v1/users` podría ser un endpoint para gestionar usuarios.

### Error Codes
Códigos devueltos por la API para indicar el resultado de una solicitud. Los códigos de error HTTP comunes incluyen 404 (No encontrado), 500 (Error interno del servidor), etc.

## F

### Fetch
Un término común en programación que se refiere a la acción de solicitar datos desde una API.

### Framework
Una plataforma de desarrollo que proporciona una estructura predeterminada para desarrollar y desplegar aplicaciones, incluyendo APIs. Ejemplos incluyen Express para Node.js y Flask para Python.

## G

### GET
Un método HTTP utilizado para solicitar datos de un servidor. Es uno de los métodos CRUD, específicamente utilizado para "Leer".

## H

### Headers
Información adicional enviada con una solicitud o respuesta HTTP. Los headers pueden incluir detalles sobre el tipo de contenido, la longitud del contenido, la autenticación, etc.

### HTTP (Hypertext Transfer Protocol)
El protocolo utilizado para la comunicación entre el cliente (navegador) y el servidor web. Las APIs suelen usar HTTP para enviar y recibir datos.

## J

### JSON (JavaScript Object Notation)
Un formato de intercambio de datos ligero y fácil de leer/escribir tanto para humanos como para máquinas. Es comúnmente usado en las respuestas de las APIs.

## K

### Key-Value Pair
Un conjunto de datos que consiste en una clave y su valor asociado. Este formato es ampliamente utilizado en la configuración de parámetros de una API.

## L

### Latency
El tiempo que tarda una solicitud en viajar desde el origen hasta el destino y regresar. En el contexto de las APIs, se refiere al tiempo de respuesta.

## M

### Middleware
Software que se encuentra entre el sistema operativo y las aplicaciones en una red. En el contexto de las APIs, puede referirse a funciones que se ejecutan entre la recepción de una solicitud y la devolución de una respuesta.

### Method
Un verbo HTTP que indica la acción a realizar en un recurso de la API, como GET, POST, PUT, DELETE.

## O

### OAuth
Un estándar abierto para la autorización que permite a los usuarios proporcionar acceso a sus recursos sin compartir credenciales. Utiliza tokens para manejar la autorización.

## P

### Parameter
Datos que se envían a la API para personalizar la solicitud. Pueden ser query parameters, path parameters o body parameters.

### POST
Un método HTTP utilizado para enviar datos al servidor, generalmente para crear un nuevo recurso.

### PUT
Un método HTTP utilizado para enviar datos al servidor para actualizar un recurso existente.

## Q

### Query Parameter
Un componente de la URL que proporciona información adicional a la API. Se encuentra después del símbolo `?` y se compone de pares clave-valor separados por `&`.

## R

### Rate Limiting
Una técnica utilizada para controlar el número de solicitudes que un cliente puede hacer a una API en un período de tiempo determinado. Ayuda a prevenir el abuso de la API.

### REST (Representational State Transfer)
Un estilo arquitectónico para diseñar APIs que utilizan HTTP para hacer solicitudes y respuestas. Los recursos se identifican mediante URLs y se manipulan utilizando los métodos HTTP estándar.

## S

### SDK (Software Development Kit)
Un conjunto de herramientas que permite a los desarrolladores crear aplicaciones para un entorno específico. Los SDKs pueden incluir ejemplos de código, documentación, bibliotecas y herramientas de depuración.

### SOAP (Simple Object Access Protocol)
Un protocolo de mensajería basado en XML para intercambiar información estructurada en la implementación de servicios web.

## T

### Token
Una cadena generada por el servidor que representa una credencial para la autenticación y autorización. Los tokens se utilizan para mantener la seguridad en las APIs.

### Throttling
El proceso de limitar el número de solicitudes que un cliente puede hacer a una API en un tiempo determinado para asegurar la estabilidad y disponibilidad del servicio.

## U

### URL (Uniform Resource Locator)
La dirección de un recurso en la web. En el contexto de las APIs, se refiere a la dirección donde se puede acceder a un endpoint específico.

## W

### Webhook
Un método para ampliar o cambiar el comportamiento de una API con callbacks personalizados. Permite que una API envíe datos a otra aplicación cuando ocurren ciertos eventos.

### WSDL (Web Services Description Language)
Un lenguaje basado en XML utilizado para describir los servicios web y sus métodos de acceso.

## X

### XML (eXtensible Markup Language)
Un lenguaje de marcado que define reglas para el formato de documentos que pueden ser leídos tanto por humanos como por máquinas. Se utiliza en algunas APIs, especialmente en las basadas en SOAP.
