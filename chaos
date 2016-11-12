import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner stdin = new Scanner(System.in);
        int t = stdin.nextInt(); // Number of cases
        for(int m=0;m<t;m++){
            boolean flag=true; // flag for swap
            boolean chaos=false; // flag for chaos
            int n=stdin.nextInt(); // Number of people
            int[] p = new int[n];
            for(int i=0;i<n;i++){
                p[i] = stdin.nextInt(); // Line's current state
                if(p[i]>i+3)
                    chaos=true;
                }
            if(!chaos){
                int sum=0;
                int temp;
                while(flag){
                    flag= false;    //set flag to false awaiting a possible swap
                    for(int j=0;  j<n-1;  j++ ){
                        if(p[j]>p[j+1]){
                            temp = p[j];                //swap elements
                            p[j] = p[j+1];
                            p[j+1] = temp;
                            flag = true;              //shows a swap occurred
                            sum++;
                        }
                    }
                }
                System.out.println(sum);
            }
            else
                System.out.println("Too chaotic");
        }

}
}
