# Tarea 1

## Conceptos Fundamentales

**¿Qué es un servicio REST?**
Un servicio REST (Representational State Transfer) es un estilo arquitectónico para diseñar servicios web que permiten la comunicación entre diferentes sistemas a través de HTTP. REST utiliza métodos HTTP estándar y está basado en recursos, donde cada recurso es representado por un URI único.

**¿Cuáles son los principios del diseño RESTful?**
1. **Identificación de recursos**: Cada recurso debe ser identificable a través de un URI.
2. **Interacción a través de representaciones**: Los clientes interactúan con los recursos a través de representaciones, generalmente en formatos como JSON o XML.
3. **Mensajes autodescriptivos**: Cada mensaje HTTP contiene toda la información necesaria para comprender la solicitud o la respuesta.
4. **Hipertext como motor del estado de la aplicación (HATEOAS)**: Las aplicaciones deben estar dirigidas por hipervínculos que guían las transiciones de estado.

**¿Qué es HTTP y cuáles son los métodos HTTP más comunes?**
HTTP (Hypertext Transfer Protocol) es un protocolo de comunicación utilizado para la transferencia de información en la web. Los métodos HTTP más comunes son:
- **GET**: Solicita la representación de un recurso.
- **POST**: Envía datos al servidor para crear un nuevo recurso.
- **PUT**: Actualiza un recurso existente.
- **DELETE**: Elimina un recurso.
- **PATCH**: Aplica modificaciones parciales a un recurso.

**¿Qué es un recurso en el contexto de un servicio REST?**
Un recurso es una entidad que puede ser identificada, manipulada y representada en un servicio REST. Los recursos se identifican mediante URIs.

**¿Qué es un endpoint?**
Un endpoint es una URL específica que expone un recurso o una funcionalidad en un servicio web REST. Es la dirección donde un cliente puede acceder a un recurso.

## Estructura de un Servicio REST

**¿Qué es un URI y cómo se define?**
Un URI (Uniform Resource Identifier) es una cadena de caracteres que identifica de manera única un recurso en la web. Se define siguiendo una estructura estándar que incluye el protocolo, el nombre del host, y la ruta del recurso.

**¿Qué es una API RESTful?**
Una API RESTful es una interfaz de programación de aplicaciones que sigue los principios del diseño REST. Permite a los clientes interactuar con los recursos del servidor utilizando métodos HTTP estándar.

**¿Qué son los códigos de estado HTTP y cómo se usan en REST?**
Los códigos de estado HTTP son respuestas numéricas del servidor que indican el resultado de una solicitud HTTP. En REST, estos códigos se utilizan para informar al cliente si la solicitud fue exitosa o si ocurrió algún error.

| Código | Significado                        |
|--------|------------------------------------|
| 200    | OK - Solicitud exitosa             |
| 201    | Created - Recurso creado           |
| 400    | Bad Request - Solicitud inválida   |
| 401    | Unauthorized - Autenticación fallida|
| 403    | Forbidden - Acceso denegado        |
| 404    | Not Found - Recurso no encontrado  |
| 500    | Internal Server Error - Error del servidor |

**¿Qué es JSON y por qué se usa comúnmente en APIs REST?**
JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos que es fácil de leer y escribir tanto para humanos como para máquinas. Se usa comúnmente en APIs REST porque es un formato estándar para representar datos estructurados, y es soportado por la mayoría de los lenguajes de programación.
