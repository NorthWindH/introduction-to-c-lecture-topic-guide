# Output

**Lecture Time: 20 Minutes**

* Idea of output buffer
* Unformatted output using putchar(int)
* Formatted output with printf
    * `% flags width . precision size conversion_character`
* Basic conversion characters
    * %d, %f, %c
* flags
    * -, 0
* width
    * Integer field width
* precision
    * Integer precision value
    * Number of decimal places to round for float
    * Min number of digits to display for int (pad with 0)
* size
    * Variable byte size modifier
        * Integer
            * none -> int
            * hh -> char
            * h -> short
            * l -> long
            * ll -> long long
        * Float
            * none -> float
            * l -> double
            * L -> long double
