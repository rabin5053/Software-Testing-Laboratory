# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:  10/04/2025                                                                          
### REGISTER NUMBER : 212224230213
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
x = input("Enter the input: ") 
if x.isnumeric(): 
    x = int(x) 
    temp = x 
    cube = 0; 
    while(temp>0): 
        digit = temp%10 
        cube = cube + (digit**3) 
        temp//=10 
    if(cube == x): 
        print("Armstrong Number") 
    else: 
        print("Not Armstrong Number") 
else: 
    print("Enter a Positive Integer.")












### Output:
![Screenshot 2025-04-10 082029](https://github.com/user-attachments/assets/6dd4e6a3-4336-4767-acdf-6575795de976)
![Screenshot 2025-04-10 082116](https://github.com/user-attachments/assets/ea7ba4f5-ab9f-469d-b1d0-12c4eafa00fd)
![Screenshot 2025-04-10 082155](https://github.com/user-attachments/assets/a7dcf67c-817a-427c-93d8-1fec18cf0ea5)
![Screenshot 2025-04-10 082217](https://github.com/user-attachments/assets/071ad89f-2d46-42a8-a58d-d77bc064a47f)





### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
