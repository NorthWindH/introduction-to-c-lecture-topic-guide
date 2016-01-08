# Looping Structures

**Lecture Time: 35 Minutes**

* All loops continue while a condition evaluates to true
* Loop types:
    * Do
        * Enters code block regardless
        * Condition evaluated after loop. If evaluates to false, no further iterations
        * Use in loops that must execute block at least once
        * **Update above calculator example to perform until user chooses to exit (add 3rd menu option)**
    * While
        * Evaluates condition before every iteration including first iteration, if evaluates to false then does not perform iteration
        * **Replicate above calculator example but now use a while loop**
            * Note how a do loop is better for this task
        * Use in loops that must evaluate condition before entering block *and* whose condition does not rely on the number of times the block should be iterated
    * For
        * Syntax: 2 semicolons, 3 statements
            * First executed on reaching loop
            * Second executed before every iteration
            * Third executed at end of each iteration
        * Similar to while, condition evaluated before each iteration
        * Use in situations where a loop must be performed a specific number of times
        * **Replicate and update above calculator example to perform calculation a preset number of times**
            * Initially ask user for number of calculations to perform, then use for loop
