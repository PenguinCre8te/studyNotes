### Functions

SUM

MIN

MAX

AVERAGE

COUNT: Count numbers **of numbers**

COUNTA: Count numbers **of values**

COUNTBLANK(range): Count blank cells **within range**

SUMIF(range, criteria, [sumRange])

COUNTIF(range, criteria)

IF(test, value if true, [value if false])

AND(logical, logical, ...): TRUE if all TRUE

OR(logical, logical, ...): TRUE if one TRUE

NOT(logical)

RANK(number, ref, order)

- rank of number in ref

- order = 0 or none: Descending, normal rank

- order != 0: Ascending, reversed

**XLOOKUP(value, array, return, [if not found], [<span style="background-color:#b7eb8f">match mode</span>], [<span style="background-color:#ffe58f">search mode</span>])**

- <span style="background-color:#b7eb8f">Match mode</span>

  - 0: Excat

  - -1: Next smaller

  - 1: Next larger

  - 2: regex

- <span style="background-color:#ffe58f">Search mode</span>

  - 1: Start from first

  - -1: Start from last

  - 2: Ascending binary search

  - -2: Descending binary search

LEFT(text, [num])

RIGHT(text, [num])

MID(text, start_num, num_chars): 1 based indexing

FIND(objective, text, [start num])

CONCATENATE(text1, [text2], ...) or text1 & text2 & ...

INT(num): round down

ROUND(num, digi)

SQRT(number)

RAND(): random number between **0-1**

LEN(text)

### Pivot Tables

Filters: Narrow down dataset

Rows: displayed as row headers on the left

Columns: Categories, split values

Values: shown as columns on top

- summarization: SUM, AVERAGE, COUNT/COUNTA, MIN/MAX, PRODUCT, %

Calculated fields

### Pivot charts

- Graphical representation of pivot table

- Insert > pivot chart
