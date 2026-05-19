return_type func_name (formal_parametersOPTIONAL) 
{ 
    // body of the function 
    // do something(s) 
 
    return some_value; // must be of type return_type 
}  
 
double AddTwoNumbers(double num1, double num2) 
{ 
    return num1 + num2; // return a value directly, or: 
 
    double sum = num1 + num2; 
    return sum;  // return  a variabl
    int x = 5, y = 7;  
 
AddTwoNumbers(x, y); // C# will accept this as a statement, but bc. there’s a return, 
 
Console.WriteLine($“The sum of { x } and { y } is {AddTwoNumbers(x, y)}” ); // this, or 
 
double sum = AddTwoNumbers(x, y);  // this, is better..
4. Common Beginner Mistake
A common mistake is not to caling  the function after creating it. This happens because beginners think defining the function automatically runs it.
## sourse ; from class notes
