# Single_inheritance
class Father
{
 int a,b;
void getdata(int x,int y)
{
  a=x;
  b=y;
}
}
class Son extends Father
{
 int add()
{
 int sum=a+b;
 return sum;
}
 void disp()
{
  System.out.println("A:"+a);
  System.out.println("B:"+b);
System.out.println("sum:"+add());
}
}
class Test18
{
public static void main(String args[])
{
 Son obj=new Son();
  obj.getdata(15,25);
  obj.disp();
}
}
