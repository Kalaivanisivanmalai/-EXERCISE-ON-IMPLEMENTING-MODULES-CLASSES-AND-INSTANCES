# -EXERCISE-ON-IMPLEMENTING-MODULES-CLASSES-AND-INSTANCES
def add(a, b):
    return a + b

def sub(a, b):
    return a - b

print(add(10, 5))
print(sub(10, 5))

class Student:
    def __init__(self, name, marks):
        self.name = name
        self.marks = marks

    def display(self):
        print(self.name, self.marks)

s1 = Student("Ravi", 85)
s2 = Student("Anita", 92)

s1.display()
s2.display()
