¿Viste cuán importante es definir bien qué comandos hay que repetir y cuáles no?

Es muy común, al principio, olvidarse de poner las llaves o incluso pensar que no son importantes. Pero ten mucho cuidado: poner las llaves en el lugar erróneo puede cambiar por completo lo que hace tu programa. Mira qué distinto habría sido el resultado si hubieras puesto el `Mover(Este)` dentro del `repeat`:

```puppet
procedure Poner3AlNoreste() {
  Mover(Norte)

  repeat(3) {
    Mover(Este)
    Poner(Negro)
  }
}
```

<gs-board> GBB/1.0 size 4 4 cell 1 1 Negro 1 cell 2 1 Negro 1 cell 3 1 Negro 1 head 3 1 </gs-board>
