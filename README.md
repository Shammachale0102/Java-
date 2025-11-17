

# Java-
### Java Introduction
What is Java?

Java is a popular programming language, created in 1995.

It is owned by Oracle, and more than 3 billion devices run Java.

#### It is used for:

* Mobile applications (specially Android apps).

* Desktop applications.

* Web applications.

* Web servers and application servers.

* Games.

* Database connection.

* And much, much more!.

### Why Use Java?
* Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.).

* It is one of the most popular programming languages in the world.

* It has a large demand in the current job market.

* It is easy to learn and simple to use.

* It is open-source and free.

* It is secure, fast and powerful.

* It has huge community support (tens of millions of developers).

* Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs.

* As Java is close to C++ and C#, it makes it easy for programmers to switch to Java or vice versa.

## Java Syntax
Java Syntax
In the previous chapter, we created a Java file called Main.java, and we used the following code to print "Hello World" to the screen:

<pre>
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
</pre>

### Example explained:
Every line of code that runs in Java must be inside a class. The class name should always start with an uppercase first letter. In our example, we named the class Main.

Note: Java is case-sensitive. MyClass and myclass would be treated as two completely different names.

The name of the Java file must match the class name. So if your class is called Main, the file must be saved as Main.java. This is because Java uses the class name to find and run your code. If the names don't match, Java will give an error and the program will not run.
When saving the file, save it using the class name and add .java to the end of the filename. To run the example above on your computer, make sure that Java is properly installed: Go to the Get Started Chapter for how to install Java. The output should be:

<pre>Hello World</pre>
#### The main Method
The main() method is required in every Java program. It is where the program starts running:
<pre>public static void main(String[] args)</pre>
Any code placed inside the main() method will be executed.

For now, you don't need to understand the keywords public, static, and void. You will learn about them later in this tutorial. Just remember: main() is the starting point of every Java program.

#### System.out.println()
Inside the main() method, we can use the println() method to print a line of text to the screen:
<pre>public static void main(String[] args) {
  System.out.println("Hello World");
}</pre>

### Java Statements
#### Statements
A computer program is a list of "instructions" to be "executed" by a computer.

In a programming language, these programming instructions are called statements.

The following statement "instructs" the compiler to print the text "Java is fun!" to the screen:
<pre>System.out.println("Java is fun!");</pre>

It is important that you end the statement with a semicolon ;.

If you forget the semicolon (;), an error will occur and the program will not run:

#### Example
<pre>System.out.println("Java is fun!")</pre>

Result:
<pre>error: ';' expected</pre>
### Many Statements
Most Java programs contain many statements.

The statements are executed, one by one, in the same order as they are written:
<pre>System.out.println("Hello World!");
System.out.println("Have a good day!");
System.out.println("Learning Java is fun!");</pre>

#### Example explained
From the example above, we have three statements:

1.System.out.println("Hello World!");

2.System.out.println("Have a good day!");

3.System.out.println("Learning Java is fun!");


The first statement is executed first (print "Hello World!" to the screen).

Then the second statement is executed (print "Have a good day!" to the screen).

And at last, the third statement is executed (print "Learning Java is fun!" to the screen).

## Java Output / Print

### Print Text
You learned from the previous chapter that you can use the println() method to output values or print text in Java:

<pre>System.out.println("Hello World!");</pre>

You can add as many println() methods as you want. Note that it will add a new line for each method:

#### Example
<pre>System.out.println("Hello World!");
System.out.println("I am learning Java.");
System.out.println("It is awesome!");</pre>

#### Double Quotes
Text must be wrapped inside double quotations marks "".

If you forget the double quotes, an error occurs:
<pre>System.out.println("This sentence will work!");</pre>
<pre>System.out.println(This sentence will produce an error);</pre>

### The Print() Method
There is also a print() method, which is similar to println().

The only difference is that it does not insert a new line at the end of the output:
<pre>System.out.print("Hello World! ");
System.out.print("I will print on the same line.");</pre>

### Java Output Numbers
#### Print Numbers
You can also use the println() method to print numbers.

However, unlike text, we don't put numbers inside double quotes:
<pre>System.out.println(3);
System.out.println(358);
System.out.println(50000);</pre>

You can also perform mathematical calculations inside the println() method:

<pre>System.out.println(3 + 3);</pre>

#### Example
<pre>System.out.println(2 * 5);</pre>

### Java Comments

#### Java Comments

Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.

