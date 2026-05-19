08_structure.md
A structure is a user data type designed to group related variables together under a single name.
structs are stored on stack
they are ideal for small, lightweighted data bundles.
## 2. Key C# Syntax
Console.WriteLine("Hello,Structs");
Movie1 m1;
m1. Id = 20161123;
m1.Title = "Moana";
m1.genre = "musical";
m1.rating = 7.6f;
//Console.WriteLine(m1.Id);
//Console.WriteLine(m1.Title);
//Console.WriteLine(m1.rating);
//Console.WriteLine(m1.genre);
movie1 m2;
m2.Id = 20141007;
m2.Title = "Flash";
m2.genre = "Action";
m2.rating = 7.5f;
//Console.WriteLine(m2.Id);
//Console.WriteLine(m2.Title);
//Console.WriteLine(m2.rating);
//Console.WriteLine(m2.genre);

void DisplayMovieInfo(Movie amovie)
{
    Console.WriteLine(amovie.Id);
    Console.WriteLine(amovie.Title);
    Console.WriteLine(amovie.Genre);
    Console.WriteLine(amovie.Rating);
}
struct Movie//PascalCase
{
    public int Id;
    public string Title;
    public string Genre;
    public int Rating;

}
3. Eureka Exercise / Moment
the fact that struct is different from array, gets me confused but it was essay to understand.
What made it click was realizing that structs  stores different types of data together.
## 4. Common Beginner Mistake
A common mistake is forgetting to create an instance of the struct before using it. 
This happens because beginners think defining the struct automatically creates usable variables, but you must create an object first.

## 5. Research References
 google,and class assignments or notes
