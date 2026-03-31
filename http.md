---
layout: default
title: HTTP
---

> Volver al [inicio](./index.md)

## Introducción a la Comunicación HTTP

Hemos hablado mucho sobre navegadores y servidores web, pero aún no hemos explorado el mecanismo real que hace posible su comunicación. Y es precisamente ahí donde está la clave de todo, porque la web entera depende de **HTTP** (*Hypertext Transfer Protocol* o Protocolo de Transferencia de Hipertexto).

HTTP es el **conjunto de reglas** que tanto los navegadores como los servidores web deben seguir para que la web funcione. Cuando solicitas un recurso desde tu navegador, ya sea una página web, una imagen, un archivo CSS, JavaScript o cualquier otro tipo de archivo, esa solicitud se formatea siguiendo las reglas del protocolo HTTP. Incluye el recurso solicitado, el tamaño de la solicitud y cualquier información adicional necesaria. El servidor recibe esa solicitud, la procesa (porque también entiende HTTP) y devuelve una respuesta al navegador.

### Métodos HTTP

Dentro de HTTP existen diferentes tipos de solicitudes, conocidas como **métodos HTTP**. Cada uno tiene un propósito específico:

**GET**
Es el método más común. Se utiliza para *obtener* información del servidor: una página web, una imagen, cualquier contenido que queramos recuperar.

**POST**
Se usa cuando queremos *crear* un nuevo recurso en el servidor. Para ello, debemos enviar toda la información necesaria. Por ejemplo, al crear una entrada de blog, necesitaríamos enviar el título, el contenido, el autor, entre otros datos.

**PUT y PATCH**
Ambos se utilizan para *actualizar* un recurso existente. La diferencia entre ellos radica en el alcance de la actualización: PUT reemplaza el recurso completo, mientras que PATCH modifica solo una parte de él.

**DELETE**
Como su nombre indica, se usa para *eliminar* un recurso del servidor. Se envía una solicitud DELETE indicando qué recurso se desea borrar, y el servidor lo elimina.

### Resumen

En total, los cinco métodos HTTP fundamentales son:

| Método | Propósito |
|--------|-----------|
| GET | Obtener un recurso |
| POST | Crear un nuevo recurso |
| PUT | Reemplazar un recurso existente |
| PATCH | Modificar parcialmente un recurso |
| DELETE | Eliminar un recurso |

Estos métodos son la base de toda comunicación entre clientes y servidores web, y forman el vocabulario esencial de cualquier aplicación en Internet.

> Contenido generado con Claude 4.6 Sonnet. Imágenes generadas con Gemini 3 Pro.