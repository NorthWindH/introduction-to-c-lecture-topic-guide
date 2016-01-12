# Functions

**Lecture Time: 55 Minutes**

* Function
    * What is it? What does it represent
    * Function syntax:
        * Signature
            * Return type (including void)
            * Function name
            * Parameters (including no params)
        * Prototype (declaration)
        * Function body (definition)
* Special functions
    * main
* Included functions
    * How #include works
    * printf
    * scanf
* Function calling
    * Argument passing by value
    * Implicit argument casting
* Documentation
* **Give example of writing a program that uses functions to print and collect data**
    * Collection function should retrieve an integer and validate for min and max given min and max, also receive third param indicating whether min is used, max is used, or both used (1, 2, 3)
    * Date collection function should make use of collection function to ask for 3 components (day, month, year)
        * Should return compound integer where year is x10000, month is x100, and day is x1
    * Printing function should print a date in sql format given a compound date integer
    * Program should have menu and allow user to loop until they quit
        * Can input date A and/or date B, ask for each component of each date individually
            * Upon entry of a full date, print the date in sql format
        * Can compare dates: can get earlier date or later date
            * Result date is printed in SQL format
    * [Finished Example](date.c)
    * [Incomplete Example](date_incomplete.c)
