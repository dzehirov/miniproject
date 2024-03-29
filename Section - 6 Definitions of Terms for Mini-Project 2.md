# Definitions of Terms for Mini-Project 2

### 1. How Python uses Indentation to control Flow
### Python uses indentation to determine which blocks of code are related. Unlike many other programming languages, python uses indentation for operation rather than code presentation. 

![Python Indentation Image](https://github.com/tejranu/miniproject/blob/master/Images/python_indents.png)

### 2. Don't Repeat Yourself
### Also know as DRY, the "Don't Repeat Yourself rule, is a coding principle. This principle aims to reduce repeating information multiple times. 

### 3. Design Patterns from Gang of Four
### Gang of Four Design Patterns are the authors of a book on design patterns for reusable object orientated software. Some examples of these design patterns include: builder, prototype and singleton. A builder is a pattern used to build complex objects in a certain order or by using a special algorithm. Prototypes are pattern used to create new and independent objects by using all properties and methods all ready defined. A singleton pattern is a pattern used to ensure that only one object of a particular class is created. 

### 4. Class
### In Python, a class is a tool in object orientated programming which contains methods and attributes which can be used by all objects that are created from the class. A class is similar to a blueprint.
![Python Class Image](https://github.com/tejranu/miniproject/blob/master/Images/python_class.png)

### 5. Object
### In Python, an object is an instantiation of a class. An object will have access to publicly defined methods and attributes that are defined. 
![Python Object Image](https://github.com/tejranu/miniproject/blob/master/Images/python_object.png)


### 6. Static
#### Static methods in Python are extremely similar to python class level methods, the difference being that a static method is bound to a class rather than the objects for that class. This means that a static method can be called without an object for that class. This also means that static methods cannot modify the state of an object as they are not bound to it. Let’s see how we can create static methods in Python.

### 7. Property/Attribute
#### In Python, property() is a built-in function that creates and returns a property object. where, fget is function to get value of the attribute, fset is function to set value of the attribute, fdel is function to delete the attribute and doc is a string (like a comment). An attribute in Python means some possessions that are linked with a particular type of object. Putting it differently, the attributes of a given object are that abilities and data that each object type integrally possesses.

### 8. Method
#### In Python, a method is a function that is available for a given object because of the object's type.

### 9. Exception
#### Python has many built-in exceptions which forces your program to output an error when something in it goes wrong. When these exceptions occur, it causes the current process to stop and passes it to the calling process until it is handled. If not handled, our program will crash

### 10. Unit Test
#### Unit testing, a testing technique using which individual modules are tested to determine if there are any issues by the developer himself. 

### 11. Constructor
A constructor in Python is used for instantiating an object. The task of a constructor is to initialize, or assign values to, the data members of the class when an object of class is created. The default constructor declaration starts with ***"def__init__(self)"*** and is followed by the body of the constructor. Constructors are always called when an object is created. The figure below shows an example of a constructor that is part of a class, along with some other elements mentioned above like method and class.

![Constructor Image](https://github.com/tejranu/miniproject/blob/master/Images/Constructor.PNG)

### 12. Factory
Factory, or the Factory Method, is used when we do not know what kind of objects we want to create in advance. Some objects can be created *only* at the time of execution after a user requests it. With the Factory Method, a class is able to defer instantiation to subclasses contained in the main class.

### 13. Decorator
Decorators are a powerful tool in Python because they allow the user to modify the behavior of a function or class. They can allow programmers to wrap one function in order to extend the behavior of another wrapped function without permanently changing it. Essentially, functions are taken as the argument into another function and then called inside the wrapper function.

### 14. Extend Class
Extend Class, also referred to as Class Inheritance, is simply creating a class within a class. These subclasses, or *Child Classes*, are able to "inherit" and make use of methods and variables that are present in their *Parent Class*.

### 15. CSV Files
CSV (Comma Separated Value) Files are a simple file format that is used to store tabular data like spreadsheets and databases. CSV is widely used in Python because of its simplicity. They store tabular data in plain text. Each line in the plain text represents a data record, which can contain one or more fields that are separated by a comma (hence the name). 

### 16. Reading Files
Python allows users to create a text file or use an existing one and have the system output the contents of the text file. The main part of the reading command comes in the form of ***"contents =f.read()"***, which is a part of a larger cluster of code. An example is shown below.

![Read File Image](https://github.com/tejranu/miniproject/blob/master/Images/Reading%20Files.PNG)
