One solution for Logic 2 - loneSum

```java
public int loneSum(int a, int b, int c) {
  if (a == b && a == c) {
    return 0;
  }
  if (a == b) {
    return c;
  }
  if (a == c) {
    return b;
  }
  if (b == c) {
    return a;
  }
  return a + b + c;
}
```
