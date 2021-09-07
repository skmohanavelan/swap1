import java.util.Scanner;
public class Swap1 {
public static void main(String args[]) {
System.out.println(&quot;Before swapping&quot;);
int a = 10;
int b = 20;
System.out.println(&quot;value of a:&quot; + a);
System.out.println(&quot;value of b:&quot; + b);
System.out.println(&quot;After swapping&quot;);
a = a + b;
b = a - b;
a = a - b;
System.out.println(&quot;value of a:&quot; + a);
System.out.println(&quot;value of b:&quot; + b);
}
}
