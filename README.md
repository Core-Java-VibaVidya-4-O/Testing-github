# abstract class Abstract {
        3 +    abstract void func();
        4 +
        5 +    void normalFunc() {
        6 +        System.out.println("Supports normal methods");
        7 +    }
        8 +}
        9 +
       10 +public class Abstraction extends Abstract{
       11 +    public static void main(String[] args) {
       12 +        new Abstraction().func();
       13 +        new Abstraction().normalFunc();
       14 +    }
       15 +
       16 +    void func() {
       17 +        System.out.println("Abstraction in java");
       18 +    }
       19 +}
