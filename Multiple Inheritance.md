# Exp.No:23  
## Multiple Inheritance

---

### AIM  
To Write a Python Program to Calculate Add, sub & Multiplication using Multiple Inheritance..


### ALGORITHM

1. Start the program
2. Define class Calculation1 with method Summation(a, b) that returns a + b.
3. Define class Calculation2 with method sub(a, b) that returns a - b.
4. Define class Derived that inherits from Calculation1 and Calculation2.
5. In class Derived, define method Mul(a, b) that returns a * b.
6. Take integer input a from the user.
7. Take integer input b from the user.
8. Create an object d of class Derived.
9. Call d.Summation(a, b) and print the result.
10. Call d.sub(a, b) and print the result.
11. Call d.Mul(a, b) and print the result.
10. Terminate the program.

---

### PROGRAM

```
class Calculation1:  
    def Summation(self,a,b):  
        return a+b;  
class Calculation2:  
    def sub(self,a,b):  
        return a-b;  
class Derived(Calculation1,Calculation2):  
    def Mul(self,a,b):  
        return a*b;  
a=int(input())
b=int(input())
d = Derived()  
print(d.Summation(a,b))  
print(d.sub(a,b))  
print(d.Mul(a,b))  
```

### OUTPUT
![image](https://github.com/user-attachments/assets/facbb43c-010a-4f55-9755-6cce64096e38)


### RESULT
Thus the Python Program to Calculate Add, sub & Multiplication using Multiple Inheritance has been executed successfully.
