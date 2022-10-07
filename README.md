# Obligatorio ISA1 - Sprint 1

Irazoqui-Costa-Castineiras-Begino-Turchi <br>

## Roles

PO: Mathias Castineiras \
 Desarrolladores: el resto \
→Investigar funcionalidades: \
 &nbsp;&nbsp; Ej: Buscar línea de bus (usuario), mostrar ads (empresas) \
→Identificación interesados (users, stakeholders -cliente, estado, publicidad, etc.) y estudio de competidores (robar ideas): \
 &nbsp;&nbsp; Analizar a todos los interesados y justificar.
Estudiar a los competidores, robar ideas, ver que funciona y porqué. Que cosas no nos gustan y queremos cambiar \
→Definition of Done (hay que tener las funcionalidades primero): \
→Definition of Ready: “The Definition of Ready is a set of agreements that lets everyone know when something is ready to begin”. Definition of Ready | Scrum Inc..\
Scrum Master: todos.

## Adaptación del marco de Scrum al contexto de nuestro proyecto

En nuestro contexto por ser estudiantes y no estar trabajando, se nos complican mucho los horarios y los días. Quizás algunos solo pueden trabajar los fines de semana, por ejemplo. Por lo tanto, no vamos a hacer la Daily Scrum como evento.

De todos modos, decidimos hacer una reunión de Daily Scrum algún día marcado por el equipo. No solo para ver el progreso del equipo, sino también para simular como sería el evento en vida real.

El resto de ceremonias de Scrum se van a realizar como es apropiado dentro del marco de Scrum en general (Sprint Planning Meeting, Sprint Review Meeting, Sprint Retrospective Meeting).

## Objetivos del Primer Sprint

→Identificación del problema a resolver\
→Definición del problema y solución.

## Problema a resolver

### Interesados

&nbsp;&nbsp;Personas de cualquier edad que utilicen el transporte público.

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

### Funcionalidades por interesado

&nbsp;&nbsp;(Estas van a ir para el PO y el board. Lo mejor sería armas épicas y separarlas en más chicas.)

ñ### Identificación y análisis de competidores

#### Moovit:

<p>Vemos que la app de moovit brinda muchas de las funcionalidades que nuestra aplicación quiere brindar. Sin embargo, hay algunas diferencias claves entre ambas aplicaciones, por lo que consideramos importante resaltar aquellas funcionalidades que sean nuevas en nuestra aplicación para que se destaque. Por otro lado, la aplicación de moovit también tiene diversas funcionalidades que son útiles, y decidimos que estaría bueno implementarlas y aprovecharnos de las que nos parezcan mejor. Las funcionalidades que decidimos implementar en nuestra app:</p>
&nbsp;1: Guardado de destinos para obtener direcciones rápidas (Ej: casa, trabajo, facultad)
<br>
&nbsp;2: Si se elige un destino al que ninguna linea cercana llegue, se proporciona una combinación de lineas de transporte diferentes
<br>
<br>

| Busqueda de lineas  | Destinos favoritos | Linea Favorita |
| ------------- | ------------- | ------------ |
| <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-Busqueda%20de%20lineas.jpg" width="250" height=auto />  | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-destinos%20favoritos%20y%20uber.jpg" width="250" height=auto />  | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-linea%20favorita.jpg" width="250" height=auto /> |

| Mapa de paradas cercanas | Paradas de la linea y proxima llegada | Mapa de ruta completa |
| -------- | -------- | -------- |
| <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-paradas%20cercanas.jpg" width="250" height=auto /> | <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-paradas%20y%20proxima%20llegada.jpg" width="250" height=auto />| <img src="https://github.com/Santirazoqui/Irazoqui-Costa-Castineiras-Begino-Turchi/blob/Iteracion1/Imagenes/Moovit-ruta%20completa.jpg" width="250" height=auto /> |


#### Google maps
<p>Google maps, al ser una aplicación que no esta centrada en el tranposrte público únicamente, tiene algunas funcionalidades que nos parece interesante implementar en nuestra aplicación:</p>
&nbsp;1: Google maps tiene la funcionalidad "Google street view", que permite ver una localización en modo 3D mediante fotos que toma el carro de google al pasar por un lugar. De forma similar, cuando se busca un lugar, google también muestra la foto más reciente de dicho lugar. Simulando estas funcionalidades, se nos ocurre aplicarlas para que el usuario pueda chequear con fotos, o girar la camara en modo 3D y mirar los alrededores, los lugares de llegada, las paradas, etc.
<br>
&nbsp;2: Otra funcionalidad interesante que proporciona google es que cuando marcamos una ruta a seguir en automovil, se le avisa al usuario que porciones de esa ruta se encuentran congestionadas por tráfico (Si es que la hay). La ruta puede aparecer en amarillo/naranja (congestionada), y rojo(muy congestionada).
</br>

