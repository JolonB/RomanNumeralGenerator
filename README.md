# Roman Numeral Generator

This program simply generates the appropriate Roman numeral representation of a given Hindu-Arabic number (i.e. the ones you probably use).

The numbers generated fit the [standard form](https://en.wikipedia.org/wiki/Roman_numerals#Standard_form) of Roman numerals.
There are other forms that could be used, but those get a bit messy.  
The numerals and their equivalent values are shown in the table below.

| Roman | Arabic |
| --- | --- |
| I | 1 |
| V | 5 |
| X | 10 |
| L | 50 |
| C | 100 |
| D | 500 |
| M | 1000 |

Numbers above 1000 can be represented with a bar over top of them.
For example, a `V` with a bar over it represents 5000.

*Some* numbers can be represented with subtractive notation.
This is when the first (smaller) numeral in a pair of numerals is subtracted from the second (larger) one.
This does not apply in every case.
In fact, it only applies for 4 (IV), 9 (IX), 40 (XL), 90 (XC), 400 (CD), and 900 (CM).
In general, you can only use subtractive notation if you are subtracting the next largest numeral that is a power of 10 (i.e. I, X, and C).

Negative numbers and zero do not exist in Roman numerals.

## Implementation


