# Card Verification Using Luhn Algorithm

This repository contains a Python program to validate credit card numbers using the Luhn algorithm.

## Description
The program verifies the validity of a credit card number by:
- Reversing the card number.
- Summing odd-positioned digits directly.
- Doubling even-positioned digits and summing the resulting digits.
- Checking if the total modulo 10 equals 0.

If the card number is valid, the program prints `VALID!`; otherwise, it prints `INVALID!`.

## Example Output
### Input:
```
4111-1111-4555-111
```
### Output:
```
INVALID!
```

## Acknowledgments
- This project is inspired by the Scientific Python Certification course from [FreeCodeCamp](https://www.freecodecamp.org/).

