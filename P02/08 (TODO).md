## 8. Completar las anotaciones requires, loop invariant y decreasing de modo que se cumpla la post-condicion del metodo:

```
1  //@ ensures \result == m ∗ n;
2  int multiply(int m, int n) {
3    int product = 0;
4    int i = 0;
5    //@ loop_invariant...
6    //@ decreasing...
7    while(i < n) {
8      product = add(product, m);
9      i = i + 1;
10   }
11   return product;
12 }
```
