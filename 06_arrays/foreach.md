// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, for each!");
char[] A = { 'a', 'b', 'c', 'd', 'e' };
foreach (char c in A)
{
    Console.WriteLine(c);
}


int[] B = { 15, 20, 25, 30, 35};
foreach(int element in B)
{
    Console.WriteLine(element);
}

string[] students    = {  "Solange", "Shivani", "Erwan" ,"Isa","Jessica","Toa"};
foreach (string element  in students)
{
    Console.WriteLine(element);

}
foreach (var element in B)
{
    Console.WriteLine(element);
}



