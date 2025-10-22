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

## 💻 Program :
class Rectangle:
      def _init_(self, length, breadth):
          self.__length = length
          self.__breadth = breadth
          print("Length:", self.__length)
          print("Breadth:", self.__breadth)
  
  rect = Rectangle(10, 5)  class Rectangle:
      def _init_(self, length, breadth):
          self.__length = length
          self.__breadth = breadth
          print("Length:", self.__length)
          print("Breadth:", self.__breadth)
  
  rect = Rectangle(10, 5)

## Output :
![WhatsApp Image 2025-10-22 at 08 41 09_987f57fc](https://github.com/user-attachments/assets/b6abac60-b4c1-4100-b0d4-e14aefc42030)


## Result
