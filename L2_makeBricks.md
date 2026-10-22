One solution for Logic 2 - makeBricks

```java
public boolean makeBricks(int small, int big, int goal) {
  int bigBricksUsed = goal / 5;
  if (bigBricksUsed > big) {
    bigBricksUsed = big;
  }
  int remainder = goal - bigBricksUsed * 5;
  return small >= remainder;
}
```
