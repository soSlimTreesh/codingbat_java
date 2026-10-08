**One solution for Logic 1 - inOrder**

```java
public boolean inOrder(int a, int b, int c, boolean bOk) {
  if (b > a && c > b)  {
    return true;
  }
  if (bOk == true && c > b)  {
    return true;
  }
  return false;
}
```

