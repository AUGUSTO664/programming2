![upy_logo](/Documentos/upy/progamming2/images/upy_logo)
# Programming 2

TEAM: 

JOSE AUGUSTO  GITBHUB: https://github.com/AUGUSTO664/programming2

ADRIANA .. GITHUB https://github.com/Adriana-ku06

This is the first work for this unit 1. we are going to describe 
programming paradigms and how solve problems using the as a source.

# UNIT 1
 
## Classification of programming paradigms

<h3>Characteristics of the Classification of  Programming Paradigms</h3>

A [programming paradigm](https://digitalfellows.commons.gc.cuny.edu/2018/03/12/an-introduction-to-programming-paradigms/) is a philosophy, style, or general approach to writing code. Most definitions of the term are so broad as to be fairly useless—the term tends to make more sense when discussing specific paradigms. Here, we’ll be comparing three specific paradigms: imperative, functional, and object-oriented.

If you’ve done programming in Python or C, you’ve used imperative programming. Imperative programming defines the solution to a problem as a series of steps—first do this, then do that, then do the next thing, and so on. The computer steps through each line of code, executing it and moving on to the next step. Programs written in the imperative style often resemble recipes—first crack the eggs, then mix in the flour, then add water. Imperative programs often change the state of the program on each line, assigning new variables and referring to or changing old ones. Though intuitive for solving small problems, imperative programs quickly become unmanageable as they become larger.

* Declarative

It is divided as Logic, Functional, Database. In computer science the declarative programming is a style of building programs that expresses logic of computation without talking about its control flow. It often considers programs as theories of some logic.It may simplify writing parallel programs. The focus is on what needs to be done rather how it should be done basically emphasize on what code code is actually doing. It just declare the result we want rather how it has be produced. This is the only difference between imperative (how to do) and declarative (what to do) programming paradigms. Getting into deeper we would see logic, functional and database.

* Functional

 he functional programming paradigms has its roots in mathematics and it is language independent. The key principal of this paradigms is the execution of series of mathematical functions. The central model for the abstraction is the function which are meant for some specific computation and not the data structure. Data are loosely coupled to functions.The function hide their implementation. Function can be replaced with their values without changing the meaning of the program. Some of the languages like perl, javascript mostly uses this paradigm.
  
 Examples of Functional programming paradigm:

JavaScript : developed by Brendan Eich
Haskwell : developed by Lennart Augustsson, Dave Barton
Scala : developed by Martin Odersky
Erlang : developed by Joe Armstrong, Robert Virding
Lisp : developed by John Mccarthy
ML : developed by Robin Milner
Clojure : developed by Rich Hickey 
 

 
* Dataflow

His programming methodology is based on data and its movement. Program statements are defined by data rather than hard-coding a series of steps. A database program is the heart of a business information system and provides file creation, data entry, update, query and reporting functions. There are several programming languages that are developed mostly for database application. For example SQL. It is applied to streams of structured data, for filtering, transforming, aggregating (such as computing statistics), or calling other programs. So it has its own wide application.

       ```
         CREATE DATABASE databaseAddress;
         CREATE TABLE Addr (
             PersonID int,
             LastName varchar(200),
             FirstName varchar(200),
             Address varchar(200),
             City varchar(200),
             State varchar(200)     ```

* Logic
It can be termed as abstract model of computation. It would solve logical problems like puzzles, series etc. In logic programming we have a knowledge base which we know before and along with the question and knowledge base which is given to machine, it produces result. In normal programming languages, such concept of knowledge base is not available but while using the concept of artificial intelligence, machine learning we have some models like Perception model which is using the same mechanism.
In logical programming the main emphasize is on knowledge base and the problem. The execution of the program is very much like proof of 
mathematical statement, e.g., Prolog
sum of two number in prolog:
         predicates
           sumoftwonumber(integer, integer)
         clauses

          ```  sum(0, 0).
            sum(n, r):-
                 n1=n-1,
                 sum(n1, r1),
                 r=r1+n ```
                 
                 



* [Constraint-based](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf).

presents the most declarative paradigm of our taxonomy, in the original sense of declarative: telling the computer what is needed instead of how to calculate it. This paradigm provides a high level of abstraction for solving problems with global conditions. This has been used in the past for combinatorial problems, but it can also be used for many more general applications such as computer-aided
composition. Constraint programming has achieved a high degree of maturity since its origins in the 1970s. It uses sophisticated algorithms to find solutions that satisfy global conditions. This means that it genuinely delivers on its ambitious claims.


* Template-based

As we already know of inheritance, it is a good way of reusing your code. However, Visual C++ provides another way of reusing your code. We can do this through templates. With templates you can make the 'type' parameter. Let me explain.
As we already know of inheritance, it is a good way of reusing your code. However, Visual C++ provides another way of reusing your code. We can do this through templates. With templates you can make the 'type' parameter. Let me explain. When you had this class that shows all processor information. The class is huge, and it uses all integers. What if, in time, the integer wouldn't be able to store the information of the processor (just because it's out of range for the integer). Now you'll need to review all your code and change the integers to longs. Or when you have this class that handles int arrays, and someday you'll need the exact same class, only you want it to handle floats.

