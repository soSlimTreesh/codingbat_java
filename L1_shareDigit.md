**One solution for Logic 1 - shareDigit**

```java
public boolean shareDigit(int a, int b) {
  if (a / 10 == b / 10 || a / 10 == b % 10) {
    return true;
  }
  if (a % 10 == b % 10 || a % 10 == b / 10){
    return true;
  }
  return false;
}
```
