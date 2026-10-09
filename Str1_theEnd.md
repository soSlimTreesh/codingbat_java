**One solution for String 1 - theEnd**

```java
public String theEnd(String str, boolean front) {
  String firstLetter = str.substring(0, 1);
  String lastLetter = str.substring(str.length() - 1);
  
  if (front)  {
    return firstLetter;
  }
  else  {
    return lastLetter;
  }
  
}
```
