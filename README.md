# Obligatorio ISA1 - Sprint 1

Irazoqui-Costa-Castineiras-Begino-Turchi <br>

## Roles

Para esta iteracion, como no se encontro mucho trabajo de desarrollo, todos los integrantes realizaron ciertas actividades que mas adelante no formaran parte de su "rol designado". Esto lo hicimos para que no se centre la mayoria del trabajo en uno de los miembros del grupo. Se mantuvo un mismo Product Owner, por ejemplo, para las ceremonias y aprobacion del Pull Request para la entrega del primer sprint, para darle una continuidad a la iteracion de todas formas.


## Uso de GitHub como control de versionado

Para tener un mayor orden y tambien seguir la rubrica de la evaluacion, el equipo utilizo un repositorio de GitHub donde el proyecto sera fraccionado en las distintas iteraciones. Las branches principales que seran creadas seran destinadas a las iteraciones particulares, siguiendo el formato "IteracionN" donde N es el numero de iteracion. En las distintas fechas de entrega, se realizara un merge de la iteracion correspondiente a la branch main, de forma que la correccion no permita malintepretaciones ni errores a la hora de controlar la version del trabajo. El equipo tomo la decision de realizar todas las branches de las features basadas en la "rama base" de la iteracion en la que se encuentre el proyecto, con el fin de evitar posibles erorres de merging. Ademas, mediante Pull Requests fomentamos la review de branches antes de mergear, para poder detectar posibles errores o incongruencias.

## Scrum

### Adaptación del marco de Scrum al contexto de nuestro proyecto

En nuestro contexto por ser estudiantes y no estar trabajando, se nos complican mucho los horarios y los días. Quizás algunos solo pueden trabajar los fines de semana, por ejemplo. Por lo tanto, no vamos a hacer la Daily Scrum como evento.

De todos modos, decidimos hacer una reunión de Daily Scrum algún día marcado por el equipo. No solo para ver el progreso del equipo, sino también para simular como sería el evento en vida real.

El resto de ceremonias de Scrum se van a realizar como es apropiado dentro del marco de Scrum en general (Sprint Planning Meeting, Sprint Review Meeting, Sprint Retrospective Meeting).

### Sprint Planning

Para esta ceremonia, el equipo decidio tanto armar un grupo de Whatsapp, como la creacion de un documento inicial utilizando Google Docs, para establecer varios puntos de comunicacion en el grupo e ir lanzando las primeras ideas. A continuacion se determino la adaptacion del grupo al marco de Scrum, dialogando acerca de como la solucion puede ser tomada desde una metodologia agil, como tambien los cronogramas de cada uno para asignar las ceremonias correspondientes. Luego, se leyo la consigna de la entrega nuevamente, para evacuar cualquier tipo de duda que haya quedado entre los integrantes. Una vez hecho eso, comenzo la separacion de requisitos en el documento, de forma informal.

Para concluir la planning meeting, se determinaron los objetivos para esta primer iteracion. Estos fueron:

- Recopilar los requisitos
- Identificar interesados
- Analizar a la competencia
- Documentar, utilizando Azure Boards, los requisitos en forma de User Stories y Epicas.

#### Aclaración sobre el tablero
Nosotros al principio consideramos que el tablero iba a tener SOLO las US, o tarjetas asociadas al producto. En esta primera iteración, las cosas que hicimos no son del producto directamente (creamos el product backlog, análsis de interesados y competidores, etc.), sino que es más una preparación del mismo. Por lo tanto, decidimos no agregar como tasks las tareas que nos dividimos en la Sprint Planning Meeting. Luego de hablar con los profesores en la clase de consulta y en la clase, decidimos que el tablero debe incluirlas, ya que son tareas que como desarrolladores llevamos acabo y son relevantes para el proyecto. Para los próximos sprints, vamos a añadir este tipo de tarjetas desde el principio o cuando surgan.

Tasks creadas: <br>
<img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/TableroConTasks.jpg" width=100% height=auto />

### Daily

El objetivo de la daily fue ver el progreso del equipo al final de la semana. Intentamos seguir el evento como se hace normalmente en Scrum. Es decir, fue una reunion corta de unos 15 minutos en la que cada uno hablo de lo que pudo hacer, que haría a futuro, y que trabas o dudas tenía para que el equipo lo ayudara.

Foto del equipo en la daily hecha en teams:<br>
<img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Daily.jpg" width=100% height=auto />

## Proyecto

## Definición del problema / solución

