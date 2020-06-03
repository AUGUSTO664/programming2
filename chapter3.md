# CHAPTER 3  SUBPROGRAMS AND RECURSION 

## SUBPROGRAMS A

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

paramer
