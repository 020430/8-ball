# 8-ball

A simple Python 8-ball game

## Description

The code allows the user to input a question and responds with an 'answer'


## Usage

```python
import random

# allows user to ask a question
question = input(" ")

# picks a random number between 1 and 9
random_num = random.randint(1, 9)

# whichever random number it picks it will print the corresponding message 
if random_num == 1:
print("Yes - definitely.")
elif random_num == 2:
print("It is decidedly so.")
...
```
