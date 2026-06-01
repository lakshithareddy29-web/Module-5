# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

class Student:
    def __init__(self):
        print("This is non parametrized constructor")
    def display_welcome(self, student_name):
        print(f"Hello {student_name}")
        
student_name_input = input()
student = Student()
student.display_welcome(student_name_input)

## Output
<img width="1056" height="257" alt="image" src="https://github.com/user-attachments/assets/7babcabe-1b2e-408c-83ac-0e65185e418f" />

## Result
Thus, the program is successfully executed
