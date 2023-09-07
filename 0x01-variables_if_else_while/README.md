# C - Variables, if, else, while 🚀

📝 Explore these notes to master the art of if-else statements, for loops, while loops, and variable handling in C programming. 

### Basics of C Programming
- [📦 Variables and Constants: Holding Information](#variables-and-constants)
- [🏷️ Variable Declarations: Giving Names to Things](#variable-declarations)
- [📝 Assigning Values: Filling the Boxes](#assigning-values)
- [🖨️ Printing Variables: Showing Off Your Data](#printing-variables)

### Decision Making in C
- [🤔 If Statements: Making Choices](#if-statements)
- [🔀 Logical Operators: Making Decisions](#logical-operators)
- [🔗 Relational Operators: Comparing Values](#relational-operators)
- [🟢 TRUE and FALSE: Understanding Boolean Values](#boolean-values)

### Control Flow in C
- [🔄 For Loops: Repeating Tasks a Known Number of Times](#for-loops)
- [🔄 While Loops: Repeating Tasks Until a Condition is Met](#while-loops)
- [🔄 Using Variables with Loops: Dynamic Data](#variables-with-loops)

### Practical C Programming
- [🧮 Arithmetic Operators: Crunching Numbers!](#arithmetic-operators)
- [🖨️ Printing with Printf: Making It Look Good](#printing-with-printf)
- [🌐 ASCII Character Set: Cracking the Code](#ascii-character-set)
- [🚩 GCC Flags: Navigating Compiler Options](#gcc-flags)

Let's dive into each topic one by one!

### 📦 Variables and Constants: Holding Information <a name="variables-and-constants"></a>

Think of variables as boxes where you can store information. Imagine you have a box labeled "age," and you can put your age in it. In C, you declare a variable by specifying its type, like `int` for integers or `char` for characters.

#### Example:
```c
int age = 25; // An integer variable named 'age' holding the value 25
char grade = 'A'; // A character variable named 'grade' holding 'A'
```

Now, constants are like boxes that cannot change their contents once you put something inside. It's like a "PIZZA" box that will always contain a pizza. In C, you create constants using the `const` keyword.

#### Example:
```c
const double PI = 3.141592; // A constant named 'pi' with the value 3.141592
```

### 📝 Variable Declarations: Giving Names to Things <a name="variable-declarations"></a>

Declaring variables means giving them names and types. It's like labeling your boxes so you know what's inside.

#### Example:
```c
int quantity; // Declaration without initialization
float discount = 0.1; // Declaration with initialization
```

### 🔄 Assigning Values: Filling the Boxes <a name="assigning-values"></a>

Assigning values to variables is like putting things into your boxes. You decide what goes inside each one.

#### Example:
```c
int apples;
apples = 5; // Assigning a value to the variable
```

### 🖨️ Printing Variables: Showing Off Your Data <a name="printing-variables"></a>

Use `printf` to display the contents of your variables. It's like taking a picture and showing it to the world.

#### Example:
```c
int age = 30;
printf("I am %d years old.\n", age);
```


### 🔀 If Statements: Making Choices <a name="if-statements"></a>

If-else statements help your program make decisions, just like you do in real life. Imagine deciding whether to take an umbrella based on the weather forecast. If it's raining, you take the umbrella; otherwise, you don't.

#### Example:
```c
int weatherForecast = 1; // 1 means rain, 0 means no rain
if (weatherForecast == 1) {
    printf("Take an umbrella!\n");
} else {
    printf("Leave the umbrella at home.\n");
}
```
### 🧩 Logical Operators: Making Decisions <a name="logical-operators"></a>

Logical operators (&&, ||, !) are your tools for making decisions in your code. They help you combine and evaluate conditions. Think of them as the "AND," "OR," and "NOT" buttons in a logic puzzle.

#### Example:
```c
int x = 5;
int y = 10;
if (x > 0 && y < 20) {
    // This condition is true because both x and y satisfy their respective conditions
    // Code inside this block will execute
}
```

### 🤝 Relational Operators: Comparing Values <a name="relational-operators"></a>

Relational operators (>, <, >=, <=, ==, !=) are your comparison tools. They help you compare values, just like comparing prices when shopping.

#### Example:
```c
int a = 10;
int b = 20;
if (a > b) {
    // This condition is false because a is not greater than b
    // Code inside this block will not execute
}
```

### 🧐 TRUE and FALSE: Understanding Boolean Values <a name="boolean-values"></a>

In C, TRUE is any non-zero value, and FALSE is zero. It's like a light switch; 0 is OFF (FALSE), and everything else is ON (TRUE).

#### Example:
```c
int isSunny = 1; // TRUE (non-zero)
int isRaining = 0; // FALSE (zero)
```

### For Loops: Repeating Tasks a Known Number of Times <a name="for-loops"></a>

For loops are like a recipe that tells you to bake cookies for 10 minutes. You know exactly how many times you need to perform a task. For example, printing numbers from 1 to 5.

#### Example:
```c
for (int i = 1; i <= 5; i++) {
    printf("Number: %d\n", i);
}
```

Here, `i` acts like a kitchen timer. It starts at 1 and counts up to 5, helping you repeat the task five times.

### ⏳ While Loops: Repeating Tasks Until a Condition is Met <a name="while-loops"></a>

While loops are like checking your phone for messages until you see an important one. You keep doing something until a condition is satisfied. Let's say you're waiting for a text from your friend.

#### Example:
```c
int receivedMessage = 0; // 0 means no message received
while (receivedMessage == 0) {
    printf("Checking for messages...\n");
    // Check for a message (not in the code, but imagine it)
    // If you receive a message, set receivedMessage to 1
}
printf("You received an important message!\n");
```

In this case, you keep checking for messages until you finally receive an important one.

### 🔄 Using Variables with Loops: Dynamic Data <a name="variables-with-loops"></a>

You can use variables inside loops to work with changing data. It's like adjusting the speed of a fan based on the room temperature.

#### Example:
```c
int temperature = 25;
while (temperature > 20) {
    printf("Temperature: %d\n", temperature);
    temperature--;
}
```

### 🧮 Arithmetic Operators: Crunching Numbers! <a name="arithmetic-operators"></a>

In C programming, arithmetic operators (+, -, *, /, %) are your tools for performing mathematical operations on integers. These operators allow you to add, subtract, multiply, divide, and find remainders. They are like the buttons on a calculator for solving math problems in your code.

#### Example:
```c
int result = 10 + 5; // Addition: result is 15
int difference = 20 - 8; // Subtraction: difference is 12
int product = 6 * 7; // Multiplication: product is 42
int quotient = 100 / 5; // Division: quotient is 20
int remainder = 17 % 4; // Modulus (remainder): remainder is 1
```

### 🖨️ Printing with Printf: Making It Look Good <a name="printing-with-printf"></a>

Printf not only shows data but also helps you format it nicely. It's like designing a beautiful poster for your event.

#### Example:
```c
double price = 19.99;
printf("Product price: $%.2lf\n", price);
```

### 🌐 ASCII Character Set: Cracking the Code <a name="ascii-character-set"></a>

Imagine the ASCII character set as a secret code for characters within the world of computers. This set assigns a unique numerical value to each character, much like how we might associate numbers with our favorite emojis to quickly identify and use them.

For instance, let's take the character 'A.' In the ASCII code, 'A' corresponds to a specific numeric value. You can unveil this code by casting the character 'A' to an integer (int), as shown in the example below:

#### Example:
```c
char letter = 'A';                 // Define a character variable 'letter' with the value 'A'
int asciiValue = (int)letter;      // Convert 'letter' to its ASCII numeric value
printf("Character: %c, ASCII Value: %d\n", letter, asciiValue);
```

In this example, we start with the character 'A,' and through the `(int)` casting, we reveal its ASCII numeric value. When you run this code, it will display both the character 'A' and its corresponding ASCII value.

Understanding the ASCII character set is like having a secret decoder ring for characters in the digital world. It enables you to work with characters in a way that computers understand, opening up a world of possibilities for text processing and manipulation in C programming.

### 🚩 GCC: Your Compiler Companion <a name="gcc-flags"></a>

GCC, or the **GNU Compiler Collection**, is a versatile compiler for multiple programming languages like C, C++, and Fortran. Its primary role is to convert your human-readable source code into machine-executable programs. GCC is known for its portability, optimization capabilities, and support for debugging, making it an essential tool for software development across different platforms and languages. It's open-source, backed by a robust community, and a crucial component in your programming toolkit.

GCC flags (-m32 and -m64) are like choosing different lanes on a highway. They determine whether your code runs in 32-bit or 64-bit mode.

#### Example:
```sh
gcc -m32 myprogram.c // Compile for 32-bit
gcc -m64 myprogram.c // Compile for 64-bit
```

---
Keep your curiosity ignited and your code bug-free. The programming universe awaits your exploration. 🌌 
Feel free to explore the projects at your own pace. If you have any questions or encounter difficulties, don't hesitate to open an issue on the issues page.

Cheers to your coding journey! 🖥️🔢🌟
