
```java

    String s = "a" + "b";

    s += "c"; // legal?

    String b = "b";
    String bb = "b";
    String ab = "ab".substring(1,1);

    b == bb; // true?
    b == ab; // true?

```

why do we prefer "abc".equals(s) over s.equal("abc")?
