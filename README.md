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
