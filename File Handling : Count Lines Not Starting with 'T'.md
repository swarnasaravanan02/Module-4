# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
file=open("story.txt","r") 

count=0 

for lines in file: 

   if lines [0] not in 'T': 
   
      count+=1 
      
print(count)
```
## Output

<img width="357" height="79" alt="image" src="https://github.com/user-attachments/assets/e9893a9a-8066-4f62-9e6c-f1676d27817c" />

## Result
Thus, the program executed successfully.
