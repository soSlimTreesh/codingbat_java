***One solution for String 1 - makeOutWord***

```java
public String makeOutWord(String out, String word) {
  String firstTwo = out.substring(0, 2);
  String secondTwo = out.substring(2);
  return firstTwo + word + secondTwo;
}
```
