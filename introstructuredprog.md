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
   ```
 Examples of Functional programming paradigm:

JavaScript : developed by Brendan Eich
Haskwell : developed by Lennart Augustsson, Dave Barton
Scala : developed by Martin Odersky
Erlang : developed by Joe Armstrong, Robert Virding
Lisp : developed by John Mccarthy
ML : developed by Robin Milner
Clojure : developed by Rich Hickey 
  ```

 
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
             State varchar(200)
         );         ```

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
 ``` C
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



## Prgramming Languages 

A _Prgramming Language_ is a vocabulary and set of grammatical rules for 
instructing a computer or computer device to perfom specific tasks. the term
ussually refers to hihg-level languages such as BASIC, C, C++, COBOL, FORTRAN,
Ada and pascal 

Eah programming language has a unique set of keywords (words that it 
understands) and a especial syntax for organizing program instructions.
[webopedia](https://www.webopedia.com/TERM/P/programming_language.html)



[digitalfellows](https://digitalfellows.commons.gc.cuny.edu/2018/03/12/an-introduction-to-programming-paradigms/)
Introduction of Programming Paradigms[geeksforgeeks](https://www.geeksforgeeks.org/introduction-of-programming-paradigms/)
[Template based](https://www.codeproject.com/Articles/2015/Template-based-programming).
[Paradigms program](https://medium.com/@jingchenjc2019/a-brief-survey-of-programming-paradigms-207543a84e2b)
[Compiled versusinterpreted languages](https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/)

