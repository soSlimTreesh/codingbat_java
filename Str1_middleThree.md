**One solution for String 1 - middleThree**

```java
public String middleThree(String str) {
  if (str.length() - 1 / 3 == 0) {
    return str;
  }
  else  {
    int middleStr = (str.length() - 1) / 2; 
    int leftMiddleStr = middleStr - 1;
    int rightMiddleStr = middleStr + 1;
    String printMiddle = str.substring(leftMiddleStr, rightMiddleStr + 1);
    return printMiddle;
  }
  
}
```
