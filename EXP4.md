# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE: 10/04/2025                                                                           
### REGISTER NUMBER : 212224230213
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:

def binary_search(arr, x):  
         low = 0 
    high = len(arr) - 1 mid = 0 
           while low <= high: 
               mid = (high + low) // 2  
               if arr[mid] < x: 
                   low = mid + 1 elif arr[mid] > x: 
               high = mid – 1 
                   else: 
           return -1 
 
arr = [ 2, 3, 4, 10,40 ] 
x = input(“Enter the element to be searched: ”);  
try: 
    x = int(x) 
    result = binary_search(arr, x)  
    if result != -1: 
          print("Element is present at index",str(result)) 
    else: 
          print("Element is not present in array") 
       except: 
    print(“Enter a valid input!”)












### Output:


![Screenshot 2025-04-10 083312](https://github.com/user-attachments/assets/51f0d205-320c-42e0-8cb2-702ed8d4f2a7)
![Screenshot 2025-04-10 083337](https://github.com/user-attachments/assets/eb74831b-457a-4899-a4a2-b8661eebd875)
![Screenshot 2025-04-10 083449](https://github.com/user-attachments/assets/31863fcf-f6e3-4159-971f-b686dc87bcad)
![Screenshot 2025-04-10 083502](https://github.com/user-attachments/assets/21e8c583-31d8-4ded-aa4d-c0f951023d07)

![Screenshot 2025-04-10 083513](https://github.com/user-attachments/assets/44a593f8-1138-4204-b278-e9e6c842aeb6)



### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


