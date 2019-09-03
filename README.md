### pebble
---
https://github.com/PebbleTemplates/pebble

http://www.mitchellbosecke.com/pebble/home

```java
// pebbble/src/test/java/com/mitchellbosecke/pebble/PebbleExtension.java

public class PebbleExtension extends AbstractExtension {
  
  @Override
  public Map<String, Filter> getFilters() {
    Map<String, Filter> f = new HashMap<>();
    f.put(TestFilter.FILTER_NAME, new TestFilter());
    return f;
  }
}

```

```
```

```
```


