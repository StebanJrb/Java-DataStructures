# Java Data Structures

A collection of classic data structure implementations in Java. This project aims to provide simple and understandable code examples for commonly used data structures, making it easy for beginners to learn and for developers to reference.

## Project Structure

```
Java-DataStructures/
├── src/
│   ├── datastructures/
│   │   ├── LinkedList.java
│   │   ├── Stack.java
│   │   ├── Queue.java
│   │   ├── BinaryTree.java
│   │   └── ...
│   └── Main.java
└── README.md
```

## What You’ll Find

- **Linked List** – Sequential collection of elements, supports efficient insertions/deletions.
- **Stack** – Follows Last-In-First-Out (LIFO) principle. Useful for undo operations, expression evaluation, etc.
- **Queue** – Follows First-In-First-Out (FIFO) principle. Useful for scheduling, buffering, etc.
- **Binary Tree** – Hierarchical data structure. Useful for fast search, insert, and delete operations.
- **More** – Additional structures may include hash tables, graphs, and heaps.

## How It Works

Each data structure is implemented as a Java class in the `datastructures` package. You can use these classes directly or study the code to better understand how they work.

### Example Usage

```java
// Import the data structure
import datastructures.Stack;

public class Main {
    public static void main(String[] args) {
        Stack<Integer> stack = new Stack<>();

        stack.push(10);
        stack.push(20);
        System.out.println(stack.pop()); // Output: 20
    }
}
```

### Running the Code

1. **Clone the repository:**
    ```bash
    git clone https://github.com/StebanJrb/Java-DataStructures.git
    cd Java-DataStructures
    ```
2. **Compile the code:**
    ```bash
    javac -d bin src/datastructures/*.java src/Main.java
    ```
3. **Run the main class:**
    ```bash
    java -cp bin Main
    ```

## Who Is This For?

- **Students** learning about data structures in Java.
- **Developers** who want reference implementations.
- **Anyone** preparing for coding interviews.

## Contributing

Feel free to open issues or submit pull requests to add more data structures or improve existing ones!

---

**Happy learning!**
