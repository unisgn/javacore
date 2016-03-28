


# anonymous inner class

```java

Thread t = new Thread(new Runnerable() {
   public void run() {
        // do something;
   } 
});

```

think about the Thread class, when you construct a Thread object, you need to pass a Runnerable object as the parameter, of course, you can write another class to implements the Runnerable interface, and 
