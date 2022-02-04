# Spring2022 Lab 2a

using System;

class Program {
  
  public static void Main (string[] args) {
    
    Console.WriteLine ("Enter the name of the item: ");
    string itemName = Console.ReadLine();
    
    Console.WriteLine ("Enter the quantity: ");
    int quantity = Convert.ToInt32(Console.ReadLine());
    
    Console.WriteLine ("Enter the price: ");
    int price = Convert.ToInt32(Console.ReadLine());
    
    Console.WriteLine("Total price of " + itemName + "= $" + quantity * price);
  }
}

# Spring2022 Lab 2b

using System;

class Program {
  
  public static void Main (string[] args) {
    
    Console.WriteLine ("Enter a number: ");
    int num1 = Convert.ToInt32(Console.ReadLine());

    Console.WriteLine ("Enter another number: ");
    int num2 = Convert.ToInt32(Console.ReadLine());

    Console.WriteLine("sum= "+ num1 + num2);
    int diff = num1-num2;
    Console.WriteLine("diff= "+ diff);
    Console.WriteLine("product= "+ num1 * num2);
    Console.WriteLine("Quotient= "+ num1/num2);
    Console.WriteLine("remainder= "+ num1 % num2);

  }
}
