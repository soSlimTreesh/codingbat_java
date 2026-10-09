**One solution for String 1 - lastChars**

```java
public String lastChars(String a, String b) {
  String firstCharA = "@";
  String lastCharB = "@";
  if (a.length() > 0) {
    firstCharA = a.substring(0, 1);
  }
  if (b.length() > 0) {
    lastCharB = b.substring(b.length() - 1);
  }
  return firstCharA + lastCharB;
}
```
