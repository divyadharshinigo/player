import java.util.scanner;
class factorial
{
public static void main(String[] args)
{
Scanner sc=new Scanner(System.in);
System.out.println("enter number");
int n=sc.nextInt();
int factorial=fact(n);
System.out.println("factorial of given number is:"+factorial);
}
static int fact(int num)
{
int output;
if(num==1)
{
return 1;
}
else
{
output=fact(num-1)*num;
return output;
}
}
