# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
```
from abc import ABC, abstractmethod
import math

class Shape(ABC):
    @abstractmethod
    def calculate_area(self):
        pass


class Rectangle(Shape):
    def __init__(self):
        self.length = 10
        self.breadth = 5

    def calculate_area(self):
        return self.length * self.breadth


class Circle(Shape):
    def __init__(self):
        self.radius = 7

    def calculate_area(self):
        return math.pi * self.radius * self.radius


r = Rectangle()
c = Circle()

print("Rectangle area:", r.calculate_area())
print("Circle area:", c.calculate_area())
```

## Output
<img width="1409" height="615" alt="image" src="https://github.com/user-attachments/assets/12986ca2-29ff-47cb-93da-d87669b0e0a2" />


## Result
