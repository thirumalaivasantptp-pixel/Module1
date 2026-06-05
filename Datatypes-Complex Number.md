# 🧮 Datatypes-Complex Number Creation in Python


🎯 Aim  
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

🧠 Algorithm  
1. Read an integer input from the user and assign it to the variable `a` (real part).  
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).  
3. Create a complex number `x` using the `complex(a, b)` function.  
4. Print the complex number `x`.  
5. Print the real part of `x` using `x.real`.  
6. Print the imaginary part of `x` using `x.imag`.  
7. End the program.

💻 Program
```python
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

x = complex(a, b)

print("Complex Number:", x)
print("Real Part:", x.real)
print("Imaginary Part:", x.imag)
```

Output
```text
Enter real part: 4
Enter imaginary part: 5
Complex Number: (4+5j)
Real Part: 4.0
Imaginary Part: 5.0
```

Result  
Thus, the Python program to create a complex number and print its real and imaginary parts was executed successfully and the output was verified.
