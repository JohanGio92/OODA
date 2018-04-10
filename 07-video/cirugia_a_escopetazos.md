# Codigo Sucio por Cirugía a Escopetazos

### Sinonimo

- Shotgun Surgery(Smell code Refactoring) - Martín Flowler

## Justificación

- Cuando cada vez que se hace una especie de cambio, lo que se tiene que hacer
es un monton de pequeños cambios en un monton de clases diferentes. Cuando los
cambios son por todos lados son dificiles de encontrar y es facíl pasar por alto
un cambio importante.

- Un cambio que altera muchas clases. Idealmente, existe una relación de uno a
uno entre los cambios comunes y las clases.

## Solución

- En este caso, hay que mover las responsabilidades entre las clases para evitarlo.
Si no hay una clase actual que parezca buena candidadata, cree una.
