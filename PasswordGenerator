# Importing the random module to randomise password.
import random

# Creating lists for a series of letters, numbers and symbols which are used to generate a random password for user.
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

# Printing a welcome message when user runs program.
print("Welcome to the Random Password Generator!")

# Using the input function to prompt user to enter the desired amount of letters, numbers and symbols for password.
nr_letters = int(input("How many letters would you like in your password?\n"))
nr_symbols = int(input(f"How many symbols would you like?\n"))
nr_numbers = int(input(f"How many numbers would you like?\n"))


password_list = []
for randomLetters in range(nr_letters):
    password_list.append(random.choice(letters))

for randomNumbers in range(nr_numbers):
    password_list.append(random.choice(numbers))

for randomSymbols in range(nr_symbols):
    password_list.append(random.choice(symbols))

random.shuffle(password_list)
password = "".join(password_list)

print(f"Your new generated password is: {password}")
