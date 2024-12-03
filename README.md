# arewadatascience
# 1. Simple Variable Assignment
x = 10
print("Task 1: x =", x)

# 2. Assigning Different Data Types
age = 25
height = 5.9
name = "John"
is_active = True
print("\nTask 2: age =", age, "height =", height, "name =", name, "is_active =", is_active)

# 3. Simple Addition
a, b = 5, 7
sum_result = a + b
print("\nTask 3: Sum of a and b =", sum_result)

# 4. String Concatenation
first_name, last_name = "Alice", "Wonderland"
full_name = first_name + " " + last_name
print("\nTask 4: Full name =", full_name)

# 5. Variable Type Check
x = "Hello"
print("\nTask 5: Type of x =", type(x))

# 6. Swap Two Variables
a, b = 10, 5
a, b = b, a
print("\nTask 6: a =", a, "b =", b)

# 7. Arithmetic Operations
x, y = 15, 4
print("\nTask 7: Addition =", x + y, "Subtraction =", x - y, "Multiplication =", x * y, 
      "Division =", x / y, "Modulus =", x % y)

# 8. Multiple Variable Assignment
x, y, z = 1, 2, 3
print("\nTask 8: x =", x, "y =", y, "z =", z)

# 9. Updating Variable Values
counter = 10
counter += 5
counter -= 3
print("\nTask 9: Final counter =", counter)

# 10. Variable Re-Assignment
x = 100
x = 50
print("\nTask 10: New x =", x)

# 11. User Input and Variable Assignment
# Uncomment the next two lines to test interactively
# name = input("\nEnter your name: ")
# print("Task 11: Hello, " + name + "!")

# 12. String to Integer Conversion
num_str = "42"
num = int(num_str)
print("\nTask 12: Integer value =", num)

# 13. Integer to String Conversion
num = 100
num_str = str(num)
print("\nTask 13: String value =", num_str)

# 14. Working with Lists
fruits = ["apple", "banana", "cherry"]
favorite_fruit = fruits[0]
print("\nTask 14: Favorite fruit =", favorite_fruit)

# 15. String Length
message = "Hello, Python!"
length = len(message)
print("\nTask 15: Length of message =", length)

# 16. Floating-Point Arithmetic
a, b = 3.14, 2.71
print("\nTask 16: Addition =", a + b, "Subtraction =", a - b, "Multiplication =", a * b)

# 17. Combining Strings with Variables
first_name, last_name = "John", "Doe"
print("\nTask 17: Hello,", first_name + " " + last_name + "!")

# 18. String Formatting with f-strings
age, name = 25, "Alice"
print(f"\nTask 18: My name is {name} and I am {age} years old.")

# 19. Constants Convention
PI = 3.14159
print("\nTask 19: PI =", PI, "Constants are written in uppercase to signify immutability.")

# 20. Working with Dictionaries
person = {"name": "Alice", "age": 25}
age_value = person["age"]
print("\nTask 20: Age value =", age_value)

# 21. Using Global and Local Variables
x = 10
def local_scope():
    x = 20
    print("Local x =", x)
local_scope()
print("Global x =", x)

# 22. Swapping Values with Pythonic Method
x, y = 5, 10
x, y = y, x
print("\nTask 22: x =", x, "y =", y)

# 23. Boolean Expressions
is_sunny, is_raining = True, False
print("\nTask 23:", "It's sunny!" if is_sunny else "It's raining!")

# 24. Typecasting Multiple Variables
x, y, z = "100", "50", "30"
sum_result = int(x) + int(y) + int(z)
print("\nTask 24: Sum =", sum_result)

# 25. Modifying String Values
sentence = "Python is awesome"
sentence = sentence.replace("awesome", "cool")
print("\nTask 25: Modified sentence =", sentence)

# 26. Complex Variable Assignment
person = {"name": "Bob", "age": 30}
person_name, person_age = person["name"], person["age"]
print("\nTask 26: Name =", person_name, "Age =", person_age)

# 27. Using Variables in Functions
def greet(name):
    print(f"\nTask 27: Hello, {name}!")
greet("Umar")

# 28. Counting Occurrences
text = "apple apple banana apple"
apple_count = text.count("apple")
print("\nTask 28: Apple count =", apple_count)

# 29. Working with Multiple Variables in a Function
def add_numbers(a, b):
    return a + b
result = add_numbers(5, 7)
print("\nTask 29: Result =", result)

# 30. Using Variables in Lists and Loops
numbers = [1, 2, 3, 4, 5]
doubled_numbers = [n * 2 for n in numbers]
print("\nTask 30: Doubled numbers =", doubled_numbers)
