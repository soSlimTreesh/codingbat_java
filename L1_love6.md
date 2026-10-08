**One solution for Logic 1 - love6**

```java
public boolean love6(int a, int b) {
  if (a == 6 || b == 6 || a + b == 6) {
    return true;
  }
  if (a - b == 6 || b - a == 6) {
    return true;
  }
  return false;
}
```
