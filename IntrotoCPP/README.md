# Introduction to C++: 
**Objectives of each exercise and the name of the concept/lesson being learned**

## Credit
The original content belongs to [SoloLearn](https://www.sololearn.com). This repository is for personal educational use, and no copyright infringement is intended.

### **My First Code Coach (Statements):**

Let's code for real!

The given program should output the text: "My first C++ Code Coach!".

But something is wrong.

Task: Complete the code to generate the required output.

### **Outputting a Quote (Program Structure):**

Let's code for real!

You need to create a program that outputs a quote by the creator of C++, Bjarne Stroustrup.

The quote is: "Proof by analogy is fraud."

Task: Complete the code to generate the required output.

### **Smiley Face (Variables):**

The given code declares a variable with a value that is a representation of a smiley face using the @ character.

Task: Complete the code to output the value of the variable and check out the result!

### **Contact Info (Data Types):**

The given code declares some variables, then outputs them.

However, the code is missing the data types of the variables.

Task: Complete the code by adding the corresponding data types of the variables, based on the values assigned to them.

*Do not change the values of the variables, as they are needed to match the required output.*

### **Painting a Wall (Math):**

You are painting a rectangular wall and need to calculate the area in order to buy the necessary amount of paint.

The variables length and height define the size of the wall.

Task: Calculate and output the area of the wall.

*Hint: The area of the wall is its length multiplied by the height.*

### **Shopping (Comments):**

A local electronics shop has a great deal for notebooks.

You want to buy as many notebooks as you can afford. For that, you need to calculate how many notebooks you can buy with the amount in your bank account and how much money will be left over.

The given code includes comments as instructions for two tasks you need to complete.

Follow the instructions to solve this code coach!

### **Taking Input (Taking Input):**

Now that we know how to take input from the user, we can make more interactive programs!

Let's change one of our previous examples, where we calculated the area of a wall, and use the length and height values as input.

Task: Complete the code to take the length and height values as input, then calculate and output the area by multiplying them.

### **Club Entrance (Conditionals):**

You are making an app to control the entrance to a club.

Only clients who are 16 or older are allowed to enter.

Task: Take the age of the client as input, then output "Welcome", in case it's greater or equal to 16, and "Not allowed", if it's not.

For example, if the user enters 28 as their age, the output should be "Welcome".

*Output the corresponding message exactly as mentioned above, with a capital starting letter.*

### **Coffee Machine (The switch statement):**

*PRACTICE EXERCISE*:
Coffee Machine
A coffee machine makes 4 types of coffee:

Espresso
Americano
Cappuccino
Latte

Task: Create a program that outputs the correct coffee type based on the user's choice.

The choice variable is taken from input and is a number that corresponds to the coffee type.

### **Playground Tickets (Multiple Conditions):**
You are making an app to control the entrance of a playground and output the ticket category based on the age of the customer.

There are 3 categories of tickets:

Free: Ages 0-3 get free tickets
Discounted: Ages 4-6 get discounted tickets.
Normal: Ages 7+ get a normal ticket.

Task: Take the age of the customer as input, then output the ticket category corresponding to that age.

For example, if the user enters 5 as the age, the output should be "Discounted".

### **Countdown (while Loops):**
Create a timer program that will take the number of seconds as input, and countdown to 0.

Here is a sample output for the input 5:

5
4
3
2
1
0

*Note that the output should also include the number 0 and have each number on a new line.*

### **Sum (for Loops):**

You need to create an app that calculates the sum of the numbers 1 to N, where N is taken from input.

For example, for the number 5, the output should be 15, because 1+2+3+4+5=15.

### **Alphabet (Arrays):**
The given code declares an array that holds the letters of the English alphabet.

Task: Take a number as input and output the letter from the array that corresponds to that index.

### **Total Price (Looping through Arrays):**
You are making an app for an online shopping portal. 

The given code declares an array, which stores prices of an order.

You need to complete the code to calculate and output the total of the order.

*Hint: Use a for-each loop to iterate over the array and calculate the sum of all items in a variable.*

### **Game Map (Multidimensional Arrays):**
You are making a game.

The map of the game is defined as a two-dimensional array, which stores 0 and 1 values.

0 corresponds to the area of the map that is free, while 1 represents a player on the map.

Task: Take two integers as input, the first representing the row, the second - the column.

Then output the corresponding value from the map array

### **Average Age (Pointers):**

The given code declares an array called ages, which stores the ages of all employees of a company.

The code also includes a for loop that outputs the array. 

Task: Modify the code to calculate and output the average age of the employees. You do not need to output the array.

*Hint: To calculate the average, first calculate the sum of all ages, then divide it by their count. The output should be an integer.*

### **An Array From Input (Dynamic Memory):**
Dynamic memory allocation is useful in many situations, such as when your program depends on input. As an example, when your program needs to read an image file, it doesn't know in advance the size of the image file and the memory necessary to store the image.

* Memory is allocated using the <b>new</b> keyword: int* p = new int[size];
* After the allocated memory is no longer needed, we can free it up using delete: delete[] p;
  
### **Loading... (Functions):**
It’s very common to have a "preloader" component, especially in multifunctional apps and websites.

Task: Complete the given function to output "Loading...", then call it

### **Chat Bot v2 (Function Parameters):**
Let's make our chat bot a bit more advanced using parameters!

The bot() function has to take 2 parameters: one integer called mode, and a string called name.

The given code takes the values for the arguments as input and passes them to the bot() function. 

Modify the bot() function to take the given 2 parameters and generate the output using the following logic:

* In case mode is 1, the output should be "Welcome, name!", where name is the parameter’s value.
* In case mode is 2, the output should be "Goodbye, name!".
* If mode has any other value, the output should be "Try again".

### **How many seconds? (Returning from Functions)**
You are making an app to calculate how many seconds there are in a given number of days.

The given code takes the number of days as input, passes it to the toSeconds() function as the parameter, assigns the result to a variable, and outputs it.

Task: Create the toSeconds() function, which takes the days as its parameter, calculates and returns the number of seconds.

*Hint: To calculate the seconds in a given number of days, multiply it by 24 to get hours, then by 60, to get minutes, then by another 60, to get the seconds.*

### **Decimal Days to Seconds (Overloading Functions)**
We need to modify our days to seconds converter app to also work with decimal days.

Task: Overload the given toSeconds() function to take double days as its parameter and return the number of seconds as a double.

*Do not modify the code in main(). It calls both versions of the function, one with an int, another one with a double.*

