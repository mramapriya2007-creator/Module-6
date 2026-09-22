# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self):
        self.__length = 10
        self.__breadth = 5

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


obj = Rectangle()
obj.display()
```

## Output
<img width="730" height="315" alt="image" src="https://github.com/user-attachments/assets/231e890f-376d-4238-a9df-3ab1492bfad9" />


## Result
