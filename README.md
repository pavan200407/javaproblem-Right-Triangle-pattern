# javaproblem-Right-Triangle-pattern
//java program to print the Right Triangle pattern.
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("Eneter any number:");
        int limit=sc.nextInt();
        int i,j;
        for(i=0;i<=limit;i++){
             for(j=0;j<i+1;j++){
                  System.out.print("*");
             }
             System.out.println();
        }  
    }
}
