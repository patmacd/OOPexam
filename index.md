<!DOCTYPE html>
<html> 
	
    1. What is Java and state the function of the compiler and the interpreter in the Java programming language
    
Java is a high-level programming language originally developed by Sun Microsystems and released in 1995. Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX. Java is compiled to an intermediate "byte code" at compilation time. This is in contrast to a language like C that is compiled to machine language at compilation time. The Java byte code cannot be directly executed on hardware the way that compiled C code can. Instead the byte code must be interpreted by the JVM (Java Virtual Machine) at runtime in order to be executed.

<b>2. Explain the concept of 'platform independence' and/or architectural neutrality. What are the supported platforms by Java Programming Language?</b>

Java is said to be platform independent or architectural neutral as a Java program do not depend upon the operating system or hardware it is running on. Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX/Linux like HP-Unix, Sun Solaris, Red hat Linux, Ubuntu, CentOS, etc.

<b>3. Define what is meant by the term 'computer program' List any five features of a Java Program?</b>

A computer program is a collection of instructions [1] that performs a specific task when executed by a computer. A computer requires programs to function, and typically executes the program's instructions in a central processing unit. Some features include Object Oriented, Platform Independent, Robust, Interpreted, Multi-threaded

<b>4. What is the Java Virtual Machine. Define JRE i.e. Java Runtime Environmen?</b>

When Java is compiled, it is not compiled into platform specific machine, rather into platform independent byte code. This byte code is distributed over the web and interpreted by virtual Machine (JVM) on whichever platform it is being run. Java Runtime Environment is an implementation of the Java Virtual Machine which executes Java programs. It provides the minimum requirements for executing a Java application.

<b>5. Define what is meant by the term 'software design'</b>

Software design is the process of defining software methods, functions, objects, and the overall structure and interaction of your code so that the resulting functionality will satisfy your users requirements.

<b>6. State the purpose of a program algorithm</b>

<b>7. Differentiate between the syntax and semantics of an object programming language.</b>

Syntax is the required grammar and punctuation of the language ie, Compile-time errors are syntax errors. Semantics is all about meaning, what the statements do, what the programs do i.e., Logic errors are semantic errors

<b>8. Distinguish between user generated source code and object/machine code. What is the extension name of a Java source code file?</b>

Source Code is the High Level Language that you have written or written by the programmer. The program that is submitted to the Compiler. The source code is often transformed by a compiler program into low-level machine code understood by the computer. The machine code might then be stored for execution at a later time. The extension is .java

<b>9. Define what is meant by the term 'object oriented programming'. What is the difference between object oriented programming language and object based programming?</b>

Object-oriented programming (OOP) is a programming language model organized around objects rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, processes it, and produces output data. Object based programming languages follow all the features of OOPs except Inheritance. JavaScript is an example of object based programming languages.

<b>10. Explain the rationale behind object design.</b>

Object is a runtime entity and its state is stored in fields and behaviour is shown via methods. Methods operate on an object's internal state and serve as the primary mechanism for object-to-object communication.

<b>11. Define a class as a blueprint for an object</b>

A class is a blue print from which individual objects are created. A class can contain fields and methods to describe the behaviour of an object.

<b>12. State the purpose of class libraries and packages</b>

Packages are used in Java in-order to prevent naming conflicts, to control access, to make searching/locating and usage of classes, interfaces, enumerations and annotations, etc., easier. A class declared as private cannot be accessed outside it's package.

<b>13. Which method can be defined only once in a program? What is the return type of a method that does not returns any value? What's the difference between constructors and other methods?</b>

main () method can be defined only once in a program. Program execution begins from the main () method by javas run time system. Void. Return type of a method must be made void if it is not returning any value. Constructors must have the same name as the class and cannot return a value. They are only called once while regular methods could be called many times.

<b>14. Where import statement is used in a Java program? Is there any need to import java Lang package?</b>

Import statement is allowed at the beginning of the program file after package statement. No, there is no need to import this package. It is by default loaded internally by the JVM.

<b>15. What is dot operator? List the three steps for creating an Object for a class</b>

The dot operator(.) is used to access the instance variables and methods of class objects. It is also used to access classes and sub-packages from a package. An Object is first declared, then instantiated and then it is initialized.

<b>16. What kind of variables a class can consist of? Describe these.</b>

A class consist of Local variable, instance variables and class variables. Variables defined inside methods, constructors or blocks are called local variables. The variable will be declared and initialized within the method and it will be destroyed when the method has completed. Instance variables are variables within a class but outside any method. These variables are instantiated when the class is loaded. Class variables are declared with in a class, outside any method, with the static keyword.

<b>17. What is a Constructor? Explain the usage of this () with constructors? What is the purpose of default constructor?</b>

Constructor gets invoked when a new object is created. Every class has a constructor. If we do not explicitly write a constructor for a class, the java compiler builds a default constructor for that class. It is used with variables or methods and used to call constructor of same class. The Java compiler creates a default constructor only if there is no constructor in the class.

<b>18. Define Inheritance? When super keyword is used?</b>

It is the process where one object acquires the properties of another. With the use of inheritance, the information is made manageable in a hierarchical order. If the method overrides one of its superclass's methods, overridden method can be invoked through the use of the keyword super. It can be also used to refer to a hidden field.

<b>19. What is Abstraction?</b>

It refers to the ability to make a class abstract in OOP. It helps to reduce the complexity and also improves the maintainability of the system.

<b>20. What is Encapsulation? What is the primary benefit of Encapsulation? If a variable is declared as private, where may the variable be accessed?</b>

It is the technique of making the fields in a class private and providing access to the fields via public methods. If a field is declared private, it cannot be accessed by anyone outside the class, thereby hiding the fields within the class. Therefore, encapsulation is also referred to as data hiding. The main benefit of encapsulation is the ability to modify our implemented code without breaking the code of others who use our code. With this Encapsulation gives maintainability, flexibility and extensibility to our code. A private variable may only be accessed within the class in which it is declared.

<b>21. Give two differences between the C programming language and Java.</b>

Java is Object Oriented while C is procedural (Procedural is a list of instructions telling the computer what to do step by step) Java is a High level Language while C is low level.

Java supports method overloading while C does not. No exception handling in C. Java supports method overloading, C does not.

<b>22. What is meant by Low Level programming and High Level programming</b>

A Low Level language is one where commands or functions in the language map closely to processor instructions.
A High Level language uses natural language elements and can be easier to use, e.g. Java.

<b>23. Explain the difference between local and global variables</b>

A local variable can only be used within the method it is declared.
A global method can be used in all methods.

<b>24. Explain the term method overloading</b>

Method overloading is when there is more than 1 method with the same name but with different signatures
e.g. Add(6,7); Add(6,7,8);

<b>25. Give two advantages of using methods in programming</b>

Saves re-writing code. Makes programming it easier. 
(divide and conquer approach)


		
				
</html>
