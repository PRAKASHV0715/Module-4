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
~~~
def create_file(file_path,content):
    with open(file_path,'w') as f:
        f.write(file_content)
def count_words_in_file(file_path):
    with open(file_path,'r')as f:
        v=f.read()
        t=v.split()
        q=len(t)
    return(q)
~~~
## Output
<img width="1136" height="461" alt="image" src="https://github.com/user-attachments/assets/048b2d36-8d48-4150-83b6-611330f33bcd" />

## Result
Thus,the Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is created successfully.

