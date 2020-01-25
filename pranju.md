using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication35
{
class Program
{
static void Main(string[] args)
{
string fruit = "Apple";
switch (fruit)
{
case "Banana":
Console.Write(fruit+"Is the delecious fruit");
break;
case "chair":
Console.Write(fruit + "Is the deleciousfruit");
break;
case "Apple":
goto case "Banana";
break;
case "Table":
goto case "chair";
break;
}
Console.ReadKey();
}
 
