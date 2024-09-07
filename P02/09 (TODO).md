## 9 ¿Que diferencia de los siguientes dos metodos es diferente?

```
1 public int hashCode1(Object o) {
2   //@ asume o != null;
3   return o.hashCode();
4 }
```
```
1 public int hashCode2(Object o) {
2   //@ assert o != null;
3   return o.hashCode();
4 }
```
