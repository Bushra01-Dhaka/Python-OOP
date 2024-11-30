# OOP Basic Questions

## What do you mean by OOP?

OOP (Object-Oriented Programming) is a programming paradigm based on the concept of "objects," which are instances of classes. It allows developers to structure programs by bundling related data and methods (functions) together. The four main principles of OOP are:
- **Encapsulation**: Bundling data (attributes) and methods (functions) into a single unit or object and restricting access to some of the object's components.
- **Abstraction**: Hiding the complex details and showing only the necessary parts of the object.
- **Inheritance**: Allowing a class to inherit properties and behaviors (methods) from another class.
- **Polymorphism**: The ability to present the same interface for different data types or objects, meaning one function can work in different ways.

OOP helps in making code more reusable, scalable, and easier to maintain.

---

## Define Class
Class is a blueprint for creating objects. Before creating an object, a class is created.

## Define Objects
Object is an instance of a class.

## Define Constructor
It is a special method in Python that gets called automatically when an object is created. In Python, the `__init__` function is called the constructor. It is also used to initialize attributes of that object.

## Define Destructor
It is a method that is used when we want to delete the entire object or a specific property of that object. It is denoted in Python by `del`.

Example:
```python
s1 = Person(“Salis Khan”)
print(s1.name)   # Output: Salis Khan
del s1.name      # Deletes the name attribute of that object
print(s1.name)   # No object available as name
