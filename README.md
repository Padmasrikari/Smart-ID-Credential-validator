# Smart ID & Credential validator – Day 2

## Challenge Overview
Day-2 focuses on building a **Smart Registration System** for a university.  
The system validates student credentials such as Student ID, Email ID, Password, and Referral Code before approving an account.

---

## Problem Statement
The program accepts the following inputs:
- Student ID
- Email ID
- Password
- Referral Code

Each input is checked against strict university rules.  
If **all validations pass**, the system prints **APPROVED**; otherwise, it prints **REJECTED**.

---

##  Validation Rules

### Student ID
- Format must be `CSE-XXX`
- Must start with `CSE`
- 4th character must be `-`
- Last three characters must be digits

### Email ID
- Must contain `@` and `.`
- `@` must not be the first or last character
- Must end with `.edu`

### Password
- Length must be at least 8 characters
- First character must be an uppercase letter
- Must contain at least one digit

### Referral Code
- Format must be `REF##@`
- Must start with `REF`
- Next two characters must be digits
- Last character must be `@`

---

## Approach / Logic Used
The solution is implemented using only **strings, slicing, and conditional statements**.  
Basic string functions like `len()`, `count()`, and `isdigit()` are used to validate formats and values.  
Each input is checked individually, and a boolean flag determines the final approval status.

---

## Algorithm / Steps
1. Start the program.
2. Read Student ID, Email ID, Password, and Referral Code.
3. Validate Student ID format.
4. Validate Email ID structure and domain.
5. Validate Password rules.
6. Validate Referral Code format.
7. If all validations pass, print **APPROVED**.
8. Otherwise, print **REJECTED**.
9. End the program.

---

## Learning Outcome
This challenge improved my understanding of string manipulation and conditional logic in Python.  
It helped me learn how strict input validation is implemented in real-world registration systems.

---

## How to Run
1. Open the Python file in any IDE or editor.
2. Run the program.
3. Enter the required inputs when prompted.
4. View the approval or rejection result.

---

##  Sample Output
### APPROVED
APPROVED
### REJECTED
REJECTED

---

## Author
Padmasrikari
