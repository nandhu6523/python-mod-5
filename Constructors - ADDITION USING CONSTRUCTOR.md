 
## Constructors - ADDITION USING CONSTRUCTOR

### AIM  

To write a Python using class to perform addition of three numbers using default constructor.

### ALGORITHM

1. Begin the program.  
2. Define a class add with an __init__ constructor that takes three numbers (num1, num2, num3) as arguments.
3. Store these numbers as instance variables.
4. Define a method result to calculate the sum of the three numbers and print the result.
5. Create an object of the add class by passing the three numbers (num1, num2, num3) as arguments.
6. Call the result method to display the sum.
7. Terminate the program.

### PROGRAM

```

class add:
    def __init__(self,num1,num2,num3):
        self.num1=num1
        self.num2=num2
        self.num3=num3
    def result(self):
        self.num=self.num1+self.num2+self.num3
        print(self.num)
num1=1000
num2=2000
num3=3000
Sum=add(num1,num2,num3)
Sum.result()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/ed945a45-2daf-4fd3-969f-c25325d0d25a)

### RESULT

Thus the Python using class to perform addition of three numbers using default constructor was successfully created.
