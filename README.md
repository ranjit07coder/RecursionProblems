# RecursionProblems
In this repository there are some problems related to recursion 
This is problem for calculating the factorial of numbers using recursion ....... 

public class Main{
    public static  calculatefact(int n){
        
        if(n == 1 || n == 0){
            
            return 1;
        }
        int fact_nm1=calculatefact(n-1);
        int fact_n = n*fact_nm1;
        return fact_n;
        
    }
    public static void main(String[] args){
         int n = 5; //initialization
         int ans=calculatefact(n);
         System.out.println(ans);
    } 
}
