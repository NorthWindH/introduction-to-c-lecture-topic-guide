# Control Structures in C

**Lecture Time: 20 Minutes**

* If
    * Enters if code block if condition evaluates to true
    * else if
        * Enters code block if condition is true and all previous conditions evaluated to false
    * else
        * Enters code block if all previous conditions evaluated to false
    * Use for flags or for evaluating user input against known conditions or for evaluating "complex" conditions such as range conditions
    * **Write super simple calculator, accepts first value, type of operation (as int, for simplicity) (+, -), second value**
    * **Write nested if, accepting first value from user as flag then second value from user as processing input then use nested ifs to decide what to do with input**
* Switch
    * Jumps to case with value that equals evaluated statement
    * If no matching case, jumps to default if given or exits switch otherwise
    * Remember to use break, otherwise control leaks to next statement
    * Use when given enumerated options
    * **Update above calculator to use a switch statement**
