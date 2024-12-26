***Problem Set 4***

```python
total = 0

while total <= 50:
    number = int(input("Please enter a number: "))
    total += number
    print(f"The total is {total}")

print("The total is over 50. Loop stopped.")
```

This initializes the `total` to 0 and continues to prompt the user for a number while the `total` is 50 or less. It adds the user's input to the `total` and prints the updated total each time. The loop stops once the total exceeds 50.


# no f string
````python
total = 0

while total <= 50:
    number = int(input("Please enter a number: "))
    total += number
    print("The total is", total)

print("The total is over 50. Loop stopped.")
````
