# Python Basics: Strings and Tuples

This Python program demonstrates basic operations with **strings** and **tuples**, including concatenation, slicing, modification, and access.

---

## 1. String Concatenation and Manipulation

### Code Examples:

```python
# Concatenating strings
String1 = "Hello"
String2 = input("Please enter your name: ")
print(String1, String2)

String3 = ", welcome to Python programming"
print(String1, String2, String3)

# Print the first character of the string
print(String1[0])

# Convert the sentence to uppercase
strM = 'Python beginner tutorial'
print(strM.upper())

# Convert the sentence to lowercase
print(strM.lower())

# Capitalize the first character of the string
print(strM.capitalize())

# Count the total number of occurrences of character 't'
print(strM.count("t"))

# Replace "Python" with "Machine Learning"
replaced_string = strM.replace("Python", "Machine Learning")
print(replaced_string)
String Slicing Examples:
python
Copy code
# Print the last character of the string
print(String3[-1])

# Print the first 5 characters of the string
print(String3[0:5])

# Print the last 11 characters of the string
print(String3[-11:])

# Print the string in reverse
print(String1[::-1])

# Print the word "Python" from the existing string
print(String3[13:19])
2. Tuples: Creation, Modification, and Access
Code Examples:
python
Copy code
# Creating tuples
tup1 = (10, 20, 30)
tup2 = (40, 50, 60)

# Concatenate the two tuples
t_combine = tup1 + tup2
print(t_combine)

# Repeat the elements of the combined tuple 3 times
print(t_combine * 3)

# Access the 3rd element
Third_element = t_combine[2]
print(Third_element)

# Access the first three elements
First_3elements = t_combine[0:3]
print(First_3elements)

# Access the last three elements
Last_3elements = t_combine[3:6]
print(Last_3elements)
Summary
This program demonstrates:

String Operations:

Concatenation

Uppercase, lowercase, capitalization

Character counting

Replacement

Slicing and indexing

Tuple Operations:

Creation and concatenation

Repetition

Accessing elements by index and slicing

It is a basic introduction to handling strings and tuples in Python.

yaml
Copy code