in template based programming we would make it look like this, no matter what the brand is.
 ```C
Hide   Copy Code
//what if we want to create a template class 
//which needs to take any valid car

template <typename MyCar>
class CTemplateCar
{
private:
    MyCar theCar;
public:
    CTemplateCar(){}
    virtual ~CTemplateCar(){}
    void SpeedUpWhateverCarWeLike()
    {
        theCar.SpeedUp();
    }
} 
```


* Structured

Structured programming is a kind of imperative programming where control flow is defined by nested loops, conditionals, and subroutines, rather than via gotos. Variables are generally local to blocks (have lexical scope).

 ``` C
result = [];
for i = 0; i < length(people); i++ {
    p = people[i];
    if length(p.name)) > 5 {
        addToList(result, toUpper(p.name));
    }
}
return sort(result);
 ```


* Imperative

* Von Neumann

It is one of the oldest programming paradigm. It features close relation relation to machine architecture. It is based on Von Neumann architecture. It works by changing the program state through assignment statements. It performs step by step task by changing state. The main focus is on how to achieve the goal. The paradigm consist of several statements and after execution of all the result is stored.

* Interpreted (Scripting)

These programming languages are often procedural and may comprise object-oriented language elements, but they fall into their own category as they are normally not full-fledged programming languages with support for development of large systems. For example, they may not have compile-time type checking. Usually, these languages require tiny syntax to get started.

* Object-oriented

based on the concept of “objects”, which can contain data, in the form of fields (often known as attributes), and code, in the form of procedures (often known as methods). An object’s procedures that can access and often modify the data fields of the object with which they are associated.
Object-oriented programming (OOP) refers to a type of computer programming (software design) in which programmers define the data type of a data structure, and also the types of operations (functions) that can be applied to the data structure.

In this way, the data structure becomes an object that includes both data and functions. In addition, programmers can create relationships between one object and another. For example, objects can inherit characteristics from other objects.

The Basic OOP Concepts
If you are new to object-oriented programming languages, you will need to know a few basics before you can get started with code. The following Webopedia definitions will help you better understand object-oriented programming:

Abstraction: The process of picking out (abstracting) common features of objects and procedures.

* Class: A category of objects. The class defines all the common properties of the different objects that belong to it.
* Encapsulation: The process of combining elements to create a new entity. A procedure is a type of encapsulation because it combines a series of computer instructions.
* Information hiding: The process of hiding details of an object or function. Information hiding is a powerful programming technique because it reduces complexity.
* Inheritance: a feature that represents the "is a" relationship between different classes.
* Interface: the languages and codes that the applications use to communicate with each other and with the hardware. 
* Messaging: Message passing is a form of communication used in parallel programming and object-oriented programming.
* Object: a self-contained entity that consists of both data and procedures to manipulate the data.
* Polymorphism: A programming language's ability to process objects differently depending on their data type or class.
* Procedure: a section of a program that performs a specific task.

   ``` java
   abstract class Animal {
	// abstract methods
	abstract void move();
	abstract void eat();
}
	// concrete method
	void label() {
		System.out.println("Animal's data:");
	} ```
 
  

#Methods of the programming paradigms:

* Interpreted Programming
Interpreters run through a program line by line and execute each command. Here, if the author decides he wants to use a different kind of olive oil, he could scratch the old one out and add the new one. Your translator friend can then convey that change to you as it happens.

Interpreted languages were once significantly slower than compiled languages. But, with the development of just-in-time compilation, that gap is shrinking.

