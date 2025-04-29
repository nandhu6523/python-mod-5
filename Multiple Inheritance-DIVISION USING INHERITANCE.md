

## Multiple Inheritance - DIVISION USING INHERITANCE

### AIM  

To write a Python program to Calculate Division using Inheritance.

### ALGORITHM

1. Start the program.
2. Define class A with method detail() to set self.a to the global variable a.
3. Define class B with method details() to set self.b to the global variable b.
4. Define class calc (inheriting from A and B) with a method div():
   Print self.a
   Print self.b
   Print the division result self.a / self.b.
5. Input two numbers (a and b) from the user.
6. Create an object of class calc.
7. Call methods detail(), details(), and div() using the object to perform and show the division.
8. Terminate the program.

### PROGRAM

```

class A:
    def detail(self):
        self.a=a
class B:
    def details(self):
        self.b=b
class calc(A,B):
    def div(self):
        print(" division value1 : ",self.a)
        print(" division value2 : ",self.b)
        print(" division value :",self.a/self.b)
    
a=int(input())
b=int(input())
obj=calc()
obj.detail()
obj.details()
obj.div()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/11a0e424-e920-49c4-97e3-d8ae5e1c0571)

### RESULT

Thus the Python program to Calculate Division using Inheritance was successfully created.

