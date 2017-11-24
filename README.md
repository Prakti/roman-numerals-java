## Roman Numerals Kata

The Romans wrote their numbers using letters; specifically the letters 'I'
meaning '1', 'V' meaning '5', 'X' meaning '10', 'L' meaning '50', 'C' meaning
'100', 'D' meaning '500', and 'M' meaning '1000'. There were certain rules
that the numerals followed which should be observed.

The symbols 'I', 'X', 'C', and 'M' can be repeated at most 3 times in a row.
The symbols 'V', 'L', and 'D' can never be repeated. The '1' symbols ('I',
'X', and 'C') can only be subtracted from the 2 next highest values
('IV' and 'IX', 'XL' and 'XC', 'CD' and 'CM'). Only one subtraction can be
made per numeral ('XC' is allowed, 'XXC' is not). The '5' symbols ('V', 'L',
and 'D') can never be subtracted.

# Feature 1 - Converting Arabic to Roman
Convert from an Integer in the range \[1, ..., 3999\] into a String, representing
a Roman numeral.

# Feature 2 - Convertig Roman to Arabic
Convert from a String representing Roman numeral (i.e.: in the range
\[I, ..., MMMCMXCIX\]) into the corresponding Integer value.

# Suggested Approach

* Baby-step your way to an algorithm using TDD:
  * Write a failing test and commit it.
  * Implement such that the test is green and commit the solution.
  * Refactor solution as desired as not to break the test
  * Write next failing test case to implement against and commit.

# Coding Dojo Format

* Navigator + Driver approach (5 minute timebox)
* Navigator becomes Driver after Driver performs a `git reset`
* New Navigator is chosen
* Last 5 minute timebox is retrospective

