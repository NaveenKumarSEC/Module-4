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
