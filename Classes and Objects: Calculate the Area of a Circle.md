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
class cse:
    def mech(self, radius):
        pi = 3.14159
        area = pi * radius ** 2
        return area

radius = int(input("Enter the radius of the circle: "))
circle = cse()
area = circle.mech(radius)
print("Area of the circle:", area)
```
## Output
<img width="530" height="233" alt="image" src="https://github.com/user-attachments/assets/81cfbc48-9356-4d54-8d11-feedcfb9349a" />

## Result
Thus To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation has been executed sucessfully.

