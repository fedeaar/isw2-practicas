## 10. Completar la especficacion del metodo F para que este sea verificado satisfactoriamente y el metodo G verifique correctamente.

```
1
2  int G(int i) {
3    \\@ requires i > 0 && i <= 10;
4    \\@ ensures \retvalue >= 1;
5    int div = F(10, i);
6    return div;
7  }
8  int F(int h , int x) {
9    //@ requires ...
10   return h / x;
11   //@ ensures ...
12 }
```
