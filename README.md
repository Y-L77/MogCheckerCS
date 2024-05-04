using System;
//do they mog simulator
class Human {
    static void Main(string[] args) {

        Console.WriteLine("Enter your age:");
        int age = int.Parse(Console.ReadLine()); //initializer for age variable, console.writeline is the input function for c#. anything after below the script will initalize for the input.

        Console.WriteLine("What is your height in centimeters:");
        int height = int.Parse(Console.ReadLine());

        Console.WriteLine("What is your salary: (no commas, no prefixes e.g K, M, B, T, Qd, Qu, etc.)");
        int salary = int.Parse(Console.ReadLine());


        Console.WriteLine("Are you good looking? (yes/no):"); // Asking for input as yes or no
        string looks = Console.ReadLine();
        bool goodLooks = looks.ToLower() == "yes"; //if the readline is yes c# will automatically assign true to goodlooks

        if (age >= 15 && height >= 182 && salary >= 96000 && goodLooks == true)
        {
        Console.WriteLine("It might not be over");
        }
        else{
            Console.WriteLine("its over gg"); //curly braces should not be like under the conditional block even though it can, i like it when it is besides the condition
        }

        
    }
}
