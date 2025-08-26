# Refresh your memory!


### Types of data:

- **int** – represents only integers and nothing else: 1, 768, etc.

- **float** – represents floating-point numbers, or numbers with decimal parts: 2.2, 4.0, etc.

- **str** – represents anything enclosed in quotation marks and is treated as text: 'just one word', "any sentence!", etc.


### Functions:

- **int()** – converts the value inside the parentheses into an integer (if possible): int('1') → 1. It does not work with letters!

- **float()** – converts the value inside the parentheses into a floating-point number (if possible): float('1') → 1.0 or float(1) → 1.0. It does not work with letters!

- **str()** – converts the value inside the parentheses into a string without exceptions: str(1) → '1' or str(1.0) → '1.0'.


### Strings:

#### F-stings:

F-strings in Python are a concise and readable way to embed expressions inside string literals.

**Ex_1:**  
name = input('Enter your name here:\n')  
age = int(input('Nice to meet you! How old are you?'))  
my_love = input(f'What do you like to do, {name}?')  

result = f"Hello!\nMy name is {name}. I'm {age} years old and I love {my_love}!\nSee you)"
print(result)

#### Some more examples:

**Ex_1:**  
result = 'I love Python!'
print(result)

**Ex_2:**  
result = 'I love' + 'Python' + '!'
print(result)

part_1 = 'I love'
part_2 = 'Python!'
result = part_1 + part_2
print(result)

**Ex_3:**  
text = 'I love Python!'
number = 5
result = text * number
print(result)

**!!!**  
We can use + and * with the strings, but the difference is in the result of these operations:  

'Py' + 'thon' == 'Python'  
'Python' * 2 == 'PythonPython'

We can't use - and / or // and etc with the strings!


#### Functions:

- **len()**

- **lower()**

- **upper()**

- **find()**

- **isdigit()**