#### Single-line Comments
Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by Java (will not be executed).

This example uses a single-line comment before a line of code:

#### Example

Get your own Java Server
<pre>// This is a comment
  
System.out.println("Hello World");</pre>
This example uses a single-line comment at the end of a line of code:

#### Example
<pre>System.out.println("Hello World"); // This is a comment</pre>
#### Java Multi-line Comments
Multi-line comments start with /* and ends with */.

Any text between /* and */ will be ignored by Java.

This example uses a multi-line comment (a comment block) to explain the code:
<pre/* The code below will print the words Hello World
to the screen, and it is amazing */
System.out.println("Hello World");></pre>

### Java Variables

#### Java Variables
Variables are containers for storing data values.

In Java, there are different types of variables, for example:

String - stores text, such as "Hello". String values are surrounded by double quotes
int - stores integers (whole numbers), without decimals, such as 123 or -123
float - stores floating point numbers, with decimals, such as 19.99 or -19.99
char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
boolean - stores values with two states: true or false

#### Declaring (Creating) Variables
To create a variable in Java, you need to:

Choose a type (like int or String)
Give the variable a name (like x, age, or name)
Optionally assign it a value using =
Here's the basic syntax:
#### Syntax 
<pre>type variableName = value;</pre>

For example, if you want to store some text, you can use a String:

#### Example
Create a variable called name of type String and assign it the value "John".
Then we use println() to print the name variable:
<pre>String name = "John";
System.out.println(name);</pre>

To create a variable that should store a number, you can use int:
#### Example
Create a variable called myNum of type int and assign it the value 15:
<pre>int myNum = 15;
System.out.println(myNum);</pre>

You can also declare a variable without assigning the value, and assign the value later:
#### Example
<pre>int myNum;
myNum = 15;
System.out.println(myNum);</pre>

Note that if you assign a new value to an existing variable, it will overwrite the previous value:
#### Example
Change the value of myNum from 15 to 20:
<pre>int myNum = 15;
myNum = 20;  // myNum is now 20
System.out.println(myNum);</pre>

#### Final Variables
If you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):

#### Example
<pre>final int myNum = 15;
myNum = 20;  // will generate an error: cannot assign a value to a final variable</pre>

#### Other Types
A demonstration of how to declare variables of other types:
#### Example
<pre>int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";</pre>
### Java Print Variables

#### Display Variables
The println() method is often used to display variables.

To combine both text and a variable, use the + character:

#### Example

Get your own Java Server
<pre>String name = "John";
System.out.println("Hello " + name);</pre>

You can also use the + character to add a variable to another variable:

#### Example
<pre>String firstName = "John ";
String lastName = "Doe";
String fullName = firstName + lastName;
System.out.println(fullName);</pre>

In Java, the + symbol has two meanings:

For text (strings), it joins them together (called concatenation).
For numbers, it adds values together.
For numeric values, the + character works as a mathematical operator (notice that we use int (integer) variables here):

#### Example
<pre>int x = 5;
int y = 6;
System.out.println(x + y); // Print the value of x + y</pre>

From the example above, here's what happens step by step:

x stores the value 5
y stores the value 6
println() displays the result of x + y, which is 11.

#### Mixing Text and Numbers
Be careful when combining text and numbers in the same line of code. Without parentheses, Java will treat the numbers as text after the first string:
<pre>int x = 5;
int y = 6;

System.out.println("The sum is " + x + y);   // Prints: The sum is 56
System.out.println("The sum is " + (x + y)); // Prints: The sum is 11</pre>

#### Explanation:

In the first line, Java combines "The sum is " with x, creating the string "The sum is 5". Then y is added to that string, so it becomes "The sum is 56".

In the second line, the parentheses make sure x + y is calculated first (resulting in 11), so the output is "The sum is 11".

### Java Declare Multiple Variables
#### Declare Many Variables
To declare more than one variable of the same type, you can use a comma-separated list:

#### Example
Instead of writing:
<pre>int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z); // 61</pre>

You can write:
<pre>int x = 5, y = 6, z = 50;
System.out.println(x + y + z); // 61</pre>

#### One Value to Multiple Variables
You can also assign the same value to multiple variables in one line:

#### Example
<pre>int x, y, z;
x = y = z = 50;
System.out.println(x + y + z); // 150</pre>

### Java Identifiers
#### Identifiers
All Java variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

