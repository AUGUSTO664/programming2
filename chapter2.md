# CHAPTER TWO 
# SELECTIVE CONTROL STRUCTURES AND ITERATIVE CONTROL STRUCTURES 

this text is to describe the concepts and characteristics of selective control
structures  and iterative control structures in algorithm coding. 

lets start 

## Decision and control statements 

>_Once a decision was made, I did not worry about it afterward_

   -Harry Truman  

Calculations and expressions are only a small part of computer programming. 
Decision and control statements are needed. they specify the order in which 
statements are to be executed.

So far, we have constructed linear programs, that is, programs that execute 
in a straight line, one statement after another. In this chapter, we weill see
how to change the control flow of a program with branching staments.

### if Stament 

the _if_ statement allow us to put some decision-making into our programs. the
general form of the if statement is: 

   if(condition)     *if(condition) statement
       statement      for one line statement 

if the condition is true (nonzero) the statement will be executed. if the 
condition is false(0), the stament will not be executed, For example, suposse 
we are writting a billing program. At the end, if the customer owes us nothing
or has a credit (owes us a negative amount), we want to print a message.

```C
 if(total_owed <= 0)
   printf("You owe nothing.\n");
```

The operator <= is a relational operator that represents less than or equal to
this statement reads "if the total owd is less than or equal to zero. print
the message. the relational operators and logic operators are used here. 
So we can compare in diferent ways de numbers. 

For multiple statements may be grouped by putting them inside curly braces 
({}). For example:

  ```C
     if(total_owed <= 0){
      ++zero_ount;
      printf("You owe nothing.\n");
     }
  ```

For readability, the statements enclosed in {} are usually indented. This 
allows the programmer to quickly tell which statements are to be 
conditionally executed.

### eslse Statement 

An alternate form of the if statement is:

   if(dontion)
      statement;
   else 
      statement;
   
  is the condition is true (nonzero), the first statement is executed. If it 
is false (0), the second statement executed. In our accounting example, we 
wrote out a message only if nothing was owed. in real life. we probably would
want to tell the customer how much is owed if there is a balance due: 

 ``` C
     if (total_owed <= 0) printf("You owe nothing.\n");

     else
       printf("You owe %d dollars\n", total_owed);
 ```
### if-else Stament 

 Syntax format for if else statement is shown below.
 if we want to evaluate multiple expression we can do it using the _else-if. 
 the format is shown here:
 we use *if* for evaluate the first expression 
 then we use *else if* to evaluate the next expressions
 if any expression was true we use *else* to perform some action you need.


 if(expression 1) //Expression 1 is evaluated. If true statements are executed
 {                //if it is false control is transferred to the next else if
   statement 1;
   statement 2;
 }                                   
 
 else if(expression 2)  // if expression 1 is false, expression 2 is evaluated
 {
   statement 1;
   statement 2;
 }

 else if(expression 3) //if expression 2 is False, expression 3 is evaluated
 {
   statement 1;
   statement 2;
 }

 else                //if all expressions (1, 2, 3) are False, the statements
 {                   // insude the else are executed.
   statement 1;
   statement 2;
 }

 ### Nested Statement 

A nested if in C is an if statement that is the target of another if 
statement. Nested if statements means an if statement inside another if 
statement C allows us to nested if statements within if statements. 
 syntax

 if(condition 1)
 {
   //Executes when condition1 is true
   if(condition2)
   {
      //executes when condition2 is true
   }
 }

 One conditional can also be nested within another. we could have written 
the three-branch example like this.

``` C
   if(x==y))
     printf("x and y are equal"\n);
   else
   {
     if(x < y)
      printf("x is less than y\n");
     else
       printf("x is greater than y\n");
   }
```

 The outer conditional contains two branches. the first branch contains a
simple stament. the second branch contains another _if_ statement, which has
two branches of its own. those two branches are both simple statements 
although they could have been conditional statements as well.

 although the identation of the statements makes the structure apparent,
nested conditionals become difficult to read very quickly. in general, it is 
a good idea to avoid then when you can.

## Iterative control structures 

 Looping statements allow the program to repeat a section of code any numbers
of times or until some condition occurs. For example, loops are used to count 
the number of words in a document or to count the number of accounts that 
have past-due balances. 

### For loop 

A for loop is a repetition control structure that allows you to efficiently 
write a loop that needs to execute a specific number of times. 

  _Syntax_ 
The syntax of a loop in C programming language is 

 for(init; condition; increment){
    statements;
 } 
 
Here is the flow of control in a "for" loop-

 the init step is executed first, and only once, 

### While Statement 

 The _while_ statement is used when the program needs to perform repetitive 
tasks. The general form of a while statement is: 

  while(condition)
    statement;

 the program will repeatedly execute the statement inside the while until
the condition becomes false (0). (if the condition is initially false, the 
statement will not be executed.) 

