El objetivo de este proyecto es el desarrollo de una aplicacion movil para ayudar al usuario con el transporte publico en la vida cotidiana, a traves de la metodologia agil de SCRUM. El equipo consta de 5 integrantes, donde los roles a impersonar por cada uno iran variando a lo largo del proyecto, con el fin de que todos tengamos experiencia en las responsabilidades que cada rol conlleva. A lo largo de las 4 iteraciones, se realizaran las ceremonias correspondientes para que el desarrollo incremental de nuestro proyecto logre completarse correctamente y brindar el prototipo final de la mejor forma posible.

### Interesados

Uno de los principales elemenots para el correcto desarrollo de una aplicacion es la identificacion de los interesados. Consideramos interesado a todo aquel potencial usuario de la aplicacion, como otras distintas entidades que se vean afectadas tanto positiva como negativamente a traves de la app. (matriz de interesados?)
Lista de interesados:

- Estudiantes
- Trabajadores
- Gente que sea incapaz de transportarse por sus propios medios.
- Entidades gubernamentales
- Competidores
- Posibles inversionistas?
- Trabajadores del rubro
- Empresa encargada de mantenimiento e instalacion de la app.

### Identificación y análisis de competidores

#### Moovit:

<p>Vemos que la app de moovit brinda muchas de las funcionalidades que nuestra aplicación quiere brindar. Sin embargo, hay algunas diferencias claves entre ambas aplicaciones, por lo que consideramos importante resaltar aquellas funcionalidades que sean nuevas en nuestra aplicación para que se destaque. Por otro lado, la aplicación de moovit también tiene diversas funcionalidades que son útiles, y decidimos que estaría bueno implementarlas y aprovecharnos de las que nos parezcan mejor. Las funcionalidades que decidimos implementar en nuestra app:</p>
&nbsp;1: Guardado de destinos para obtener direcciones rápidas (Ej: casa, trabajo, facultad)
<br>
&nbsp;2: Si se elige un destino al que ninguna linea cercana llegue, se proporciona una combinación de lineas de transporte diferentes
<br>
<br>

| Busqueda de lineas                                                                                                                                                        | Destinos favoritos                                                                                                                                                                 | Linea Favorita                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-Busqueda%20de%20lineas.jpg" width="250" height=auto /> | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-destinos%20favoritos%20y%20uber.jpg" width="250" height=auto /> | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-linea%20favorita.jpg" width="250" height=auto /> |

| Mapa de paradas cercanas                                                                                                                                              | Paradas de la linea y proxima llegada                                                                                                                                              | Mapa de ruta completa                                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-paradas%20cercanas.jpg" width="250" height=auto /> | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-paradas%20y%20proxima%20llegada.jpg" width="250" height=auto /> | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-ruta%20completa.jpg" width="250" height=auto /> |

#### Google maps

<p>Google maps, al ser una aplicación que no esta centrada en el tranposrte público únicamente, tiene algunas funcionalidades que nos parece interesante implementar en nuestra aplicación:</p>
&nbsp;1: Google maps tiene la funcionalidad "Google street view", que permite ver una localización en modo 3D mediante fotos que toma el carro de google al pasar por un lugar. De forma similar, cuando se busca un lugar, google también muestra la foto más reciente de dicho lugar. Simulando estas funcionalidades, se nos ocurre aplicarlas para que el usuario pueda chequear con fotos, o girar la camara en modo 3D y mirar los alrededores, los lugares de llegada, las paradas, etc.
<br>
&nbsp;2: Otra funcionalidad interesante que proporciona google es que cuando marcamos una ruta a seguir en automovil, se le avisa al usuario que porciones de esa ruta se encuentran congestionadas por tráfico (Si es que la hay). La ruta puede aparecer en amarillo/naranja (congestionada), y rojo(muy congestionada).
</br>

### Evidencia de utilizacion de marco ágil a través de Azure Boards

Para explayar las funcionalidades por usuario, hicimos uso de la tecnologia brindada por Azure Boards. Esta herramienta nos permite crear un proyecto bajo las caracteristicas de un marco agil como lo es Scrum o Kanban. Se realizo una lista de work items que fueron definidos por los distintos integrantes del equipo.
Dividimos los distintos requisitos y funcionalidades en Epicas, Features y User stories, dependiendo de la magnitud, tipo, y proposito de el objeto de trabajo del que se tratase.

## Épicas, features y user stories

### Template para user stories:

Las identificamos por la abreviación “US” seguida de un número identificador

Siguen el siguiente template:

    CÓMO <ROL>

    QUIERO <ACCION>

    PARA <MOTIVO DE NEGOCIO>

# Épica 1: Gestión de Usuarios

## Feature: Sesión

### US1:

    COMO  usuario

    QUIERO poder logearme al sistema

    PARA identificarme y obtener información relevante a mis viajes

