# REST API

REST (Representational State Transfer) es un estilo arquitectónico para la creación de servicios web, que utiliza el protocolo HTTP para la transferencia de datos entre sistemas. En términos simples, REST es un conjunto de reglas y convenciones para crear servicios web que sean fáciles de entender, evolucionar y usar.

> Nuevo por aqui? Tal vez debas empezar por conocer la arquitectura  [cliente-servidor](cliente-servidor.md)

En un servicio web RESTful, cada recurso es identificado por una URL única, y se utiliza un conjunto estándar de verbos HTTP (GET, POST, PUT y DELETE) para acceder a los recursos y realizar operaciones en ellos. Estos verbos HTTP se utilizan para indicar la acción que se debe realizar en un recurso. Por ejemplo:

| Verbo  | URL        | Accion                  |
| ------ | ---------- | ----------------------- |
| GET    | /users     | Obetener usuarios       |
| GET    | /users/:id | Obetener usuario por ID |
| POST   | /users     | Crear usuario           |
| PUT    | /users/:id | Actualizar usuario      |
| DELETE | /users/:id | Eliminar usuario por ID |

REST se basa en el principio de que cada recurso debe tener una representación única, que puede ser en diferentes formatos como XML o JSON, y que estas representaciones pueden ser manipuladas a través de los verbos HTTP. Además, REST también se enfoca en la escalabilidad y la simplicidad de la implementación de servicios web.

Una de las principales ventajas de REST es que permite una alta interoperabilidad entre sistemas, ya que utiliza los estándares de la web, como HTTP y URI, que son ampliamente adoptados y conocidos. REST también permite una fácil evolución y mantenimiento de los servicios web, ya que cada recurso se trata de manera independiente. Además, tambien puede ser implementada en cualquier lenguaje de programacion.
