# Simple Calculator

```python
# Simple Calculator

# Get two numbers from the user and convert them to floats
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform calculations
sum_result = num1 + num2
difference = num1 - num2
product = num1 * num2

# Handle division, avoiding division by zero
if num2 != 0:
    quotient = num1 / num2
else:
    quotient = "Undefined (cannot divide by zero)"

# Display the results
print("\nResults:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference}")
print(f"Product: {product}")
print(f"Quotient: {quotient}")
```

## Sample Output

```python
Enter the first number: 10
Enter the second number: 5

Results:
Sum: 15.0
Difference: 5.0
Product: 50.0
Quotient: 2.0
```

## Notes

* The program converts user input to float to handle both integers and decimal numbers.
* It includes a check to prevent division by zero, which would cause a runtime error.