## Uso de GitHub como control de versionado

Para tener un mayor orden y tambien seguir la rubrica de la evaluacion, el equipo utilizo un repositorio de GitHub donde el proyecto sera fraccionado en las distintas iteraciones. Las branches principales que seran creadas seran destinadas a las iteraciones particulares, siguiendo el formato "IteracionN" donde N es el numero de iteracion. En las distintas fechas de entrega, se realizara un merge de la iteracion correspondiente a la branch main, de forma que la correccion no permita malintepretaciones ni errores a la hora de controlar la version del trabajo. El equipo tomo la decision de realizar todas las branches de las features basadas en la "rama base" de la iteracion en la que se encuentre el proyecto, con el fin de evitar posibles erorres de merging. Ademas, mediante Pull Requests fomentamos la review de branches antes de mergear, para poder detectar posibles errores o incongruencias.

## Definición del problema / solución

El objetivo de este proyecto es el desarrollo de una aplicacion movil para ayudar al usuario con el transporte publico en la vida cotidiana, a traves de la metodologia agil de SCRUM. El equipo consta de 5 integrantes, donde los roles a impersonar por cada uno iran variando a lo largo del proyecto, con el fin de que todos tengamos experiencia en las responsabilidades que cada rol conlleva. A lo largo de las 4 iteraciones, se realizaran las ceremonias correspondientes para que el desarrollo incremental de nuestro proyecto logre completarse correctamente y brindar el prototipo final de la mejor forma posible.

### Evidencia de utilizacion de marco ágil a través de Azure Boards

Para explayar las funcionalidades por usuario, hicimos uso de la tecnologia brindada por Azure Boards. Esta herramienta nos permite crear un proyecto bajo las caracteristicas de un marco agil como lo es Scrum o Kanban. Se realizo una lista de work items que fueron definidos por los distintos integrantes del equipo.
Dividimos los distintos requisitos y funcionalidades en Epicas, Features y User stories, dependiendo de la magnitud, tipo, y proposito de el objeto de trabajo del que se tratase.

- Epica: Gestion de Usuarios

  - Feature: Sesion
  - US1: Log in
  - US2: Log out
  - Feature: CRUD Usuarios
    - US: Registrar usuario
    - US: Editar usuario
    - US: Eliminar usuario
    - US: Restaurar contraseña
    - US:

- Feature: Busqueda de linea con filtros

  - US: Buscar linea utilizando filtros.

- Feature: Listado de lineas cercanas con informacion relevante.

  - US: Ver información de destino/origen
  - US: Ver información de cantidad de pasajeros

- Feature: Historial de busqueda

  - US: Ver historial de busqueda
 
- Feature: Modo viaje

  - US: Hacer seguimiento de trayecto de la linea
  - US: Ver siguientes paradas hasta el destino
  - US: Ver informacón extra ==> puede ser hora de llegada a parada, hora de llegada a destino, etc.
  - US: Ver fotos o street view de parada de origen y destino
  - US: Ver estado de congestión de la ruta
  - US: Ver combinaciones de lineas posibles para llegar a destino

- Feature: Compartir viaje a otro usuario

  - US: Compartir viaje a otro usuario (wpp, live location?)

- Feature: Guardado de destinos para obtener direcciones rápidas

  - US: Guardar un destino para obtener direcciones rápidas

- Epica: Sistema de notificaciones
  - US: Notificar omnibus por llegar a la parada
  - US: Notificar que la proxima parada es tu destino
  - US: Notificar el tiempo de llegada a parada habitual.
  - US: Notificar si la linea seleccionada esta retrasada
  - US: Notificar si la linea seleccionada esta desviada.

## Planilla con el tiempo de trabajo

Para llevar un seguimiento de las horas trabajadas por el equipo, se decidio crear una tabla, dividida en actividades, donde cada integrante del equipo registre las horas trabajadas para sus respectivas tareas.

En esta iteracion, tomamos las categorias que se observaran a continuacion como las tareas principales para llevar a cabo.
