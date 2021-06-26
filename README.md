         1+  import java.util.Arrays;
        2 +import java.util.Scanner;
        3 +
        4 +public class ProblemArray {
        5 +    public static void main(String[] args) {
        6 +        Scanner sc = new Scanner(System.in);
        7 +        int n = sc.nextInt();
        8 +
        9 +        int a[] = new int[n];
       10 +        int mul=1;
       11 +
       12 +        for (int i=0; i<a.length; i++) {
       13 +            a[i] = sc.nextInt();
       14 +            mul=mul*a[i];
       15 +        }
       16 +
       17 +        a[0]  = mul;
       18 +
       19 +        System.out.println(Arrays.toString(a));
       20 +
       21 +        sc.close();
       22 +    }
       23 +}            
