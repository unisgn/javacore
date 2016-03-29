
# interface


```java

    public interface MyInterface {
        int AGE = 12;
        int getMethod();
        void setMethod();
    }

    class MyInterfaceImpl implements MyInterface {
        public int getMethod() {
            return 0;
        }

        public void setMethod() {
            ;
        }
    }

    class Demo {
        public static void main() {
            MyInterface myinf = new MyInterfaceImpl();
            myinf.getMethod();
            myinf.setMethod();
        }
    }

```

interface里面的方法默认为public，可在定义时省略。


## constant field

static final

## multi-inheritance

```java

    public interface MyInterface extends ThisInterface, ThatInterface {}

```
