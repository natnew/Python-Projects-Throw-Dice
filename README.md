# Python Projects: Throw Dice 🐍
This repo contains python code that simulates throwing any amount of dice. <br>
Run the code.


Python
```python
import random

def throw_dice(n):
    for i in range(n):
        random_num = random.randint(1, 6)
        print(f"Throw from dice {i+1}: {random_num}")


def run():
    number = int(input("Welcome to Throw a Dice! \nHow many dice would you like to throw?:"))
    throw_dice(number)

if __name__ == "__main__":
    run()
```

Output
```python
Welcome to Throw a Dice! 
How many dice would you like to throw?:4
Throw from dice 1: 3
Throw from dice 2: 1
Throw from dice 3: 3
Throw from dice 4: 2
```
