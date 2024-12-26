# **Problem Set 4**
**Question 1**

```python
total = 0

while total <= 50:
    number = int(input("Please enter a number: "))
    total += number
    print(f"The total is {total}")

print("The total is over 50. Loop stopped.")
```

This initializes the `total` to 0 and continues to prompt the user for a number while the `total` is 50 or less. It adds the user's input to the `total` and prints the updated total each time. The loop stops once the total exceeds 50.


**no f string**
````python
total = 0

while total <= 50:
    number = int(input("Please enter a number: "))
    total += number
    print("The total is", total)

print("The total is over 50. Loop stopped.")
````
**Question 2**


```python
while True:
    number = int(input("Please enter a number between 10 and 20: "))
    if number < 10:
        print("Too Low")
    elif number > 20:
        print("Too High")
    else:
        print("Thank You")
        break
```


