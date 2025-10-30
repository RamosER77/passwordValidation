# Password Validation Checker

A Python script that validates password strength based on security best practices.
## Description

The project teaches how to validate and enforce secfurity policies by checking if a 
- ✅ At least 8 characters
- ✅ Contains at least one uppercase letter
- ✅ Contains at least one lowercase letter
- ✅ Contains at least one number
- ✅ Contains at least one special character (e.g. !, @, #)

## Features

- Python 3.
- Google Colab

# How to use:

### Run in Google Colab
1. Click the "Open in Colab" badge above the code
2. Run the function definition cell
3. Run the test cell or interactive mode cell
4. Enter password to validate

## Examples:
''' Python
check_password_strength("Test123!")   # ✅ Password passed all requirements
check_password_strength("weak")       # ❌ Password too short
check_password_strength("mandarin")   # ❌ Password needs at least one uppercase letter
check_password_strength("Mandarin3")  # ❌ Password needs at least one special character
check_password_stregth("Mandarin@1")  # ✅ Password passed all requirements

## Learning Outcomes
The project demonstrates:
- String manipulation in Python
- Using 'any()' function with generators
- Conditional logic and validation
- Writing clean, readable code

## Author:
Erubiel Ramos - BS Software Engineering CSU San Marcos

## License

MIT License - FREE to use for educational purpose.
