**One solution for Logic 1 - fizzString**

```java
public String fizzString(String str) {
  char firstChar = str.charAt(0);
  char lastChar = str.charAt(str.length() - 1);
  char charB = 'b';
  char charF = 'f';
  
  if(firstChar == charF && lastChar == charB) {
    str = "FizzBuzz";
  }
  else if(firstChar == charF)  {
    str = "Fizz";
  }
  else if(lastChar == charB)  {
    str = "Buzz";
  }
  return str;
}
```
