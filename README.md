# Trignometry
This is a Java program to find trignometric ratios of angles 
import java.util.*;
class trignometry
{
    void main()
{
    Scanner obj = new Scanner(System.in);
    System.out.println("enter the angle");
    int a = obj.nextInt();
    double r = Math.toRadians(a);
    double s = Math.sin(r);
    double c = Math.cos(r);
    double t = Math.tan(r);
    System.out.println("Sin:"+s);
    System.out.println("Cos"+c);
    System.out.println("Tan"+t);

    
    
}
}
