# CSC-461-Assignment
1. Fixed Dynamic:
What It Is: Memory is set aside at runtime with a size that can’t be changed later.
Example: Think of an array where you know how many items it will hold from the start.
When to Use: Good for situations where you know the amount of data you’ll be working with ahead of time.
2. Stack Dynamic:
What It Is: Memory is allocated while the program is running, specifically for temporary variables inside functions.
How It Works: The memory is automatically freed up when the function finishes running.
Benefits: Fast and efficient because it uses a simple system for managing memory.
3. Fixed Heap Dynamic:
What It Is: Memory is set aside in the heap at runtime, but once allocated, its size stays the same.
Common Usage: Used for objects or arrays that you don’t need to resize after creating them.
Things to Consider: Can lead to memory fragmentation over time, which might slow down performance.
4. Heap Dynamic:
What It Is: Memory is allocated in the heap and can grow or shrink while the program is running.
Example: Like ArrayLists in Java or dynamic arrays in JavaScript that can change size as needed.
Flexibility: Great for handling data when you’re not sure how much you’ll need.

Comparing Java and JavaScript:
| Feature              | **Java**                                            | **JavaScript**                                      |
|----------------------|-----------------------------------------------------|-----------------------------------------------------|
| **Type**             | Object-oriented, compiled language                 | Interpreted scripting language                      |
| **Runs on**          | Java Virtual Machine (JVM)                         | Web browsers and Node.js                           |
| **Syntax**           | Statically typed (must declare types)              | Dynamically typed                                  |
| **Use Cases**        | Backend systems, Android apps, enterprise software | Web development (front-end + back-end with Node.js)|
| **Performance**      | Typically faster due to compiled nature            | Slower, but fast enough for web applications        |
| **Concurrency**      | Built-in multithreading                            | Uses event loop and async callbacks                 |
| **File Extension**   | `.java`                                             | `.js`                                               |
| **Learning Curve**   | Steeper                                             | Easier for beginners                                |


Conclusion:
Java: A strict language that keeps things organized with clear rules about memory.

JavaScript: A more flexible language that makes it easier to work with changing amounts of data.
Feel free to ask if you need more changes!

