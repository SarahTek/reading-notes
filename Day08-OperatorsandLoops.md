# Operators and Loops

**Loops are the abily to repeat an action to a set number of times.**

**While Loops**
**do while loops** 
**for loops**

 ## while loops 

A **While Loop** is used to repeat a specific block of code an unknown number of times, until a condition is met. we giving unlimited number of attempt.

for example:

let number = '';
While(number <5){
    console.log(number);
number = number +1;
}
it will execute those numbers 1 2 3 4

## do while loops

A **do...while** loop is similar to a while loop, except that a do...while loop is guaranteed to execute at least one time.
example 

let answer = '';
do{
    answer = prompt('guess a number from 1 - 10?')

if (answer() === '5'){
    console.log('good job');
}
}while(answer() === '5')

 ## for loops 

  * It tells us to do something for a specific number of times. there is a specific number of attempts we need to make to get the right answer.
  we are only dealing with just numberic value(-in - +in)


for (let i = 0; i < 10; i++){

console.log(i);

} 

## experssions and operators

**Assignment Operators**

+ An assignment operator assigns a value to its left operand based on the value of its right operand.

**comparison operators**

+ A comparison operator compares its operands and returns a logical value based on whether the comparison is true

>>Equal(==) means true if the operand are equal.

>>Not equa (!==) means true if the operand are not equal.

>>Strict equal(===) means true if the operands are equal and of the same type.


### Local variables and Global Variables

The main difference between Global and local variables is that global variables can be accessed globally in the entire program, whereas local variables can be accessed only within the function or block in which they are defined.