# Lab: 6.0.2

**Objective:**

- Understand the concept and importance of One-Dimensional Arrays in Java development.
- Learn how to implement One-Dimensional Arrays using Java's array syntax and utilities.
- Explore practical applications of One-Dimensional Arrays in real-world Java projects.
- Identify common pitfalls and best practices when working with One-Dimensional Arrays.
- Gain hands-on experience with a complete Java example that demonstrates One-Dimensional Arrays.

**Prerequisites:**

- Basic understanding of Java programming.
- Familiarity with primitive data types and variables in Java.

**What You'll Achieve:**

- Develop a solid understanding of One-Dimensional Arrays in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in array manipulation and basic algorithms.

**Assignment Details**

1. Open the provided `ArrayExplorer.java` file in your preferred Java development environment.
2. In the `main` method, you'll implement the following tasks:
   - Create an integer array of size 10 and populate it with random numbers between 1 and 100.
   - Print the array elements.
   - Calculate and print the sum of all elements in the array.
   - Find and print the maximum and minimum values in the array.
   - Calculate and print the average of the array elements.
   - Create a new array that contains the elements of the original array in reverse order.
   - Print the reversed array.
   - Search for a specific number in the array and print its index (or a message if not found).
3. Use appropriate Java array syntax and utilities (e.g., `java.util.Random` for generating random numbers).
4. Print clear, descriptive messages for each operation's result.

**Example Output**

```
Original Array: [45, 23, 78, 12, 90, 34, 56, 1, 67, 89]
Sum of elements: 495
Maximum value: 90
Minimum value: 1
Average of elements: 49.5
Reversed Array: [89, 67, 1, 56, 34, 90, 12, 78, 23, 45]
Searching for 34...
34 found at index 5
Searching for 100...
100 not found in the array
```

**Starter Code**

The `ArrayExplorer.java` file contains the following starter code:

```java
package academy.javapro.lab;

import java.util.Random;

public class ArrayExplorer {
    public static void main(String[] args) {
        // TODO: Implement array operations here

        // Hint: Use Random class to generate random numbers
        Random random = new Random();

        // TODO: Create and populate the array

        // TODO: Implement required operations
    }
}

```

**Hints**

- Use a for loop to iterate through the array elements.
- Remember that array indices start at 0 and go up to `array.length - 1`.
- When finding the maximum and minimum, initialize your variables with the first element of the array.
- For reversing the array, you can create a new array and populate it in reverse order.
- Use the enhanced for loop (for-each) when you don't need the index of elements.
- Be careful with integer division when calculating the average.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required array operations in the `ArrayExplorer.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.