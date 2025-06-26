
# Python Greeting Program

This Python script asks the user to input their first and last names, and then prints a personalized greeting.

## How It Works

1. The user is prompted to input their **first name** and **last name**.
2. The script concatenates the names and prints a greeting message.

## Python Code

```python
first_name = input("enter your first name: ")
last_name = input("enter your last name: ")
print("Hello,", first_name + last_name, "! Welcome to the Python program")
```

## Example

```
enter your first name: John
enter your last name: Doe
Hello, JohnDoe ! Welcome to the Python program
```

## Note

To add a space between the first and last name in the greeting, you can modify the print line to:
```python
print("Hello,", first_name + " " + last_name, "! Welcome to the Python program")
```

## Requirements

- Python 3.x
