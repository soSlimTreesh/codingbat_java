**One solution for Logic 1 - withoutDoubles**

```java
public int withoutDoubles(int die1, int die2, boolean noDoubles) {
  int sum = die1 + die2;
  if(noDoubles && die1 == die2) {
     if (die1 == 6 && die2 == 6)  {
       return sum = die1 + 1;
     }
     return sum += 1;
  }
  else if (die1 == die2)  {
    return sum;
  }
  else  {
    return sum;
  }
}
```
