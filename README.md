# yearsanddate.java
by aditya 

import java.util.Scanner;
    public static void main(String[] args) {
     Scanner input = new Scanner(System.in);
   
    System.out.println("Enter the number of minutes:");
    int minutes = input.nextInt();

     
    int year = minutes / 525600;
    int day = minutes / 1440;
    int remainingMinutes = day % 525600;


    System.out.println(minutes + " minutes is " + year + " years and "  +  remainingMinutes + " days ");
    }

