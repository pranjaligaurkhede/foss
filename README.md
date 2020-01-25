# foss
WAP IN C# TO SHOW SORTING AND REVERSING AN ARRAY.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication6
{
    class Program
    {
        static void Main(string[] args)
        {
            //creating an Array
            int[] x = { 30, 20, 80, 90, 20 };
            Console.WriteLine("Array before sorting");
            foreach (int i in x)
            {
                Console.WriteLine(" " + i);
                Console.WriteLine();
                //Sorting and Reversing the array elements
            }
                Array.Sort(x); Array.Reverse(x);
                Console.WriteLine("Array after Sorting and Reversing");
                foreach (int i in x)
                {
                    Console.Write(" " + i);
                Console.WriteLine();
            }
            Console.ReadKey();
  //creating an Array
        }
    }
}



