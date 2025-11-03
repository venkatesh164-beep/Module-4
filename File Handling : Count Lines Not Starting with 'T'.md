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
f=open("story.txt","r") <br>
count=0 <br>
for lines in f: <br>
if lines [0] not in 'T':<br> 
count+=1 <br>
print(count)

## Output
<img width="467" height="102" alt="image" src="https://github.com/user-attachments/assets/3cc7b3b1-98d5-422c-944c-bd828808bc54" />

## Result
Thus, the program has been successfully executed.
