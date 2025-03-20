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
```
# a)do..while
def display():
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
# b)while..do
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
# c)if..else

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
# d)switch
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
# e)for
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## Output
# a)do..while
![Screenshot 2025-03-20 104825](https://github.com/user-attachments/assets/af2eb597-2e52-49af-aa4b-0f4b5a8da43b)
![Screenshot 2025-03-20 104850](https://github.com/user-attachments/assets/3e30fb6a-ab32-479f-86d6-42dff99d1473)
![Screenshot 2025-03-20 104959](https://github.com/user-attachments/assets/89763cfe-65ed-4e5b-80b3-8d918b8302ac)
![Screenshot 2025-03-20 105021](https://github.com/user-attachments/assets/de767e73-735a-4c66-b004-074abd222203)




# b)while..do
![Screenshot 2025-03-20 105635](https://github.com/user-attachments/assets/484eb46a-836d-4b02-936d-36e3b7c401af)
![Screenshot 2025-03-20 105655](https://github.com/user-attachments/assets/06b5e83d-217a-42b0-91af-fd242c42ebaf)
![Screenshot 2025-03-20 105712](https://github.com/user-attachments/assets/81eb05f3-12fa-4163-8401-e649cf0cb146)
![Screenshot 2025-03-20 105729](https://github.com/user-attachments/assets/92f2fa87-3e5f-46fc-8979-04c924b515fb)




# c)if..else
![Screenshot 2025-03-20 110312](https://github.com/user-attachments/assets/15d93561-3688-4789-8707-fdc442b92449)
![Screenshot 2025-03-20 110332](https://github.com/user-attachments/assets/dfbfadb1-e706-4c0f-a8ef-3223991317dc)
![Screenshot 2025-03-20 110352](https://github.com/user-attachments/assets/9d83bae4-ff24-44e8-8f22-c2ed537d2896)
![Screenshot 2025-03-20 110408](https://github.com/user-attachments/assets/011bc9d7-014f-4579-8bd1-55fc4878824d)






# d)switch
![Screenshot 2025-03-20 110755](https://github.com/user-attachments/assets/553ab294-8023-405e-b06b-8c7ecaf0d661)

![Screenshot 2025-03-20 110813](https://github.com/user-attachments/assets/418d27a0-8992-4054-97ea-718154479690)

![Screenshot 2025-03-20 110906](https://github.com/user-attachments/assets/2fc3c1d6-1cd9-4f04-85bd-a9eb130f970b)

![Screenshot 2025-03-20 110924](https://github.com/user-attachments/assets/c3591231-7c69-48ad-aa6d-ba1f420ef43b)






# e)for
![Screenshot 2025-03-20 111305](https://github.com/user-attachments/assets/ff390e15-8b47-486f-af2c-e0153c37669e)


![Screenshot 2025-03-20 111230](https://github.com/user-attachments/assets/58669010-eb28-4b2b-a09f-609068671064)


![Screenshot 2025-03-20 111211](https://github.com/user-attachments/assets/29091097-551b-4398-960c-1c489dd28c4f)



## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the 
output is verified successfully. 




