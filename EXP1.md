# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                            
### REGISTER NUMBER : 

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
# do..while
~~ def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() ~~
# while..do
~~ start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.") ~~
# Switch
~~ def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() ~~
# if..else
~~ def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) ~~
# for
~~ def iterate(): string=input("Enter a string: ") for i in string: print(ord(i),end=" ") iterate() ~~













### Output:
![Screenshot 2025-03-13 085917](https://github.com/user-attachments/assets/6bf04dad-eaff-4f02-8875-049be6c85606)
![Screenshot 2025-03-20 084821](https://github.com/user-attachments/assets/81a38329-d74a-4a16-83ac-c6e4fd1c8ee2)
![Screenshot 2025-03-20 084838](https://github.com/user-attachments/assets/9c384188-1bac-4557-aab0-3178a12edaf9)
![Screenshot 2025-03-20 084858](https://github.com/user-attachments/assets/b1674b18-aebf-48bf-a27b-9dada8a553f4)


![Screenshot 2025-03-13 090624](https://github.com/user-attachments/assets/22828ef6-d205-49df-82ee-340550875332)
![Screenshot 2025-03-20 083356](https://github.com/user-attachments/assets/e26cfdfe-d35d-4ffc-a42b-b1d16e7ebbfd)
![Screenshot 2025-03-20 083505](https://github.com/user-attachments/assets/04b6113a-f8f5-4086-a3df-e0a8084f5548)



![Screenshot 2025-03-13 090913](https://github.com/user-attachments/assets/56224cc6-df8e-4768-aabf-494c367ddb4c)
![Screenshot 2025-03-20 083920](https://github.com/user-attachments/assets/3484ad4f-ce9a-4405-a803-555d2105905f)
![Screenshot 2025-03-20 083936](https://github.com/user-attachments/assets/aed0cf7d-7807-4992-8907-a91451c043f5)


![Screenshot 2025-03-13 091031](https://github.com/user-attachments/assets/727e0dbc-9ef8-4fb9-826f-0f148628c324)
![Screenshot 2025-03-20 084251](https://github.com/user-attachments/assets/a8bd2222-68ca-47d4-8840-e49cfa100998)

![Screenshot 2025-03-20 084321](https://github.com/user-attachments/assets/bb1e6f06-1004-4946-8416-743cf3b5bb9b)
![Screenshot 2025-03-20 084306](https://github.com/user-attachments/assets/0a881f32-977b-4fa8-80bc-a5ead92494cf)


![Screenshot 2025-03-13 091413](https://github.com/user-attachments/assets/a6087054-83c1-4887-ba20-d6fc8abc8118)
![Screenshot 2025-03-20 084545](https://github.com/user-attachments/assets/13878e65-8d46-4a95-9ed8-8b332a573cf3)
![Screenshot 2025-03-20 084600](https://github.com/user-attachments/assets/965231ad-89da-4a52-95b7-d0d1e4d01eec)
![Screenshot 2025-03-20 084613](https://github.com/user-attachments/assets/54016748-e596-4c9b-ab2e-398d01b3c8a6)







### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


