# File Handling in Python: find and replace a word in a file.

## 🎯 Aim
 Write a Python function to find and replace a word in a file.

## 🧠 Algorithm
1. Start the program.
2. Define a function create_file(file_path, file_content).
3. Open the file specified by file_path in write mode.
4. Write the given file_content into the file.
5. Close the file.
6. Define a function find_and_replace(file_path, old, new).
7. Open the file specified by file_path in read mode.
8. Read the entire content of the file and store it in a variable text.
9. Close the file.
10. Replace all occurrences of the word old with the word new in text.
11. Open the same file again in write mode.
12. Write the modified content back to the file.
13. Close the file.
14. Define a function read_file(file_path).
15. Open the file in read mode.
16. Read and return the file content.
17. Close the file.
18. End the program.

## 🧾 Program

def create_file(file_path, file_content):
    
    with open(file_path, 'w') as f:
        
        f.write(file_content)


def find_and_replace(file_path, old, new):
   
    with open(file_path,"r") as f:
        
        text=f.read()
    
    text=text.replace(old,new)
    
    with open(file_path,"w") as f:
    
        f.write(text)
    


def read_file(file_path):
    
    with open(file_path, 'r') as file:
    
        return file.read()

## Output

<img width="1154" height="469" alt="image" src="https://github.com/user-attachments/assets/33911a63-706d-4952-abf6-906bd3b27f6a" />


## Result
Thus the program is simulated sucessfully
