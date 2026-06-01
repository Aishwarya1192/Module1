# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
Add Code Here
x = int(input("Enter the real part: "))
y = int(input("Enter the imaginary part: "))

c = complex(x, y)

print("Complex number:", c)
print("Real part:", c.real)
print("Imaginary part:", c.imag)


## Output
Enter the real part: 3
Enter the imaginary part: 4
Complex number: (3+4j)
Real part: 3.0
Imaginary part: 4.0

## Result
Hence the output is verified
