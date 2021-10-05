# Quick Start

```
// this is a comment
// comments start with 2 slashes
// comments are ignored

// whitespace is also ignored

// only one command per line.
// commands look like this:

set(a, 1)     // store 1 in variable a
set(b, 2)     // store 2 in variable b
add(a, b)     // add a and b and store the result in a
print(a)      // prints a to the terminal, which is 3

// you can use commands to control robots
// find the correct robot alias in Variables window

robot1.move(state1) // moves the robot to a specific state
robot1.weld()       // activates the robot's welder

// each type of robot has it's own specific commands
// check out the API docs for more info

// VARIABLES
// store data under names for later use
// so you can easily access them
set(my_age, 25)
set(pi, 3.1415927)
set(is_coding_fun, true)

// we can store 3 types of data:
// integers  - clean whole numbers
// floats    - messy numbers with decimals
// booleans  - true or false

// WAIT
// pause the program until some real world condition is met
// you can wait until some seconds have passed
wait(3)
wait(1.5)
// or you can wait for two states to be equal
wait(sensor1.activated, true)

// LABELS & JUMPS
// Control the flow of your program
// Declare labels, a place where your code can jump to
// call jump commands, to skip ahead or go back to a specific line in your program

// a label is some text with a colon at the end
set(a, 1)
INFINITE_LOOP:
add(a, 1)
print(a)
jump(INFINITE_LOOP)
// we "jump" to right below the label, INIFNITE_LOOP
// the program would be stuck forever and ever (unless you stop it)

// MATH
// does some calculation and stores the result in the first given variable
add(a, b)
sub(a, b)
mult(a, b)
div(a, b)
mod(a, b)
pow(a, b)

// COMPARISON
// compares 2 passed values and stores the resulting boolean in the first variable
eq(a, b)      // is a and b equal?
approx(a, b)  // is a and b close?
neq(a, b)     // is a and b not equal?
lt(a, b)      // is a less than b?
gt(a, b)      // is a greater than b?
lte(a, b)     // is a less than or equal to b?
gte(a,b)      // is a greater than or equal to b?

// LOGICAL
// takes in 2 booleans and returns one boolean
and(a, b)    // is both a and b true?
or(a, b)     // are either a or b true?
not(a)       // what is the opposite of a? (true is the opposite of false)

// POINTERS
// manually access data from memory by setting addresses
set(a, 1)
set(b, 33)

addr(a, b)    // addr gets the memory address of b
peek(val, a)  // peek accesses memory location a
print(val)    // val is 33

// ALLOC
// allocate a block of memory
alloc(a, 10)  // allocates 10 addresses of memory set to 0
              // stores the base address in "a"

// DEBUGGING
// commands that can help you figure out what's wrong with your program
print(a)    // prints the value of a to the terminal
break()     // pauses the running program

```