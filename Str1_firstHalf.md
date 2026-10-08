**One solution for String 1 - firstHalf**

```java
public String firstHalf(String str) {
  int stringLength = str.length();
  int halfLength = stringLength / 2;
  String subString = str.substring(0, halfLength);
  return subString;
}
```
