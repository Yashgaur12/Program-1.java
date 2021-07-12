# Program-1.java
import java.util.Scanner;
class main
{
public static void main(String[] args)
{
double a,b;
String operator="+,-,*,/"
Scanner sc=new scanner (System.in);
System.out.print("Enter first number:");
a=sc.nextDouble();
System.out.print("Enter second number:");
b=sc.nextDouble();
System.out.print("Enter the operator(+,-,*,/):");
char operator = scanner.next().charAt();
scanner.close();
double result;
switch(operator)
{
case'+':
result=a+b;
break;
case'-':
result=a-b;
break;
case'*':
result=a*b;
break;
case'/':
result=a/b;
break;
default:
 System.out.printf("You have entered wrong value");
 return;
 }
System.out.println( a+ "operator+" "b+": "+result);
}
}