Note: It is recommended to use descriptive names in order to create understandable and maintainable code:
#### Example
<pre>// Good
int minutesPerHour = 60;

// OK, but not so easy to understand what m actually is
int m = 60;</pre>

The general rules for naming variables are:

.Names can contain letters, digits, underscores, and dollar signs

.Names must begin with a letter

.Names should start with a lowercase letter, and cannot contain whitespace

.Names can also begin with $ and _

.Names are case-sensitive ("myVar" and "myvar" are different variables)

.Reserved words (like Java keywords, such as int or boolean) cannot be used as names

#### Invalid Identifiers
Here are some examples of invalid identifiers that would cause errors:

#### Example
<pre>// Invalid identifiers:
int 2ndNumber = 5;  // Cannot start with a digit
int my var = 10;    // Cannot contain spaces
int int = 20;       // Cannot use reserved keywords</pre>

### Java Constants (final)
#### Constants (final keyword)
When you do not want a variable's value to change, use the final keyword.

A variable declared with final becomes a constant, which means unchangeable and read-only:
#### Example
<pre>final int myNum = 15;
myNum = 20;  // Error: cannot assign a value to final variable 'myNum'</pre>

#### When to Use final?
You should declare variables as final when their values should never change. For example, the number of minutes in an hour, or your birth year:

#### Example
<pre>final int MINUTES_PER_HOUR = 60;
final int BIRTHYEAR = 1980;</pre>

### Java Variables - Examples
#### Real-Life Examples

Often in our examples, we simplify variable names to match their data type (myInt or myNum for int types, myChar for char types, and so on). This is done to avoid confusion.


However, for a practical example of using variables, we have created a program that stores different data about a college student:
#### Example
<pre>// Student data
String studentName = "John Doe";
int studentID = 15;
int studentAge = 23;
float studentFee = 75.25f;
char studentGrade = 'B';

// Print variables
System.out.println("Student name: " + studentName);
System.out.println("Student id: " + studentID);
System.out.println("Student age: " + studentAge);
System.out.println("Student fee: " + studentFee);
System.out.println("Student grade: " + studentGrade);</pre>

### Calculate the Area of a Rectangle
In this real-life example, we create a program to calculate the area of a rectangle (by multiplying the length and width):

#### Example
<pre>// Create integer variables
int length = 4;
int width = 6;
int area;

// Calculate the area of a rectangle
area = length * width;

// Print variables
System.out.println("Length is: " + length);
System.out.println("Width is: " + width);
System.out.println("Area of the rectangle is: " + area);</pre>

### Java Data Types
#### Java Data Types
As explained in the previous chapter, a variable in Java must be a specified data type:
#### Example

<pre>int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String</pre>

Data types are divided into two groups:

.Primitive data types - includes byte, short, int, long, float, double, boolean and char.

.Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)

### Primitive Data Types
A primitive data type specifies the type of a variable and the kind of values it can hold.


There are eight primitive data types in Java:

Data Type ||Description

byte	::        Stores whole numbers from -128 to 127

short	 ::       Stores whole numbers from -32,768 to 32,767

int	 ::         Stores whole numbers from -2,147,483,648 to 2,147,483,647

long	  ::      Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807

float	  ::      Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits

double	::      Stores fractional numbers. Sufficient for storing 15 to 16 decimal digits

boolean  ::    	Stores true or false values

char	  ::      Stores a single character/letter or ASCII values

### You Cannot Change the Type
Once a variable is declared with a type, it cannot change to another type later in the program:

#### Example
int myNum = 5;       // myNum is an int
// myNum = "Hello";  // Error: cannot assign a String to an int

String myText = "Hi"; // myText is a String
// myText = 123;      // Error: cannot assign a number to a String

### Java Numbers
#### Numbers
Primitive number types are divided into two groups:

Integer types stores whole numbers, positive or negative (such as 123 or -456), without decimals. Valid types are byte, short, int and long. Which type you should use, depends on the numeric value.

Floating point types represents numbers with a fractional part, containing one or more decimals. There are two types: float and double.

### Integer Types
#### Byte
The byte data type can store whole numbers from -128 to 127. This can be used instead of int or other integer types to save memory when you are certain that the value will be within -128 and 127:

####Example 
<pre>byte myNum = 100;
System.out.println(myNum);</pre>

### Short
The short data type can store whole numbers from -32768 to 32767:

#### Example
<pre>short myNum = 5000;
System.out.println(myNum);</pre>

