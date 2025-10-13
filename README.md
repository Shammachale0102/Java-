
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


