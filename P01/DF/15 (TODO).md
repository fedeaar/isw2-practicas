## 15. Sea el siguiente programa:

```c
1   y = 0;
2   x = 0;
3   z = 1;
4   while (true) {
5       x = y + 1;
6       if (y == 0)
7           x = 0;
8   }
```

### a) Constuir el CFG del programa.

Tenemos
```
1 - 2 - 3 - 4 - 5 - 6 - 7
            ||______|   |
            |___________|
```

### b) Calcular las igualdades de la forma $x = y$:

#### i. Definir un reticulado para trackear igualdad entre variables (hint: usar conjunto de pares de variables)

#### ii. Definir la funciones de transferencia para las instrucciones que aparecen en el programa.

#### iii. Definir las ecuaciones de Dataflow para el programa.

#### iv. Calcular la soluciıon a las ecuaciones (usando cualquier algorirmo de punto fijo)
