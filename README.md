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

###Java Statements
####Statements
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
###Many Statements
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
