# Chapter-1 Content 

* [What is Java](#What-is-Java)
* [Why Use Java](#Why-Use-Java)
* [Hello World using Java Programming](#Hello-World-using-Java-Programming)
* [Java Syntax](#Java-Syntax)


## What is Java?
Java is a high-level programming language originally developed by Sun Microsystems and released in 1995.Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX. 


## Why Use Java?

*Object Oriented* − In Java, everything is an Object. Java can be easily extended since it is based on the Object model.

*Platform Independent* − Unlike many other programming languages including C and C++, when Java is compiled, it is not compiled into platform specific machine, rather into platform independent byte code. This byte code is distributed over the web and interpreted by the Virtual Machine (JVM) on whichever platform it is being run on.

*Simple* − Java is designed to be easy to learn. If you understand the basic concept of OOP Java, it would be easy to master.

*Secure* − With Java's secure feature it enables to develop virus-free, tamper-free systems. Authentication techniques are based on public-key encryption.

*Portable* − Being architecture-neutral and having no implementation dependent aspects of the specification makes Java portable. Compiler in Java is written in ANSI C with a clean portability boundary, which is a POSIX subset.

*Robust* − Java makes an effort to eliminate error prone situations by emphasizing mainly on compile time error checking and runtime checking.


## Hello World using Java Programming.

Let's create our first Java file, called MyFirstJavaProgram.java, which can be done in any text editor (like Notepad).
In Java, every application begins with a class name, and that class must match the filename.The file should contain a "Hello World" message, which is written with the following code:

INPUT :
```
public class MyFirstJavaProgram {

/* This is my first java program.
* This will print 'Hello World' as the output
    */

public static void main(String []args) {
        System.out.println("Hello World"); // prints Hello World
      }
    }

```
OUTPUT :
 
    Hello World
  
  
## Java Syntax  
Every line of code that runs in Java must be inside a class. In our example, we named the class MyFirstJavaProgram . A class should always start with an uppercase first letter.

**Note: Java is case-sensitive: "MyFirstJavaProgram" and "myFirstJavaProgram" has different meaning.**

The name of the java file must match the class name. When saving the file, save it using the class name and add ".java" to the end of the filename. 

### The main Method
The main() method is required and you will see it in every Java program:

    public static void main(String[] args)
    
Any code inside the main() method will be executed.For now, just remember that every Java program has a class name which must match the filename, and that every program must contain the main() method.

### System.out.println()
Inside the main() method, we can use the println() method to print a line of text to the screen:

    public static void main(String []args) {
        System.out.println("Hello World"); // prints Hello World



**Note:**

**1) The curly braces { } marks the beginning and the end of a block of code.**

**2) Each code statement must end with a semicolon.**

### Java Comments
Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.
Single-line comments start with two forward slashes (//).
Any text between // and the end of the line is ignored by Java (will not be executed).
This example uses a single-line comment before a line of code:

    // This is a comment
    System.out.println("Hello World");
    
 ### Java Multi-line Comments
Multi-line comments start with /* and ends with */.
Any text between /* and */ will be ignored by Java.
This example uses a multi-line comment (a comment block) to explain the code:

    /* The code below will print the words Hello World
    to the screen, and it is amazing */
    System.out.println("Hello World");
    
    

 





 

