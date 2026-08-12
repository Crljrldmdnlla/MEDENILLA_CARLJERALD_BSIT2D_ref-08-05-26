# MEDENILLA_CARLJERALD_BSIT2D_ref-08-05-26
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Enter your name: ");
        string name = Console.ReadLine();
        
        Console.WriteLine("Enter your age: ");
        int age = Convert.ToInt32(Console.ReadLine());
        
        Console.WriteLine("Enter your weight (kg): ");
        double weightkg = Convert.ToDouble(Console.ReadLine());
        
        double weightpounds = (weightkg * 22) / 10;
        bool weighttrue = true;
        
        
        Console.WriteLine("Hello " + name + ", you are " + age + " years old, your weight is " + weightkg.ToString("F2") + " kg and " + weightpounds + " pounds and this is verified " + weighttrue + ".");
        
    }

}


using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine ("My name is Carl Jerald Medenilla, I'm 18 years old, From San Francisco, Lubao, Pampanga.");
    }
}


using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
       int myInt = 18;
       string myString = "Carl Jerald Medenilla";
       double myFloat = 47.00;
       bool myBoolean = true;

       Console.WriteLine (myInt);
       Console.WriteLine (myString);
       Console.WriteLine ($"{myFloat:F2}");
       Console.WriteLine (myBoolean);
    }
}
