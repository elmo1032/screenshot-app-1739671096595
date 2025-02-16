Certainly! Below is a simple implementation of a sum function in Python that takes a list of numbers and returns their sum.

```python
def sum_numbers(numbers):
    total = 0
    for number in numbers:
        total += number
    return total

# Example usage:
numbers_list = [1, 2, 3, 4, 5]
result = sum_numbers(numbers_list)
print("The sum is:", result)
```

If you want a more concise version using Python's built-in `sum()` function, you can do it like this:

```python
def sum_numbers(numbers):
    return sum(numbers)

# Example usage:
numbers_list = [1, 2, 3, 4, 5]
result = sum_numbers(numbers_list)
print("The sum is:", result)
```

Both implementations will give you the same result. You can call the `sum_numbers` function with any list of numbers to get their sum.