Examples of common interpreted languages are PHP, Ruby, Python, and JavaScript.

* Compiled Programming

Compiled languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. They also give the developer more control over hardware aspects, like memory management and CPU usage.

Compiled languages need a “build” step – they need to be manually compiled first. You need to “rebuild” the program every time you need to make a change. In our hummus example, the entire translation is written before it gets to you. If the original author decides that he wants to use a different kind of olive oil, the entire recipe would need to be translated again and resent to you.

Examples of pure compiled languages are C, C++, Erlang, Haskell, Rust, and Go.


![Image of Yaktoc](https://1571b175-a-62cb3a1a-s-sites.googlegroups.com/site/cs4217jan2011team2/programming-paradigms/Programming%20Paradigms.PNG?attachauth=ANoY7cr00QAE79H5ixHlh1KAE8HoQmnBXr1ZX39pmkvEgAYkH6SdHB8NgqzqqWRYT2H4iEQ5DZg521oBlstosOgRrK51dPIDYK5pz3kAq-uF2vHqqu4A8DDYCNz_d8LksoqNo8C1MWa_ZzxOwfbhw3fGU1IzyQ1GvpGsmqZXfglgM78yGXCCzLkvDq_V3k3bmTZRZaEUfjBoFlfJUIxJ7hEz9sfMlAXeV-bWZSa9f2FJRDaCBKc8z8o4MjdxpiZUcCF8NuFz_nUest2fYbNy-adeEf2MWO_6zQ%3D%3D&attredirects=0)



## DATA REPRESENTATION AND DATA OPERATORS

A _Programming Language_ is a vocabulary and set of grammatical rules for 
instructing a computer or computer device to perfom specific tasks. the term
ussually refers to hihg-level languages such as BASIC, C, C++, COBOL, FORTRAN,
Ada and pascal 

### IDENTIFIERS

are name for entitites for example in C such as variables, arrays, functions, structures, 
unions and labels An identifier can be composed only of uppercase, lowercase letters, underscore and digits, but should start only with an alphabet or an underscore. If the identifier is not used in an external link process, then it is called as internal. Example: Local variable. If the identifier is used in an external link process, then it is called as external. Example: Global variable

An identifier is a string of alphanumeric characters that begins with an alphabetic character or an underscore character that are used to represent various programming elements such as variables, functions, arrays, structures, unions and so on. Actually, an identifier is a user-defined word. There are 53 characters, to represent identifiers. They are 52 alphabetic characters (i.e., both uppercase and lowercase alphabets) and the underscore character. The underscore character is considered as a letter in identifiers. The underscore character is usually used in the middle of an identifier. There are 63 alphanumeric characters, i.e., 53 alphabetic characters and 10 digits (i.e., 0-9).

Rules for constructing identifiers

1.     The first character in an identifier must be an alphabet or an underscore and can be followed only by any number alphabets, or digits or underscores.
2.     They must not begin with a digit.
3.     Uppercase and lowercase letters are distinct. That is, identifiers are case sensitive.
4.     Commas or blank spaces are not allowed within an identifier.
5.     Keywords cannot be used as an identifier.
6.     Identifiers should not be of length more than 31 characters.
7.     Identifiers must be meaningful, short, quickly and easily typed and easily read.

kinds of identifiers
       
C defines two kinds of identifiers:

    Internal
    External
Internal identifier   If the identifier is used in an external link process, then it is called as external. These identifiers are also known as external names; include function names and global variable names that are shared between source files. It has at least 63 significant characters.

External identifier  If the identifier is not used in an external link process, then it is called as internal. These identifiers are also known as internal names; includes the names of local variables. It has at least 31 significant characters.

### VARIABLES

The most simple form of storage is called a variable. It's an area of memory that stores one item of data, such as a number or a character. They have two purposes - the programmer is able to choose the names of the variables, making programming easier, and also, you can write programs or functions that will work with any values. If you're familiar with spreadsheets already, you can think of variables as being like the cells, which you can then use in formulae regardless of the values they contain. All procedural programming languages, such as C, BASIC and Pascal, have variables, although they may support different types and let you manipulate them in different ways.

Some languages are strongly typed (see below), whereas others aren't typed at all. Some require that you declare a variable before you use it, and others let you go straight in and define a variable's value without declaring it first.

Declaring a variable gives the variable a name, and, in most programming languages, gives it a type - in effect it creates the container that stores your value. See the Type section for examples of declarations.

When you define a variable, you are simply giving it a value.

### CONSTANTS

most programming languages also support the use of constants - these are used in the same way as variables, but their values can't be changed once the program is running. They are useful because you can refer to mathematic values by name, rather than having to remember them, or you can personalise many parts of your programming by setting a constant to the name of the user at the start of the program. Programming languages may also include many constants of their own, which are predefined. In Visual BASIC, for example, these include values such as pi, true and false, and also the arguments used for certain functions, such as msgbox() types (e.g. vbYesNo), which are actually just integers.

With compiled languages, the compiler often works by replacing the names of the constants with their actual value (like Find and Replace in a text editor or word processor) before compiling the code, thereby reducing the amount of memory required for storage and making the code more efficient.

### Reserved Word 
 reserved words are terms or phrases appropriated for special use that may not be utilized in the creation of variable names. For example, "print" is a reserved word because it is a function in many languages to show text on the screen.
 
### TYPE OF DATA

  Primitive Data Structures are the basic data structures that directly operate upon the machine instructions.
hey have different representations on different computers.
Integers, Floating point numbers, Character constants, String constants and Pointers come under this category.
Non-primitive Data Structures

Non-primitive data structures are more complicated data structures and are derived from primitive data structures.
They emphasize on grouping same or different data items with relationship between each data item.
Arrays, Lists and Files come under this category.

### MEMORY SPACE FOR EACH DATA TYPE AND RANGE OF VALUES

### DATA TYPE CONVERSION 

Changing a data type of a value is refered to as "type conversion".
There are two ways to do this:

1. Impliclit - the change is implied
2. Explicit  - the change is explicity done with an operator or function.

The value being changed may be:
1. Promotion - going from a smaller domain to a larger domain 
2. Demotion  - going from a larger domain to a smaller domain

Implicit type conversion 

Automatic conversion of a value from one data type to another by a programming
language, without the programmer specifically doing so, is called implicit
type conversion. It happens whenever a binary operator has two operands of 
different data types. Depending on the operator, one of the operands is going 
to be converted to the data type of the other. It could be promoted or demoted
depending on the operator.

  Implicit Promotion     55 + 1.75
In this example, the integer value 55 is converted to a floating-point value
(most likely double) of 55.0 it was promoted 

  Implicit Demotion  
In programming languages that have explicit integer data types (C++, C#, Java)
care must be taken to avoid implicit demotion. For example:

int money;
money = 23.15;
In this example, the variable money is an integer. We are trying to move a 
floating-point value usually gets truncated to 23.

## Identify The operators of structured programming language.
operators are the foundation of any programming language. thus the 
functionally of C/C++ programming language is incomplete without the use of
operators. We can define operators as symbols that help us to perform specific
mathematical and logic computations on operands. In other words, we can say 
that an operand operates the operands.

### Conditional operators or Ternary operators in C
Conditional operators return one value if condition is true and returns 
another if the condition is false. This operator is also as ternary operator

  syntax : (condition?true_value:false_value);
  example : (A > 100 ? 0 : 1);
In above example, If A is greater than 100, 0 is returned else 1 is returned.
this is equal to if else conditional statements 

  ``` C
  #include <stdio.h>

  int main()
  {
    int x = 1, y;
    y = (x == 1 ? 2 : 0 );
    printf("x value is %d\n", x);
    printf("y value is %d\n", y);
  }

  ```
   Output 
  ******************
  *  X value is 1  *
  *  Y value is 2  *
  ******************

### Logical Operators
A logical operator is a symbol or word used to connect two or more expressions such 
that the value of the compound expression produced depends only on that of the 
original expressions and on the meaning of the operator. 
Common logical operators include AND, OR and NOT.

Within most languages, expressions that yield Boolean data type values are divided 
into two groups. One group uses the relational operator within their expressions and
the other group uses logical operators within their expressions. 

The logical operators are often used to help create a test expression that controls 
program flow. This type of expression is also known as a Boolean expression because
they create a Boolean answer or value when evaluated.

 |Language | AND  | OR  | NOT |
 |.........|......|.....|.....|
 |C++      | &&   | ||  |  !  |
 |C#       | &&   | ||  |  !  |
 |Java     | &&   | ||  |  !  |
 |Python   | and  | or  | not |

 For Example 
In most languages there are strict rules for forming proper logical expressions.
 6 > 4 && 2 <= 14
 6 > 4 and 2 <=14
This expression has two relational operators and one logical operator. Using the 
precedence of operator rules the two "relational comparison" operators will be donde
before the "logical and" operator 
  true && true
  true and true

The final evaluation of the expression is: true.
We can say this in English as: It is true that six is greater than four and two is 
less than  or equal to fourteen.

### Relational Operators 

A relational operator is a programming language construct or operator that tests or 
defines some kind of relation between two entities. These include numerical equality 
and inequalities.

The relational operators are often used to create a test expression that controls 
program flow. This type of expression is also known as Boolean expression because
they create a Boolean answer or value when evaluated. There are six common relational
operators that give a Boolean value by comparing (showing the relationship) between
two operands. If the operands are different data types, implicit promotion occurs 
to convert the operands to the same data type.

Operator symbols and/or names can vary with different programming languages. Most 
programming languages use relational operators similar to the following: 

  |Operator  | Meaning             |
  |:********:|:*******************:|
  |  <       | less   than         |
  |  >       |greater than         |
  |  <=      |less than or equal to|
  |  >=      |greater than or equal|
  | ==       |  equal to           |
  |!= or <>  | not equal to        |



 programming language has a unique set of keywords (words that it 
understands) and a especial syntax for organizing program instructions.
[webopedia](https://www.webopedia.com/TERM/P/programming_language.html)


### Version Control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. For the examples in this book, you will use software source code as the files being version controlled, though in reality you can do this with nearly any type of file on a computer.

If you are a graphic or web designer and want to keep every version of an image or layout (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use. It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead.

* Local Version Control Systems
Many people’s version-control method of choice is to copy files into another directory (perhaps a time-stamped directory, if they’re clever). This approach is very common because it is so simple, but it is also incredibly error prone. It is easy to forget which directory you’re in and accidentally write to the wrong file or copy over files you don’t mean to.

To deal with this issue, programmers long ago developed local VCSs that had a simple database that kept all the changes to files under revision control.
![Image of Yaktocat](https://git-scm.com/book/en/v2/images/local.png)

One of the most popular VCS tools was a system called RCS, which is still distributed with many computers today. RCS works by keeping patch sets (that is, the differences between files) in a special format on disk; it can then re-create what any file looked like at any point in time by adding up all the patches.

* Centralized Version Control Systems

The next major issue that people encounter is that they need to collaborate with developers on other systems. To deal with this problem, Centralized Version Control Systems (CVCSs) were developed. These systems (such as CVS, Subversion, and Perforce) have a single server that contains all the versioned files, and a number of clients that check out files from that central place. For many years, this has been the standard for version control.


* Distributed Version Control Systems

This is where Distributed Version Control Systems (DVCSs) step in. In a DVCS (such as Git, Mercurial, Bazaar or Darcs), clients don’t just check out the latest snapshot of the files; rather, they fully mirror the repository, including its full history. Thus, if any server dies, and these systems were collaborating via that server, any of the client repositories can be copied back up to the server to restore it. Every clone is really a full backup of all the data.


References 
* [digitalfellows](https://digitalfellows.commons.gc.cuny.edu/2018/03/12/an-introduction-to-programming-paradigms/)
* Introduction of Programming Paradigms[geeksforgeeks](https://www.geeksforgeeks.org/introduction-of-programming-paradigms/)
* [Template based](https://www.codeproject.com/Articles/2015/Template-based-programming).
* [Paradigms program](https://medium.com/@jingchenjc2019/a-brief-survey-of-programming-paradigms-207543a84e2b)
* [Compiled versusinterpreted languages](https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/)
* [Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
* [identifiers](http://aboutc.weebly.com/identifiers.html)
* [variables and data structure](https://www.advanced-ict.info/programming/variables.html)
* [data types](https://www.tutorialspoint.com/cprogramming/c_data_types.htm)
* [data type conversion](https://press.rebus.community/programmingfundamentals/chapter/data-type-conversions/)
* [Conditional operators](https://fresh2refresh.com/c-programming/c-operators-expressions/c-conditional-operators/)
* [logical operator](https://press.rebus.community/programmingfundamentals/chapter/logical-operators/)
* [relational operatos](https://press.rebus.community/programmingfundamentals/chapter/relational-operators/)
