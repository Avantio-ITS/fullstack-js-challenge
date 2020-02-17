# FullStack JS Challenge
![atrends](./readme/first.png)
Nuestros amigos de UX/UI nos han dejado un diseño preparado en figma, para tener acceso a toda la funcionalidad de la plataforma es necesario el registro, es muy similar a Invision o Zeplin, así que si no lo has utilizado nunca no te preocupes, te harás con ella enseguida: https://www.figma.com/file/OZo8wGsr4aDns0lnOqYk39/Frontend-Challenge-atrendsPRO?node-id=0%3A1

En el diseño se aprecian dos vistas:
1. Listado de noticias
2. Detalle de noticia

Dentro del detalle de la noticia tenemos un slide-out que nos vale tanto para editar la noticia como para crearla.

Encontrarás todos los assets necesarios para la realización de la prueba dentro de `readme/assets.zip`

En cuanto al backend consiste en desarrollar una API REST con Express, en cuanto al modelo de datos, hay que modelar las noticias de la aplicación, y este modelo debe tener: title, body, image, url y publisher siendo este ultimo el periodico que ha publicado esa noticia. La tecnologia de base de datos con la que se tendrá que realizar la prueba es MongoDB

Los endpoints que habrá que implementar serán los siguientes:
- Listado de noticias
- Detalle de noticia
- Eliminación de noticia
- Edición de noticia
- Creación de noticia

## Tareas previas
- Crear un repositorio de GIT (Bitbucket, GitHub o similar) con acceso público uno para backend y otro para frontend
- Antes de empezar las tareas envíanos por e-mail el enlace del repositorio.
- Haz los commits que consideres oportunos conforme vayas desarrollando las diferentes tareas (Mínimo un commit por tarea).

## Que se espera de ti
### Frontend
**Puedes utilizar la versión de Angular que te parezca (excepto Angular.js)**

Al tratarse de un challenge para fullstack el diseño responsive es *opcional*

Se valorará:
- La arquitectura del proyecto
- La arquitectura de componentes que se creen
- La claridad del codigo y de las hojas de estilo
- El uso de layout css modernos (flexbox, cssgrid)

Se tendrá en cuenta también:
- Código preparado para producción
- Entregar una solución que se pueda escalar o añadir funcionalidad con facilidad
- Sientete libre a la hora de añadir cualquier mejora de UX/UI

*[BONUS]*: Nuestro departamento de UX no ha tenido tiempo en pensar en las animaciones. Queda de tu parte añadir las que consideres necesarias.

### Backend
Se valorará:
- La arquitectura de la aplicación
- El diseño del API según el standard
- Las buenas prácticas en el desarrollo de una solución
- Código preparado para producción

Se tendrá en cuenta:
- Testing
- Dockerización de la aplicación

### Otras cosas a tener en cuenta
En cualquier punto del desarrollo de la prueba no dudes en exponer tus dudas, estaremos encantados de solucionartelas.

Además de los puntos de frontend y backend se tendrá en cuenta lo siguiente:
- Representa en un dibujo la arquitectura de la aplicación.
- Usa todas las buenas prácticas que conozcas.
- Haz los tests que consideres necesarios.
- Usa el motor de estilos que más te guste.

Y sobre todo... DISFRUTA!
