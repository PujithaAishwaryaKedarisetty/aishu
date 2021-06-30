# aishuimport java.util.*;

public class harshad {

    public static void main(String[] args) {
            int n,sum=0,r,x,temp;
            Scanner S=new Scanner(System.in);
//System.out.println("enter n value");
n=S.nextInt();
x=n;
while(n!=0)
{
    r=n%10;
    sum=sum+r;
    n=n/10;
    }
    temp=x%sum;
    if(temp==0)
    {
        System.out.println("harshad number");
    }
    else
    {System.out.println("not harshad number");}
    }
    }
