import random
from shlex import join

#Password generator

letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

print("Welcome to the PyPassword Generator!")
nr_letters = int(input("How many letters would you like in your password?\n"))
nr_symbols = int(input(f"How many symbols would you like?\n"))
nr_numbers = int(input(f"How many numbers would you like?\n"))

#Easy
password = ""
for num in range(0, nr_letters):
    pass_letters = random.randint(0, 52 + 1)
    password += letters[pass_letters]
for num in range(0, nr_symbols):
    password_symbols = random.randint(0, 8 + 1)
    password += symbols[password_symbols]
for num in range(0, nr_numbers):
    password_numbers = random.randint(0, 8 + 1)
    password += numbers[password_numbers]

# print(password)

#Hard
seperator = ""
pass_list = []


for y_letters in password:
    pass_list.append(y_letters)

random.shuffle(pass_list)
hard_pass = "".join(pass_list)

print(f"Your password could be: {hard_pass}")
print("Thank you for using the PyPassword Generator!")
