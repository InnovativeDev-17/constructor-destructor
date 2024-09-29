# constructor-destructor
### Constructors and Destructors in C++

**Aim:** To explore the functionality of constructors and destructors.

**Theory:**
Constructors and destructors are special member functions in C++ that manage the lifecycle of objects. A constructor is automatically called when an object is instantiated, allowing for the initialization of its member variables and resource allocation, ensuring the object is in a valid state. Conversely, a destructor is invoked when an object is destroyed, facilitating the release of resources and cleanup operations, such as deallocating memory or closing file handles. This prevents resource leaks and promotes efficient memory management. Together, these functions support robust object lifecycle management, adhering to the principles of encapsulation and resource management in Object-Oriented Programming (OOP).

### Constructors

A constructor is a special member function that automatically executes when an object of the class is created. Its main purpose is to initialize the object's properties or allocate necessary resources. Constructors can be classified into three primary types:

1. **Default Constructor:** A constructor that either has no parameters or has parameters with default values.
   
2. **Parameterized Constructor:** This type accepts one or more parameters, allowing the programmer to initialize an object with specific values during creation.

3. **Copy Constructor:** A copy constructor initializes a new object as a duplicate of an existing object. It takes a reference to an object of the same class as its parameter.

### Destructors

A destructor is a special member function that is automatically called when an object of the class is destroyed. Its main purpose is to release resources that the object may have acquired during its lifetime, such as memory or file handles.

- **Purpose:** To free resources allocated to the object.
- **Characteristics:** A class can only have one destructor, which cannot be overloaded. It is invoked in the reverse order of the constructors.

### Algorithm for Default Constructor

1. **Start Class Definition**
2. **Define a class** named `Construct`.
3. **Declare public member variables:** `int a` and `int b`.
4. **Implement a Default Constructor:** 
   - Initialize `a` to 10.
   - Initialize `b` to 20.
5. **Display Method:**
   - Define a method `void display()` to print the values of `a` and `b` in the format: `"a = [value of a]" "b = [value of b]"`.
6. **Main Function:** 
   - Create an instance of the `Construct` class named `constructor`.
   - Call the `display()` method on `constructor` to output the values of `a` and `b`.
7. **End.**
