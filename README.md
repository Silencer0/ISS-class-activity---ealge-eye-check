# ISS-class-activity---ealge-eye-check
the eagle eye check for the given code

# Bug Fixes in Narcissistic Number Checker

## 1. Syntax Errors

| Line | Original Code | Fixed Code | Description |
|------|---------------|------------|-------------|
| 1 | `def is_narc(n)` | `def is_narc(n):` | Added missing colon after function definition |
| 6 | `def print_narcis_numbers(start end)` | `def print_narcis_numbers(start,end):` | Added missing comma between parameters and colon after function definition |
| 8 | `for num in range(start, end + 1)` | `for num in range(start, end + 1):` | Added missing colon after for loop |
| 9 | `if is_narcissistic(num)` | `if is_narc(num):` | Added missing colon after if statement |

## 2. Assignment Errors

| Line | Original Code | Fixed Code | Description |
|------|---------------|------------|-------------|
| 3 | `num_str == str(n)` | `num_str = str(n)` | Changed equality operator `==` to assignment operator `=` |
| 4 | `num_digits == len(num_str)` | `num_digits = len(num_str)` | Changed equality operator `==` to assignment operator `=` |

## 3. Operator Errors

| Line | Original Code | Fixed Code | Description |
|------|---------------|------------|-------------|
| 6 | `int(digit) *** num_digits` | `int(digit) ** num_digits` | Fixed exponentiation operator from `***` to `**` |

## 4. Function Name Errors

| Line | Original Code | Fixed Code | Description |
|------|---------------|------------|-------------|
| 9 | `if is_narcissistic(num)` | `if is_narc(num):` | Changed function name to match the defined function `is_narc` |
| 11 | `print_narc_numbers(1000, 5000)` | `print_narcis_numbers(1000, 5000)` | Changed function call to match the defined function `print_narcis_numbers` |

## 5. Comment Changes

| Line | Original Code | Fixed Code | Description |
|------|---------------|------------|-------------|
| 2 | `"""Check if a number is narc."""` | `#Check if a number is narc.` | Changed docstring to single-line comment |
| 7 | `"""Print all narc numbers in a given range."""` | `#"""Print all narc numbers in a given range."""` | Commented out the docstring |
