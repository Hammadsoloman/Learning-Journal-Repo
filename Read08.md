# Comparison and logical operators
•	Comparison operators — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.
•	Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.
## COMPARISON OPERATORS
You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.
•	Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
•	Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
•	Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
•	Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
•	Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
•	Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.
## LOGICAL OPERATORS
*Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.
assertions.*
•	&& (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
•	|| (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
var isTrue = ('yellow' === 'green') && (4 >= 4);
In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
•	The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
•	The second expression is true, because the number 4 is greater than or equal to 4.
The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is falsy and evaluates to false.


*Many things may seem confusing to you in the above program at this point of time but do not worry you will be able to understand everything about loops in JavaScript by the end of this tutorial. You can observe that in the above program using loops we have used the document.write statement only once but still, the output of the program will be same as that of the iterative program where we have used the document.write statement 10 times.*
In computer programming, a loop is a sequence of instructions that is repeated until a certain condition is reached.
•	An operation is done, such as getting an item of data and changing it, and then some condition is checked such as whether a counter has reached a prescribed number.
•	Counter not Reached: If the counter has not reached the desired number, the next instruction in the sequence returns to the first instruction in the sequence and repeat it.
•	Counter reached: If the condition has been reached, the next instruction “falls through” to the next sequential instruction or branches outside the loop.

There are mainly two types of loops:
1.	Entry Controlled loops: In this type of loops the test condition is tested before entering the loop body. For Loop and While Loop are entry controlled loops.
2.	Exit Controlled Loops: In this type of loops the test condition is tested or evaluated at the end of loop body. Therefore, the loop body will execute atleast once, irrespective of whether the test condition is true or false. do – while loop is exit controlled loop.
JavaScript mainly provides three ways for executing the loops. While all the ways provide similar basic functionality, they differ in their syntax and condition checking time. Let us learn about each one of these in details.
1.	while loop: A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.

![image]( https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)
•	While loop starts with the checking of condition. If it evaluated to true, then the loop body statements are executed otherwise first statement following the loop is executed. For this reason it is also called Entry control loop
•	Once the condition is evaluated to true, the statements in the loop body are executed. Normally the statements contain an update value for the variable being processed for the next iteration.
•	When the condition becomes false, the loop terminates which marks the end of its life cycle.


for loop: for loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.

## Flowchart:
![image]( https://media.geeksforgeeks.org/wp-content/uploads/loop2.png)
1.	Initialization condition: Here, we initialize the variable in use. It marks the start of a for loop. An already declared variable can be used or a variable can be declared, local to loop only.
2.	Testing Condition: It is used for testing the exit condition for a loop. It must return a boolean value. It is also an Entry Control Loop as the condition is checked prior to the execution of the loop statements.
3.	Statement execution: Once the condition is evaluated to true, the statements in the loop body are executed.
4.	Increment/ Decrement: It is used for updating the variable for next iteration.
5.	Loop termination:When the condition becomes false, the loop terminates marking the end of its life cycle.



I hope u found it useful 


