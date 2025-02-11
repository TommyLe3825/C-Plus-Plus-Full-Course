# **C++ Intermediate:**
**Objectives of each exercise and the name of the concept/lesson being learned**

## Credit
The original content belongs to [SoloLearn](https://www.sololearn.com). This repository is for personal educational use, and no copyright infringement is intended.

-------------------------
### **Example of a class (classes/access specifiers)**
Complete the given program. Define a class Bird which has one public method called makeSound(). That prints "chirp-chirp" when called.

Expected Output: chirp-chirp

*Don't forget to add access specifier - the public keyword.*

-------------------------
### **Example of Encapsulation (Encapsulation)**
You are a supercar engineer and currently setting the engine's horsepower.

Complete the given program by completing methods to set and get the horsepower of the car object in order to output it.

The program should warn "Too much" if the inputted horsepower is above 800.

Sample Input: 
950

Sample Output:

Too much

950

*You should use the if statement directly inside the setter function.*

-------------------------
### **The Ninth Wave (Constructors)**

The given program defines a Painting class and creates an object using the constructor.

Fix the code so that the constructor takes the name as the argument and outputs it.

Sample Input:

Ocean

Sample Output:

Ocean

*The constructor should take one string as the argument and output it.*

-------------------------
### **Queue Management (Part 1)**

You are working on a Queue management system and need to create the class to hold the queue data, which are customer IDs (integers).

You make a **Queue** class, which has a size attribute, and an array, to hold the data of the queue.

The class has a **remove()** method to remove the front item of the queue, a **print()** method to output the queue.

You need to create an **add()** method for the Queue class, that will take an item and add it to the end of the queue.

The code needs to be fully working, so that the Queue declaration and manipulation code in main() works.

*Do not forget to increment the size after adding the item to the array.*
*Read the code carefully, before making any changes.*

-------------------------
### **Player Destructor (Destructors)**

You are making a game. The given code declares a Player class with a points member.

You need to add the destructor to the Player class, which should print the remaining points when the program finishes execution.

*Remember, the destructor is defined using the ~ symbol.*

-------------------------
### **Charge! (Selection Operator)**
You are creating a program to manage smartphones. The given code declares a **Phone** class, with its constructor and two methods: **use()** and **getCharge()**.
A **Phone** object is declared in main. Complete the code to call the **getCharge()** method using the correct selection operator.

*You can call a member function directly on the object, or using the pointer.*

-------------------------
### **Creating Classes (Constant Objects)**
You are making a **Number** class to handle different math operations. The class includes an integer member and a **square()** method.

You need to complete the **square()** method so that the given code executes successfully. 

The **square()** method should return the square of **num**.

*Note, that the object is constant, so it can call only constant methods.*

-------------------------
### **Sorting By Size (Member Initializers)**
You are making a program to store TVs with their width and height.
The given program declares a **TV** class with **height** and **width** members, an **area()** method, as well as a constructor that initializes the members of the class.

Complete the program by taking 2 integers as input, create a TV object by passing them to the constructor, and call the **area()** method.

*Note, that the constructor needs 2 integer values.*

-------------------------
### **Fast Engine (Composition)**
You are creating a program to make **Cars**. Each Car has an **Engine**, which is declared as a separate class.

Complete the given code to:

1. call the start() method of the Engine in the start() method of the Car,

2. create a Car object with the given Engine and inputs in main and call its start() method.

*Read and understand the given code first, before making any modifications.*

-------------------------
### **Find The Coordinates (Friend Function)**

You are given a Point class, which defines a **point** on a 2D grid (x, y).

The program creates a Point in main based on user input and calls the **shift()** function, which should increment the coordinates by the given step.

However, the code is not working, as the coordinates are **private**. 

Modify the code to fix it.

*Remember, functions declared as **friend** in a class are able to modify the private members.*

-------------------------
### **Tracking Your Bank Account (Operator Overloading)**

You are creating a program for a Bank to manage Accounts.

The given code declares an **Account** class which has a **balance** and **interest** members.

The bank asks you to add a new functionality to merge two accounts together, resulting in a new account with the sum of the balances and interests of the given accounts.

Overload the + operator to allow adding two **Account** objects, adding the **balances** and **interests**.

*The overloaded operator should return a new Account object, with the corresponding member values.*

----------------------------
### **Queue Management (Part 2)**
We continue to develop our Queue management system that we made in the previous module.

You are asked to add a new functionality: adding two queues together. The result should be a new queue, where the elements of the first queue come first, followed by the second queue's elements.

Given the **Queue** class, overload the + operator, so that the code in main works and successfully adds two queues.

*The overloaded operator should return a new **Queue** object, which contains the elements of the first queue, followed by the elements of the second queue.*

-------------------------
### **Doodling! (Inheritance)**
You are making a drawing application. The code you are given declares a **Shape** base class, and you are making separate classes for each shape that your application is going to support. 

Inherit the **Rectangle** class from the **Shape** class and call its **draw()** method. 

*Inherit using a colon and an access specifier.*

----------------------------
### **Inherited Fruit (Protected Members)**
You work at a grocery store and want to build an app to manage the products in the store.

You make a **Product** base class and separate classes for each product type.

Inherit the **Fruit** class from **Product** and make sure the given code works correctly.

*The code tries to access the private members of Product in the Fruit class. Fix it by applying the correct access specifier.*

------------------------------
### **Game Over! (Derived Class Constructor and Destructor)**
You are making a Quiz game. **The Quiz class inherits from the Game base class.**

Both classes have constructors, which output a Start message. 

Create destructors for each class, which will output "Game Over" in the **Game** class, and "Quiz Over" in the **Quiz** class, so that when the program executes, it outputs:

Game Started

Quiz Started

Quiz Over

Game Over

*The derived class destructor gets executed first, before the base class destructor.*

------------------------------
### **Another Cup Of Coffee (Polymorphism)**
Your friend made a program for a robot, which makes different drinks, including tea and coffee.

The code defines a **Drink** class, and separate **Tea** and **Coffee** classes. 

It tries to create a Tea and Coffee object, set their prices with the corresponding method and call their make() method.

However, the code does not work, as it has multiple errors.

Find the errors in the code and fix them, so that the program runs as expected.

*Remember, to call a method with a pointer, you need to use the -> operator, whereas on an object you need to use the dot operator.*

----------------------------
### **Roar! (Virtual Functions)**
You are making a program to manage an animal zoo. 

You have a base class **Animal**, and two subclasses: **Dog and Cat**. 

In main, you have an array of Animal pointers, where each pointer can hold a Dog or a Cat. 

The code loops through the array and calls the **speak()** method of the object, irrespective of its type. 

Complete the code by adding the **speak()** method to the **Animal** class, so that the code works and the corresponding methods get called correctly.

*This is an example of polymorphism in action: without knowing the subtype of the objects, you are able to call the speak() method, and the corresponding implementation is getting executed.*

--------------------------------
### **Going For A Ride (Abstract Classes/Pure Virtual Functions)**
You are given a **Vehicle** base class, and two subclasses, **Car** and **Bicycle**.

Both classes have a drive() method which is called in main, using **Vehicle** pointers.

Complete the Vehicle class, so that it correctly represents a Vehicle abstraction.

*Remember, an abstract class should include a pure virtual function, which the derived classes must implement.*

-----------------------------
### **Queue Management (Part 3)**
Your **Queue** class is up and working in a customer service company. The company opens up a new branch and asks you to make another version of the Queue for them. The only difference is the way the Queue is displayed: each number on a new line.

You decide to create a new class called **Queue2**, which is derived from the **Queue** class and overrides the **print()** method, outputting each element of the queue on a new line.

*Do not forget to change the access specifier of the Queue members, as they won't be inherited if private.*

------------------------------
### **Function Templates (Functions)**
You need to write a function, which returns the maximum of its two parameters, and it should work for different data types (integers, doubles, etc.)

Create a function template called **myMax()**, which takes two parameters and returns the larger one, so that the code in main works as expected.

Sample Input

4.2

8.1

Sample Output 

8.1

*Remember, the syntax for declaring a template function is **template <class T>***
