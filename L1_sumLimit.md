**One solution for Logic 1 - sumLimit**

```java
public int sumLimit(int a, int b) {
  int sum = a + b;
  String intA = String.valueOf(a);
  String sumStr = String.valueOf(sum);
  int lengthA = intA.length();
  int sumLength = sumStr.length();
  
  if (lengthA == sumLength) {
    return sum;
  }
  else if (lengthA != sumLength)  {
    return a;
  }
  return sum;
}
```
