# Experiment-1
## Name:SATHISH.B
## Regno:212224040299
##  Write a C programs  to demonstrate the working of following constructs with possible test cases:
a) do…while b) while…do c) if …else d) switch e) for
## a) Aim
To demonstrate the working of the do...while loop, which ensures the loop body is executed at least once, even if the condition is false initially.

## Algorithm
1.	Initialize the loop variable.
2.	Execute the statements inside the loop body.
3.	After executing the loop body, check the condition.
4.	If the condition is true, repeat the loop; otherwise, exit the loop.

## Program
```
#include <stdio.h>

int main() {
    int i = 0;

    // do...while loop to print numbers from 0 to 4
    do {
        printf("Number: %d\n", i);
        i++;
    } while(i < 5); // condition to stop after 5 iterations

    return 0;
}
```
## Output
![Screenshot (2)](https://github.com/user-attachments/assets/283064b4-3915-46d7-bb09-46c0884eefe7)

## Result
To demonstrating the do...while loop is completed successfully. The program executes the loop body at least once before evaluating the condition.


## b) Aim
To demonstrate the working of the while...do loop, where the loop will execute the body of the loop as long as the condition is true.

## Algorithm
1.	Initialize the loop variable.
2.	Check the condition before executing the loop body.
3.	If the condition is true, execute the statements inside the loop.
4.	Repeat steps 2 and 3 until the condition becomes false.

## Program
```
#include <stdio.h>

int main() {
    int i = 0;

    // while loop to print numbers from 0 to 4
    while(i < 5) {
        printf("Number: %d\n", i);
        i++;
    }

    return 0;
}
```
## Output
![Screenshot (3)](https://github.com/user-attachments/assets/9209530a-6f72-42b8-9c25-ecba9725f6c2)

## Result
To demonstrating the while...do loop is completed successfully. The program checks the condition first and executes the loop body while the condition remains true.
## c) Aim
To demonstrate the working of the if...else conditional statement, which allows for decision-making based on a condition.

## Algorithm
1.	Evaluate the condition.
2.	If the condition is true, execute the block of code inside the if statement.
3.	If the condition is false, execute the block of code inside the else statement.

## Program
```
#include <stdio.h>

int main() {
    int num;

    // Get user input
    printf("Enter a number: ");
    scanf("%d", &num);

    // if...else to check if the number is even or odd
    if(num % 2 == 0) {
        printf("The number %d is even.\n", num);
    } else {
        printf("The number %d is odd.\n", num);
    }

    return 0;
}
```
## Output
![Screenshot (4)](https://github.com/user-attachments/assets/fdc83951-ba1d-43a6-b730-c5cf322289f9)

## Result
To demonstrating the if...else statement is completed successfully. The program correctly decides between two possible execution paths based on a given condition.


## d) Aim
To demonstrate the working of the switch statement, which is used to select one of many code blocks to be executed.

## Algorithm
1.	Evaluate the expression in the switch statement.
2.	Compare the expression's value with each case value.
3.	If a match is found, execute the associated block of code.
4.	If no match is found, execute the default case (if defined).

## Program
```
#include <stdio.h>

int main() {
    int choice;

    // Display menu
    printf("Enter a number between 1 and 3: ");
    scanf("%d", &choice);

    // switch statement
    switch(choice) {
        case 1:
            printf("You selected option 1\n");
            break;
        case 2:
            printf("You selected option 2\n");
            break;
        case 3:
            printf("You selected option 3\n");
            break;
        default:
            printf("Invalid option selected!\n");
    }

return 0;
}
```
## Output
![Screenshot (5)](https://github.com/user-attachments/assets/371f27f5-7c1a-4314-8ad1-0dd643cfb8a1)

## Result
To demonstrating the switch statement is completed successfully. The program selects and executes a specific case based on the input value, ensuring efficient multiple-choice decision-making.
# e) Aim
To demonstrate the working of the for loop, which is used to iterate a fixed number of times.

## Algorithm
1.	Initialize the loop variable.
2.	Set the loop condition.
3.	Execute the loop body.
4.	After each iteration, increment/decrement the loop variable and repeat until the condition becomes false.

## Program
```
#include <stdio.h>

int main() {
    int i;

    // for loop to print numbers from 0 to 4
    for(i = 0; i < 5; i++) {
        printf("Number: %d\n", i);
    }

    return 0;
}
```
## Output
![Screenshot (6)](https://github.com/user-attachments/assets/7750f856-94e0-4812-941b-e10dc1c5a68f)

## Result
To demonstrating the for loop is completed successfully. The program iterates a fixed number of times, performing initialization, condition checking, and incrementing in a single statement.
