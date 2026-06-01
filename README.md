# java-training
code's
import java.util.Scanner;
class Calculator {
 public static void main(String[] args) {
Scanner sc = new Scanner(System.in);

System.out.println("Enter first number: ");
int a = sc.nextInt();

 System.out.println("Enter second number: ");
 int b = sc.nextInt();

 System.out.println("Enter third number: ");
int c = sc.nextInt();

 System.out.print("Enter operator (+, -, *, /): ");
 char op = sc.next().charAt(0);

 if (op == '+') {
 System.out.println("Result = " + (a + b + c));
 } 
 else if (op == '-') {
 System.out.println("Result = " + (a - b - c));
 }
 else if (op == '*') {
 System.out.println("Result = " + (a*b*c));
 }
 else if (op == '/') {
 System.out.println("Result = " + (a/b/c));
 }
 else {
 System.out.println("Invalid Operator");
 }

 sc.close();
 }
}
