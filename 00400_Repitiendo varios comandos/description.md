Hasta el momento, los ejemplos que vimos sólo repetían un comando, pero como mencionamos al comenzar, es posible repetir cualquier **secuencia de comandos**. En definitiva, lo que se repite es un **bloque** y, como ya sabíamos, en un bloque puede haber tantos comandos como se nos ocurra.

Miremos el código de `DibujarLineaNegra6` que podríamos haber hecho sin usar `repeat`, con algunos espacios en blanco para ayudarnos a reconocer la secuencia que se repite:

```gobstones
procedure DibujarLineaNegra6() {
  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)

  Poner(Negro)
  Mover(Este)  

  Poner(Negro)
  Mover(Este)  
}
```

¿Te das cuenta de qué es lo que se repite y cuántas veces? Bueno, eso es lo que tienes que poner en el `repeat`.

> Escribe una versión superadora de `DibujarLineaNegra6`, esta vez usando `repeat`.