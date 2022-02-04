# Spring2022 Lab 2

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
