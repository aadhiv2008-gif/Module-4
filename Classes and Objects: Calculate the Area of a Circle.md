# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```

import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")
r = float(input())
obj = cse()
obj.mech(r)
```

## Output
<img width="965" height="285" alt="568911847-57d525c1-4898-4247-a2d7-410720909ad1" src="https://github.com/user-attachments/assets/d0f63455-c6ad-47fc-a0fa-6c6b220a6b15" />

## Result
Thus the program executed successfully.
