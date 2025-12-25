# Exception handling - check whether the number is even or odd

## 🎯 Aim
write a python program for the solution of value error in exception handling and check whether the number is even or odd.

## 🧠 Algorithm
1. inside try define a user input
2. if a%2==0 print even number
3. else odd number
4. inside except valueerror print enter only number
5. end

## 🧪Program

try:
    
    a=int(input())
    
    if a%2==0:
        
        print("You entered even number")
    
    else:
       
        print("An odd number")

except ValueError:
   
    print("Enter only number")

## Sample Output

<img width="709" height="201" alt="image" src="https://github.com/user-attachments/assets/4a6e457d-8ee6-4641-9b93-441bd473e7ae" />


## Result
Thus, the program is simulated sucessfully
