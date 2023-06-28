# Using ChatGPT to speed up and optimise your research

ChatGPT can be helpful to speed up and optimise your research - if you know how to use it and know its shortcomings (keep thinking critically)!

## Getting Started with ChatGPT

To get started with ChatGPT, sign up for an OpenAI account at https://chat.openai.com. It's free and once you have registered, you can start to use it with one conversation at a time.

## Useful examples

### Write documented python functions

Coding is difficult - good coding even more so. ChatGPT helps you to write well commented code and also let's you learn from other people's code.

For example, you could "write quickly written down, uncommented code that should be in a python function" like this:
```python
num1 = 10
num2 = 15
num3 = 20
total = num1 + num2 + num3
average = total / 3
print("The average is:", average)

num4 = 5
num5 = 12
num6 = 18
total = num4 + num5 + num6
average = total / 3
print("The average is:", average)
```

You can easily ask ChatGPT to "optimise the code and include docstrings and comments":
```
def calculate_average(numbers):
    """
    Calculate the average of a list of numbers.

    Args:
        numbers (list): A list of numbers.

    Returns:
        float: The average of the numbers.
    """
    total = sum(numbers)  # Calculate the sum of the numbers
    average = total / len(numbers)  # Calculate the average
    print("The average is:", average)

    return average


# Example usage for the first set of numbers
nums1 = [10, 15, 20]
result1 = calculate_average(nums1)

# Example usage for the second set of numbers
nums2 = [5, 12, 18]
result2 = calculate_average(nums2)
```