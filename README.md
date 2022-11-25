# Hollow-Square-Pattern-in-java.-Java-Program-to-print-Hollow-Square
Write a java program to print Hollow Square Pattern

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       
       
        Scanner console = new Scanner(System.in);
        System.out.println("Enter Number of Rows: ");
        int row = console.nextInt();
        for (int i = 1; i<=row; i++ ){
            for (int j =1; j<= (row*2)-1; j++){
                if (j == 1 || j == (row*2)-1 || i==1 || i==row ){
                    System.out.print("*");

                }else {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }

    }
}
