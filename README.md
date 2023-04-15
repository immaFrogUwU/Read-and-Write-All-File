using System;
using System.IO;
using static System.Console;
namespace Homework
{ 
  public class Program
  {
    public static void Main()
    {
      WriteLine("Doc noi dung trong file: ");
      string a = File.ReadAllText("test.txt");
      WriteLine(a);
      string noidung = "Ech HB Academy";
      File.WriteAllText("out.txt", noidung);
      string b = File.ReadAllText("out.txt");
      WriteLine(b); 
     }
   }
 }

            
                  
