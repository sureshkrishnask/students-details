# students-details

import java.util.Scanner;
public class Main{
    public static void main (String[] args) {
        Scanner sc = new Scanner(System.in);
        String name , vaccination;
        int roll , age ;
       
        System.out.println("Name : ");
         name = sc.nextLine();
        System.out.println("Roll Number :");
         roll = sc.nextInt();
         System.out.println("Age : ");
         age = sc.nextInt();
         System.out.println("vaccination :");
         vaccination=sc.next();
         System.out.println("-----------------------------------------");
         System.out.println("The Details are ");
         System.out.println("name : " +name);
         System.out.println("roll Number :"  +roll);
         System.out.println("age : "   +age);
         System.out.println("vaccination :"   +vaccination);
    }
}
