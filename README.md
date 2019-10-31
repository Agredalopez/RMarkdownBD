# RMarkdownBD
## Introducción

El economista Franco Modigliani, Premio Nobel de Economía en 1985, desarrolló una hipótesis de la vida donde se concibe que durante el período activo, los individuos economizan y forman un capital que consumen durante su jubilación. <https://blog.gvcgaesco.es/post/20192>.

Bajo la hipótesis de *Ahorro del ciclo vital* desarrollada Franco Modigliani, el ratio de ahorro (Ahorro personal agregado respecto al ingreso disponible) es explicado por las variables detalladas en la tabla previa (leyenda). 

**Leyenda:**

|Variable|Descripción                             |
|--------|----------------------------------------|
|sr      | Ratio de Ahorro Agregado               |
|pop15   | % de población menor a 15              |
|pop75   | % de población mayor a 75              |
|dpi     | Ingreso disponible real per-capita     |
|ddpi    | var. Ingreso disponible real per-capita|

La base de datos es un promedio de los años comprendidos entre 1960 y 1970, para mitigar el efecto del ciclo económico u otras fluctuaciones del corto plazo.

## Conclusiones

Todas las variables, excepto  `pop75` resultan con estimador significativo al 95% de nivel de confianza.

A pesar de que `pop75` no es significativa al 95%, si lo es al 90%, lo más relevante de ésta es el sentido de la variable, resulta intuitivo pensar, viendo la gráfica expuesta de la hipótesis, que el ahorro en ese tramo debe de tener relación negativo respecto a la edad, en ese periodo, las personas ya viven de su pensión.

Se puede inferir que el la variación del ingreso disponible per-capita afecta positivamente al nivel del ratio de ahorros de cada país.
