# prime
Public class Prime
{
public static void main (String[] args)
{		
   for(int i = 2; i<= 100; i++)         
  {
 int num=0;		  	  	  
    for(int j =2; j<=i/2; j++)
 {
    if(i%j==0)
 {
 num=1;
break;
 }
 }
   if(num==0)
  {
       System.out.println(i);}
   }
  }
}
