**One solution for Logic 1 - blueTicket**

```java
public int blueTicket(int a, int b, int c) {
  if (a + b == 10 || b + c == 10 || a + c == 10 )  {
    return 10;
  }
  else if (a + b == b + c + 10 || a + b == a + c + 10)  {
    return 5;
  }
  else if (b + c == a + b + 10 || b + c == a + c + 10)  {
    return 5;
  }
  else if (a + c == a + b + 10 || a + c == b + c + 10)  {
    return 5;
  }
  else  {
    return 0;
  }
}
```
