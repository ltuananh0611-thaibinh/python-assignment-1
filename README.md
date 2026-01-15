
[ex2_greeting.py](https://github.com/user-attachments/files/24631563/ex2_greeting.py)name = input("Enter your name: ")
print(f"Hello, {name}!")


[ex3_circle.py](https://github.com/user-attachments/files/24631567/ex3_circle.py)import math

radius = float(input("Enter the radius of the circle: "))
circumference = 2 * math.pi * radius

print("The circumference is:", circumference)


[ex4-rectangle.py](https://github.com/user-attachments/files/24631573/ex4-rectangle.py)
length = float(input("Enter the length: "))
width = float(input("Enter the width: "))

perimeter = 2 * (length + width)
area = length * width

print("Perimeter:", perimeter)
print("Area:", area)


[ex5_number.py](https://github.com/user-attachments/files/24631575/ex5_number.py)
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

sum_numbers = a + b + c
product = a * b * c
average = sum_numbers / 3

print("Sum:", sum_numbers)
print("Product:", product)
print("Average:", average)


[ex6_medieval_units.py](https://github.com/user-attachments/files/24631579/ex6_medieval_units.py)
talents = float(input("Enter talents: "))
pounds = float(input("Enter pounds: "))
lots = float(input("Enter lots: "))

# Convert to lots
total_lots = talents * 20 * 32 + pounds * 32 + lots

# Convert lots to grams
total_grams = total_lots * 13.3

kilograms = int(total_grams // 1000)
grams = total_grams % 1000

print("The weight in modern units:")
print(f"{kilograms} kilograms and {grams:.2f} grams.")



[ex7_random_codes.py](https://github.com/user-attachments/files/24631585/ex7_random_codes.py)import random

# 3-digit code (0–9)
code1 = (
    random.randint(0, 9),
    random.randint(0, 9),
    random.randint(0, 9)
)

# 4-digit code (1–6)
code2 = (
    random.randint(1, 6),
    random.randint(1, 6),
    random.randint(1, 6),
    random.randint(1, 6)
)

print("3-digit code:", code1)
print("4-digit code:", code2)

[README.md](https://github.com/user-attachments/files/24631593/README.md)# Assignment 1 – Python Basics

## Description
This assignment contains basic Python exercises to practice variables,
input/output, calculations, and random number generation.

## Files Included

- ex2_greeting.py  
  Prints a greeting message to the user.

- ex3_circle.py  
  Calculates the area and circumference of a circle.

- ex4_rectangle.py  
  Calculates the area and perimeter of a rectangle.

- ex5_number.py  
  Performs basic number operations and comparisons.

- ex6_medieval_units.py  
  Converts medieval units into modern units.

- ex7_random_codes.py  
  Generates random 3-digit and 4-digit codes.

## How to Run
Open each file and run it using Python 3.

## Author
Le Tuan Anh






