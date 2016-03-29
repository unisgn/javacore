

```java
    
    class OuterClass {
        private boolean msg = "abc";



        class InnerClass {

            void greeting() {
                System.out.print(msg);
            }
        }
    }

```

inner class has knowledge about the outer class in the specified scope;


## anonymous inner class

```java

    class Demo {

        public static void main(String[] args){
              Thread t = new Thread(new Runnable() {
                 public void run() {
                      // do something;
                 }
              });
        }
    }

```

think about the Thread class, when you construct a Thread object, you need to pass a Runnerable object as the parameter, of course, you can write another class to implements the Runnerable interface, and 
