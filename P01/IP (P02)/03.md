### 3. Para el siguiente programa:

```C
1   inc(a) {
2       return a + 1;
3   }
4   main() {
5       y = input;
6       x = 0;
7       while (y > 0) {
8           inc (x);
9           y−−;
10      }
11      print(x);
12  }
```

### a) Calcular el CFG de double y main.
### b) Calcular el análisis interprocedural usando el dominio del signo sin contextos.
### c) Qué valor calcula el análisis para el print?
### d) Recalcular el dataflow luego de aplicar cloning a la función inc.
### e) Recalcular el dataflow usando cadenas de llamadas con $k = 1$.
### f) Recalcular el dataflow usando functional context.

Mismas ideas que antes, ahora con más cuidado de cómo se actualizan los valores por los loops.
