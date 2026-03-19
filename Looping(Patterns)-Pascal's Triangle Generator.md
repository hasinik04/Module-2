# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```python
n=int(input())
for i in range(0,n):
    for j in range(i,n):
        print(n,"",end="")
    print()

```

## Sample Output
![image](https://github.com/user-attachments/assets/a1cf7bed-c40b-427d-85d4-fa0c8669b9c0)

## Result
Thus the Python program that generates **Pascal's Triangle** using numbers is executed successfully.
