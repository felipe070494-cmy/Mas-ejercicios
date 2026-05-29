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


using System;

namespace MyApplication
{
  class Program
  {
    static void Main(string[] args)
    {
      // Sort a string
      string[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
      Array.Sort(cars);
      foreach (string i in cars)
      {
        Console.WriteLine(i);
      }

      // Sort an int
      int[] myNumbers = {5, 1, 8, 9};
      Array.Sort(myNumbers);
      foreach (int i in myNumbers)
      {
        Console.WriteLine(i);
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
      int[,] numbers = { {1, 4, 2}, {3, 6, 8} };
      numbers[0, 0] = 5;
      Console.WriteLine(numbers[0, 0]);
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
      int[,] numbers = { {1, 4, 2}, {3, 6, 8} };

      foreach (int i in numbers)
      {
        Console.WriteLine(i);
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
      int[,] numbers = { {1, 4, 2}, {3, 6, 8} };

      for (int i = 0; i < numbers.GetLength(0); i++)
      {
        for (int j = 0; j < numbers.GetLength(1); j++)
        {
          Console.WriteLine(numbers[i, j]);
        }
      }
    }
  }
}
