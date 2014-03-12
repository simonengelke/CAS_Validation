CAS Validation

The Chemical Abstracts Service (CAS) Registry Number is a useful for the idendification chemicals.
This code in Python uses the Check Digit to validate the number (the validation does not test if the CAS number is already assigned). Feel free to contribute the validation with a database for CAS.

CAS Number Validation following to Wikipedia (http://en.wikipedia.org/wiki/CAS_registry_number):

A CASRN is separated by hyphens into three parts, the first consisting of up to 7 digits, the second consisting of two digits, and the third consisting of a single digit serving as a check digit. The check digit is found by taking the last digit times 1, the previous digit times 2, the previous digit times 3 etc., adding all these up and computing the sum modulo 10. For example, the CAS number of water is 7732-18-5: the checksum 5 is calculated as (8×1 + 1×2 + 2×3 + 3×4 + 7×5 + 7×6) = 105; 105 mod 10 = 5.

The official website for the CAS check digit: http://www.cas.org/content/chemical-substances/checkdig