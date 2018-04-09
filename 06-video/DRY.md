# DRY: ´Don't repeat yourself´

- codigo repetido que se parecen en casi todo, es muy diferentes a que tengan
las mismas lineas.

metodos reescritos en Board Player, sentencias repetidas de fila y columna.

- codigo maloliente por grupos de datos.

row y colum presentes en muchos sitios de Board.

- codigo maloliente por listas de parametros Largo.

## Mejora

- Clase Player y Board con metodos definidos en funcion de otro.
incorporar la clase coordinate que reune a row colum como metodo de lectura y
la clase LimitedInDialog incorporada con la validacion minima y maximo.
