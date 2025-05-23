## Metro App

# Java Data Structures Project – Graph and Heap

This project is a basic implementation of two important data structures in Java:

- `Graph_M.java`: Implements a graph using an adjacency matrix.
- `Heap.java`: Implements a min-heap using an array.

These implementations are useful for understanding how core data structures work and can serve as a foundation for more complex algorithms or applications.

## 📌 Features

### Graph_M.java
- Graph representation using a 2D adjacency matrix.
- Add and remove edges between vertices.
- Display the adjacency matrix.

### Heap.java
- Min-heap implementation using a simple array.
- Insert and delete elements while maintaining the heap property.
- Display current heap contents.

## 🚀 How to Run

### Requirements
- Java JDK 8 or higher installed on your system.
- A text editor or IDE (like VS Code, IntelliJ, or Eclipse).

### Steps

1. **Compile the Java files**  
Open your terminal or command prompt, navigate to the folder containing the `.java` files, and run:

```bash
javac Graph_M.java Heap.java

2. **Run the Java files**
If the files contain a main method, you can run them directly:

java Graph_M

or

java Heap
If no main method is provided, you can create your own Main.java file to test the classes.

### Example Main.java (Optional)

public class Main {
    public static void main(String[] args) {
        // Example usage of Graph
        Graph_M graph = new Graph_M(4);
        graph.addEdge(0, 1);
        graph.addEdge(1, 2);
        graph.display();

        // Example usage of Heap
        Heap heap = new Heap(10);
        heap.insert(20);
        heap.insert(5);
        heap.insert(15);
        heap.deleteMin();
        heap.display();
    }
}

To compile and run:

javac Main.java
java Main
