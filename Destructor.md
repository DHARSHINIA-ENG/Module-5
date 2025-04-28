# Exp.No:22  
## Destructor

### AIM  
To Add the destructor in the following python code to delete the instance of the class.

### ALGORITHM

1. Begin the program.
2. Define a class named Student.
3. Inside the class, define the __init__ method to initialize name and age.
4. Assign the parameters name and age to instance variables.
5. Define a method printDetail to print the student's name and age.
6. Define a destructor method __del__ to print a message when the object is deleted.
7. Create an object s1 of class Student with name "Vishvajit Rao" and age 22.
8. Call the method printDetail() using object s1.
9. Delete the object s1 using the del statement.
10. The destructor __del__ is automatically called and prints the deletion message.
9. Terminate the program.

### PROGRAM
```
class Student:
	def __init__(self, name, age):
		self.name = name
		self.age = age

	def printDetail(self):
		print(f"My name is {self.name} and I am {self.age} years old.")

	def __del__(self):
	    print(f"{self.name} student is deleted.")


s1 = Student("Vishvajit Rao", 22)
s1.printDetail()
del s1
```
### OUTPUT
![Screenshot 2025-04-27 165149](https://github.com/user-attachments/assets/99af972d-6c00-4279-8169-5ed0f1083f4e)
### RESULT
Thus Add the destructor in the following python code to delete the instance of the class has been successfully implemented.
