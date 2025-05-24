# Classes and Objects: Calculate the Area of a Circle

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

class cse:
    def mech(self, r):
        c = math.pi * r**2
        print(f"Area of circle: {c:.2f}")

r = int(input("Enter radius: "))
ci = cse() 
ci.mech(r)
```
## Output
![image](https://github.com/user-attachments/assets/5e5cd6dd-9c39-4645-a7f5-364ec23357a8)

## Result
Thus the given program is verified and executed successfully.


# Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```
## Output
![image](https://github.com/user-attachments/assets/997fa494-875c-400f-9f46-2fb48d5bbabb)


## Result
 Thus, the program has been successfully executed.


# 🔤 Dictionary-Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```input_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sorted_items = sorted(input_dict.items())
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sorted_items:
    print(f"({key}, {value})", end=' ')
```

## Sample Output
![image](https://github.com/user-attachments/assets/2d85ff10-b89a-4492-b181-ba987b141c80)

## Result
thus code is executed successfully


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


