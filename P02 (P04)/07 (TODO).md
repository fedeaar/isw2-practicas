## 7. Completar la anotacion requires del siguiente metodo de forma que su ejecucion no produzca una excepcion:

```
1  //@ requires ...
2  int sum (int array[], int len) {
3    int sum = 0;
4    int i = 0;
5    while (i < len) {
6      sum = sum + array[i];
7      i = i + 1;
8    }
9    return sum ;
10 }
```
