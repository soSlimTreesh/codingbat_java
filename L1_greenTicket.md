**One solution for Logic 1 - greenTicket**

```java
public int greenTicket(int a, int b, int c) {
  if (a == b && b == c && c == a) {
    return 20;
  }
  else if (a == b || b == c || c == a)  {
    return 10;
  }
  return 0;
}
```
