# 102 - Day 06

## What I learned today
- There are 2 componentes in making a decision:
  1. Evaluation of a condition
    - In order to make a decision,your code checkes the current status of the script. This is commonly done by comparing two values using a comparison operator which returns a True or False value
  2. Conditional statements: if/then/else
  
- a comparison operator usually contains 2 operands and a comparison operator: `(score >= pass)`
  - `var comparison = (score1 + score2) > (highScore1 + highScore2);` will display a True or False
  
 - and statement `((2 < 4) && (3 >= 2))` 
  - if **both** expressions evaluate to true, then the expression returns true
  - if just **one** of these returns false, then the expression will return false
  - **false** && anything: there is no reason in continuing to determine the result because **both** have to be true
  
 - or statement `((2 < 4) || (3 > 5))`
  - if **either** expression evaluates to true, then the expression returns true
  - **both** have to return false in order to return false.
  - **true** || anything : there is no reason in continuting because **one** expression evaluates to true
  
 - logical not `!(2 < 1)` operator takes a single boolean value and inverts it


### Comparison and logical operators


### for and while loops
- For: if you need to run a specific number of times, use a for-loop (this is the most common loop).
  - utilizes a counter to tell how many times the loop should run
- While: use a while loop if you do not know how many times the code should run.
  - the condition here can be something other than a counter, and the code will continue to loop for as long as the condition is true.
- Do While: same as the while loop, will ALWAYS run what is inside the curly braces at least once

### for loop
- the for loop _condition_ is made up of 3 statements: `for (var i = 0; i < 10; i++)
  1. initialization: acts as a counter `var i = 0`
  2. condition: the loop should continue to run until the counter reaches a specific number `i < 10`
  3. update: every time the loop has run the statements in the curly braces, it adds one to the counter `i++
