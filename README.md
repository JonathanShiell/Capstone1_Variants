# Capstone1_Versions
Versions of Capstone 1, as described in this file. Note that the original specification was taken to imply correct input (as error handling was not specified), this will generally be assumed although some versions may attempt to allow for this.

## Version Descriptions
Versions are allocated descriptive names, rather than numbers, as they are intended to be parallel forks.

`finance_calculators_decimal.py` uses `decimal.Decimal` (as `Decimal`) from the Python Standard Library (built-in but not loaded by default) rather than the `float` type for greater accuracy.
