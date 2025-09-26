# Credit Card Validator (Python)

This project is a **Credit Card Number Validator** implemented in Python using the **Luhn Algorithm**.  
It checks whether a given card number is valid by applying digit-based checksum verification.

---

## How It Works
- Reverses the card number
- Splits digits into odd and even positions
- Doubles every second digit (from the right), adjusting values greater than 9
- Sums all digits
- Validates if the total is divisible by 10

---

## Example
Input:
4211-1111-4555-1141

Output:
VALID!

---

## Learnings
From this project, I learned:
- How the **Luhn Algorithm** works for card validation  
- String manipulations (`translate`, slicing, reversing)  
- Working with **list slicing** (`[::2]`, `[1::2]`)  
- Basic arithmetic and modular operations  
- Writing clean and reusable functions in Python  

---

## Credits
Project inspired by **freeCodeCamp**.
