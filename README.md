# lab6
Grade.java

import java.util.Scanner;

public class Grade
{
        public static void main(String[] args) 
        {
                int PP, Lab, Mid, End, Total;

                Scanner sc = new Scanner(System.in);

                System.out.print("Enter practice problems marks:");
                PP = sc.nextInt();

                System.out.print("Enter Labs marks:");
                Lab = sc.nextInt();

                System.out.print("Enter Midterms marks:");
                Mid = sc.nextInt();

                System.out.print("Enter End marks:");
                Final = sc.nextInt();

                Total = PP + Lab + Mid + End;

                if(Total > 89)
                        System.out.print("Grade A");
                else if(Total > 79)
                        System.out.print("Grade B");
                else if(Total > 69)
                        System.out.print("Grade C");
                else if(Total > 59)
                        System.out.print("Grade D");
                else 
                        System.out.print("Grade F");
        }
}
