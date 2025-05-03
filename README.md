# 🐍 Python OOPs Concepts Project by Mohsin Raza

Welcome to my OOPs in Python project! This repository is created to help beginners understand **Object-Oriented Programming** using **real-world relatable examples** such as phones, vehicles, and more.

---

## 📌 Concepts Covered

- ✅ Class & Object
- ✅ Encapsulation
- ✅ Inheritance
- ✅ Polymorphism

---

## 📚 What is OOP?

Object-Oriented Programming (OOP) is a way to write code by organizing it into objects — just like we have real-world entities such as phones, students, or vehicles.

---

## 💡 Real-World Examples with Python Code

### 📱 1. Class & Object – Example: Mobile Phone

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


🔐 2. Encapsulation – Example: Phone Password Lock

class Phone:
    def __init__(self, brand):
        self.brand = brand
        self.__password = "1234"  # Private variable

    def unlock(self, pwd):
        if pwd == self.__password:
            print("Phone Unlocked!")
        else:
            print("Wrong Password")

p = Phone("Samsung")
p.unlock("1234")


🚘 3. Inheritance – Example: Car from Vehicle

class Vehicle:
    def start(self):
        print("Vehicle started")

class Car(Vehicle):
    def play_music(self):
        print("Music is playing")

c = Car()
c.start()
c.play_music()


🔁 4. Polymorphism – Example: Power Button Behavior

class Samsung:
    def press(self):
        print("Samsung powering on...")

class iPhone:
    def press(self):
        print("iPhone booting...")

def power_button(phone):
    phone.press()

power_button(Samsung())
power_button(iPhone())

🎯 Student Challenge
Try building your own:

Custom class (like Student, Laptop, or Animal)

Add:

__init__ constructor

A private variable (encapsulation)

An inherited class

Polymorphic method (same name, different behavior)

💻 Requirements
Python 3.x

Any Code Editor (VS Code, PyCharm, etc.)

🤝 Connect with Me
Made with ❤️ by Mohsin Raza
🔗 GitHub: https://github.com/mohsinraza23
📧 Email: mohsinraza23@gmail.com

📜 License
This project is open-source and free to use for learning purposes.
