# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python
# NAME: Madhupriya R
# REG NO:212224040177

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
```
def triangle(n):
    for i in range(n):
        num=1
        row=[]
        for j in range(i+1):
            row.append(num)
            num=num*(i-j)//(j+1)
        print(*row)
n=int(input())
triangle(n)
```

## Sample Output
![438840153-bedfa805-97aa-47f8-b9b0-a4253a06ec69](https://github.com/user-attachments/assets/ce715bd3-36b3-44e6-9c3a-6163bc636590)

## Result
Thus ,the program is executed successfully.
