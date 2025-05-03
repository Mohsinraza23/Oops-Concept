# 🐍 Python OOPs Concepts for Beginners

Welcome to a beginner-friendly guide to **Object-Oriented Programming (OOP)** in Python!  
Understand OOP with **real-world examples** like phones, cars, and more.

Made with ❤️ by [Mohsin Raza](https://github.com/mohsinraza23)

---

## 📘 What is OOP?

OOP (Object-Oriented Programming) is a way to structure code using **classes** and **objects**, just like real-world entities.

| Concept         | Real-Life Example              |
|------------------|-------------------------------|
| Class            | Blueprint of a Car            |
| Object           | Actual Car built from class   |
| Encapsulation    | Locking private data          |
| Inheritance      | Child inherits traits         |
| Polymorphism     | Same function, different job  |

---

## 📌 Topics Covered

✅ Class & Object  
✅ Encapsulation  
✅ Inheritance  
✅ Polymorphism  

---

## 💡 Real-Life Code Examples

### 📱 1. Class & Object — Phone

```python
class Phone:
    def __init__(self, brand, price):
        self.brand = brand
        self.price = price

    def call(self):
        print(f"{self.brand} is calling...")

phone1 = Phone("Samsung", 50000)
phone2 = Phone("iPhone", 150000)

phone1.call()
phone2.call()
🔐 2. Encapsulation — Phone Password
python
Copy
Edit
class Phone:
    def __init__(self, brand):
        self.brand = brand
        self.__password = "1234"

    def unlock(self, pwd):
        if pwd == self.__password:
            print("Phone Unlocked!")
        else:
            print("Wrong Password")

p = Phone("Samsung")
p.unlock("1234")
🚗 3. Inheritance — Car from Vehicle

class Vehicle:
    def start(self):
        print("Vehicle started")

class Car(Vehicle):
    def play_music(self):
        print("Playing music...")

car1 = Car()
car1.start()
car1.play_music()
🔁 4. Polymorphism — Power Button
python
Copy
Edit
class Samsung:
    def press(self):
        print("Samsung Powering On...")

class iPhone:
    def press(self):
        print("iPhone Booting...")

def power_button(device):
    device.press()

power_button(Samsung())
power_button(iPhone())
🧪 Challenge for Students
Try building your own:

✅ Student or Laptop class

✅ Add private variables

✅ Create a child class

✅ Use polymorphism

💻 Requirements
Python 3.x

Code Editor (VS Code / PyCharm)

👨‍💻 Author
Name: Mohsin Raza

GitHub: mohsinraza23

Email: mohsinraza23@gmail.com

⭐ Support
If you found this helpful, feel free to star 🌟 the repo and share it!

📜 License
Open-source for educational use only.
