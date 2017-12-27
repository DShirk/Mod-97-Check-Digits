# Mod-97-Check-Digits
HMDA ULI Mod 97 Check Digits Generator and Validator

This code generates and validates Mod 97 check digits for Home Mortgage Disclosure Act (HMDA) Universal Loan Identifiers (ULIs).

This code is not production ready. It is simple Mod 97 check digit generator and validator for long numbers that exceed MS Excel capacity. The code coverts alpha characters to numbers from 10-35 (case insensitive - A and a each are 10, B and b are 11, etc.) and then appends check digits which are derived from subtracting from 98 the remainder of the numeric conversion multiplied by 100 and divided by 97. A loop is used to address the large math.
