# Compare-the-Triplates
hackerRank , Compare the Triplates ,  Solution 

uttam kumar 


import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
   
        Scanner scan = new Scanner(System.in);
//        int N = scan.nextInt();
        int[] Uttam = new int[3];
        int[] Kumar = new int[3];
        int a=0, b=0;
        for(int i=0;i<3;i++)
            Uttam[i]=scan.nextInt();
        for(int i=0;i<3;i++)
            Kumar[i]=scan.nextInt();
        for(int i=0;i<3;i++)
            if(Uttam[i]>Kumar[i])
                a++;
            else if(Uttam[i]<Kumar[i])
                b++;
        System.out.println(a+" "+b);
        scan.close();
    }
}

