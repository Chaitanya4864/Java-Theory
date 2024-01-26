# Java-Theory
# Java-Theory
1). WHAT IS JAVA??
SOL---
a.Java is a popular programming language created in 1995.
b.It is owned by Oracle & more than 3 billion devices run Java.
c.Java was created by James Gosling, born in 1955 on May 19.
d. It is mainly used for mobile applications and desktop applications.

USES OF JAVA
a. Java works on different platforms (Windows, Mac, Linux etc). 
b.It is easy to learn and It is open source.
c. Java is a platform because it has its own runtime environment which is JVM (java virtual Machine). JVM provides a platform that accepts the byte code & executes it on the machine.
d. Java is close to C++ & C.
e. Every line of code that runs in Java must be inside a class and the class should always start with upper case.
f.  The name of the Java file must match the class name.

2). WHAT IS OOPs?
SOL----
a.  Object-Oriented Programming System.
b.  Procedural programming is about writing procedures or methods that perform operations on the data, while object-oriented programming is about creating an object that contains both data & methods.

NEED OF OOPS?-------
A. OOP has several advantages over procedural programming.
B. OOP provides a clear structure for the programs.
C. OOP is faster & eaiser to execute.
D. OOP helps to keep the Java code DRY ("Don't repeat yourself") and makes the code easier to maintain modify and debug.
E. OOP makes it possible to create fully reusable applications with less code & shorter development time.

WHY THE NAME JAVA? WHAT IS THE PREVIOUS NAME OF THIS PROGRAMMING LANGUAGE?
A. JAVA stands for Just Another Virtual Accelerator
B.  The language was initially called Oak after an oak tree that stood outside Gosling's office. Later the project went by the name Green and was finally renamed Java, from Java coffee, a type of coffee from Indonesia.

6). WHAT IS TOKEN (IDENTIFIERS, KEYWORDS, DATATYPES, OPERATORS)?

SOL-------
What is the token in Java?

Tokens are the basic building blocks of any code script. These include keywords, operators, constants, or other unique syntactic stuff specific to the language. The JAVA compiler identifies these tokens based on delimiters and converts them into bytecode. These tokens are used in the source code of any program...

In Java, tokens are the basic building blocks of a program. They are the smallest individual units of a program that have meaning to the compiler and are used to represent the various elements of a program, such as keywords, identifiers, operators, and literals.
Here are the different types of Java tokens that can be found:

(i). Keywords:
These are reserved words that have a specific meaning in the Java language. Examples of keywords in Java include class, public, private, if, else, while, for, switch, case, break, continue, return, and static, among others.
In Java, a keyword is a reserved word that has a specific meaning and purpose within the language. Keywords are used to define various constructs, such as control flow statements, data types, access modifiers, and more.
As a token in Java, a keyword is a sequence of characters that are treated as a single unit by the Java compiler. When Java code is compiled, the compiler recognizes keywords as special words with a predefined meaning and function within the language.
Examples of Java keywords include:
public, private, protected: access modifiers used to control access to class members.
class, interface, enum: used to define different types of Java classes.
if, else, switch, while, do, for - : used to define control flow statements.
int, float, boolean, char: used to define data types.
As a programmer, it’s important to be familiar with Java keywords and their usage to write correct and effective Java code.

