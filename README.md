# square-free-number

    import java.util.Scanner;
    public class Main{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();
        int a[]={2,3,5,7,11,13,17,19};
        int val=1;
        for(int i=0;i<8;i++){
            if(n%a[i]==0)
            val*=2;
        }
       System.out.print(val-1);
    }
      }
  
