# MEDENILLA_CARL-JERALD_08-05-26
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
        
        
        Console.WriteLine("Hello " + name + ", you are " + age + " years old, your weight is " + weightkg + " and " + weightpounds + " pounds and this is verified " + weighttrue + ".");
        
    }

}
