Siempre que tengas problemas como este vas a poder solucionarlos de la misma manera: **procesando el último caso por separado**.

Otra variante menos común, y tal vez más difícil de construir, es la de procesar el **primer** caso aparte:

```puppet
procedure LineaNegra4Este() {
  Poner(Negro)
  repeat(3) {
    Mover(Este)
    Poner(Negro)
  }
}
```

Por convención, vamos a preferir la forma que procesa distinto el último caso, aunque muchas veces ambas sean equivalentes (es decir, produzcan el mismo resultado).