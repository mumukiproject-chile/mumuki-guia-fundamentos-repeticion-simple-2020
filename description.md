Como te contábamos cuando empezaste, programar nos da un gran poder: **nos permite automatizar tareas repetitivas y tediosas**.

¿Y qué quiere decir eso de "repetitivas"? Pensemos, por ejemplo, cómo haríamos un programa que ponga 5 bolitas azules:

```puppet
program {
  Poner(Azul)    
  Poner(Azul)    
  Poner(Azul)    
  Poner(Azul)    
  Poner(Azul)    
}
```

¿Te das cuenta de qué es lo que se repite? Sí, estamos haciendo 5 veces lo mismo: poner una bolita azul. Sin duda, sería mucho más interesante que el computador hiciera eso por nosotros... ¡o si no, te estaríamos mintiendo con lo de automatizar!

En esta guía vamos a aprender cómo decirle al computador que repita varias veces lo mismo, y también algunos trucos más.