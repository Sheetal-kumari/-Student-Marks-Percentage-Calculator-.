# -Student-Marks-Percentage-Calculator-.
"Student-Marks-Percentage-Calculator".
Overview

A simple Java program to calculate the percentage of marks obtained by a student in a given subject.

Features

- Calculates percentage based on marks obtained and total marks
- Handles invalid input and edge cases

Usage

1. Compile the Java program using javac
2. Run the program using java
3. Enter the marks obtained and total marks when prompted
4. The program will display the calculated percentage

Requirements

- Java 8 or later

Contributing

Contributions are welcome! If you find any bugs or want to improve the program, please submit a pull request.

CODE:-

   import java.util.*;
class Main {
    public static void main(String[] args) {
        Scanner marks = new Scanner(System.in);
          System.out.println("marks out of :");
          int num = marks.nextInt();
        System.out.println("number of subjects :");
               int subject = marks.nextInt();
               System.out.println("totalmarks");
           int totalmarks = num*subject;
           System.out.println(totalmarks);
           double sum = 0;
        for(int i = 0;i<subject;i++){
            System.out.println("enter the marks");
            int score = marks.nextInt();
            sum = sum + score;
           }
           System.out.println("total marks obtained :");
       System.out.println(sum);
       double percantage = sum * 100 /totalmarks;
       System.out.println(percantage);
    }
}
