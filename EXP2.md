# Ex.No: 2   Matrix Multiplication 

### DATE: 20/03/2025                                                                            
### REGISTER NUMBER : 212224230213

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:

def matrix_multiplication():
    # Get matrix dimensions from user
    try:
        r1, c1 = map(int, input("Enter row and column count in matrix 1: ").split())
        r2, c2 = map(int, input("Enter row and column count in matrix 2: ").split())
    except ValueError:
        print("Enter valid numbers for matrix dimensions.")
        return

    # Validate matrix multiplication conditions
    if c1 != r2:
        print("Matrix multiplication not possible (columns of matrix 1 must match rows of matrix 2).")
        return
    if max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) <= 0:
        print("Matrix size should be between 1x1 and 20x20.")
        return

    # Initialize matrices
    matrix1 = []
    matrix2 = []
    result = []

    # Get values for Matrix 1
    print("Enter values for Matrix 1 row by row (space-separated):")
    for i in range(r1):
        row = list(map(int, input().split()))
        if len(row) != c1:
            print(f"Please enter exactly {c1} values per row.")
            return
        matrix1.append(row)

    # Get values for Matrix 2
    print("Enter values for Matrix 2 row by row (space-separated):")
    for i in range(r2):
        row = list(map(int, input().split()))
        if len(row) != c2:
            print(f"Please enter exactly {c2} values per row.")
            return
        matrix2.append(row)

    # Matrix multiplication logic
    for i in range(r1):
        inter = []
        for j in range(c2):
            total = 0  # Renamed 'sum' to 'total'
            for k in range(c1):  # or k in range(r2), since c1 == r2
                total += matrix1[i][k] * matrix2[k][j]
            inter.append(total)
        result.append(inter)

    # Print result matrix
    print("Resultant Matrix:")
    for row in result:
        print(" ".join(map(str, row)))

# Run the function
matrix_multiplication()












### Output:
![Screenshot 2025-03-20 090306](https://github.com/user-attachments/assets/7f117ab2-187d-4458-8d83-e02bf9351243)
![Screenshot 2025-03-20 090350](https://github.com/user-attachments/assets/098ccc4d-6368-4ca2-b46d-b833525cdd13)
![Screenshot 2025-03-20 090412](https://github.com/user-attachments/assets/24c977fd-7031-4e9b-ac7e-a216cf0fe9d9)
![Screenshot 2025-03-20 090444](https://github.com/user-attachments/assets/90f00a66-38c8-42de-ae07-1c67f29c73cb)
![Screenshot 2025-03-20 090056](https://github.com/user-attachments/assets/3bf04122-73bb-422a-a069-fab376206aac)






### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

