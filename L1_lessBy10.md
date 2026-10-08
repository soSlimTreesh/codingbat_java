**One solution for Logic 1 - lessBy10**

```java
public boolean lessBy10(int a, int b, int c) {
  if (a + 10 <= b || a + 10 <= c) {
    return true;
  }
  if (b + 10 <= a || b + 10 <= c) {
    return true;
  }
  if (c + 10 <= a || c + 10 <= b) {
    return true;
  }
  return false;
}
```
