# CHAPTER 3  SUBPROGRAMS AND RECURSION 

## SUBPROGRAMS 

A subprogram us a sequence of instruccions whose execution is invoked from 
one or more remote locations in a program, with the expectation that when 
the subprogram execution is complete, execution resumes at the instruction 
after the one that invoked the subprogram. In high level languages, 
subprograms are also called subroutines, procedures, and fucntions. In object-
oriented languages, ther are usually called methods or constructors. In most 
modern high-level languages, subprograms can have parameters, local variable
and return values.
### Basic definition 
1. A subprogram definition describes the interface to and the actions of the 
subprogram abstaction. 
2. A subprogram call us the explicit request that the subprogram be executed.
3. A subprogram is active if after having been calling, it has begun execution
but has not yet completed that execution. 
4. A _subprogram header_ which is the first line of the definition, serves 
several purposes. it specifies that the following syntatic unit is a 
subprogram definition. it provides the name for the subprogram and it may 
optionally specify list of parameters. 
5. Parameter profile of a subprogram is the number, order and types of its 
formal parameters. 
6. The protocol of a subprogram is its parameter profile plus, if it is a
function, it return types
 
### PARAMETERS 
Subprograms usually describe computations. There are two ways that a 
subprogram can gain access to the data that is to process: through direct 
access to nonlocal variables or through parameter passing. 
Data passed through parameters are accessed through names that are local to 
the subprogram. Parameter passing is more flexible than direct access to 
nonlocal variables.  The parameters in the subprogram header are called 
_formal parameters_, the subprograms call statements must include the name 
of the subprogram and a list of parameters to be bound to the formal 
parameters of the subprogram. These parameters are called _actual parameters_

the binding of actual parameters to formal parameters is done by simple 
position,   

### LOCAL REFERENCING ENVIRONMENTS

Suprograms are generally allowed to define their own variables, thereby 
defining local referencing environments. Variables that are defined inside 
subprograms are called local variables. because access to them is usually 
restricted to the subprogram in which they are defined. 


### PARAMETER PASSING METHODS

Are the ways in which parameters are transmitted to and/or from 
called programs. Formal parameters are characterized by one of three 
semantics models: 
-They can receive data from the corresponding actual parameter
-They can transmit data to the actual parameter. 

These three semantics models are called _in mode_, _out mode_ and _inout mode_
There are 2 conceptual models of how data transfer take place in parameter 

### PASS BY VALUE 

When a parameter is passed by value, the value of the actual parameter is 
used to initialize the corresponding formal parameter, which then acts as a
local variable in the subprogram. 
-Pass by value is implemented by actual data transfer
-The main disadvantage of pass by value is that if physical moves are done,
the additional storage is required for formal parameterm either in the called
subprogram or in some area outside both, the caller and the called subprogram. 

### PASS BY RESULT
this is an implementation model for out-mode parameters. When a parameter is
passed by result, no value is transmitted to the subprogram. One problem with 
the pass by result is that there can be an actual parameter collision such as 
the one created with the call. 

### PASS BY REFERENCE
 
Pass by reference is a second implementation of in-out mode parameters.
Rather than transmitting data values back and forth, as in pass by value result
the pass by reference method transmits an access path, usually just an address,
to the called subprogram. This provides the access path to the cell storing 
the actual parameter. 

the advantage of pass by reference is efficiency in both time and space. 

### PASS BY NAME

Pass by name is an in-out mode parameter transmission method that does not 
correspond to a single implementation model. When parameters are passed by 
name, the actual parameter is textually substituted for the corresponding 
formal parameter in all its occurrences in the subprogram. 

## RECURSIVE PROCESSES 

_What is Recursion?_ 
Is the process in which a function calls itself directly or indirectly is called
recursion and the corresponding function is called as recurive function. Using
recursive algorithms, certain problems can be solved quite easily.

_What is the base condition in recursion?_ 
In the recursive program, the solution to the base case is provided and the
solution of bigger problem is expressed in terms of smaller problems. 

_How a particular problem is solved using recursion?_
The idea is to represent a problem in terms of one or more smaller problems,
and add one or more base conditions that stop the recursion. For example we 
compute factorial n if we know factorial of (n-1). The base case for factorial 
would be n=0.

### DIRECT AND INDIRECT RECURSION 

A function is called direct recursive if its calls the the same function fun. A
function fun is called indirect recursive if it calls another function say 
fun_new and fun_new calls fun directly or indirectly. D
