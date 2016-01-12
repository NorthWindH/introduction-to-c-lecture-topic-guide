# Input

**Lecture Time: 90 Minutes**

* Buffered input
* Unformatted input with `int getchar()`
* After user enters something, buffer will have `\n` as the last character
* Clearing the buffer
* Pausing execution
    * When buffer is clear, loop `getchar()` until `\n` is returned
* Formatted input with scanf
* Objects in the format string
    * `% * width size conversion_character`
        * `*`
            * suppress storage of converted data
        * width
            * max number of characters to accept (applies for strings only, covered later)
        * size
            * byte size modifier, see printf chart
        * Basic conversion characters
            * c, d, f
    * Whitespace
        * Accepts and discards as much whitespace as possible in input buffer
    * All conversion characters **except c** discard leading whitespace
    * Plain characters must be matched exactly or scanf stops converting at the first mismatch
* Return value indicates how many variables were successfully filled
* **Give example of advanced scanf being used**
* Return value usage in validation
    * **Give example that accounts for exact sql date format input**
        * Requires 3 ints filled
        * Requires separation by hyphens
        * Requires no trailing characters
