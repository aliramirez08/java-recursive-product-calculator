# Recursive Product Calculator (Java)

This project was built to strengthen my understanding of recursion and core Java programming concepts. It calculates the product of five user-input integers using a recursive approach, where each call multiplies the current number by the result of the next recursive call until reaching the base case. This demonstrates how recursion can break down a problem into smaller steps while maintaining clean, modular code.

## Features

- Prompts user for integer input
- Uses recursion to calculate product
- Includes input validation
- Modular structure with clear function separation

## Concepts Demonstrated

- Recursion
- Call stack behavior
- Base case and recursive case
- Input validation

## Technologies Used

- Java
- JDK 11+

## Project Structure

- `RecursiveProduct.java` – Main program with recursive logic

## How to Run

### Prerequisites
- Java Development Kit (JDK 11+)
- Any Java IDE or terminal

### Steps
1. Clone or download the repository
2. Navigate to the project directory
3. Compile the program:
```bash
javac RecursiveProduct.java
```
4. Run the program:
```bash
java RecursiveProduct
```

### Example

```text
Input: 2 3 4 5 6
Output: 720
```

## What I Learned
This project helped me understand how recursion works by breaking a problem into smaller repeated steps. I also learned the importance of defining a proper base case to prevent infinite recursion.

## Future Improvements
- Allow dynamic number of inputs instead of fixed 5
- Add better error handling for invalid input

### Screenshots

![RecursiveProductSource1](screenshots/RecursiveProductSource.png)

![RecursiveProductOutput](screenshots/RecursiveProductOutput.png)
