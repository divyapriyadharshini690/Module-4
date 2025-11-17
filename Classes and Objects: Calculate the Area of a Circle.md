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
import math

class cse():

def init(self,radius):

self.radius=radius def mech(self):

return math.pi*(self.radius**2) r=int(input())

obj=cse(r)

print("Area of circle:",round(obj.mech(),2))

## Output
<img width="959" height="383" alt="image" src="https://github.com/user-attachments/assets/0874c7b9-4fe5-4a5f-a319-7f4f6fa7aaa7" />


## Result
Thus, To write a Python program that calculates the area of a circle based on the radius provided by the user is verified. This program uses a class named cse and a method mech to perform the calculation.
