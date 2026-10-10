**One solution for String 1 - extraFront**

```java
public String extraFront(String str) {
  if (str.length() > 1) {
    String str2 = str.substring(0, 2);
    return str2 + str2 + str2;
  }
  else if (str.length() == 1) {
    String str1 = str.substring(0, 1);
    return str1 + str1 + str1;
  }
  return str;
}
```
