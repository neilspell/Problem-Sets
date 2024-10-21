
***Problem set 3***
```

# selection - if/else
#while loop
while True:
    print("Menu")
    print("1. Music")
    print("2. History")
    print("3. Design and Technology")
    print("4. Exit")
    choice = input("Please enter your choice: ")

    if choice == '1':
        print("You chose Music")
    elif choice == '2':
        print("You chose History")
    elif choice == '3':
        print("You chose Design and Technology")
    elif choice == '4':
        print("Goodbye")
        break
    else:
        print("Invalid choice, please try again.")

print()

print()
#no while loop
        
print("Menu")
print("1. Music")
print("2. History")
print("3. Design and Technology")
print("4. Exit")
choice = input("Please enter your choice: ")

if choice == '1':
    print("You chose Music")
elif choice == '2':
    print("You chose History")
elif choice == '3':
    print("You chose Design and Technology")
elif choice == '4':
    print("Goodbye")
else:
    print("Invalid choice, please try again.")
    
print()
print()
#Q2
    
import random

# Simulate the throw of two dice
die1 = random.randint(1, 6)
die2 = random.randint(1, 6)

# Print the numbers representing the two throws
print(f"Die 1: {die1}")
print(f"Die 2: {die2}")

# Calculate and print the score
if die1 == die2:
    score = 2 * (die1 + die2)
    print("You threw a double!")
else:
    score = die1 + die2

print(f"Your score is: {score}")
```
