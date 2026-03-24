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
class Cse:
    def mech(self,a):
        area=math.pi*a*a
        print(f"Area of circle: {area:.2f}")
a=int(input())
obj=Cse()
obj.mech(a)
```

## Output

![439085688-adad297a-c23a-418f-a5ff-05c242c486c1](https://github.com/user-attachments/assets/58e64c1d-e2a8-4b31-861f-a9fb9d877855)

## Result
Hence the program executed successfully!
