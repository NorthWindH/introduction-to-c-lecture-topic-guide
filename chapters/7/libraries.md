# Libraries

**Lecture Time: 90 Minutes**

* stdlib
    * integer absolute
        * `abs, labs, llabs`
    * pseudorandomness
        * `rand`
        * `srand`
        * `RAND_MAX`
    * Useful random mods
        * Convert rand to float from 0 to 1
        * Convert rand to integer between a min and a max
* math
    * float abs: `fabs, fabsf, fabsl`
    * floor: `floor, floorf, floorl`
    * ceiling: `ceil, ceilf, ceill`
    * rounding*: `round, roundf, roundl`
        * Note round only exists on some platforms (eg windows)
    * truncate to whole number: `trunc, truncf, truncl`
    * square root: `sqrt, sqrtf, sqrtl`
    * powers: `pow(base, exp), powf, powl`
* time
    * `time_t time(time_t*)`
        * Accurate down to the second
        * Integer values as number of seconds since unix epoch ie january 1st 1970
        * Difference in seconds can be obtained by subtracting values
    * `clock_t clock()`
        * `CLOCKS_PER_SEC`
* ctype
    * Conversion
        * `int tolower(int)`
        * `int toupper(int)`
        * Non-alphabetical characters are not affected
    * Analysis
        * `islower`
        * `isupper`
        * `isalpha`
        * `isdigit`
        * `isspace`
