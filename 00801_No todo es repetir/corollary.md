¿Viste qué importante es definir bien qué comandos hay que repetir y cuáles no?

Es muy común, al principio, olvidarse de colocar las llaves o incluso pensar que no son importantes. Pero tené mucho cuidado: poner las llaves en el lugar erróneo puede cambiar por completo lo que hace tu programa. Mirá qué distinto sería el resultado si hubieras puesto el `Mover(Este)` adentro del `repeat`:

```puppet
procedure Poner3AlNoreste() {
  Mover(Norte)

  repeat(3) {
    Mover(Este)
    Poner(Negro)
  }
}
```

<gs-board>
 GBB/1.0
    size 4 4
    cell 1 1 Negro 1
    cell 2 1 Negro 1
    cell 3 1 Negro 1
    head 3 1
</gs-board>
