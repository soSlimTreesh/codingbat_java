**One solution for String 1 - nonStart**

```java
public String nonStart(String a, String b) {
  String subString1 = a.substring(1);
  String subString2 = b.substring(1);
  
  return subString1 + subString2;
}
```
