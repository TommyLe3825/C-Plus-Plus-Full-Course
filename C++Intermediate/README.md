# **C++ Intermediate:**
**Objectives of each exercise and the name of the concept/lesson being learned**

## Credit
The original content belongs to [SoloLearn](https://www.sololearn.com). This repository is for personal educational use, and no copyright infringement is intended.

### **Example of a class (classes/access specifiers)**
Complete the given program. Define a class Bird which has one public method called makeSound(). That prints "chirp-chirp" when called.
Expected Output: chirp-chirp

*Don't forget to add access specifier - the public keyword.*

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

### **The Ninth Wave (Constructors)**

The given program defines a Painting class and creates an object using the constructor.

Fix the code so that the constructor takes the name as the argument and outputs it.

Sample Input:

Ocean

Sample Output:

Ocean

*The constructor should take one string as the argument and output it.*

### **Queue Management (Part 1)**

You are working on a Queue management system and need to create the class to hold the queue data, which are customer IDs (integers).

You make a **Queue** class, which has a size attribute, and an array, to hold the data of the queue.

The class has a **remove()** method to remove the front item of the queue, a **print()** method to output the queue.

You need to create an **add()** method for the Queue class, that will take an item and add it to the end of the queue.

The code needs to be fully working, so that the Queue declaration and manipulation code in main() works.

*Do not forget to increment the size after adding the item to the array.*
*Read the code carefully, before making any changes.*

### **Player Destructor (Destructors)**

You are making a game. The given code declares a Player class with a points member.

You need to add the destructor to the Player class, which should print the remaining points when the program finishes execution.

*Remember, the destructor is defined using the ~ symbol.*

### **Charge! (Selection Operator)**
You are creating a program to manage smartphones. The given code declares a **Phone** class, with its constructor and two methods: **use()** and **getCharge()**.
A **Phone** object is declared in main. Complete the code to call the **getCharge()** method using the correct selection operator.

*You can call a member function directly on the object, or using the pointer.*

### **Creating Classes (Constant Objects)**
You are making a **Number** class to handle different math operations. The class includes an integer member and a **square()** method.

You need to complete the **square()** method so that the given code executes successfully. 

The **square()** method should return the square of **num**.

*Note, that the object is constant, so it can call only constant methods.*

### **Sorting By Size (Member Initializers)**
You are making a program to store TVs with their width and height.
The given program declares a **TV** class with **height** and **width** members, an **area()** method, as well as a constructor that initializes the members of the class.

Complete the program by taking 2 integers as input, create a TV object by passing them to the constructor, and call the **area()** method.

*Note, that the constructor needs 2 integer values.*

### **Fast Engine** (Composition)
You are creating a program to make **Cars**. Each Car has an **Engine**, which is declared as a separate class.

Complete the given code to:

1. call the start() method of the Engine in the start() method of the Car,

2. create a Car object with the given Engine and inputs in main and call its start() method.

*Read and understand the given code first, before making any modifications.*

### **Find The Coordinates** (Friend Function)

You are given a Point class, which defines a **point** on a 2D grid (x, y).

The program creates a Point in main based on user input and calls the **shift()** function, which should increment the coordinates by the given step.

However, the code is not working, as the coordinates are **private**. 

Modify the code to fix it.

*Remember, functions declared as **friend** in a class are able to modify the private members.*

### **Tracking Your Bank Account** (Operator Overloading)


You are creating a program for a Bank to manage Accounts.

The given code declares an **Account** class which has a **balance** and **interest** members.

The bank asks you to add a new functionality to merge two accounts together, resulting in a new account with the sum of the balances and interests of the given accounts.

Overload the + operator to allow adding two **Account** objects, adding the **balances** and **interests**.

*The overloaded operator should return a new Account object, with the corresponding member values.*
