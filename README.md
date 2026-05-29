# Mas-ejercicios
using System;

namespace myApplication
{
class program
{
    static void Main(string[] args)
    {
        for (int i = 0; i <= 10; i = i + 2)
        {
            console.WriteLine(i);
        }
    }
}
}

using System;

namespace MyApplication
{
    class Program
    {
        static void Main(string[] args)
        {
            // Outer loop
            for (int i = 1; i <= 2; ++i)
            {
                Console.WriteLine("Outer: " + i);  // Executes 2 times

                // Inner loop
                for (int j = 1; j <= 3; j++)
                {
                    Console.WriteLine(" Inner: " + j);  // Executes 6 times (2 * 3)
                }
            }

        
        using System;

namespace MyApplication
{
    class Program
    {
        static void Main(string[] args)
        {
            string[] cars = { "Volvo", "BMW", "Ford", "Mazda" };
            Console.WriteLine(cars[2]);
        }
}
    }
}


using System;

namespace MyApplication
{
    class Program
    {
        static void Main(string[] args)
        {
            string[] cars = { "Volvo", "BMW", "Ford", "Mazda" };
            cars[0] = "Opel";
            Console.WriteLine(cars[3]);
        }
    }
}



using System;

namespace MyApplication
{
    class Program
    {
        static void Main(string[] args)
        {
            string[] cars = { "Volvo", "BMW", "Ford", "Mazda", "Toyota" };
            Console.WriteLine(cars.Length);
        }
    }
}

using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      // Declare an array
      string[] cars;

      // Add values, using new
      cars = new string[] {"Volvo", "BMW", "Ford"};

      // This would cause an error: cars = {"Volvo", "BMW", "Ford"};

      Console.WriteLine(cars[0]);
    }
  }
}
