# Style

**Lecture Time: 15 Minutes**

* Identifiers
    * Should be self descriptive
    * Prefer shorter names
    * Use rules of english:
        * Nouns describe objects
        * Verbs describe actions
        * Prefer nouns for variables
    * Use short variable names, abbreviate if possible
    * Do not add variable type into the variable name directly
    * Avoid cryptic identifiers
    * eg:
        * iterCount -> iteration count
        * numPizza or numPizzas-> number of pizzas
        * i -> first loop counter
        * j -> second loop counter
        * k -> third loop counter
* Layout
    * Indentation
    * Braces
* Spaces
    * Space after punctuation (eg comma, for-loop semicolon)
    * Space after keyword and before first paren (eg for (...) )
    * No space after function call and before first paren (eg printf(...) )
* Magic numbers should be #defined
* Comments
    * Comments should be added *where they matter*
    * Comment line directly above block they reference, indented at same level
    * Comment block above function definition or prototype describing what the function does, what each parameter is, return type, etc...
    * Header comment block
        * the title of the program
        * the source file name
        * the name of the author(s)
        * eg:
<pre>
    /* Payroll Deductions
     * payroll.c
     * Jane Doe
     */
</pre>
