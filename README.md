# Various Loops in Perl language

Looping in programming languages is a feature which facilitates the execution of a set of instructions or functions repeatedly while some condition evaluates to true. Loops make the programmers task simpler. Perl provides the different types of loop to handle the condition based situation in the program. The loops in Perl are :

for loop
foreach loop
while loop
do…. while loop
until loop
Nested loops

for Loop

“for” loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.

Syntax:

for (init statement; condition; increment/decrement ) 
{
    # Code to be Executed
}

foreach Loop

A foreach loop is used to iterate over a list and the variable holds the value of the elements of the list one at a time. It is majorly used when we have a set of data in a list and we want to iterate over the elements of the list instead of iterating over its range. The process of iteration of each element is done automatically by the loop.

Syntax:

foreach variable 
{
    # Code to be Executed
}

do…. while loop

A do..while loop is almost same as a while loop. The only difference is that do..while loop runs at least one time. The condition is checked after the first execution. A do..while loop is used when we want the loop to run at least one time. It is also known as exit controlled loop as the condition is checked after executing the loop.

Syntax:

do {
statments to be Executed
} while(condition);

until loop

until loop is the opposite of while loop. It takes a condition in the parenthesis and it only runs until the condition is false. Basically, it repeats an instruction or set of instruction until the condition is FALSE. It is also entry controller loop i.e. first the condition is checked then set of instructions inside a block is executed.

Syntax:

until (condition) 
{ # Statements to be executed
}

Nested Loops

A nested loop is a loop inside a loop. Nested loops are also supported by Perl Programming. And all above-discussed loops can be nested.

Syntax for different nested loops in Perl:

Nested for loop
for (init statement; condition; increment/decrement ) 
{
    for (init statement; condition; increment/decrement ) 
    {
         # Code to be Executed
    }
}
Nested foreach loop
foreach variable_1 (@array_1) {

   foreach variable_2 (@array_2) 
   {

   # Code to be Executed
   } 
}
Nested while loop
while (condition)
{
    while (condition)
    {
        #Code to be Executed
    }
}
Nested do..while loop
do{
    do{   #Code to be Executed
    
   }while(condition);

}while(condition);
Nested until loop
until (condition) {

   until (condition) 
    {  #Code to be Executed
    }
}
