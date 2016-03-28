
# interface



<code>
    public interface MyInterface {
        int AGE = 12;
        int getMethod();
        voit setMethod();
    }
</code>

interface里面的方法默认为public，可在定义时省略。


interface可以有常量域，默认为static final

interface可多重继承。

<code>
public interface MyInterface extends ThisInterface, ThatInterface {
    
}
</code>
