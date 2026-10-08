**One solution for Logic 1 - cigarParty**

```java
public boolean cigarParty(int cigars, boolean isWeekend) {
  if (cigars >= 40 && cigars <= 60) {
    return true;
  }
  if (isWeekend)  {
    if (cigars > 60)  {
      return true;
    }
  }
  return false;
}
```
