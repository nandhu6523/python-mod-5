
## Destructor

### AIM  

To create a Python to Add the destructor in the following python code.

### ALGORITHM

1. Begin the program.  
2. Define a class Fruits with a __del__ method that prints "Fruits deleted" when an object is deleted.
3. Create an object a of the Fruits class.
4. Delete the object a using del which calls the __del__ method and prints "Fruits deleted".
5. Create another object a, and assign it to a new object b.
6. Delete object b using del which also calls the __del__ method and prints "Fruits deleted".
7. Finally, delete object a using del, triggering the __del__ method again and printing "Fruits deleted"
8. Terminate the program.

### PROGRAM

```

class Fruits:
    def __del__(self):
        print("Fruits deleted")
a = Fruits()
del a
a = Fruits()
b = a
del b
del a

```

### OUTPUT

![image](https://github.com/user-attachments/assets/e498f876-8ab1-4df4-84d6-8c8da1a6ccad)

### RESULT

Thus the Python to Add the destructor in the following python code was successfully created.