### US2:

    COMO  usuario

    QUIERO poder cerrar sesión

    PARA poder acceder al sistema desde un dispositivo de manera temporal

## Feature: CRUD Usuarios

### US3:

    COMO  usuario

    QUIERO poder registrarme en el sistema

    PARA poder disfrutar de una experiencia personalizada

### US4:

    COMO  usuario

    QUIERO poder editar los datos que asocie a mi usuario

    PARA poder corregir o actualizar datos asociados a mi persona

### US5:

    COMO  usuario

    QUIERO poder eliminar mi cuenta

    PARA no quedarme registrado en contra de mi voluntad

### US6:

    COMO  usuario

    QUIERO poder restaurar mi contraseña

    PARA no perder la cuenta si se me olvida la contraseña

# Epica: Busqueda y listado

- Feature: Busqueda de linea con filtros

  - US: Buscar linea utilizando filtros.

- Feature: Listado de lineas cercanas con informacion relevante.

  - US: Ver información de destino/origen
  - US: Ver información de cantidad de pasajeros

- Feature: Historial de busqueda y de viajes

  - US: Ver historial de busqueda
  - US: Guardar un destino para obtener direcciones rápidas

- Epica: Modo viaje.

  - Feature: Modo viaje

    - US: Hacer seguimiento de trayecto de la linea
    - US: Ver siguientes paradas hasta el destino
    - US: Ver informacón extra ==> puede ser hora de llegada a parada, hora de llegada a destino, etc.
    - US: Ver fotos o street view de parada de origen y destino
    - US: Ver estado de congestión de la ruta
    - US: Ver combinaciones de lineas posibles para llegar a destino

  - Feature: Compartir viaje a otro usuario

    - US: Compartir viaje a otro usuario (wpp, live location?)

- Epica: Sistema de notificaciones
  - US: Notificar omnibus por llegar a la parada
  - US: Notificar que la proxima parada es tu destino
  - US: Notificar el tiempo de llegada a parada habitual.
  - US: Notificar si la linea seleccionada esta retrasada
  - US: Notificar si la linea seleccionada esta desviada.

### Definition of Ready

Una historia de usuario está lista para ser integrada al Sprint Backlog del Sprint actual si:

- La historia de usuario está definida de forma clara, y esta es entendible por parte de todos los integrantes del equipo.
- La historia de usuario es testeable, se puede verificar que cumple su funcionalidad.
- La historia de usuario debe ser realizable dentro del tiempo del Sprint acorde a nuestra Definition of Done.

#### ¿Cómo pensamos cumplir con Definition Of Ready?

- Escribir historias de usuario en forma grupal, y añadir criterios de aceptación para cada una de ellas, de forma de que estas sean claras pero no establezcan un - contrato, sino que permitan una conversación con el cliente que de la posibilidad de expandir en cómo llevar a cabo la user story.
- Escribir criterios de aceptación para cada historia de forma que estos permitan que cada historia sea testeable.
- Escribir historias de usuario que sean realizables dentro del scope del team. Si no es el caso, separarlas en unidades mas pequeñas hasta que su tamaño sea acorde para cumplir con nuestra Definition Of Ready.

### Definition of Done

El equipo, ademas de tener como requisito de la entrega, decidio que formalizar una Definition of Done era vital para el correcto, eficiente y constante desarrollo del proyecto.

Una historia de usuario se puede considerar como completada si:
-Cumple con los criterios de aceptación asociados a ella.
-Se realizó una validacion con potenciales usuarios finales. Su contenido fue revisado por otros integrantes del equipo, que realizaron su validación.

## Planilla con el tiempo de trabajo

Para llevar un seguimiento de las horas trabajadas por el equipo, se decidio crear una tabla, dividida en actividades, donde cada integrante del equipo registre las horas trabajadas para sus respectivas tareas.

En esta iteracion, tomamos las categorias que se observaran a continuacion como las tareas principales para llevar a cabo.

| Iteración 1 | Participante        | Horas de Investigación | Horas de documentación | Horas de investigación funcionamiento de herramienta | Total horas |
| ----------- | ------------------- | ---------------------- | ---------------------- | ---------------------------------------------------- | ----------- |
| 1           | Sofia Begino        | 3                      | 4                      | 2                                                    | 9           |
| 1           | Mathias Castiñeiras | 3                      | 2                      | 4                                                    | 9           |
| 1           | Mateo Costa         | 3                      | 3                      | 3                                                    | 9           |
| 1           | Santiago Irazoqui   | 5                      | 2                      | 2                                                    | 9           |
| 1           | Juan Turchi         | 1                      | 5                      | 3                                                    | 9           |
