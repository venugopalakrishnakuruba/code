# code
import java.util.Scanner;
class Solu{
public static void main(String [] args){
char oper;
Double n1,n2,result;
Scanner in=new Scanner(System.in);
System.out.println("Choose operator: +,-,*,or /");
oper=in.next().charAt(0);
System.out.println("enter first number");
n1=in.nextDouble();
System.out.println("enter second number"):
n2=in.nextDouble();
switch(oper){
case '+':
result=n1+n2;
system.out.println(n1+"+"+n2+"="+result);
break;
case '-':
result=n1-n2;
system.out.println(n1+"-"+n2+"="+result);
break;
case '*':
result=n1*n2;
system.out.println(n1+"*"+n2+"="+result);
break;
case '/':
result=n1/n2;
system.out.println(n1+"/"+n2+"="+result);
break;
default:
System.out.println("invalid");
break;
}
in.close();
}
}
