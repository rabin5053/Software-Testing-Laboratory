Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for
DATE: 13/03/2025
REGISTER NUMBER : 212224230213
AIM:
To write python programs for do…while, while, for, switch and if…else and test with possible test Cases

Algorithm:
Start the program.
Create separate files for each given program.
Write simple program for each construct.
the program with possible test cases.
Stop the program.
Program:
# do..while
def display():
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
  display()
# while..do
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")
# Switch
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch()
# if..else
def compare():
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
        print(“Enter a valid number.”)
# for
def iterate(): string=input("Enter a string: ") for i in string: print(ord(i),end=" ") iterate()

Output:
![Screenshot 2025-03-13 091413](https://github.com/user-attachments/assets/d73cc361-b93c-44ab-b0b8-fabc80bdfa43)

while..do
![Screenshot 2025-03-13 090624](https://github.com/user-attachments/assets/3ea0783a-864c-48b1-9ec6-a5145cf406d6)


switch
![Screenshot 2025-03-13 090913](https://github.com/user-attachments/assets/b8666cc2-bb88-424a-8c5b-e079bbf99b42)


if..else
![Screenshot 2025-03-13 091031](https://github.com/user-attachments/assets/6a9b43c8-e65f-4ba3-9340-ae4e15050aba)


for
![Screenshot 2025-03-13 091413](https://github.com/user-attachments/assets/ab3a20d3-30ae-4b30-98a8-dd596913cd79)

Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
