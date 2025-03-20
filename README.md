# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
## a)do..while
```def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
## b)while...do
```start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```
## c)if..else
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

## d)switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }
    
    n = input("Enter a value for N: ")  
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
## e)for
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## Output
## a)do..while
![Screenshot 2025-03-20 105021](https://github.com/user-attachments/assets/49b25392-d362-40e6-b029-df442ca2d751)
![Screenshot 2025-03-20 104850](https://github.com/user-attachments/assets/c94d5f99-579c-43c7-a8b0-922c6e057061)
![Screenshot 2025-03-20 104959](https://github.com/user-attachments/assets/46f8c11a-47ec-45d8-b447-2aae3e265264)
![Screenshot 2025-03-20 104825](https://github.com/user-attachments/assets/95a2d75c-3802-4003-b2b8-4846c6089fc8)

## b)while..do
![Screenshot 2025-03-20 105635](https://github.com/user-attachments/assets/9638e964-d1d6-4930-a89d-caed06d2a4af)
![Screenshot 2025-03-20 105655](https://github.com/user-attachments/assets/8466e49f-35a5-4906-a6e0-34bfa60411b1)
![Screenshot 2025-03-20 105712](https://github.com/user-attachments/assets/473acac7-9f1d-4202-b387-ae619687ae5f)
![Screenshot 2025-03-20 105729](https://github.com/user-attachments/assets/4f757876-6d01-4bc5-9fa0-9b1bd1c447d0)

## c)if..else
![Screenshot 2025-03-20 110755](https://github.com/user-attachments/assets/beb895be-41bd-4b8d-901a-7215d1f3b80d)
![Screenshot 2025-03-20 110813](https://github.com/user-attachments/assets/6c9fd167-d57c-494e-953b-7dc706cb0623)
![Screenshot 2025-03-20 110906](https://github.com/user-attachments/assets/b09478e3-e7eb-45be-968a-e6c17eac3190)
![Screenshot 2025-03-20 110924](https://github.com/user-attachments/assets/42885805-5724-4f22-ae26-a2e55da08348)

## d)switch
![Screenshot 2025-03-20 110312](https://github.com/user-attachments/assets/d12932bd-fe24-47c1-8eca-f1d16e21fba4)

![Screenshot 2025-03-20 110332](https://github.com/user-attachments/assets/6edfa336-d40c-4234-a362-87c216d3d322)

![Screenshot 2025-03-20 110352](https://github.com/user-attachments/assets/8ff03fe4-1473-4f6d-906b-bb1f692c4fb5)

![Screenshot 2025-03-20 110408](https://github.com/user-attachments/assets/ab92ae84-f351-4e5c-830c-55cb99877e14)

## e)for
![Screenshot 2025-03-20 111211](https://github.com/user-attachments/assets/ba7b546b-353e-47a4-90e1-5a71fe2b446e)

![Screenshot 2025-03-20 111230](https://github.com/user-attachments/assets/891122aa-d0dd-4262-8647-9c8001b8f493)

![Screenshot 2025-03-20 111305](https://github.com/user-attachments/assets/04bb0081-77b8-4279-9ca1-75ef47ac2028)


## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the 
output is verified successfully. 

