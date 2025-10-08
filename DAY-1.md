DAY-1 

Task-1

Addtition of three numbers

import java.util.Scanner;

public class AddThreeNumbers {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Enter first number: ");

&nbsp;       int num1 = sc.nextInt();

&nbsp;       System.out.print("Enter second number: ");

&nbsp;       int num2 = sc.nextInt();

&nbsp;       System.out.print("Enter third number: ");

&nbsp;       int num3 = sc.nextInt();

&nbsp;       int sum = num1 + num2 + num3;

&nbsp;       System.out.println("The sum of the three numbers is: " + sum);

&nbsp;       sc.close();

&nbsp;   }

}



*DAY-1(Task-2)*

<b>Get name and contact number and email and password from user and print them</b>



import java.util.Scanner;

public class UserInfo {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Enter your full name: ");

&nbsp;       String name = sc.nextLine();

&nbsp;       System.out.print("Enter your contact number: ");

&nbsp;       String contact = sc.nextLine(); 

&nbsp;       System.out.print("Enter your email: ");

&nbsp;       String email = sc.nextLine();

&nbsp;       System.out.print("Enter your password: ");

&nbsp;       String password = sc.nextLine(); 

&nbsp;       sc.close();

&nbsp;       System.out.println("\\n--- You entered ---");

&nbsp;       System.out.println("Name    : " + name);

&nbsp;       System.out.println("Contact : " + contact);

&nbsp;       System.out.println("Email   : " + email);

&nbsp;       System.out.println("Password: " + password);

&nbsp;   }

}



*DAY-1(Task-3)*

<b>Swap of two numbers</b>

import java.util.Scanner;

public class SwapNumbers {

&nbsp;   public static void main(String\[] args) {

&nbsp;       Scanner sc = new Scanner(System.in);

&nbsp;       System.out.print("Enter first number: ");

&nbsp;       int n1 = sc.nextInt();

&nbsp;       System.out.print("Enter second number: ");

&nbsp;       int n2 = sc.nextInt();

&nbsp;       System.out.println("\\nBefore swapping:");

&nbsp;       System.out.println("First number = " + n1);

&nbsp;       System.out.println("Second number = " + n2);

&nbsp;       int temp = n1;

&nbsp;       n1 = n2;

&nbsp;       n2 = temp;

&nbsp;       System.out.println("\\nAfter swapping:");

&nbsp;       System.out.println("First number = " + n1);

&nbsp;       System.out.println("Second number = " + n2);

&nbsp;       sc.close();

&nbsp;   }

}

*DAY-1(Task-4)*

**Area of circle**

*import java.util.Scanner;*

*public class AreaOfCircle {*

    *public static void main(String\[] args) {*

        *Scanner sc = new Scanner(System.in);*

        *System.out.print("Enter the radius of the circle: ");*

        *double radius = sc.nextDouble();*

        *double area = Math.PI \* radius \* radius;*

        *System.out.println("The area of the circle is: " + area);*

        *sc.close();*

    *}*

*}*





