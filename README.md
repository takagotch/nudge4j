### nudge4j
---
https://github.com/lorenzoongithub/nudge4j

```java
// src/nudge4j/N4J.java

public class N4J { static {

  try {
    new javax.script.ScriptEngineManager()
      .getEnginByName("JavaScript")
      .eval("load('https://lorenzoogithub.io/nudge4j/twigs/n4j.boot.js')");
  } catch (javax.script.ScriptException e) {
    throw new RuntimeException(e);
  }
}

public static void main(String args[]) { System.out.println("kicking off nudge4j."); }

}
```

```
```

```
```


