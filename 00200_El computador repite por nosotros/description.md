Como te adelantamos en el ejercicio anterior, en Gobstones existe una forma de decir _"quiero que **estos comandos** se **repitan esta cantidad de veces**"_.

Entonces, cuando es necesario repetir un comando (como `Mover`, `Poner`, `DibujarLineaNegra`, etc) un cierto número de veces, en lugar de copiar y pegar como veníamos haciendo hasta ahora, podemos utilizar la sentencia `repeat`.

Sabiendo esto, así es como quedaría `MoverOeste10` usando `repeat`:

```gobstones
procedure MoverOeste10() {
  repeat(10) {
    Mover(Oeste)
  }
}
```

> Pero no tienes por qué creernos: ¡escribe este código en el editor y fíjate si funciona!