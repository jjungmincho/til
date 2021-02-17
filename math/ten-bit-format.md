# 10 bit format:

- 1 bit = sign bit, 1 for - and 0 for +
- 4 bits = exponent in excess 7
- 5 bits = mantissa
- Hidden bit = 1
- Special Case:
    1. Exponent = all zeros and mantissa =/ 00000 then the number is denormalized form (hidden bit = 0) and the exponent is assumed to be -6
    2. Exponent = all zeros and mantissa = all zeros then the number is zero (+ or -)
    3. Exponent = all 1's and mantissa = all zeros then the number is +-∞
    4. Exponent = all 1's and mantissa =/ all zeros then the number is NaN (not a number)