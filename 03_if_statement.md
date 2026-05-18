# Topic Name
## 1. Concept in my own Words
## 2. Key C# Syntax
## 3. Eureka Exercise/ Moment

If statement: A control structure that checks a condition and runs a block of code only if that condition is true.
If statement = runs code only when something is true

## 2. Key C# Syntax
int age = 10;

if (age < 18 >=13) // condition
{
    Console.WriteLine("teen"); // runs if true
}
else
{
    Console.WriteLine("Minor"); // runs if false
}

## 3. Eureka Exercise / Moment
I was  confused about how the condition worked. What helped me understand was stepping through the code and seeing that the program checks the condition first and only runs one block depending on whether 
it’s true or false.

## 4. Common Beginner Mistake

A common mistake is forgetting to use == when comparing values and using = instead. This happens because they look similar, 
but = assigns a value and == checks equality, which can cause errors.

if (score >= 50)
{
  Console.WriteLine("pass");
}
else
{
 Console.WriteLine("fail");
}
