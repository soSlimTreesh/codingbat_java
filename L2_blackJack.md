One solution for Logic 2 - blackJack

```java
public int blackjack(int a, int b) {
  if (a > 21) {
    a = 0;
  }
  if (b > 21) {
    b = 0;
  }
  
  if (a > b)  {
    return a;
  }
  else if (b > a) {
    return b;
  }
  return 0;
}
```
