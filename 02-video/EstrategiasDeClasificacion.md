# Estrategias De Clasificacion

1 Descripcion Informal
2 Analisis Clasificacion
3 Analisis del Dominio
4 Analisis del comportamiento
5 Analisis de Casos de Usos

## Descripcion Informal

### Estrategia

- Abbott sugiere escribir una descripcion del problema (o una parte del problema)
 y luego subrayar ´Los Sustantivos y Verbos. Los nombres reperesentan objetos
 candidatos, y los verbos representan operaciones candidatos en ellos´

### Inconvenientes

- cualquier susutantivo puede ser verbo, y cualquier verbo puede ser sustantivo
(cosificación) ejm: gestionar vs gestion.

## Analisis de Clasificacion

### Estrategia

- Un numero de metodologos han propuesto diversas fuentes de clases y objetos,
derivados de los requisitos del dominio del problema.

  *Cosas, objetos fisicos o grupos de objetos que son tangibles: cohes, datos
  de telemetria, sensores de posición.

  *Conceptos, principios o ideas que no son tangibles: por ser utilizados para
  organizar o realizar un seguimiento de las actividades comerciales y/o
  comunicaciones: prestamo, reunion, interseccion.

  *Cosas que pasan, por lo general de otra cosa en una fecha determinada, eventos:
  aterrizaje, interrumpir, solicitud. Importante los eventos son muy usados, y Los
  puedes cosificar. ejm: picharUnBotton a bottonPinchado or seHaPinchadoUnBottom.

  *Gente, seres humanos que llevan una determina función: madre, profesor, politico.

  *Organizaciones, colecciones formalmente organizadas de personas y recursos
  que tienen una mision definida. ejm: clase facultad, electorado, departamento,
  universidad.

  *Lugares Fisicos: oficinas y sitios importantes para la aplicación clases
  laboratorio

  *Dispositvos con lo que interactua la aplicacion

  *Otro sistemas externas con los que interactua la aplicacio. ejem: gestorDEComunicaciones.
************************************************************************************
# Analisis del Dominio

## Estrategia

- Es el intento para identificar a los objetos, las operaciones y las relaciones
los expertos del dominio perciben como importantres sobre el dominio.

- A menudo el experto del dominio es un usuario, como un ingeniero del tren o
emprededor en un sistema ferroviario o una enferma de un hospital.

- Un experto del dominio normalmente no sera un desarrolador de software; mas
communmente este familiarizado con todos los elementos de un problema particular.

- No son los que van a pagar sobre sistema, sino los usuarios que usaran el sistema.

# Analisis del Comporatimiento

## Estrategias

Mientras que estos enfoques clasicos se centran en cosas tangibles del Dominio
del problema, otra escuela de pensamiento en el analisis orientado a objetos se centra en el comportamiento dinamico como la fuente primaria de calses y objetos.

- las responsabilidad de una clase es el conocimiento de un objeto que tiene
que mantener y las acciones que puede que realizar.