(ii). Identifiers:
These are names that are used to identify variables, methods, classes, and other elements of a program. An identifier must start with a letter or underscore and can contain letters, digits, and underscores. Identifiers are case-sensitive in Java.
In Java, an identifier is a sequence of characters used to name a variable, method, class, or another program element. Identifiers are used to refer to these program elements throughout the code, allowing programmers to access and manipulate them.
An identifier in Java must follow certain rules:
It can only contain letters, digits, underscores (_), and dollar signs ($).
It must begin with a letter, an underscore (_), or a dollar sign ($).
It cannot be a Java keyword.
Examples of valid identifiers in Java include:
myVariable
_myVariable
$myVariable
MyClass
myMethod
Identifiers are case-sensitive in Java, meaning that myVariable and myvariable are considered two different identifiers.
It’s important to choose meaningful and descriptive names for identifiers to make the code easier to read and understand. Good naming conventions also help make the code more maintainable and easier to modify java tokens in the future.
Operators:
These are symbols or token bus that are used to perform operations on operands, such as arithmetic operations (+, -, *, /, %), logical operations (&&, ||, !), relational operations (==, !=, <, >, <=, >=), and assignment operations (=, +=, -=, *=, /=, %=, etc.).
In Java, an operator is a symbol that represents a specific action or computation that can be performed on one or more operands. Operators are used to manipulate and compare data values in Java programs.
Java operators can be classified into several categories based on their functionality:
Arithmetic Operators: Used to perform arithmetic operations such as addition, subtraction, multiplication, division, and modulo. Examples: +, -, *, /, %.
Relational Operators: Used to compare values and determine the relationship between them. Examples: ==, !=, <, >, <=, >=.
Logical Operators: Used to perform logical operations on boolean values. Examples: && (logical AND), || (logical OR), ! (logical NOT).
Bitwise Operators: Used to perform bitwise operations on binary values. Examples: & (bitwise AND), | (bitwise OR), ^ (bitwise XOR), ~ (bitwise NOT), << (left shift), >> (right shift), >>> (unsigned right shift).
Assignment Operators: Used to assign values to variables. Examples: =, +=, -=.
Separators:
These are symbols that are used to separate different parts of a program, such as commas (,), semicolons (;), parentheses (()), braces ({ }), and brackets ([]).
In Java, separators are characters used to separate or group parts of a Java program. Separators are not operators and do not perform any operations on data values.
Java has several types of separators:
Semicolons (;): Used to separate statements in Java. Every statement in Java must end with a semicolon.
Commas (,): Used to separate multiple arguments or parameters in method calls or definitions or to separate multiple variable declarations.
Parentheses (( and )): Used to group expressions, define method parameters, and control the order of evaluation.
Braces ({ and }): Used to define a block of code, such as a method body or a class definition.
Brackets ([ and ]): Used to define arrays or to access individual elements of an array.
Periods (.): Used to access class members or invoke methods on objects.
Colon (:): Used in switch statements and for-each loops to separate case values or to define iteration variables.
Separators play an important role in structuring and organizing Java code, and using them correctly is crucial for writing correct and readable programs.

(iii). Literals:
These are values that are directly specified in the program, such as integer literals (e.g., 42), floating-point literals (e.g., 3.14), boolean literals (true or false), character literals (e.g., ‘a’), and string literals (e.g., “Hello, world!”).
In Java, a literal is a notation used to represent a fixed value in the source code. Literals are used to represent values of data types such as integers, floating-point numbers, characters, and strings.
Java supports several types of literals:
Integer literals: Used to represent integer values, such as 42 or 0xFF.
Floating-point literals: Used to represent floating-point values, such as 3.14159 or 1.0e-6.
Boolean literals: Used to represent boolean values, such as true or false.
Character literals: Used to represent single characters, enclosed in single quotes, such as ‘a’ or ‘9’.
String literals: Used to represent sequences of characters enclosed in double quotes, such as “Hello, World!”.
Null literal: Used to represent a reference that does not refer to any object, represented by the keyword null.

Literals are used to initialize variables and constants, as well as to specify values in expressions and statements. They are constant values and cannot be changed during the execution of the program.
It’s important to choose the appropriate type of literal to represent a value to avoid data loss or unexpected results in the program.
When a Java program is compiled, the compiler breaks it down into a sequence of token bus, which are then used to generate the executable code.
Originally Source: Tokens In Java.

7). WHAT ARE THE METHODS??

SOL)......
 a). A method in Java is a block of code that when called performance-specific actions mentioned in it. 
 b). For instance if you have written instructions to draw a circle in the method it will do that task.




