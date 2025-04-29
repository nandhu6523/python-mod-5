 
## Multi-level Inheritance

### AIM  

To write a Python program to Get the name, age and location of a person and display using Multilevel inheritance.

### ALGORITHM

1. Start the program.
2. Define class Name with method name() to set self.name from the global variable name.
3. Define class Age (inheriting Name) with method age() to set self.age from the global variable age.
4. Define class Location (inheriting Age) with method location() to set self.location from the global variable location.
5. Define class Person (inheriting Location) with method display() to print self.name, self.age, and self.location.
6. Input name, age, and location from the user.
7. Create an object of class Person.
8. Call methods name(), age(), and location() to set values.
9. Call display() method to show the collected details.
10. Terminate the program.

### PROGRAM

```

class Name:
    def name(self):
        self.name=name
class Age(Name):
    def age(self):
        self.age=age
class Location(Age):
    def location(self):
        self.location=location
class Person(Location):
    def display(self):
        print(f"{self.name} {self.age} {self.location}")
name=input()
age=int(input())
location=input()
obj=Person()
obj.name()
obj.age()
obj.location()
obj.display()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/0d578f73-5a8e-4c2e-b2ac-5691858e0bbf)

### RESULT

Thus the Python program to Get the name, age and location of a person and display using Multilevel inheritance was successfully created.
