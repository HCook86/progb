# progb
A simple python library to implement simple, customizable, multi-platform progress bars
![](https://github.com/HCook86/progb/img/bars.png)
## Installation

#### Using pip:
    pip install progb

#### Using git:
    git clone https://github.com/HCook86/progb.git

## Usage
```
from progb import Bar

bar = Bar(12)                  # Make an instance of the Bar object

for i in range(0,12):
  bar.cycle()                  # Call bar.cycle() on each iteration

bar.end()                      # Call bar.end() after the for loop

```

## Features

## Limitations
