# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
class Fish:
    def type(self):
        return "fish"
class Shark(Fish):
	def type(self):
	    return "shark"
obj_goldfish=Fish()
obj_hammerhead=Shark()
for fishes in (obj_goldfish,obj_hammerhead):
    print(fishes.type())
```
## OUTPUT
<img width="453" height="217" alt="Screenshot 2025-10-20 171214" src="https://github.com/user-attachments/assets/65ee60d8-5a0e-4603-aa47-b9069fe2a0c5" />

## RESULT
Thus, to write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method is executed successfully.
