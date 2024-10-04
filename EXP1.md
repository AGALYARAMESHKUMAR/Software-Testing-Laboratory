# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 212222040003

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
1.do..While:
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Please enter valid positive numbers.")

display()
```
2.while..do:
```
start = input("Enter a positive value for START: ")
end = input("Enter a positive value for END: ")

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
```
3.switch:
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input('Enter a value for N: ')
    
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
4.if..else:
```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")
        
compare()
```
5.for:
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```

## Output:
![Screenshot 2024-10-04 103856](https://github.com/user-attachments/assets/51f0569f-5192-4576-ac75-53aada0f8172)
![Screenshot 2024-08-23 110509](https://github.com/user-attachments/assets/afbe97be-2f79-4e26-9ca8-41e4d2bf0412)
![Screenshot 2024-08-23 111911](https://github.com/user-attachments/assets/388a5ef5-4e65-469d-a37d-838d7843004f)
![if else](https://github.com/user-attachments/assets/270b2466-9cb1-48cc-b230-4fb8a40effd9)
![Screenshot 2024-09-13 103731](https://github.com/user-attachments/assets/2dee3885-ff2a-4aa2-827f-8c34242ab4ec)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


