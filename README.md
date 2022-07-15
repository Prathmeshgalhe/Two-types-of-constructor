# Two-types-of-constructor
class Result
{
    int roll_no;
    String name;
    double per;
    Result()
    {
        System.out.println("We are in default constructor");
    }
    Result(int i, String s, double d)
    {
        roll_no=i;
        name=s;
        per=d;
    }
    void display()
    {
        System.out.println("roll no "+roll_no+ " having Name "+name+ " get "+per+" % ");
    }
}
public class ResultNew
{
    public static void main(String args[])
    {
        Result r1 = new Result();
Result r2 = new Result(1,"Avi",90.20);
        Result r3 = new Result(2,"Sid",91.20);
        Result r4 = new Result(3,"Omkar",92.20);
        r2.display();
        r3.display();
        r4.display();
    }
}
