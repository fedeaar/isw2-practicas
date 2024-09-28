## 5. Dado el siguiente programa:

```C
1   void main() {
2       x = new h1;
3       z = new h2;
4       y = f(x);
5       w = f(z);
6   
7       int f(object v) {
8           if (v null)
9               v = f(v);
10          return v;
11      }
12   }
```

### a) Calcular el PTG para el final del método main usando Andersen sin contexto.
### b) Se puede hacer cloning?
### c) Calcular PTG usando contexto de llamada con k = 2.
### d) Calcular PTG usando contexto funcional.