### Int
The int data type can store whole numbers from -2147483648 to 2147483647. In general, and in our tutorial, the int data type is the preferred data type when we create variables with a numeric value.

#### Example
<pre>int myNum = 100000;
System.out.println(myNum);</pre>

### Long
The long data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when int is not large enough to store the value. Note that you should end the value with an "L":

#### Example
<pre>Example</pre>

### Floating Point Types
You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

The float and double data types can store fractional numbers. Note that you should end the value with an "f" for floats and "d" for doubles:

#### Float Example

<pre>float myNum = 5.75f;
System.out.println(myNum);</pre>

### Double Example
<pre>double myNum = 19.99d;
System.out.println(myNum);</pre>

### Scientific Numbers
A floating point number can also be a scientific number with an "e" to indicate the power of 10:

#### Example
 <pre>float f1 = 35e3f;
double d1 = 12E4d;
System.out.println(f1);
System.out.println(d1);</pre>

## Java Boolean Data Types
### Boolean Types

Very often in programming, you will need a data type that can only have one of two values, like:

.YES / NO

. ON / OFF

.TRUE / FALSE

For this, Java has a boolean data type, which can only take the values true or false:
#### Example
<pre>boolean isJavaFun = true;
boolean isFishTasty = false;
System.out.println(isJavaFun);     // Outputs true
System.out.println(isFishTasty);   // Outputs false</pre>

### Java Characters

#### Characters
The char data type is used to store a single character. The character must be surrounded by single quotes, like 'A' or 'c':

#### Example
<pre>char myGrade = 'B';
System.out.println(myGrade);</pre>

Alternatively, if you are familiar with ASCII values, you can use those to display certain characters:
#### Example 
<pre>char myVar1 = 65, myVar2 = 66, myVar3 = 67;
System.out.println(myVar1);
System.out.println(myVar2);
System.out.println(myVar3);</pre>

### Strings 
The String data type is used to store a sequence of characters (text). String values must be surrounded by double quotes:

#### Example
<pre>String greeting = "Hello World";
System.out.println(greeting);</pre>

### Java Data Types Example
#### Real-Life Example

Here's a real-life example of using different data types, to calculate and output the total cost of a number of items:

#### Example

<pre>// Create variables of different data types
int items = 50;
float costPerItem = 9.99f;
float totalCost = items * costPerItem;
char currency = '$';

// Print variables
System.out.println("Number of items: " + items);
System.out.println("Cost per item: " + costPerItem + currency);
System.out.println("Total cost = " + totalCost + currency);</pre>

### Java Non-Primitive Data Types
#### Non-Primitive Data Types

Non-primitive data types are called reference types because they refer to objects.


The main differences between primitive and non-primitive data types are:


.Primitive types in Java are predefined and built into the language, while non-primitive types are created by the programmer (except for String).

.Non-primitive types can be used to call methods to perform certain operations, whereas primitive types cannot.

.Primitive types start with a lowercase letter (like int), while non-primitive types typically starts with an uppercase letter (like String).

.Primitive types always hold a value, whereas non-primitive types can be null.

### Java var
#### The var Keyword

The var keyword was introduced in Java 10 (released in 2018).

The var keyword lets the compiler automatically detect the type of a variable based on the value you assign to it.

This helps you write cleaner code and avoid repeating types, especially for long or complex types.

For example, instead of writing int x = 5;, you can write:
#### Example
<pre>var x = 5;  // x is an int
System.out.println(x);</pre>

#### Example with Different Types
Here are some examples showing how var can be used to create variables of different types, based on the values you assign:

#### Example
<pre>var myNum = 5;         // int
var myDouble = 9.98;   // double
var myChar = 'D';      // char
var myBoolean = true;  // boolean
var myString = "Hello"; // String</pre>

#### Important Notes
1. var only works when you assign a value at the same time (you can't declare var x; without assigning a value):
<pre>var x; // Error
var x = 5;  // OK</pre>

2. Once the type is chosen, it stays the same. See example below:
   <pre>var x = 5;  // x is now an int
x = 10;     // OK - still an int
x = 9.99;   // Error - can't assign a double to an int</pre>

### When to Use var
For simple variables, it's usually clearer to write the type directly (int, double, char, etc.).

#### Example
<pre>// Without var
ArrayList<String> cars = new ArrayList<String>();

// With var
var cars = new ArrayList<String>();</pre>
