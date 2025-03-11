# My-Snippets
Мy snippets that I created to help me.

0. cr - Console.ReadLine(); // read input from user (Console). The return value is a string.

1. ipr - int name = int.Parse(Console.ReadLine()); // new int waiting for input from user

2. ca - type [] names = new type [size]; // creates a new empty array

3. cl - List name<type> = new list<type>(); // creates a new list of type variable

4. str - string name = Console.ReadLine(); // new string waiting for input from user

5. crs - string [] name = Console.ReadLine() .Split(", "); Console.ReadLine() // Read input from console as niz (string).
.Split(", ") – Splits the read string into substrings, using ", " (comma and space) as separator.
string[] name – Declares an array of strings (string[]) that will contain the results of the split.

6. ssa - int[] numbers = Console.ReadLine().Split(", ").Select(int.Parse).ToArray();//Read the input as a string.
.Split(", ") – Splits the string into parts, using ", " (comma and space) as a separator.
.Select(int.Parse) – Converts each element of the array (which is a string) to an integer (int).
.ToArray() – Converts the result back to an array of integers (int[]).

7. ssl - List<int> numbers = Console.ReadLine() .Split(", ") .Select(int.Parse) .ToList();//Read the input as a string.
.Split(", ") – Splits the read string into substrings, using ", " (comma and space) as a separator.
.Select(int.Parse) – Converts each string to an integer (int).
.ToList() – Converts the result to a list of integers (List<int>)

8. sysypm - namespace ConsoleApp1 { internal class Program { static void Main(string[] args) { }}//namespace ConsoleApp1
Defines a namespace that groups classes and other types. ConsoleApp1 is the name of the namespace that is usually included with the project name.internal class Program Defines a class named Program.The Internal modifier means that this class is only accessible within the next project. static void Main(string[] args) This is the main method (Main), which is executed first when the program is started.
string[] args – This is an array of arguments that can be passed by a command red.void – The method has no return value. Method body { }

9. cr - Console.ReadLine();// read input from the console as niz (string).

10. no - Create a new object
MyClass myObject = new MyClass();

11. nl - Initialize a list
List<int> numbers = new List<int>() { 1, 2, 3, 4, 5 };

12. fcw - Loop through a list with a foreach loop
foreach (integer in numbers)
{
Console.WriteLine(number);
}

13. adi - Add an element to the list
numbers.Add(0);

14. rmi - Remove an element from a list
numbers.Remove(0);

15. bc - Check if the list contains a specific element
bool contains Number = numbers. Contains(4);

16. sl - Sort a list
numbers.Sort();

17. rl - Reverse the order of elements in the list
numbers.Reverse();

18. fl - Filtering a list with LINQ
var evenNumbers = numbers.Where(n => n % 2 == 0).ToList();

19. ig - Grouping elements by criteria
var groupedByRemainder = numbers.GroupBy(n => n % 3);

20. ll - Combining two lists
List<int> moreNumbers = new List<int>() { 7, 8, 9 };
var combinationList = numbers.Concat(moreNumbers).ToList();

21. anm - Using anonymous methods
Action<string> printString = delegate (string s) { Console.WriteLine(s); };
printString("Hello, world!");

22. lax - Using lambda expressions
Func<int, int> square = x => x * x;
int result = square(5);

23. dic - Working with dictionaries (Dictionary)
Dictionary<string, int> ages = new Dictionary<string, int>()
{
{"Name1", 01},
{"Name2", 02}
};
24. acd - Accessing a value in a dictionary
int namesAge = ages["Name"];

25. ank - Adding a new key-value pair to a dictionary
ages.Add("Name", 01);

26. cnk - Checking if the dictionary contains a certain key
bool hasKey = ages.ContainsKey("Bob");

27. rmi - Removing an element from a dictionary
numbers.Remove(0);

28. uty - Using try-catch blocks to handle exceptions
try
{
// Code that can throw an exception
}
catch (exception ex)
{
Console.WriteLine($"An error occurred: {ex.Message}");
}
finally
{
// Code that always runs regardless of an exception
}

29. ua - Using using to automatically release resources
using (StreamWriter writer = new StreamWriter("example.txt"))
{
writer.WriteLine("This is an example.");
}

30. dn - Dictionary declaration and initialization
var dic = new Dictionary<object, object>();

31.dnx - Creates a new dictionary
var dic = new Dictionary<object, object>() { [0] = null };

32. dc - Dictionary Dictionary
Dictionary<object, object>

33. va - Empty array of T variable
variable items = new T[0];

34. vax - Declaration and initialization of an array with a T variable
var items = new T[] {null};

35. lx - Empty list of type T variable
List<T>

36. vn - Empty of a list with a T variable
variable items = new List<T>();

37. vnx - Declaration and initialization of a list with a T variable
var items = new List<T>() { null };

38. nc - New Empty Class
class ClassName
{

}
