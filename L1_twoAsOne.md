**One solution for Logic 1 - twoAsOne**

```java
public boolean twoAsOne(int a, int b, int c) {
  if (a + b == c)  {
    return true;
  }
  if (c + a == b)  {
    return true;
  }
  if (c + b == a)  {
    return true;
  }
  return false;
}
```
