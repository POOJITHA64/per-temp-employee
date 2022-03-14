# per-temp-employee
import java.util.*;
class employee
{
    int id;
    String name;
    double salary;
    Scanner s=new Scanner(System.in);
    void reademp()
    {
        System.out.println("enter id:");
        id=s.nextInt();
        System.out.println("enter name:");
        name=s.next();
        System.out.println("enter salary:");
        salary=s.next.double()
    }
}
class permanent_employee extends employee
{
    void print_emp()
    {
        double salary;
        salary=(salary+salary*(0.05));
        System.out.println("if empployee is permanent the salary increments 5% the final saslary is:"+salary);
    }
}
class temporary_employee extends employee
{
    void print_emp()
    {
        double salary;
        salary=(salary+salary*(0.05));
        System.out.println("if employee is temporary the salary increments 3.5% the final salary is"+salary);
    }
}
class Main
    {
        public static void main(String args[])
        {
            Scanner s=new Scanner(System.in);
            System.out.println("enter the value of n:");
            int n=s.nextInt();
            int i;
            employee e=new employee();
            temporary_employee t=new temporary_employee();
            permanent_employee p=new permanent_employee();
            for(i=0;i<n;i++)
            {
                t.read_emp();
                t.print_emp();
                p.read_emp();
                p.print_emp();
            }
        }
    }
