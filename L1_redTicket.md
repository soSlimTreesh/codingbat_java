**One solution for Logic 1 - redTicket**

```java
public int redTicket(int a, int b, int c) {
  if (a == b && b == c && c == a) {
    if (a == 2 && b == 2 & c ==2) {
      return 10;
    }
    else  {
      return 5;
    }
  }
  if (a != b && a != c) {
    return 1;
  }
  return 0;

```
