
## strong typed language

```java

    a = 1;
    int b = 1;
    s = "abc";
    String ss = "abc";

```


## comma seprator
```java

    int a = 1, b = 2;

```


## variable name rule
start with a 'letter': a-z, A-Z, $, _, and any unicode letter
followed by letter or digit
java key word are reserved.

```java

    int 1a2;
    int $ab;
    int \u2233;
    int for;

```


# declare before use

illegal forward reference
```java

    int k = t + 1; // compile-error illegal forward reference
    int t = 2;

```

illegal self reference
```java

    int k = k + 1;

```

