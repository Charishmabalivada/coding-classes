 import java.util.*;
class CountEvenOdd
{
    public static void main(String ars[])
    {
        Scanner sc=new Scanner(System.in);
        int size,i,evenCount=0,oddCount=0;
        System.out.println("Enter number of elements in an array:");
        size=sc.nextInt();
        int [] a=new int[size];
        System.out.println("Enter "+size+"elements of an array:");
        for(i=0;i<size;i++)
        {
           a[i]=sc.nextInt();
        }
        for(i=0;i<size;i++)
        {
            if(a[i]%2==0)
            {
                evenCount++;
            }
            else
            {
                oddCount++;
            }
        }
        System.out.println("\n total no. of even numbers:"+evenCount);
        System.out.println("\n total no. of odd numbers:"+oddCount);
        int r;
        r=evenCount*oddCount;
        System.out.println(r);
    }
}
