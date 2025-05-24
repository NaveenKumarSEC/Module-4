

# Exception Operations And Its Functions

## AIM:
To write a python program for the solution of value error in exception handling and check whether the number is even or odd.

## ALGORITHM:
1. Start

2. Prompt the user to enter a number

3. Try the following:

   Convert the input to an integer and store it in variable x
      
   Check if x % 2 == 0:

     If true, print "You entered even number"
            
     Else, print "An odd number"

4. If an error occurs during conversion (i.e., the input is not a valid number):

    Catch the ValueError exception
    
    Print "Enter only number"

5. End.

## PROGRAM:
```
Developed by: Naveenkumar M
Reg No: 212224230182

try:
    x=int(input())
    if x%2==0:
        print("You entered even number")
    else:
        print("An odd number")
except ValueError:
    print("Enter only number")

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/8f9909e3-6574-4c45-9320-cb847699adea)

## RESULT:
The expected output is successfully executed.


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
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```
## Output
![439316102-584ecff1-9dfb-4670-b1c8-ee354a85ed3d](https://github.com/user-attachments/assets/41d81ae2-8c98-4593-96fc-37fb26047070)

## Result
Thus,the program has been executed successfully.


