# C-
CALULATE A KILOWATT UNIT OF DEVICES AND COST 
using System;
namespaces Calculator;
{
class Calculator 
{ 
static void Main(string [] args) // main function
{
Console.WriteLine("ENTER A DEVICE NAME:"); // Take a appliance name
string name=Console.ReadLine();
Console.WriteLine(name); // Show a appliance name
Console.WriteLine("ENTER A DEVICE WATT:--"); // Take a appliances watt that consumed by it
string watt=Console.ReadLine();
Console.WriteLine("Enter a run time of appliances in hours:--");
string hour=Console.ReadLine();
double kwh=(Convert.ToDouble32(watt) * Convert.ToDouble32(hour))/1000;
Console.WriteLine(" Appliances total unit is:---" + kwh);
Console.WriteLine("Enter a rate of unit:--");
string rate=Console.ReadLine();
double cost=(Convert.TODouble32(rate))*kwh;
double bill=(Convert.ToDouble32(watt) * 24 *30)/1000;
Console.WriteLine("The appliances name is:--" + name + "Total unit consumed by its:--" + kwh + "Total bill consumed by it one month is:--" + bill);
Console.ReadLine();
}
}
}
}}
