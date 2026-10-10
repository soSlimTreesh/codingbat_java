**One solution for String 1 - seeColor**

```java
public String seeColor(String str) {
  String colorRed = "red";
  String colorBlue = "blue";
  String empty = "";
  if (str.startsWith("red")) {
    return colorRed;
  }
  else if (str.startsWith("blue"))  {
    return colorBlue;
  }
  return empty;
}
```
