# Classes and Objects in Python: Calculate the perimeter of a Circle

## 🎯 Aim
Write a python program to find perimeter of a circle using class name 'saveetha'  and function name 'cse'.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `saveetha`.
3. **Define the method**: Inside the class, define the method `cse` to calculate the perimeter of the circle using the formula:  
   Area = 2*pi*r 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

class saveetha:
    
    def cse(self,r):
    
        perimeter=2*3.1412*r
        
        return perimeter

obj=saveetha()

radius=int(input())

result=obj.cse(radius)

print(f"Perimeter of circle: {round(result,2)}")

## Output

<img width="777" height="161" alt="image" src="https://github.com/user-attachments/assets/855cd5bd-1262-4711-b0a2-01b0c6b4afb7" />


## Result
Thus the program is simulated sucessfully
