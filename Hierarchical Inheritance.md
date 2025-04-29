

## Hierarchical Inheritance - EMPLOYEE DETAILS

### AIM  

To write a Python program to Display the Employee Details

EmpId , Emp Name., and Also Check Valid Employee or Not.

Note : If Employee id > 500000 Valid, Else Invalid

### ALGORITHM

1. Begin the program.
2. Define a class employee with a constructor __init__() that stores id and name.
3. Define a method details():
   If id is greater than 500000, print "Valid Employee" with id and name.
   Else, print "Invalid Employee" with id and name.
4. Input employee id and name from the user.
5. Create an object of the employee class using the input values.
6. Call the details() method to display if the employee is valid or invalid.
7. Terminate the program.

### PROGRAM
```

class employee:
    def __init__(self,id,name):
        self.id=id
        self.name=name
    def details(self):
        if id > 500000:
            print(f"({self.id}, '{self.name}')  Valid Employee")
        else:
            print(f"({self.id}, '{self.name}')  Invalid Employee")
id=int(input())
name=input()
obj=employee(id,name)
obj.details()

```

### OUTPUT  

![image](https://github.com/user-attachments/assets/461b5059-04b1-46e5-b78a-3378cd29e752)

### RESULT

Thus the write a Python program to Display the Employee Details was successfully created.
