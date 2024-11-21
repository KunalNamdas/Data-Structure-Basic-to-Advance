# **Data Structures** 

---

### **Chapter 1: Introduction to Data Structures**
- What are Data Structures?
- Importance and Applications of Data Structures
- Types of Data Structures (Linear and Non-Linear)
- Choosing the Right Data Structure

---

### **Chapter 2: Applications of Data Structures**
- Real-World Use Cases
- Data Structures in System Design
- Competitive Programming Problems
- Future Trends in Data Structures

### **Chapter 3: Complexity Analysis**
- Time Complexity and Space Complexity
- Big O Notation
- Amortized Analysis
- Best, Worst, and Average Case Scenarios

### **Chapter 4: Arrays**
- Introduction to Arrays
- Types of Arrays (1D, 2D, Multi-dimensional)
- Operations on Arrays (Traversal, Insertion, Deletion, Searching)
- Advantages and Limitations of Arrays

---

### **Chapter 5: Strings**
- String Basics
- Common String Operations (Concatenation, Substrings, Reversal)
- String Manipulation Algorithms
- Applications of Strings in Real-world Problems

---

### **Chapter 6: Linked Lists**
- Introduction to Linked Lists
- Types of Linked Lists:
  - Singly Linked List
  - Doubly Linked List
  - Circular Linked List
- Operations on Linked Lists (Insertion, Deletion, Traversal)
- Use Cases of Linked Lists

---


### Chapter 7: ArrayList in Java

- What is an ArrayList?
- Key Features of ArrayList
- Creating an ArrayList
- Common Operations with ArrayList
   - Adding Elements
   - Accessing Elements
   - Removing Elements
   - Modifying Elements
   - Iterating Through an ArrayList
   - Checking if an ArrayList Contains an Element
- Time Complexity of ArrayList Operations
- Advantages of ArrayList
- Disadvantages of ArrayList
- Use Cases of ArrayList

---

### **Chapter 8: Stacks**
- What is a Stack?
- LIFO Principle
- Stack Operations (Push, Pop, Peek)
- Implementation of Stacks (Array and Linked List)
- Applications of Stacks (Undo Feature, Expression Evaluation)

---

### **Chapter 9: Queues**
- What is a Queue?
- FIFO Principle
- Types of Queues:
  - Simple Queue
  - Circular Queue
  - Priority Queue
- Queue Operations (Enqueue, Dequeue, Peek)
- Applications of Queues (Task Scheduling, BFS)

---

### **Chapter 10: Hashing**
- Introduction to Hashing
- Hash Tables and Hash Functions
- Collision Handling (Chaining, Open Addressing)
- Applications of Hashing (Database Indexing, Caching)

---

### **Chapter 11: Trees**
- Basics of Trees
- Binary Trees
- Binary Search Trees (BST)
- AVL Trees and Red-Black Trees
- Applications of Trees (File Systems, Databases)

---

### **Chapter 12: Heaps**
- Introduction to Heaps
- Types of Heaps (Min-Heap, Max-Heap)
- Heap Operations (Insert, Delete, Heapify)
- Priority Queues using Heaps
- Applications of Heaps (Sorting, Scheduling)

---

### **Chapter 13: Graphs**
- Basics of Graphs
- Types of Graphs (Directed, Undirected, Weighted)
- Graph Representations (Adjacency Matrix, Adjacency List)
- Traversal Techniques (BFS, DFS)
- Applications of Graphs (Navigation, Social Networks)

---

### **Chapter 14: Searching Algorithms**
- Linear Search
- Binary Search
- Interpolation Search
- Advanced Searching Techniques

---

### **Chapter 15: Sorting Algorithms**
- Bubble Sort
- Selection Sort
- Insertion Sort
- Quick Sort
- Merge Sort
- Heap Sort
- Time Complexity Analysis of Sorting Algorithms

---

### **Chapter 16: Recursion**
- What is Recursion?
- Advantages and Limitations
- Recursive vs Iterative Solutions
- Examples: Factorial, Fibonacci, Tower of Hanoi

---

### **Chapter 17: Dynamic Programming**
- Basics of Dynamic Programming
- Difference Between Recursion and DP
- Common Problems:
  - Longest Common Subsequence (LCS)
  - Knapsack Problem
  - Matrix Chain Multiplication

---

### **Chapter 18: Backtracking**
- Introduction to Backtracking
- N-Queens Problem
- Subset Sum Problem
- Applications of Backtracking (Puzzle Solving)

---

### **Chapter 19: Advanced Data Structures**
- Tries (Prefix Trees)
- Segment Trees
- Fenwick Trees (Binary Indexed Trees)
- Disjoint Set Union (Union-Find)

---

### **Chapter 20: Graph Algorithms**
- Shortest Path Algorithms (Dijkstra, Bellman-Ford, Floyd-Warshall)
- Minimum Spanning Tree (Kruskal, Prim)
- Topological Sorting
- Network Flow (Ford-Fulkerson)

---

### **Chapter 21: String Matching Algorithms**
- Naive Pattern Matching
- Knuth-Morris-Pratt (KMP) Algorithm
- Rabin-Karp Algorithm
- Applications of String Matching

---


# **Chapter 1: Introduction to Data Structures**

### **What are Data Structures?**
Data structures are specialized formats for organizing, processing, storing, and retrieving data. They define the logical relationships between the data elements, which enables efficient data manipulation.  

#### **Examples**:
- A list of tasks (To-Do List) can be represented as an **Array**.
- A sequence of webpages visited in a browser is managed using a **Stack**.

---

### **Importance of Data Structures**
Efficient data structures are essential for designing algorithms that solve computational problems effectively.  
- **Speed**: Helps reduce time complexity for operations like search, insert, or delete.  
- **Memory Management**: Optimizes the use of memory resources.  
- **Scalability**: Enables handling of larger datasets effectively.  

---

### **Applications of Data Structures**
1. **Web Development**: HTML DOM (Tree) is used to represent web pages.  
2. **Databases**: Use Hash Tables, Trees, and Graphs for indexing and managing relationships.  
3. **Networking**: Graphs represent connections and routing paths.  
4. **Machine Learning**: Arrays, Matrices, and Trees are used for data representation and decision-making.

---

### **Types of Data Structures**
Data structures can be broadly classified into **Linear** and **Non-Linear** structures.  

#### **1. Linear Data Structures**  
- **Definition**: Data is organized in a sequential manner.  
- **Examples**:  
  - **Arrays**: Fixed-size data structure for storing homogeneous data.  
  - **Linked Lists**: Dynamic-sized collection where elements are connected using pointers.  
  - **Stacks**: Follows the **Last In, First Out (LIFO)** principle.  
  - **Queues**: Follows the **First In, First Out (FIFO)** principle.  

#### **2. Non-Linear Data Structures**  
- **Definition**: Data is organized hierarchically or in interconnected nodes.  
- **Examples**:  
  - **Trees**: Binary Trees, Binary Search Trees, AVL Trees.  
  - **Graphs**: Represent networks of connected elements.  

---

### **Choosing the Right Data Structure**
Selecting the right data structure is crucial for solving a problem efficiently.  

| **Problem Type**            | **Recommended Data Structure**     |  
|------------------------------|-------------------------------------|  
| Search for an element        | Binary Search Tree, Hash Table     |  
| Store hierarchical data      | Tree                               |  
| Manage sequential tasks      | Queue                              |  
| Navigate relationships       | Graph                              |  

---

### **Key Characteristics to Consider**
1. **Ease of Access**: How quickly can you retrieve an element?  
2. **Insertion/Deletion**: Are these operations frequent and need optimization?  
3. **Memory Usage**: Does the structure use memory efficiently?  
4. **Flexibility**: Can it adapt to changes in size or type?  

---

### **Example Use Cases**
#### **Case 1: Managing Web Pages (Browser Back/Forward Navigation)**  
- **Data Structure Used**: Stack.  
- **Reason**: Supports the LIFO principle.  
- **Explanation**: The last page visited is the first to be removed when moving back.  

#### **Case 2: Network Routing**  
- **Data Structure Used**: Graph.  
- **Reason**: Represents the network nodes and paths between them.  
- **Explanation**: Algorithms like Dijkstra's or BFS can find the shortest path between nodes.

---

### **Chapter Recap**
- **Definition**: Data structures are ways to organize and manage data for efficient operations.  
- **Importance**: Crucial for performance and scalability in software solutions.  
- **Types**: Linear (Array, Linked List, Stack, Queue) and Non-Linear (Tree, Graph).  
- **Key Considerations**: Access speed, flexibility, and memory usage determine the best choice.  

---

#  **Chapter 2: Applications of Data Structures**

Data structures are a fundamental part of computer science and have vast applications across different fields. From optimizing algorithms to designing complex systems, understanding and applying the right data structure is crucial for efficiency and scalability. This chapter delves into the real-world applications of data structures, their role in system design, their significance in competitive programming, and future trends in data structures.

---

#### **1. Real-World Use Cases of Data Structures**

Data structures are used in various real-world applications, from simple everyday software to complex systems that power our modern world.

##### **Examples:**

- **Databases:**
  - **B-trees** and **hash tables** are used to implement indexing mechanisms in databases, enabling fast searching, inserting, and deleting records.
  - **Example:** A database management system (DBMS) like MySQL or MongoDB uses B-trees to maintain an index for faster querying.

- **File Systems:**
  - **File Allocation Tables (FAT)** or **Inodes** are used to manage files and directories on a disk.
  - **Example:** Operating systems use data structures like **linked lists** and **trees** for managing directories, file paths, and file system integrity.

- **Social Networks:**
  - **Graphs** are used to represent social connections, such as followers, friends, and the relationships between them.
  - **Example:** In platforms like Facebook or Twitter, user profiles and the connections between them are modeled as graphs.

- **Compilers and Interpreters:**
  - **Stacks** and **trees** are widely used in parsing and interpreting programming languages.
  - **Example:** The syntax tree and expression tree built during the compilation process help in parsing and optimizing code.

- **Internet Routing:**
  - **Graphs** are used for finding the shortest paths between network routers or determining the best route for data transmission.
  - **Example:** The internet's routing algorithms, like **Dijkstra’s** or **Bellman-Ford**, use graph data structures to determine the optimal path.

- **E-commerce:**
  - **Heaps** are often used to maintain the priority queues in systems like product recommendation engines or fraud detection systems.
  - **Example:** Amazon uses heaps for efficient real-time product suggestions.

---

#### **2. Data Structures in System Design**

In system design, data structures play a key role in ensuring scalability, maintainability, and performance. Selecting the right data structure can lead to more efficient and optimized system architectures.

##### **Key Considerations:**
- **Performance Requirements:**
  - **Queues** and **stacks** are used in job scheduling, message passing, and network packet handling.
  - **Hash tables** or **trees** are used in systems requiring fast lookups, such as key-value stores or caches.
  
- **Memory Usage:**
  - **Trie** or **Radix Trees** are used in systems where space efficiency for storing strings is important, such as autocomplete and spell-checking.

- **Real-Time Systems:**
  - **Heaps** are essential for systems that prioritize the execution of tasks or jobs, such as CPU scheduling in operating systems.
  
- **Distributed Systems:**
  - **Graphs** are used in systems like blockchain and peer-to-peer networks where the structure of data is inherently distributed and decentralized.

- **Large-scale Data Processing:**
  - **Bloom filters** and **hashing** techniques are applied in distributed databases, where exact matches or membership tests need to be performed quickly with low memory usage.

---

#### **3. Data Structures in Competitive Programming**

Competitive programming challenges often require efficient use of data structures to solve problems in limited time. Efficient implementation and selection of the right data structure can dramatically affect the speed of solutions.

##### **Common Data Structures Used in Competitive Programming:**
- **Arrays and Lists:**
  - Used in problems that require random access to elements.
  - Example: Sorting algorithms, searching problems.

- **Stacks and Queues:**
  - Used for problems that require a last-in, first-out (LIFO) or first-in, first-out (FIFO) strategy.
  - Example: Expression evaluation, backtracking problems, breadth-first search (BFS).

- **Graphs:**
  - Widely used to solve problems related to networks, like finding shortest paths, cycles, or connected components.
  - Example: Social network problems, routing problems, traversal problems (DFS, BFS).

- **Heaps:**
  - Used for problems where the largest or smallest element is required frequently.
  - Example: Priority queue, job scheduling problems, finding the k-th largest element.

- **Hashing:**
  - Used to store data in a way that allows for constant-time complexity lookup.
  - Example: Detecting duplicates in an array, solving problems with constraints involving fast lookups.

- **Dynamic Programming:**
  - Involves using arrays or other data structures to store intermediate results to avoid recomputation.
  - Example: Knapsack problem, longest common subsequence, coin change problem.

##### **Example Problem:**
**Problem:** Find the shortest path in a weighted graph.
- Data Structures: **Graph**, **Priority Queue (Heap)**
- Algorithm: **Dijkstra’s Algorithm** is used to find the shortest path, where the graph is stored using an adjacency list, and the priority queue is used to process nodes in order of their distances.

---

#### **4. Future Trends in Data Structures**

Data structures continue to evolve with advances in technology, especially with the advent of big data, machine learning, and distributed systems. Future trends indicate more specialized data structures aimed at solving modern computational problems efficiently.

##### **Key Future Trends:**
- **Machine Learning Optimized Data Structures:**
  - With the rise of AI and machine learning, data structures will need to evolve to handle large datasets and perform well on machine learning algorithms.
  - **Example:** Specialized **tensors** in machine learning libraries like TensorFlow, which are designed to handle high-dimensional data efficiently.

- **Distributed Data Structures:**
  - As cloud computing and distributed systems grow, data structures will need to support data replication, fault tolerance, and parallel processing.
  - **Example:** **Distributed hash tables** (DHT) and **consistent hashing** used in distributed databases like Cassandra.

- **Quantum Data Structures:**
  - With the emergence of quantum computing, there is a need for new types of data structures to handle quantum data, such as **quantum trees** or **quantum lists**.

- **Persistent Data Structures:**
  - These data structures retain previous versions of data after updates, which is useful in systems that require undo/redo functionality or historical data tracking.
  - **Example:** **Immutable lists** or **trees** used in version-controlled data systems.

- **Blockchain and Cryptography Data Structures:**
  - Blockchain technology relies heavily on specialized data structures like **Merkle trees**, **cryptographic hash functions**, and **distributed ledgers** to maintain secure, decentralized records.

---

### **Summary:**

Data structures are pivotal in addressing real-world challenges, from system design to solving problems in competitive programming. Understanding how to apply data structures effectively in various contexts can lead to more efficient, optimized, and scalable solutions. Future trends in data structures will increasingly focus on handling large-scale data, distributed systems, machine learning applications, and quantum computing, ensuring that data structures evolve to meet the growing demands of technology.

---

# **Chapter 3: Complexity Analysis**

Complexity analysis is crucial in understanding the efficiency of an algorithm. By determining how the resources (such as time and space) grow as the input size increases, we can evaluate and compare different algorithms. 

This chapter covers the essential concepts of time complexity, space complexity, Big O notation, amortized analysis, and the different types of cases (best, worst, and average).

---

#### **1. Time Complexity and Space Complexity**

- **Time Complexity** refers to the amount of time an algorithm takes to complete, relative to the input size. It helps in analyzing how the runtime grows as the input size increases.
  
- **Space Complexity** refers to the amount of memory an algorithm uses relative to the input size. It considers the extra space required by the algorithm aside from the input itself.

---

#### **2. Big O Notation**

Big O notation is used to express the time and space complexity of an algorithm in a way that describes its behavior for large input sizes. It provides an upper bound for the runtime or space required.

- **O(1): Constant time/space**
  - The algorithm takes the same amount of time/space, regardless of the input size.
  - **Example:** Accessing an element in an array by index.

- **O(log n): Logarithmic time**
  - The algorithm's time/space grows logarithmically as the input size increases.
  - **Example:** Binary search algorithm.

- **O(n): Linear time/space**
  - The time/space grows linearly with the input size.
  - **Example:** Iterating through all elements in an array.

- **O(n log n): Linearithmic time**
  - A combination of linear and logarithmic growth.
  - **Example:** Merge sort, quicksort.

- **O(n^2): Quadratic time**
  - The time/space grows quadratically with the input size.
  - **Example:** Bubble sort, selection sort.

- **O(2^n): Exponential time**
  - The time/space doubles with each addition to the input size.
  - **Example:** Recursive Fibonacci sequence.

- **O(n!): Factorial time**
  - The time/space grows factorially, which is extremely inefficient for large inputs.
  - **Example:** Solving the traveling salesman problem using brute-force.

---

#### **3. Amortized Analysis**

Amortized analysis is used to determine the average time or space cost per operation over a sequence of operations, considering both cheap and expensive operations.

It is particularly useful when analyzing algorithms that have a mix of cheap and expensive operations, such as the dynamic array resizing in certain data structures.

##### **Example:**
- **Dynamic Array Resizing:** When you add elements to a dynamic array, the array might resize after a certain threshold. While resizing is expensive (O(n)), it doesn’t happen with every operation. Over multiple insertions, the amortized cost of adding an element is O(1), since resizing occurs infrequently.
  
##### **Types of Amortized Analysis:**
1. **Aggregate Analysis:** Summing up the costs of all operations and dividing by the number of operations.
2. **Accounting Method:** Assigning different "costs" to operations, ensuring that expensive operations are accounted for with cheaper ones.
3. **Potential Method:** Using a potential function to relate the state of the data structure to its future costs.

---

#### **4. Best, Worst, and Average Case Scenarios**

When analyzing algorithms, it's important to consider different scenarios, which provide insights into how the algorithm performs under different conditions.

- **Best Case:**
  - The best-case scenario refers to the input that results in the minimum possible time or space complexity for an algorithm.
  - **Example:** For bubble sort, the best case occurs when the input array is already sorted. Its time complexity is O(n).

- **Worst Case:**
  - The worst-case scenario refers to the input that results in the maximum possible time or space complexity for an algorithm.
  - **Example:** For bubble sort, the worst case occurs when the input array is sorted in reverse order. Its time complexity is O(n^2).

- **Average Case:**
  - The average-case scenario represents the expected performance of an algorithm, considering all possible inputs.
  - **Example:** For quicksort, the average case time complexity is O(n log n).

##### **Example of Worst, Best, and Average Case in Sorting Algorithms:**

| **Algorithm**     | **Best Case**        | **Average Case**     | **Worst Case**       |
|-------------------|----------------------|----------------------|----------------------|
| **Bubble Sort**    | O(n)                 | O(n^2)               | O(n^2)               |
| **Merge Sort**     | O(n log n)           | O(n log n)           | O(n log n)           |
| **Quick Sort**     | O(n log n)           | O(n log n)           | O(n^2)               |
| **Insertion Sort** | O(n)                 | O(n^2)               | O(n^2)               |

---

#### **Time Complexity and Space Complexity: Common Patterns**

- **Nested loops:** For algorithms with nested loops, the time complexity is often the product of the sizes of the loops. For example, if you have two loops that iterate over an array of size n, the time complexity is O(n^2).
  
- **Recursion:** Recursive algorithms often have time complexity that depends on the number of recursive calls and the work done in each call. The time complexity can often be determined using recurrence relations.

- **Sorting algorithms:** Sorting algorithms like merge sort, quicksort, and heapsort are typically O(n log n) for average and worst-case scenarios, but bubble sort and insertion sort are O(n^2) in the worst case.

---

#### **Examples of Complexity Analysis in Algorithms**

##### **1. Linear Search**

- **Time Complexity:** O(n)
  - In the worst case, the algorithm searches through the entire list to find the element.
  
- **Space Complexity:** O(1)
  - The algorithm only uses a constant amount of extra space.

```java
public class LinearSearch {
    public static int linearSearch(int[] arr, int target) {
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] == target) {
                return i;
            }
        }
        return -1;
    }

    public static void main(String[] args) {
        int[] arr = {1, 2, 3, 4, 5};
        int target = 3;
        System.out.println("Element found at index: " + linearSearch(arr, target));
    }
}
```

##### **2. Binary Search**

- **Time Complexity:** O(log n)
  - The algorithm halves the search space with each iteration.

- **Space Complexity:** O(1) (Iterative version)

```java
public class BinarySearch {
    public static int binarySearch(int[] arr, int target) {
        int low = 0, high = arr.length - 1;
        
        while (low <= high) {
            int mid = low + (high - low) / 2;
            
            if (arr[mid] == target) {
                return mid;
            }
            if (arr[mid] < target) {
                low = mid + 1;
            } else {
                high = mid - 1;
            }
        }
        
        return -1;
    }

    public static void main(String[] args) {
        int[] arr = {1, 3, 5, 7, 9};
        int target = 5;
        System.out.println("Element found at index: " + binarySearch(arr, target));
    }
}
```

---

### **Summary:**

- **Time Complexity** and **Space Complexity** are used to measure the efficiency of algorithms.
- **Big O Notation** provides an upper bound for algorithm performance.
- **Amortized Analysis** averages the time/space complexity of an operation over a series of operations.
- **Best, Worst, and Average Cases** offer a complete picture of an algorithm's performance under different conditions.
- By understanding and applying complexity analysis, we can select the most efficient algorithm for a given problem, ensuring optimal performance even as data grows.


# **Chapter 4: Arrays**

### **What are Arrays?**
An array is a collection of elements of the same type stored in contiguous memory locations. It allows you to store multiple values under a single variable name and access them using indices.

---

### **Characteristics of Arrays**
1. **Fixed Size**: The size of an array is defined at the time of creation and cannot be changed later.  
2. **Homogeneous Elements**: All elements must be of the same type.  
3. **Random Access**: Elements can be accessed directly using their indices.

---

### **Types of Arrays**
1. **One-Dimensional Array**: A simple list of elements. Example: `[10, 20, 30, 40]`.  
2. **Two-Dimensional Array**: A table-like structure with rows and columns. Example:  
   ```
   1  2  3  
   4  5  6  
   7  8  9  
   ```
3. **Multi-Dimensional Array**: Arrays with more than two dimensions (e.g., 3D arrays).

---

### **Operations on Arrays**
Below are the commonly used operations on arrays with examples, time complexity, and space complexity.

---

#### **1. Traversal**
Accessing each element of the array.  

**Time Complexity**: \(O(n)\), where \(n\) is the number of elements.  
**Space Complexity**: \(O(1)\), as no extra space is used.

**Java Example**:
```java
public class ArrayTraversal {
    public static void main(String[] args) {
        // Initialize an array
        int[] arr = {10, 20, 30, 40};

        // Traversing and printing each element
        System.out.println("Array Elements:");
        for (int i = 0; i < arr.length; i++) {
            // Printing the element at index i
            System.out.println(arr[i]);
        }
    }
}
```
**Output**:
```
Array Elements:
10
20
30
40
```

---

#### **2. Insertion**
Adding an element at a specific index.  

**Time Complexity**:  
- **Best Case**: \(O(1)\), if inserting at the end.  
- **Worst Case**: \(O(n)\), if inserting at the beginning or middle due to shifting.  
**Space Complexity**: \(O(1)\).

**Java Example**:
```java
import java.util.Arrays;

public class ArrayInsertion {
    public static void main(String[] args) {
        int[] arr = {10, 20, 30, 40};
        int index = 2; // Position where new element will be inserted
        int element = 25; // New element to insert

        // Shift elements to the right to make space for the new element
        for (int i = arr.length - 1; i > index; i--) {
            arr[i] = arr[i - 1];
        }

        // Insert the new element at the specified index
        arr[index] = element;

        // Print the modified array
        System.out.println("Array after insertion: " + Arrays.toString(arr));
    }
}
```
**Output**:
```
Array after insertion: [10, 20, 25, 40]
```

---

#### **3. Deletion**
Removing an element from a specific index.  

**Time Complexity**: \(O(n)\), as elements need to be shifted.  
**Space Complexity**: \(O(1)\).

**Java Example**:
```java
import java.util.Arrays;

public class ArrayDeletion {
    public static void main(String[] args) {
        int[] arr = {10, 20, 30, 40};
        int index = 2; // Index of the element to delete

        // Shift elements to the left to fill the gap
        for (int i = index; i < arr.length - 1; i++) {
            arr[i] = arr[i + 1];
        }

        // Print the modified array
        System.out.println("Array after deletion: " + Arrays.toString(arr));
    }
}
```
**Output**:
```
Array after deletion: [10, 20, 40, 40]
```

---

#### **4. Searching**
Finding the index of an element.  

**Time Complexity**:  
- **Best Case**: \(O(1)\), if the element is at the beginning.  
- **Worst Case**: \(O(n)\), if the element is not found or is at the end.  
**Space Complexity**: \(O(1)\).

**Java Example**:
```java
public class ArraySearch {
    public static void main(String[] args) {
        int[] arr = {10, 20, 30, 40};
        int target = 30; // Element to search for

        int index = -1; // Initialize index to -1 (not found)

        // Traverse the array to find the element
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] == target) {
                index = i; // Update index if element is found
                break;
            }
        }

        // Print the result
        if (index != -1) {
            System.out.println("Element found at index: " + index);
        } else {
            System.out.println("Element not found.");
        }
    }
}
```
**Output**:
```
Element found at index: 2
```

---

### **Advantages of Arrays**
1. **Random Access**: Access elements using indices with constant time complexity \(O(1)\).  
2. **Simplicity**: Easy to implement and use.  
3. **Memory Contiguity**: Efficient use of memory due to sequential allocation.

---

### **Limitations of Arrays**
1. **Fixed Size**: Cannot grow or shrink dynamically.  
2. **Homogeneity**: Only elements of the same type can be stored.  
3. **Insertion/Deletion Overhead**: Requires shifting elements, resulting in \(O(n)\) complexity.

---

### **Recap**
- Arrays are fixed-size, homogeneous data structures that offer efficient random access.  
- Common operations include traversal, insertion, deletion, and searching.  
- Arrays are simple and efficient but have limitations such as fixed size and insertion/deletion overhead.

---
  

# **Chapter 5: Strings**

---

### **What are Strings?**
A **String** is a sequence of characters. Strings are used to represent text in most programming languages, including Java. Unlike arrays, strings are immutable in Java, meaning their content cannot be changed once created.

---

### **Key Characteristics of Strings**
1. **Immutable**: Strings cannot be altered after creation. Any modification creates a new string.
2. **Stored in String Pool**: Optimizes memory usage by reusing existing string literals.
3. **Unicode Support**: Strings in Java support Unicode characters, making them suitable for internationalization.

---

### **Creating Strings**
Strings in Java can be created in two ways:
1. **Using String Literals**:
   ```java
   String str = "Hello";
   ```
   Stored in the String Pool for memory efficiency.

2. **Using the `new` Keyword**:
   ```java
   String str = new String("Hello");
   ```
   Creates a new object in the heap memory.

---

### **Common Operations on Strings**

#### **1. Concatenation**
Joining two or more strings.

**Time Complexity**:  
- \(O(n)\), where \(n\) is the length of the strings being concatenated.  
**Space Complexity**: \(O(n)\), as a new string is created.

**Java Example**:
```java
public class StringConcatenation {
    public static void main(String[] args) {
        String str1 = "Hello, ";
        String str2 = "World!";
        
        // Concatenate strings
        String result = str1 + str2;
        System.out.println("Concatenated String: " + result);
    }
}
```
**Output**:
```
Concatenated String: Hello, World!
```

---

#### **2. Length of a String**
Find the number of characters in a string.

**Time Complexity**: \(O(1)\)  
**Space Complexity**: \(O(1)\)

**Java Example**:
```java
public class StringLength {
    public static void main(String[] args) {
        String str = "Hello, World!";
        
        // Get the length of the string
        int length = str.length();
        System.out.println("String Length: " + length);
    }
}
```
**Output**:
```
String Length: 13
```

---

#### **3. Character Extraction**
Retrieve a specific character from a string.

**Time Complexity**: \(O(1)\)  
**Space Complexity**: \(O(1)\)

**Java Example**:
```java
public class CharExtraction {
    public static void main(String[] args) {
        String str = "Hello, World!";
        
        // Get character at index 7
        char ch = str.charAt(7);
        System.out.println("Character at index 7: " + ch);
    }
}
```
**Output**:
```
Character at index 7: W
```

---

#### **4. Substring**
Extract a portion of a string.

**Time Complexity**: \(O(n)\), where \(n\) is the length of the substring.  
**Space Complexity**: \(O(n)\), as a new substring is created.

**Java Example**:
```java
public class SubstringExample {
    public static void main(String[] args) {
        String str = "Hello, World!";
        
        // Extract substring
        String sub = str.substring(7, 12);
        System.out.println("Substring: " + sub);
    }
}
```
**Output**:
```
Substring: World
```

---

#### **5. String Comparison**
Compare two strings for equality.

**Time Complexity**: \(O(n)\), where \(n\) is the length of the string.  
**Space Complexity**: \(O(1)\)

**Java Example**:
```java
public class StringComparison {
    public static void main(String[] args) {
        String str1 = "Hello";
        String str2 = "Hello";
        String str3 = "World";

        // Compare strings
        System.out.println("str1 equals str2: " + str1.equals(str2));
        System.out.println("str1 equals str3: " + str1.equals(str3));
    }
}
```
**Output**:
```
str1 equals str2: true
str1 equals str3: false
```

---

#### **6. String Replacement**
Replace characters or substrings within a string.

**Time Complexity**: \(O(n)\), where \(n\) is the length of the string.  
**Space Complexity**: \(O(n)\), as a new string is created.

**Java Example**:
```java
public class StringReplacement {
    public static void main(String[] args) {
        String str = "Hello, World!";
        
        // Replace "World" with "Java"
        String replaced = str.replace("World", "Java");
        System.out.println("Replaced String: " + replaced);
    }
}
```
**Output**:
```
Replaced String: Hello, Java!
```

---

### **Advantages of Strings**
1. **Ease of Use**: Strings offer many built-in methods for manipulation.
2. **Immutable**: Ensures security and thread safety.
3. **Unicode Support**: Enables global language compatibility.

---

### **Limitations of Strings**
1. **Immutability Overhead**: Frequent modifications result in high memory usage.
2. **Performance**: String operations like concatenation can be slow.

---

### **StringBuilder and StringBuffer**
For frequent modifications, **StringBuilder** and **StringBuffer** are recommended.  
- **StringBuilder**: Not thread-safe but faster.  
- **StringBuffer**: Thread-safe but slower.

---

#### **StringBuilder Example**
**Time Complexity**: \(O(n)\) for most operations.  
**Space Complexity**: \(O(n)\).

**Java Example**:
```java
public class StringBuilderExample {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder("Hello");

        // Append a string
        sb.append(", World!");
        System.out.println("Modified String: " + sb.toString());
    }
}
```
**Output**:
```
Modified String: Hello, World!
```

---

### **Summary**
- Strings in Java are immutable and stored in a string pool.  
- Common operations include concatenation, substring extraction, comparison, and replacement.  
- For frequent modifications, **StringBuilder** or **StringBuffer** is preferred.  

---

# **Chapter 6: Linked Lists in Java (Using Collection Framework)**

---

### **What is a Linked List?**
A **Linked List** is a linear data structure where elements are stored in nodes. Each node contains two parts:
1. **Data**: Stores the value.
2. **Next**: A reference (or link) to the next node in the sequence.

Unlike arrays, linked lists do not store elements in contiguous memory locations, and the size can grow or shrink dynamically.

---

### **Types of Linked Lists**
1. **Singly Linked List**: Each node points to the next node.
2. **Doubly Linked List**: Each node points to both the next and previous nodes.
3. **Circular Linked List**: The last node points to the first node, forming a circle.

---

### **Using Linked List in Java**

In Java, we can use the **`LinkedList`** class from the **Java Collection Framework** to implement a linked list. The **`LinkedList`** class implements the **List** interface and provides methods to insert, delete, and access elements efficiently.

### **Key Features of `LinkedList`**
- **Dynamic Size**: Unlike arrays, the size of a linked list is not fixed.
- **Efficient Insertion and Deletion**: Operations like insertion and deletion are faster as they don't require shifting elements.
- **Indexed Access**: Similar to an array, you can access elements by index.

---

### **Basic Operations with LinkedList**

#### **1. Creating a Linked List**
You can create a `LinkedList` using the following syntax:
```java
LinkedList<Type> list = new LinkedList<>();
```

**Example:**
```java
import java.util.LinkedList;

public class LinkedListExample {
    public static void main(String[] args) {
        LinkedList<String> list = new LinkedList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");
        System.out.println("Linked List: " + list);
    }
}
```
**Output**:
```
Linked List: [Apple, Banana, Orange]
```

---

#### **2. Adding Elements to a Linked List**
Elements can be added at the end, beginning, or any specific position.

**Add at the end**:
```java
list.add("Grapes");
```

**Add at the beginning**:
```java
list.addFirst("Mango");
```

**Add at a specific position**:
```java
list.add(2, "Pineapple");
```

**Example**:
```java
public class LinkedListAddExample {
    public static void main(String[] args) {
        LinkedList<String> list = new LinkedList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        list.addFirst("Mango");
        list.add(2, "Pineapple");
        
        System.out.println("Updated Linked List: " + list);
    }
}
```
**Output**:
```
Updated Linked List: [Mango, Apple, Pineapple, Banana, Orange]
```

---

#### **3. Removing Elements from a Linked List**
You can remove elements by value, index, or from the beginning or end.

**Remove first element**:
```java
list.removeFirst();
```

**Remove last element**:
```java
list.removeLast();
```

**Remove by value**:
```java
list.remove("Banana");
```

**Remove by index**:
```java
list.remove(1);
```

**Example**:
```java
public class LinkedListRemoveExample {
    public static void main(String[] args) {
        LinkedList<String> list = new LinkedList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");
        
        list.remove("Banana");
        list.removeFirst();

        System.out.println("Updated Linked List: " + list);
    }
}
```
**Output**:
```
Updated Linked List: [Orange]
```

---

#### **4. Accessing Elements**
You can access elements in a linked list using methods like **`get()`** and **`getFirst()`**.

**Get element at index**:
```java
String fruit = list.get(1);
```

**Get first element**:
```java
String firstFruit = list.getFirst();
```

**Example**:
```java
public class LinkedListAccessExample {
    public static void main(String[] args) {
        LinkedList<String> list = new LinkedList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");
        
        System.out.println("Element at index 1: " + list.get(1));
        System.out.println("First element: " + list.getFirst());
    }
}
```
**Output**:
```
Element at index 1: Banana
First element: Apple
```

---

#### **5. Iterating Through a Linked List**
You can iterate through the elements of a linked list using various methods like **`for-each` loop** or **Iterator**.

**Using `for-each` loop**:
```java
for (String fruit : list) {
    System.out.println(fruit);
}
```

**Using Iterator**:
```java
Iterator<String> iterator = list.iterator();
while (iterator.hasNext()) {
    System.out.println(iterator.next());
}
```

**Example**:
```java
public class LinkedListIterateExample {
    public static void main(String[] args) {
        LinkedList<String> list = new LinkedList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        // Using for-each loop
        System.out.println("Using for-each loop:");
        for (String fruit : list) {
            System.out.println(fruit);
        }
        
        // Using Iterator
        System.out.println("\nUsing Iterator:");
        Iterator<String> iterator = list.iterator();
        while (iterator.hasNext()) {
            System.out.println(iterator.next());
        }
    }
}
```
**Output**:
```
Using for-each loop:
Apple
Banana
Orange

Using Iterator:
Apple
Banana
Orange
```

---

### **Advantages of LinkedList**
1. **Dynamic Size**: Can grow and shrink in size at runtime.
2. **Efficient Insertions and Deletions**: Insertion or deletion of elements does not require shifting the other elements.
3. **Flexible Memory Usage**: Unlike arrays, linked lists can utilize non-contiguous memory.

---

### **Disadvantages of LinkedList**
1. **Higher Memory Usage**: Each node in the list requires extra memory for storing a reference to the next (and previous, in case of doubly linked list) node.
2. **Slower Access**: Accessing elements by index requires traversing the list from the beginning, leading to slower access time.

---

### **Use Cases of LinkedList**
1. **When Frequent Insertions and Deletions are Needed**: LinkedLists are optimal when operations like inserting and removing elements from the middle or beginning are frequent.
2. **When Memory Allocation is Dynamic**: LinkedLists can dynamically allocate memory, unlike arrays that need to be allocated upfront.

---

### **Conclusion**
The **`LinkedList`** class in Java provides an efficient way to perform operations like insertion, deletion, and traversal. It's ideal for scenarios where the number of elements may change frequently and direct access by index is not a major concern.

---

# **Chapter 7: ArrayList in Java**

---

### **What is an ArrayList?**
An **ArrayList** is a part of the Java Collection Framework and is an implementation of the **List** interface. It is a **resizable array** that allows dynamic resizing of the array as elements are added or removed. 

Unlike arrays in Java, which have a fixed size, **ArrayList** can grow and shrink as needed, making it more flexible when dealing with a list of elements.

---

### **Key Features of ArrayList**
- **Dynamic Sizing**: Unlike arrays, the size of an ArrayList can grow or shrink dynamically.
- **Index-based Access**: Allows fast access to elements using indices.
- **Can store objects of any type**: ArrayList can store objects of any type, including primitive types when wrapped in corresponding wrapper classes.
- **Maintains Insertion Order**: ArrayList maintains the order in which elements are inserted.

---

### **Creating an ArrayList**

You can create an ArrayList using the following syntax:
```java
ArrayList<Type> list = new ArrayList<>();
```

**Example**:
```java
import java.util.ArrayList;

public class ArrayListExample {
    public static void main(String[] args) {
        // Creating an ArrayList of String type
        ArrayList<String> list = new ArrayList<>();
        
        // Adding elements
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        // Displaying the ArrayList
        System.out.println("ArrayList: " + list);
    }
}
```
**Output**:
```
ArrayList: [Apple, Banana, Orange]
```

---

### **Common Operations with ArrayList**

#### **1. Adding Elements**
You can add elements to the ArrayList using the `add()` method.

**Add to the end**:
```java
list.add("Grapes");
```

**Add at a specific index**:
```java
list.add(1, "Mango");
```

**Example**:
```java
public class ArrayListAddExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        list.add("Grapes");      // Add at the end
        list.add(1, "Mango");    // Add at index 1
        
        System.out.println("Updated ArrayList: " + list);
    }
}
```
**Output**:
```
Updated ArrayList: [Apple, Mango, Banana, Orange, Grapes]
```

---

#### **2. Accessing Elements**
You can access elements using their index with the `get()` method.

**Example**:
```java
String fruit = list.get(2); // Gets the element at index 2
```

**Example**:
```java
public class ArrayListAccessExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        // Accessing an element
        String fruit = list.get(1);
        System.out.println("Element at index 1: " + fruit); // Output: Banana
    }
}
```
**Output**:
```
Element at index 1: Banana
```

---

#### **3. Removing Elements**
You can remove elements by index or by value.

**Remove by index**:
```java
list.remove(1); // Removes the element at index 1
```

**Remove by value**:
```java
list.remove("Banana"); // Removes the element "Banana"
```

**Example**:
```java
public class ArrayListRemoveExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        list.remove(1);    // Removes "Banana" (index 1)
        list.remove("Apple"); // Removes "Apple" by value
        
        System.out.println("Updated ArrayList: " + list);
    }
}
```
**Output**:
```
Updated ArrayList: [Orange]
```

---

#### **4. Modifying Elements**
You can modify an element using the `set()` method, which updates the value at a specific index.

**Example**:
```java
list.set(1, "Pineapple"); // Replaces the element at index 1
```

**Example**:
```java
public class ArrayListModifyExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        list.set(1, "Pineapple"); // Replace "Banana" with "Pineapple"

        System.out.println("Updated ArrayList: " + list);
    }
}
```
**Output**:
```
Updated ArrayList: [Apple, Pineapple, Orange]
```

---

#### **5. Iterating Through an ArrayList**
You can iterate through an ArrayList using different methods, such as the **for-each loop** or **Iterator**.

**Using for-each loop**:
```java
for (String fruit : list) {
    System.out.println(fruit);
}
```

**Using Iterator**:
```java
Iterator<String> iterator = list.iterator();
while (iterator.hasNext()) {
    System.out.println(iterator.next());
}
```

**Example**:
```java
public class ArrayListIterateExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        // Using for-each loop
        System.out.println("Using for-each loop:");
        for (String fruit : list) {
            System.out.println(fruit);
        }

        // Using Iterator
        System.out.println("\nUsing Iterator:");
        Iterator<String> iterator = list.iterator();
        while (iterator.hasNext()) {
            System.out.println(iterator.next());
        }
    }
}
```
**Output**:
```
Using for-each loop:
Apple
Banana
Orange

Using Iterator:
Apple
Banana
Orange
```

---

#### **6. Checking if an ArrayList Contains an Element**
You can use the `contains()` method to check if a specific element exists in the ArrayList.

**Example**:
```java
boolean containsBanana = list.contains("Banana");
```

**Example**:
```java
public class ArrayListContainsExample {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>();
        list.add("Apple");
        list.add("Banana");
        list.add("Orange");

        // Checking if "Banana" exists
        boolean containsBanana = list.contains("Banana");
        System.out.println("Contains Banana: " + containsBanana);
    }
}
```
**Output**:
```
Contains Banana: true
```

---

### **Time Complexity of ArrayList Operations**

- **Accessing an element by index**: **O(1)** (constant time)
- **Adding an element at the end**: **O(1)** (amortized)
- **Adding an element at a specific index**: **O(n)** (in the worst case, when all elements need to be shifted)
- **Removing an element by index**: **O(n)** (in the worst case, when all elements after the removed element need to be shifted)
- **Removing an element by value**: **O(n)** (you need to find the element first)
- **Search for an element**: **O(n)** (you may need to traverse the entire list)
  
---

### **Advantages of ArrayList**
1. **Dynamic Resizing**: ArrayList automatically adjusts its size as elements are added.
2. **Fast Random Access**: You can quickly access elements by index.
3. **Simplicity**: It's easy to use and does not require knowledge of complex data structures.

---

### **Disadvantages of ArrayList**
1. **Slower Insertions/Deletions**: Inserting or removing elements from the middle or beginning requires shifting other elements.
2. **Memory Overhead**: ArrayList has a higher memory overhead compared to arrays, as it needs to store both the elements and metadata.

---

### **Use Cases of ArrayList**
1. **When Random Access is Required**: If you need to frequently access elements by index, ArrayList is ideal.
2. **When Size May Change**: When the number of elements is dynamic, and you don’t know how many elements there will be in advance, ArrayList is useful.

---

### **Conclusion**
The **ArrayList** is one of the most commonly used data structures in Java due to its flexibility, dynamic size, and easy-to-use features. It is suitable for scenarios where frequent access to elements by index is necessary and where the number of elements may change dynamically.

---

# **Chapter 8: Stack in Java**

---

### **What is a Stack?**

A **Stack** is a collection of elements that follows the **Last In, First Out (LIFO)** principle. This means that the last element added to the stack will be the first to be removed. The two main operations in a stack are:

- **Push**: Adds an element to the top of the stack.
- **Pop**: Removes the element from the top of the stack.

Stacks are often used in scenarios like **undo operations**, **expression evaluation**, **backtracking algorithms**, and **function calls** in recursion.

---

### **Key Features of a Stack**
- **LIFO Order**: The last element pushed onto the stack is the first one to be popped off.
- **Dynamic Size**: The size of the stack can grow or shrink as needed, similar to other collections like ArrayList.
- **Limited Operations**: A stack only allows adding and removing elements from one end (the top of the stack).

---

### **Creating a Stack**

In Java, the `Stack` class is part of the `java.util` package, and it extends the `Vector` class. You can create a stack using the following syntax:

```java
Stack<Type> stack = new Stack<>();
```

---

### **Basic Operations in Stack**

1. **Push**: Adds an element to the top of the stack.

   **Syntax**:
   ```java
   stack.push(element);
   ```

2. **Pop**: Removes the element from the top of the stack and returns it.

   **Syntax**:
   ```java
   stack.pop();
   ```

3. **Peek**: Returns the element at the top of the stack without removing it.

   **Syntax**:
   ```java
   stack.peek();
   ```

4. **Empty**: Checks if the stack is empty.

   **Syntax**:
   ```java
   stack.isEmpty();
   ```

5. **Search**: Searches for an element in the stack and returns its position from the top of the stack.

   **Syntax**:
   ```java
   stack.search(element);
   ```

---

### **Example of Stack Operations**

Here's an example demonstrating the use of stack operations:

```java
import java.util.Stack;

public class StackExample {
    public static void main(String[] args) {
        // Create a stack of Strings
        Stack<String> stack = new Stack<>();
        
        // Push elements onto the stack
        stack.push("Apple");
        stack.push("Banana");
        stack.push("Orange");

        // Peek the top element
        System.out.println("Top element: " + stack.peek());

        // Pop an element from the stack
        System.out.println("Popped element: " + stack.pop());

        // Check if the stack is empty
        System.out.println("Is stack empty? " + stack.isEmpty());

        // Search for an element in the stack
        System.out.println("Position of 'Apple': " + stack.search("Apple"));

        // Display the remaining elements in the stack
        System.out.println("Remaining elements in stack: " + stack);
    }
}
```

**Output**:
```
Top element: Orange
Popped element: Orange
Is stack empty? false
Position of 'Apple': 1
Remaining elements in stack: [Apple, Banana]
```

---

### **Time and Space Complexity of Stack Operations**

- **Push**: **O(1)** (Adding an element is done in constant time)
- **Pop**: **O(1)** (Removing the top element is done in constant time)
- **Peek**: **O(1)** (Accessing the top element is done in constant time)
- **Empty**: **O(1)** (Checking if the stack is empty takes constant time)
- **Search**: **O(n)** (In the worst case, you may need to traverse the entire stack)

**Space Complexity**: **O(n)** (The space complexity depends on the number of elements in the stack, as each element occupies space in memory.)

---

### **Use Cases of Stack**

1. **Expression Evaluation**:
   - Stacks are used to evaluate expressions like **infix**, **postfix**, and **prefix**.
   - For example, converting an infix expression to postfix or evaluating a postfix expression.

2. **Backtracking**:
   - Stacks can be used in algorithms like **Depth First Search (DFS)** for graph traversal.
   - In puzzles like the **N-Queens Problem**, **Sudoku**, and **Maze Solving**, stacks can help backtrack to previous steps.

3. **Undo/Redo Functionality**:
   - In applications like text editors, stacks are used to store previous states of a document, enabling undo and redo operations.

4. **Recursion**:
   - In recursive algorithms, the function calls themselves are managed by the call stack.

---

### **Advantages of Stack**

1. **Fast Operations**: Operations like push, pop, and peek are done in constant time.
2. **Memory-efficient**: Since the stack grows dynamically, it doesn't require extra memory allocation upfront.
3. **Useful for Algorithms**: Many algorithms such as DFS, balancing parentheses, and evaluating expressions use stacks.

---

### **Disadvantages of Stack**

1. **Limited Access**: You can only access the element at the top of the stack. You cannot access any other element unless you pop the top ones first.
2. **Overflow**: Although Java's `Stack` class dynamically resizes, other implementations (like in C/C++) may face overflow issues when the stack size exceeds the memory limit.

---

### **Stack vs Queue**

- **Stack**: Follows the **LIFO** (Last In, First Out) principle.
- **Queue**: Follows the **FIFO** (First In, First Out) principle. In a queue, the element added first is the first to be removed.

While a stack is used for scenarios where you need to access the last added element first (such as function calls in recursion), a queue is useful for situations like task scheduling or data stream processing.

---

### **Conclusion**

Stacks are a fundamental data structure in computer science, widely used for various applications such as expression evaluation, function calls, undo mechanisms, and more. They provide an efficient way to manage elements in a **LIFO** order, which is critical in many algorithms and systems.

---

# **Chapter 9: Queue in Java**

---

### **What is a Queue?**

A **Queue** is a collection of elements that follows the **First In, First Out (FIFO)** principle. This means that the first element added to the queue will be the first to be removed. The two main operations in a queue are:

- **Enqueue**: Adds an element to the rear of the queue.
- **Dequeue**: Removes the element from the front of the queue.

Queues are used in scenarios where elements need to be processed in the order they arrive, such as **task scheduling**, **data buffers**, and **breadth-first search (BFS)** algorithms.

---

### **Key Features of a Queue**
- **FIFO Order**: The first element enqueued is the first one to be dequeued.
- **Dynamic Size**: The size of the queue grows and shrinks as elements are added or removed.
- **Limited Operations**: A queue only allows adding elements to the rear and removing elements from the front.

---

### **Creating a Queue**

In Java, the `Queue` interface is part of the `java.util` package, and there are several implementations such as `LinkedList` and `PriorityQueue`. To create a queue, you can use one of the following approaches:

```java
Queue<Type> queue = new LinkedList<>();
```

Alternatively, you can use the `PriorityQueue` for queue elements that need to be processed in priority order.

---

### **Basic Operations in Queue**

1. **Enqueue**: Adds an element to the rear of the queue.

   **Syntax**:
   ```java
   queue.offer(element);  // Or queue.add(element);
   ```

2. **Dequeue**: Removes the element from the front of the queue and returns it.

   **Syntax**:
   ```java
   queue.poll();  // Removes and returns the element at the front
   ```

3. **Peek**: Returns the element at the front of the queue without removing it.

   **Syntax**:
   ```java
   queue.peek();
   ```

4. **Empty**: Checks if the queue is empty.

   **Syntax**:
   ```java
   queue.isEmpty();
   ```

---

### **Example of Queue Operations**

Here’s an example that demonstrates queue operations in Java using a `LinkedList` as the implementation:

```java
import java.util.LinkedList;
import java.util.Queue;

public class QueueExample {
    public static void main(String[] args) {
        // Create a Queue of Strings
        Queue<String> queue = new LinkedList<>();
        
        // Enqueue elements
        queue.offer("Apple");
        queue.offer("Banana");
        queue.offer("Orange");
        
        // Peek the front element
        System.out.println("Front element: " + queue.peek());
        
        // Dequeue an element
        System.out.println("Dequeued element: " + queue.poll());
        
        // Check if the queue is empty
        System.out.println("Is queue empty? " + queue.isEmpty());
        
        // Display remaining elements in the queue
        System.out.println("Remaining elements in queue: " + queue);
    }
}
```

**Output**:
```
Front element: Apple
Dequeued element: Apple
Is queue empty? false
Remaining elements in queue: [Banana, Orange]
```

---

### **Time and Space Complexity of Queue Operations**

- **Enqueue**: **O(1)** (Adding an element to the rear of the queue is done in constant time)
- **Dequeue**: **O(1)** (Removing an element from the front is done in constant time)
- **Peek**: **O(1)** (Accessing the front element is done in constant time)
- **Empty**: **O(1)** (Checking if the queue is empty takes constant time)

**Space Complexity**: **O(n)** (The space complexity depends on the number of elements in the queue, as each element occupies space in memory.)

---

### **Use Cases of Queue**

1. **Task Scheduling**:
   - Queues are ideal for task scheduling systems where tasks are processed in the order they arrive. Examples include job scheduling in operating systems or print queues in printers.

2. **Breadth-First Search (BFS)**:
   - In graph traversal algorithms like BFS, a queue is used to explore nodes level by level.

3. **Buffering**:
   - Queues are used to store data temporarily as it’s being transferred between different systems, such as streaming data or reading from a file.

4. **Asynchronous Processing**:
   - In distributed systems or messaging queues (e.g., RabbitMQ), queues are used to store and process messages asynchronously.

---

### **Advantages of Queue**

1. **Efficient Processing**: Queues allow for efficient, fair processing of tasks or elements in the order they arrive.
2. **Simple Operations**: Basic queue operations such as enqueue, dequeue, and peek are simple and operate in constant time.
3. **Dynamic Size**: Like stacks, queues are dynamic and can grow or shrink as needed based on the number of elements.

---

### **Disadvantages of Queue**

1. **Limited Access**: Similar to stacks, you can only access the element at the front of the queue. You cannot access any other element unless it is dequeued first.
2. **Overflow**: Although Java's `LinkedList` implementation is dynamic, other implementations (like in C/C++) may face overflow issues when the queue size exceeds the available memory.

---

### **Queue vs Stack**

- **Queue**: Follows the **FIFO** (First In, First Out) principle. The first element enqueued is the first one to be dequeued.
- **Stack**: Follows the **LIFO** (Last In, First Out) principle. The last element pushed is the first one to be popped.

While a stack is used for situations where the most recent element needs to be processed first, a queue is used when elements should be processed in the order they arrive.

---

### **Conclusion**

Queues are fundamental data structures used for scenarios where elements need to be processed in a first-come-first-served manner. From task scheduling to BFS algorithms, queues offer an efficient way to handle elements in a **FIFO** order. They are highly versatile and essential for various computing problems.

---

# **Chapter 10: Hashing in Java**

---

### **What is Hashing?**

Hashing is a technique used to uniquely identify a specific object from a group of similar objects. The process of transforming data into a fixed-size string of characters, which is usually a hash code, is known as hashing.

The **hash code** is a number generated from a string (or any data type), which uniquely identifies the data. Hashing is essential for efficient data retrieval, especially when implementing data structures like hash maps or hash sets.

---

### **HashMap in Java**

A **HashMap** is a part of the `java.util` package and is an implementation of the **Map** interface. It is used to store key-value pairs, where each key is unique. Internally, it uses a **hashing mechanism** to store the keys and find their corresponding values in constant time, **O(1)**, in most cases.

---

### **Key Features of HashMap**
- **Key-Value Pair**: A `HashMap` stores data in pairs (key, value).
- **Unordered**: It does not guarantee any specific order of elements.
- **Allows Null**: Both the key and the value can be `null`.
- **Unique Keys**: Keys in a `HashMap` are unique, but values can be duplicated.

---

### **Creating a HashMap**

```java
import java.util.HashMap;

public class HashMapExample {
    public static void main(String[] args) {
        // Creating a HashMap with String as the key and Integer as the value
        HashMap<String, Integer> map = new HashMap<>();

        // Adding key-value pairs to the map
        map.put("Apple", 2);
        map.put("Banana", 3);
        map.put("Orange", 4);

        // Display the map
        System.out.println("HashMap: " + map);
    }
}
```

**Output**:
```
HashMap: {Apple=2, Banana=3, Orange=4}
```

---

### **Basic Operations in HashMap**

1. **put()**: Adds a key-value pair to the map.
   ```java
   map.put("Key", Value);
   ```

2. **get()**: Retrieves the value associated with a key.
   ```java
   map.get("Key");
   ```

3. **containsKey()**: Checks if the map contains a specific key.
   ```java
   map.containsKey("Key");
   ```

4. **remove()**: Removes the key-value pair from the map based on the key.
   ```java
   map.remove("Key");
   ```

5. **size()**: Returns the number of key-value pairs in the map.
   ```java
   map.size();
   ```

---

### **Example of HashMap Operations**

```java
import java.util.HashMap;

public class HashMapOperations {
    public static void main(String[] args) {
        // Creating a HashMap
        HashMap<String, Integer> map = new HashMap<>();

        // Adding elements
        map.put("Apple", 5);
        map.put("Banana", 7);
        map.put("Cherry", 3);

        // Displaying the map
        System.out.println("Original HashMap: " + map);

        // Getting the value associated with key "Banana"
        System.out.println("Banana: " + map.get("Banana"));

        // Checking if a key exists
        System.out.println("Contains key 'Cherry': " + map.containsKey("Cherry"));

        // Removing a key-value pair
        map.remove("Apple");
        System.out.println("HashMap after removal: " + map);

        // Getting the size of the map
        System.out.println("Size of map: " + map.size());
    }
}
```

**Output**:
```
Original HashMap: {Apple=5, Banana=7, Cherry=3}
Banana: 7
Contains key 'Cherry': true
HashMap after removal: {Banana=7, Cherry=3}
Size of map: 2
```

---

### **Time Complexity of HashMap Operations**

- **put()**: **O(1)** (Inserting an element takes constant time on average)
- **get()**: **O(1)** (Accessing a value by its key takes constant time on average)
- **remove()**: **O(1)** (Removing an element by key takes constant time)
- **containsKey()**: **O(1)** (Checking if a key exists in the map takes constant time)
- **size()**: **O(1)** (Getting the size of the map takes constant time)

**Space Complexity**: **O(n)** (The space complexity depends on the number of key-value pairs stored in the map)

---

### **HashSet in Java**

A **HashSet** is an implementation of the **Set** interface, backed by a hash map. It stores unique elements and uses hashing to check for duplicates.

---

### **Key Features of HashSet**
- **Unique Elements**: A `HashSet` does not allow duplicate elements.
- **Unordered**: The elements in a `HashSet` are not ordered.
- **Null Values**: A `HashSet` allows at most one `null` value.

---

### **Creating a HashSet**

```java
import java.util.HashSet;

public class HashSetExample {
    public static void main(String[] args) {
        // Creating a HashSet
        HashSet<String> set = new HashSet<>();

        // Adding elements to the set
        set.add("Apple");
        set.add("Banana");
        set.add("Orange");

        // Displaying the set
        System.out.println("HashSet: " + set);
    }
}
```

**Output**:
```
HashSet: [Apple, Banana, Orange]
```

---

### **Basic Operations in HashSet**

1. **add()**: Adds an element to the set.
   ```java
   set.add("Element");
   ```

2. **contains()**: Checks if an element is present in the set.
   ```java
   set.contains("Element");
   ```

3. **remove()**: Removes an element from the set.
   ```java
   set.remove("Element");
   ```

4. **size()**: Returns the number of elements in the set.
   ```java
   set.size();
   ```

---

### **Time Complexity of HashSet Operations**

- **add()**: **O(1)** (Adding an element takes constant time on average)
- **contains()**: **O(1)** (Checking if an element exists in the set takes constant time on average)
- **remove()**: **O(1)** (Removing an element takes constant time on average)
- **size()**: **O(1)** (Getting the size of the set takes constant time)

**Space Complexity**: **O(n)** (The space complexity depends on the number of elements stored in the set)

---

### **Use Cases of Hashing**

1. **Fast Data Retrieval**: Hash maps and hash sets are widely used for fast data retrieval, offering constant time lookups on average.
2. **Unique Data**: Hash sets are used when you need to store unique elements and need constant-time operations.
3. **Caching**: Hashing is often used in caching mechanisms where data is retrieved quickly based on the hash value of the keys.
4. **Database Indexing**: Hashing is used in databases to index rows for efficient searching.

---

### **Conclusion**

Hashing is an essential technique in computer science and is used extensively in implementing **HashMap** and **HashSet**. Hash-based data structures provide **O(1)** time complexity for operations like insertion, removal, and access in most cases. They are highly efficient and are used in a wide range of applications like caching, database indexing, and task scheduling.

---

# **Chapter 11: Trees in Java**

---

### **What is a Tree?**

A **Tree** is a hierarchical data structure that consists of nodes connected by edges. It starts with a root node and branches into subtrees of children, with no cycles.

---

### **Key Properties of Trees**
1. **Root**: The top node in the tree.
2. **Parent**: A node that has children.
3. **Child**: Nodes directly connected to another node when moving away from the root.
4. **Leaf**: A node with no children.
5. **Height of Tree**: The number of edges on the longest path from the root to a leaf.
6. **Depth of Node**: The number of edges from the root to the node.

---

### **Types of Trees**

1. **Binary Tree**: Each node has at most two children.
2. **Binary Search Tree (BST)**: A binary tree where the left subtree contains values less than the root, and the right subtree contains values greater than the root.
3. **Balanced Binary Tree**: A tree where the height difference between left and right subtrees is at most 1.
4. **AVL Tree**: A self-balancing binary search tree.
5. **Heap**: A complete binary tree used to implement priority queues.
6. **B-Tree**: A self-balancing tree used in databases.

---

### **Binary Tree Implementation in Java**

```java
// A class representing a node in the binary tree
class Node {
    int data;
    Node left, right;

    // Constructor
    Node(int value) {
        data = value;
        left = right = null;
    }
}

public class BinaryTree {
    // Root node
    Node root;

    // Traversing the tree in Inorder
    void inorder(Node node) {
        if (node != null) {
            inorder(node.left);       // Visit left subtree
            System.out.print(node.data + " ");  // Visit root
            inorder(node.right);      // Visit right subtree
        }
    }

    public static void main(String[] args) {
        BinaryTree tree = new BinaryTree();

        // Creating a binary tree
        tree.root = new Node(1);
        tree.root.left = new Node(2);
        tree.root.right = new Node(3);
        tree.root.left.left = new Node(4);
        tree.root.left.right = new Node(5);

        // Inorder Traversal
        System.out.println("Inorder traversal of binary tree:");
        tree.inorder(tree.root);
    }
}
```

**Output**:
```
Inorder traversal of binary tree:
4 2 5 1 3
```

---

### **Binary Search Tree (BST) Implementation in Java**

A **Binary Search Tree (BST)** allows for fast insertion, deletion, and search operations.

```java
class BST {
    // Node class
    class Node {
        int data;
        Node left, right;

        Node(int value) {
            data = value;
            left = right = null;
        }
    }

    // Root node of BST
    Node root;

    // Insert a node into BST
    void insert(int value) {
        root = insertRec(root, value);
    }

    // Recursive function to insert a value
    Node insertRec(Node root, int value) {
        if (root == null) {
            root = new Node(value);
            return root;
        }
        if (value < root.data)
            root.left = insertRec(root.left, value);
        else if (value > root.data)
            root.right = insertRec(root.right, value);

        return root;
    }

    // Inorder traversal
    void inorder() {
        inorderRec(root);
    }

    void inorderRec(Node root) {
        if (root != null) {
            inorderRec(root.left);
            System.out.print(root.data + " ");
            inorderRec(root.right);
        }
    }

    public static void main(String[] args) {
        BST tree = new BST();

        // Insert values
        tree.insert(50);
        tree.insert(30);
        tree.insert(20);
        tree.insert(40);
        tree.insert(70);
        tree.insert(60);
        tree.insert(80);

        // Print inorder traversal
        System.out.println("Inorder traversal of BST:");
        tree.inorder();
    }
}
```

**Output**:
```
Inorder traversal of BST:
20 30 40 50 60 70 80
```

---

### **Common Tree Traversal Techniques**

1. **Inorder Traversal**:
   - Left subtree → Root → Right subtree.
   - Output for the above BST: **20 30 40 50 60 70 80**.

2. **Preorder Traversal**:
   - Root → Left subtree → Right subtree.
   - Output for the above BST: **50 30 20 40 70 60 80**.

3. **Postorder Traversal**:
   - Left subtree → Right subtree → Root.
   - Output for the above BST: **20 40 30 60 80 70 50**.

---

### **Time Complexity of Tree Operations**

| **Operation** | **Average Case** | **Worst Case** |
|---------------|-------------------|----------------|
| Search        | O(log n)         | O(n)           |
| Insert        | O(log n)         | O(n)           |
| Delete        | O(log n)         | O(n)           |

**Space Complexity**: 
- Depends on the height of the tree: **O(h)** where **h** is the height of the tree.

---

### **Advantages of Trees**
1. **Hierarchical Data**: Trees naturally represent hierarchical relationships, such as file systems or organizational structures.
2. **Efficient Searching**: Operations like searching and sorting are faster in trees compared to linear structures like arrays.
3. **Dynamic Data Structure**: Trees can grow and shrink dynamically, unlike arrays which are fixed in size.

---

Let’s dive deeper into **advanced tree concepts**. We'll cover the following sections in detail:

---

## **Advanced Trees in Java (Deep Dive)**

---

#### **1. AVL Trees (Self-Balancing Binary Search Tree)**

##### **What is an AVL Tree?**
An **AVL Tree** is a type of self-balancing binary search tree where the difference between the heights of the left and right subtrees (called the balance factor) is at most 1 for every node.

##### **Why Use AVL Trees?**
- Ensures that the tree remains balanced, improving search, insertion, and deletion times.
- Prevents degeneration into a linked list (as can happen with unbalanced binary search trees).

##### **Key Operations**
1. **Rotation**: To balance the tree after insertion or deletion.
   - **Left Rotation (LL)**
   - **Right Rotation (RR)**
   - **Left-Right Rotation (LR)**
   - **Right-Left Rotation (RL)**

##### **Implementation in Java**
```java
class AVLTree {
    class Node {
        int data, height;
        Node left, right;

        Node(int value) {
            data = value;
            height = 1; // New nodes are initially added at height 1
        }
    }

    private Node root;

    // Get height of a node
    int height(Node node) {
        return node == null ? 0 : node.height;
    }

    // Get balance factor of a node
    int getBalance(Node node) {
        return node == null ? 0 : height(node.left) - height(node.right);
    }

    // Right rotation
    Node rotateRight(Node y) {
        Node x = y.left;
        Node T = x.right;

        x.right = y;
        y.left = T;

        // Update heights
        y.height = Math.max(height(y.left), height(y.right)) + 1;
        x.height = Math.max(height(x.left), height(x.right)) + 1;

        return x;
    }

    // Left rotation
    Node rotateLeft(Node x) {
        Node y = x.right;
        Node T = y.left;

        y.left = x;
        x.right = T;

        // Update heights
        x.height = Math.max(height(x.left), height(x.right)) + 1;
        y.height = Math.max(height(y.left), height(y.right)) + 1;

        return y;
    }

    // Insert a value into the AVL tree
    Node insert(Node node, int value) {
        if (node == null)
            return new Node(value);

        if (value < node.data)
            node.left = insert(node.left, value);
        else if (value > node.data)
            node.right = insert(node.right, value);
        else
            return node; // Duplicates not allowed

        // Update height of the current node
        node.height = Math.max(height(node.left), height(node.right)) + 1;

        // Get balance factor
        int balance = getBalance(node);

        // Perform rotations if unbalanced
        if (balance > 1 && value < node.left.data)
            return rotateRight(node); // LL case
        if (balance < -1 && value > node.right.data)
            return rotateLeft(node); // RR case
        if (balance > 1 && value > node.left.data) {
            node.left = rotateLeft(node.left);
            return rotateRight(node); // LR case
        }
        if (balance < -1 && value < node.right.data) {
            node.right = rotateRight(node.right);
            return rotateLeft(node); // RL case
        }

        return node;
    }

    // Wrapper for inserting
    void insert(int value) {
        root = insert(root, value);
    }

    // Inorder traversal
    void inorder(Node node) {
        if (node != null) {
            inorder(node.left);
            System.out.print(node.data + " ");
            inorder(node.right);
        }
    }

    void inorder() {
        inorder(root);
    }

    public static void main(String[] args) {
        AVLTree tree = new AVLTree();

        tree.insert(10);
        tree.insert(20);
        tree.insert(30);
        tree.insert(40);
        tree.insert(50);
        tree.insert(25);

        System.out.println("Inorder traversal of AVL Tree:");
        tree.inorder();
    }
}
```

**Output**:
```
Inorder traversal of AVL Tree:
10 20 25 30 40 50
```

##### **Time Complexity of AVL Trees**
- **Search, Insert, Delete**: O(log n)
- **Space Complexity**: O(n) (for storage)

---

#### **2. Heaps (Binary Heap)**

##### **What is a Heap?**
A **Heap** is a specialized tree-based data structure that satisfies the **heap property**:
1. **Max-Heap**: The key at the root is greater than or equal to its children.
2. **Min-Heap**: The key at the root is less than or equal to its children.

##### **Why Use Heaps?**
- Used in **priority queues**, **heap sort**, and finding the **k largest/smallest elements**.

##### **Implementation of Min-Heap in Java**
```java
import java.util.PriorityQueue;

public class MinHeap {
    public static void main(String[] args) {
        // Min-Heap using PriorityQueue
        PriorityQueue<Integer> minHeap = new PriorityQueue<>();

        // Add elements
        minHeap.add(10);
        minHeap.add(30);
        minHeap.add(20);
        minHeap.add(5);

        System.out.println("Elements in Min-Heap:");
        while (!minHeap.isEmpty()) {
            System.out.print(minHeap.poll() + " ");
        }
    }
}
```

**Output**:
```
Elements in Min-Heap:
5 10 20 30
```

---

#### **3. B-Trees**

##### **What is a B-Tree?**
A **B-Tree** is a self-balancing search tree designed for disk-based storage systems. It maintains sorted data and allows for efficient insertion, deletion, and search operations.

##### **Use Cases of B-Trees**
- Database indexing.
- Filesystem implementations.

---

### **Advanced Traversals and Use Cases**

1. **Level-Order Traversal**: Visits all nodes at the same depth before moving to the next level.
   - Use case: Finding the shortest path in unweighted graphs.
2. **Boundary Traversal**: Traverses the boundary nodes of a tree.
   - Use case: Visualization or printing tree boundaries.

---

# **Chapter 12: Heap**

---

### **What is a Heap?**
A **Heap** is a special tree-based data structure that satisfies the **heap property**:
1. **Max-Heap**: The key of the root node is greater than or equal to the keys of its children.
2. **Min-Heap**: The key of the root node is less than or equal to the keys of its children.

---

### **Why Use Heaps?**
- Efficiently supports **priority queues**.
- Optimized for **heap sort**.
- Solves problems like **finding the k-largest/smallest elements**, **median in a stream**, and more.

---

### **Types of Heaps**
1. **Max-Heap**:
   - The largest element is always at the root.
   - Used in algorithms like **Heap Sort**.
   
2. **Min-Heap**:
   - The smallest element is always at the root.
   - Used in **priority queues**.

---

### **Heap Operations**
1. **Insertion**: Add an element to the heap and maintain the heap property.
2. **Deletion (Remove)**: Remove the root node and reheapify.
3. **Peek**: Access the root node without removing it.
4. **Heapify**: Transform an arbitrary array into a valid heap.

---

### **Time Complexity**
| Operation  | Time Complexity |
|------------|-----------------|
| Insert     | O(log n)        |
| Delete     | O(log n)        |
| Peek       | O(1)            |
| Build Heap | O(n)            |

---

### **Heap Implementation**

#### **1. Max-Heap in Java**
```java
import java.util.Collections;
import java.util.PriorityQueue;

public class MaxHeap {
    public static void main(String[] args) {
        // Max-Heap using PriorityQueue with reverse order
        PriorityQueue<Integer> maxHeap = new PriorityQueue<>(Collections.reverseOrder());

        // Insert elements
        maxHeap.add(10);
        maxHeap.add(20);
        maxHeap.add(15);
        maxHeap.add(30);

        // Display elements
        System.out.println("Max-Heap elements:");
        while (!maxHeap.isEmpty()) {
            System.out.print(maxHeap.poll() + " ");
        }
    }
}
```

**Output**:
```
Max-Heap elements:
30 20 15 10
```

---

#### **2. Min-Heap in Java**
```java
import java.util.PriorityQueue;

public class MinHeap {
    public static void main(String[] args) {
        // Min-Heap using PriorityQueue
        PriorityQueue<Integer> minHeap = new PriorityQueue<>();

        // Insert elements
        minHeap.add(50);
        minHeap.add(30);
        minHeap.add(20);
        minHeap.add(10);

        // Display elements
        System.out.println("Min-Heap elements:");
        while (!minHeap.isEmpty()) {
            System.out.print(minHeap.poll() + " ");
        }
    }
}
```

**Output**:
```
Min-Heap elements:
10 20 30 50
```

---

### **Build Heap from Array**

```java
import java.util.Arrays;

public class Heap {
    // Helper function to heapify a subtree rooted at index i
    static void heapify(int[] arr, int n, int i) {
        int largest = i; // Initialize largest as root
        int left = 2 * i + 1; // Left child
        int right = 2 * i + 2; // Right child

        // If left child is larger
        if (left < n && arr[left] > arr[largest])
            largest = left;

        // If right child is larger
        if (right < n && arr[right] > arr[largest])
            largest = right;

        // If root is not the largest
        if (largest != i) {
            int swap = arr[i];
            arr[i] = arr[largest];
            arr[largest] = swap;

            // Recursively heapify the affected subtree
            heapify(arr, n, largest);
        }
    }

    // Function to build a Max-Heap from an array
    static void buildHeap(int[] arr, int n) {
        // Index of last non-leaf node
        int startIdx = (n / 2) - 1;

        // Perform reverse level-order traversal
        for (int i = startIdx; i >= 0; i--) {
            heapify(arr, n, i);
        }
    }

    // Main function to demonstrate heap construction
    public static void main(String[] args) {
        int[] arr = {3, 9, 2, 1, 4, 5};
        int n = arr.length;

        buildHeap(arr, n);

        System.out.println("Max-Heap Array:");
        System.out.println(Arrays.toString(arr));
    }
}
```

**Output**:
```
Max-Heap Array:
[9, 4, 5, 1, 3, 2]
```

---

### **Heap Sort Algorithm**

**Steps**:
1. Build a Max-Heap.
2. Swap the root (largest) with the last element.
3. Reduce the heap size and call `heapify` for the root.
4. Repeat until the heap size becomes 1.

```java
import java.util.Arrays;

public class HeapSort {
    static void heapify(int[] arr, int n, int i) {
        int largest = i;
        int left = 2 * i + 1;
        int right = 2 * i + 2;

        if (left < n && arr[left] > arr[largest])
            largest = left;

        if (right < n && arr[right] > arr[largest])
            largest = right;

        if (largest != i) {
            int swap = arr[i];
            arr[i] = arr[largest];
            arr[largest] = swap;

            heapify(arr, n, largest);
        }
    }

    static void heapSort(int[] arr) {
        int n = arr.length;

        // Build Max-Heap
        for (int i = n / 2 - 1; i >= 0; i--)
            heapify(arr, n, i);

        // Extract elements from heap one by one
        for (int i = n - 1; i > 0; i--) {
            // Move current root to the end
            int temp = arr[0];
            arr[0] = arr[i];
            arr[i] = temp;

            // Call max heapify on reduced heap
            heapify(arr, i, 0);
        }
    }

    public static void main(String[] args) {
        int[] arr = {12, 11, 13, 5, 6, 7};

        heapSort(arr);

        System.out.println("Sorted Array:");
        System.out.println(Arrays.toString(arr));
    }
}
```

**Output**:
```
Sorted Array:
[5, 6, 7, 11, 12, 13]
```

---

### **Applications of Heaps**
1. **Priority Queue**: Scheduling and managing tasks efficiently.
2. **Dijkstra's Algorithm**: Finding the shortest path in graphs.
3. **Median Maintenance**: Streaming data problems.
4. **Heap Sort**: Sorting algorithms with O(n log n) complexity.

---

# **Chapter 13: Graphs**

---

### **What is a Graph?**

A **Graph** is a collection of:
1. **Vertices (Nodes)**: Represent entities (e.g., cities, computers).
2. **Edges (Connections)**: Represent relationships or links between nodes.

Graphs can be visualized as a network of nodes connected by lines.

---

### **Types of Graphs**

1. **Directed Graph (Digraph)**:
   - Edges have a direction.
   - Example: Webpages with hyperlinks.

2. **Undirected Graph**:
   - Edges have no direction.
   - Example: Social networks.

3. **Weighted Graph**:
   - Edges have weights or costs.
   - Example: Road networks with distances.

4. **Unweighted Graph**:
   - Edges are not weighted.
   - Example: Friendship graphs.

5. **Cyclic Graph**:
   - Contains at least one cycle (closed loop).

6. **Acyclic Graph**:
   - Does not contain any cycles.

---

### **Graph Representation**

Graphs can be represented in the following ways:

1. **Adjacency Matrix**:
   - A 2D array where `matrix[i][j] = 1` if there is an edge from vertex `i` to vertex `j`, otherwise `0`.

2. **Adjacency List**:
   - A list of lists where each vertex has a list of connected vertices.

3. **Edge List**:
   - A list of edges, where each edge is represented as a pair `(u, v)` or `(u, v, weight)`.

---

### **Applications of Graphs**
- **Social Networks**: Representing friendships or followers.
- **Navigation Systems**: Shortest paths in road networks.
- **Computer Networks**: Routing and packet transmission.
- **Dependency Resolution**: Build systems or project planning.
- **Machine Learning**: Graph-based clustering and recommendation systems.

---

### **Graph Traversal Algorithms**

#### **1. Breadth-First Search (BFS)**
- Explores nodes layer by layer (level order traversal).
- Uses a **queue** for implementation.

#### BFS Implementation in Java
```java
import java.util.*;

public class GraphBFS {
    private int vertices;
    private LinkedList<Integer>[] adjList;

    public GraphBFS(int vertices) {
        this.vertices = vertices;
        adjList = new LinkedList[vertices];
        for (int i = 0; i < vertices; i++) {
            adjList[i] = new LinkedList<>();
        }
    }

    public void addEdge(int src, int dest) {
        adjList[src].add(dest); // For directed graph
    }

    public void bfs(int start) {
        boolean[] visited = new boolean[vertices];
        Queue<Integer> queue = new LinkedList<>();

        visited[start] = true;
        queue.add(start);

        System.out.print("BFS Traversal: ");
        while (!queue.isEmpty()) {
            int node = queue.poll();
            System.out.print(node + " ");

            for (int neighbor : adjList[node]) {
                if (!visited[neighbor]) {
                    visited[neighbor] = true;
                    queue.add(neighbor);
                }
            }
        }
    }

    public static void main(String[] args) {
        GraphBFS graph = new GraphBFS(5);
        graph.addEdge(0, 1);
        graph.addEdge(0, 2);
        graph.addEdge(1, 3);
        graph.addEdge(2, 4);

        graph.bfs(0);
    }
}
```

**Output**:
```
BFS Traversal: 0 1 2 3 4
```

---

#### **2. Depth-First Search (DFS)**
- Explores as far as possible along one branch before backtracking.
- Uses a **stack** for implementation (or recursion).

#### DFS Implementation in Java
```java
import java.util.*;

public class GraphDFS {
    private int vertices;
    private LinkedList<Integer>[] adjList;

    public GraphDFS(int vertices) {
        this.vertices = vertices;
        adjList = new LinkedList[vertices];
        for (int i = 0; i < vertices; i++) {
            adjList[i] = new LinkedList<>();
        }
    }

    public void addEdge(int src, int dest) {
        adjList[src].add(dest); // For directed graph
    }

    public void dfsUtil(int node, boolean[] visited) {
        visited[node] = true;
        System.out.print(node + " ");

        for (int neighbor : adjList[node]) {
            if (!visited[neighbor]) {
                dfsUtil(neighbor, visited);
            }
        }
    }

    public void dfs(int start) {
        boolean[] visited = new boolean[vertices];
        System.out.print("DFS Traversal: ");
        dfsUtil(start, visited);
    }

    public static void main(String[] args) {
        GraphDFS graph = new GraphDFS(5);
        graph.addEdge(0, 1);
        graph.addEdge(0, 2);
        graph.addEdge(1, 3);
        graph.addEdge(2, 4);

        graph.dfs(0);
    }
}
```

**Output**:
```
DFS Traversal: 0 1 3 2 4
```

---

### **Shortest Path Algorithms**

#### **1. Dijkstra's Algorithm**
- Finds the shortest path from a source to all other nodes in a weighted graph.
- Uses a **priority queue**.

```java
import java.util.*;

public class Dijkstra {
    static class Edge {
        int dest, weight;

        Edge(int dest, int weight) {
            this.dest = dest;
            this.weight = weight;
        }
    }

    public static void dijkstra(List<List<Edge>> graph, int src) {
        int vertices = graph.size();
        int[] dist = new int[vertices];
        Arrays.fill(dist, Integer.MAX_VALUE);
        dist[src] = 0;

        PriorityQueue<int[]> pq = new PriorityQueue<>(Comparator.comparingInt(a -> a[1]));
        pq.add(new int[]{src, 0});

        while (!pq.isEmpty()) {
            int[] current = pq.poll();
            int node = current[0], nodeDist = current[1];

            if (nodeDist > dist[node]) continue;

            for (Edge edge : graph.get(node)) {
                int newDist = dist[node] + edge.weight;
                if (newDist < dist[edge.dest]) {
                    dist[edge.dest] = newDist;
                    pq.add(new int[]{edge.dest, newDist});
                }
            }
        }

        System.out.println("Shortest distances from source " + src + ":");
        for (int i = 0; i < vertices; i++) {
            System.out.println("To " + i + ": " + dist[i]);
        }
    }

    public static void main(String[] args) {
        int vertices = 5;
        List<List<Edge>> graph = new ArrayList<>();
        for (int i = 0; i < vertices; i++) graph.add(new ArrayList<>());

        graph.get(0).add(new Edge(1, 4));
        graph.get(0).add(new Edge(2, 1));
        graph.get(2).add(new Edge(1, 2));
        graph.get(1).add(new Edge(3, 1));
        graph.get(2).add(new Edge(3, 5));

        dijkstra(graph, 0);
    }
}
```

**Output**:
```
Shortest distances from source 0:
To 0: 0
To 1: 3
To 2: 1
To 3: 4
To 4: Infinity
```

---

### **Graph Algorithms**

| **Algorithm**           | **Purpose**                                     | **Time Complexity**       |
|--------------------------|------------------------------------------------|----------------------------|
| BFS                     | Traversal, shortest path in unweighted graphs   | O(V + E)                  |
| DFS                     | Traversal, cycle detection                      | O(V + E)                  |
| Dijkstra's Algorithm    | Shortest path in weighted graphs                | O((V + E) log V)          |
| Floyd-Warshall Algorithm | All-pairs shortest paths                       | O(V³)                     |
| Kruskal's Algorithm     | Minimum Spanning Tree                          | O(E log E)                |
| Prim's Algorithm        | Minimum Spanning Tree                          | O((V + E) log V)          |

---

# **Chapter 14: Searching Algorithms**

---

### **What are Searching Algorithms?**

Searching algorithms are used to find the position or presence of a specific element in a collection of elements (e.g., arrays, lists). They are fundamental to computer science and are widely used in various applications like databases, file systems, and search engines.

---

### **Types of Searching Algorithms**

1. **Linear Search**: A sequential search where each element is checked one by one.
2. **Binary Search**: A divide-and-conquer approach that works on sorted collections.
3. **Exponential Search**: Combines binary search and jumping, useful for unbounded or infinite lists.
4. **Jump Search**: Skips a fixed number of elements to reduce comparisons in sorted arrays.
5. **Interpolation Search**: Enhances binary search using the mathematical relationship between elements, ideal for uniformly distributed data.

---

### **Linear Search**

#### **How It Works**:
- Start from the first element and move sequentially.
- Compare each element with the target until it is found or the end of the array is reached.

#### **Time Complexity**:
- **Best Case**: O(1) (element found at the start)
- **Worst Case**: O(n) (element at the end or not present)

#### **Implementation in Java**:
```java
public class LinearSearch {
    public static int linearSearch(int[] arr, int target) {
        for (int i = 0; i < arr.length; i++) {
            if (arr[i] == target) {
                return i; // Return the index of the target
            }
        }
        return -1; // Element not found
    }

    public static void main(String[] args) {
        int[] arr = {3, 5, 7, 9, 11, 13};
        int target = 7;

        int result = linearSearch(arr, target);
        if (result != -1) {
            System.out.println("Element found at index: " + result);
        } else {
            System.out.println("Element not found");
        }
    }
}
```

**Output**:
```
Element found at index: 2
```

---

### **Binary Search**

#### **How It Works**:
1. Requires the collection to be sorted.
2. Divide the array into halves and compare the target with the middle element.
3. Narrow down the search to either the left or right half based on the comparison.

#### **Time Complexity**:
- **Best Case**: O(1)
- **Worst Case**: O(log n)

#### **Implementation in Java**:
```java
public class BinarySearch {
    public static int binarySearch(int[] arr, int target) {
        int left = 0, right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2; // Avoid overflow

            if (arr[mid] == target) {
                return mid; // Element found
            }
            if (arr[mid] < target) {
                left = mid + 1; // Search in the right half
            } else {
                right = mid - 1; // Search in the left half
            }
        }
        return -1; // Element not found
    }

    public static void main(String[] args) {
        int[] arr = {3, 5, 7, 9, 11, 13};
        int target = 9;

        int result = binarySearch(arr, target);
        if (result != -1) {
            System.out.println("Element found at index: " + result);
        } else {
            System.out.println("Element not found");
        }
    }
}
```

**Output**:
```
Element found at index: 3
```

---

### **Jump Search**

#### **How It Works**:
1. Jump ahead by a fixed number of steps (`√n`) to locate the range containing the target.
2. Perform a linear search within the identified range.

#### **Time Complexity**:
- **Best Case**: O(1)
- **Worst Case**: O(√n)

#### **Implementation in Java**:
```java
public class JumpSearch {
    public static int jumpSearch(int[] arr, int target) {
        int n = arr.length;
        int step = (int) Math.sqrt(n); // Jump size
        int prev = 0;

        while (arr[Math.min(step, n) - 1] < target) {
            prev = step;
            step += (int) Math.sqrt(n);
            if (prev >= n) {
                return -1; // Element not found
            }
        }

        for (int i = prev; i < Math.min(step, n); i++) {
            if (arr[i] == target) {
                return i; // Element found
            }
        }
        return -1; // Element not found
    }

    public static void main(String[] args) {
        int[] arr = {3, 5, 7, 9, 11, 13};
        int target = 11;

        int result = jumpSearch(arr, target);
        if (result != -1) {
            System.out.println("Element found at index: " + result);
        } else {
            System.out.println("Element not found");
        }
    }
}
```

**Output**:
```
Element found at index: 4
```

---

### **Interpolation Search**

#### **How It Works**:
1. Uses the formula:
   \[
   pos = low + \frac{(target - arr[low]) \times (high - low)}{arr[high] - arr[low]}
   \]
2. Ideal for uniformly distributed sorted data.

#### **Time Complexity**:
- **Best Case**: O(1)
- **Worst Case**: O(n) (for non-uniform data)

#### **Implementation in Java**:
```java
public class InterpolationSearch {
    public static int interpolationSearch(int[] arr, int target) {
        int low = 0, high = arr.length - 1;

        while (low <= high && target >= arr[low] && target <= arr[high]) {
            if (low == high) {
                if (arr[low] == target) return low;
                return -1;
            }

            int pos = low + ((target - arr[low]) * (high - low)) / (arr[high] - arr[low]);

            if (arr[pos] == target) {
                return pos; // Element found
            }
            if (arr[pos] < target) {
                low = pos + 1; // Move to right subarray
            } else {
                high = pos - 1; // Move to left subarray
            }
        }
        return -1; // Element not found
    }

    public static void main(String[] args) {
        int[] arr = {3, 5, 7, 9, 11, 13};
        int target = 13;

        int result = interpolationSearch(arr, target);
        if (result != -1) {
            System.out.println("Element found at index: " + result);
        } else {
            System.out.println("Element not found");
        }
    }
}
```

**Output**:
```
Element found at index: 5
```

---

### **Comparison of Searching Algorithms**

| Algorithm              | Best Case    | Worst Case   | Suitable For                              |
|------------------------|--------------|--------------|-------------------------------------------|
| **Linear Search**      | O(1)         | O(n)         | Small or unsorted datasets                |
| **Binary Search**      | O(1)         | O(log n)     | Sorted datasets                           |
| **Jump Search**        | O(1)         | O(√n)        | Sorted datasets, large arrays             |
| **Interpolation Search** | O(1)       | O(n)         | Sorted, uniformly distributed data        |

---

# **Chapter 15: Sorting Algorithms**

---

### **What are Sorting Algorithms?**

Sorting algorithms are techniques used to rearrange elements in a dataset in a specific order (ascending, descending, or based on custom conditions). Sorting is fundamental in optimizing searches, organizing data, and ensuring efficient processing in various applications.

---

### **Types of Sorting Algorithms**

1. **Bubble Sort**: A simple comparison-based algorithm.
2. **Selection Sort**: Selects the minimum/maximum element and places it in the sorted section.
3. **Insertion Sort**: Builds the sorted array one element at a time.
4. **Merge Sort**: A divide-and-conquer algorithm for efficient sorting.
5. **Quick Sort**: Partitions the array and sorts recursively.
6. **Heap Sort**: Utilizes a heap data structure to sort elements.
7. **Radix Sort**: Non-comparison-based algorithm for integers.
8. **Counting Sort**: Counts occurrences of elements to determine the sorted order.

---

### **1. Bubble Sort**

#### **How It Works**:
- Repeatedly compares adjacent elements and swaps them if they are in the wrong order.
- Process continues until no swaps are needed.

#### **Time Complexity**:
- **Best Case**: O(n) (already sorted)
- **Worst Case**: O(n²) (reverse sorted)

#### **Implementation in Java**:
```java
public class BubbleSort {
    public static void bubbleSort(int[] arr) {
        int n = arr.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = 0; j < n - i - 1; j++) {
                if (arr[j] > arr[j + 1]) {
                    // Swap elements
                    int temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                }
            }
        }
    }

    public static void main(String[] args) {
        int[] arr = {5, 3, 8, 4, 2};
        bubbleSort(arr);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

**Output**:
```
Sorted Array: [2, 3, 4, 5, 8]
```

---

### **2. Selection Sort**

#### **How It Works**:
- Divides the array into sorted and unsorted sections.
- Repeatedly finds the minimum/maximum element in the unsorted section and places it in the sorted section.

#### **Time Complexity**:
- **Best Case**: O(n²)
- **Worst Case**: O(n²)

#### **Implementation in Java**:
```java
public class SelectionSort {
    public static void selectionSort(int[] arr) {
        int n = arr.length;
        for (int i = 0; i < n - 1; i++) {
            int minIndex = i;
            for (int j = i + 1; j < n; j++) {
                if (arr[j] < arr[minIndex]) {
                    minIndex = j;
                }
            }
            // Swap elements
            int temp = arr[minIndex];
            arr[minIndex] = arr[i];
            arr[i] = temp;
        }
    }

    public static void main(String[] args) {
        int[] arr = {29, 10, 14, 37, 13};
        selectionSort(arr);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

**Output**:
```
Sorted Array: [10, 13, 14, 29, 37]
```

---

### **3. Insertion Sort**

#### **How It Works**:
- Builds the sorted array one element at a time.
- Inserts each new element into its correct position relative to already sorted elements.

#### **Time Complexity**:
- **Best Case**: O(n) (already sorted)
- **Worst Case**: O(n²)

#### **Implementation in Java**:
```java
public class InsertionSort {
    public static void insertionSort(int[] arr) {
        int n = arr.length;
        for (int i = 1; i < n; i++) {
            int key = arr[i];
            int j = i - 1;

            // Move elements of arr[0..i-1] that are greater than key
            while (j >= 0 && arr[j] > key) {
                arr[j + 1] = arr[j];
                j--;
            }
            arr[j + 1] = key;
        }
    }

    public static void main(String[] args) {
        int[] arr = {12, 11, 13, 5, 6};
        insertionSort(arr);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

**Output**:
```
Sorted Array: [5, 6, 11, 12, 13]
```

---

### **4. Merge Sort**

#### **How It Works**:
1. Recursively splits the array into halves.
2. Sorts each half and merges them back together.

#### **Time Complexity**:
- **Best Case**: O(n log n)
- **Worst Case**: O(n log n)

#### **Implementation in Java**:
```java
public class MergeSort {
    public static void mergeSort(int[] arr, int left, int right) {
        if (left < right) {
            int mid = (left + right) / 2;

            mergeSort(arr, left, mid);
            mergeSort(arr, mid + 1, right);

            merge(arr, left, mid, right);
        }
    }

    private static void merge(int[] arr, int left, int mid, int right) {
        int n1 = mid - left + 1;
        int n2 = right - mid;

        int[] leftArr = new int[n1];
        int[] rightArr = new int[n2];

        System.arraycopy(arr, left, leftArr, 0, n1);
        System.arraycopy(arr, mid + 1, rightArr, 0, n2);

        int i = 0, j = 0, k = left;

        while (i < n1 && j < n2) {
            if (leftArr[i] <= rightArr[j]) {
                arr[k++] = leftArr[i++];
            } else {
                arr[k++] = rightArr[j++];
            }
        }

        while (i < n1) arr[k++] = leftArr[i++];
        while (j < n2) arr[k++] = rightArr[j++];
    }

    public static void main(String[] args) {
        int[] arr = {38, 27, 43, 3, 9, 82, 10};
        mergeSort(arr, 0, arr.length - 1);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

**Output**:
```
Sorted Array: [3, 9, 10, 27, 38, 43, 82]
```

---

### **Sorting Algorithm Comparison**

| Algorithm       | Time Complexity (Best) | Time Complexity (Worst) | Space Complexity | Stability |
|------------------|-------------------------|--------------------------|-------------------|-----------|
| Bubble Sort     | O(n)                   | O(n²)                   | O(1)             | Stable    |
| Selection Sort  | O(n²)                  | O(n²)                   | O(1)             | Unstable  |
| Insertion Sort  | O(n)                   | O(n²)                   | O(1)             | Stable    |
| Merge Sort      | O(n log n)             | O(n log n)              | O(n)             | Stable    |

---

### **5. Quick Sort**

---

#### **What is Quick Sort?**
Quick Sort is a divide-and-conquer sorting algorithm that selects a **pivot element** and partitions the array around the pivot. All elements smaller than the pivot are placed to the left, and all elements larger are placed to the right. The process is then recursively applied to the left and right subarrays.

---

#### **How It Works**:
1. Pick a pivot element (commonly the last or middle element).
2. Partition the array:
   - Rearrange elements such that elements less than the pivot are on the left and elements greater are on the right.
3. Recursively apply the same process to the subarrays.

---

#### **Time Complexity**:
- **Best Case**: O(n log n) (balanced partitioning)
- **Average Case**: O(n log n)
- **Worst Case**: O(n²) (highly unbalanced partitioning, e.g., already sorted array)

#### **Space Complexity**:
- O(log n) (due to recursive calls)

---

#### **Implementation in Java**:
```java
public class QuickSort {
    public static void quickSort(int[] arr, int low, int high) {
        if (low < high) {
            int partitionIndex = partition(arr, low, high);
            
            // Recursively sort the subarrays
            quickSort(arr, low, partitionIndex - 1);
            quickSort(arr, partitionIndex + 1, high);
        }
    }

    private static int partition(int[] arr, int low, int high) {
        int pivot = arr[high]; // Choosing the last element as pivot
        int i = low - 1;

        for (int j = low; j < high; j++) {
            if (arr[j] <= pivot) {
                i++;
                // Swap elements
                int temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }

        // Place the pivot in its correct position
        int temp = arr[i + 1];
        arr[i + 1] = arr[high];
        arr[high] = temp;

        return i + 1;
    }

    public static void main(String[] args) {
        int[] arr = {10, 7, 8, 9, 1, 5};
        quickSort(arr, 0, arr.length - 1);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

---

**Output**:
```
Sorted Array: [1, 5, 7, 8, 9, 10]
```

**Explanation**:
- The pivot is placed in its correct position, and the left and right sections are sorted recursively.

---

### **6. Heap Sort**

---

#### **What is Heap Sort?**
Heap Sort is a comparison-based sorting algorithm that builds a **binary heap** (a complete binary tree where the parent node is greater than or equal to its children) from the array. It repeatedly extracts the largest element (the root of the heap) and places it at the end of the array.

---

#### **How It Works**:
1. Build a **max heap** from the array.
2. Swap the root (largest element) with the last element.
3. Reduce the heap size and repeat heapifying until the array is sorted.

---

#### **Time Complexity**:
- **Best Case**: O(n log n)
- **Worst Case**: O(n log n)
- **Average Case**: O(n log n)

#### **Space Complexity**:
- O(1) (in-place sorting)

---

#### **Implementation in Java**:
```java
public class HeapSort {
    public static void heapSort(int[] arr) {
        int n = arr.length;

        // Build max heap
        for (int i = n / 2 - 1; i >= 0; i--) {
            heapify(arr, n, i);
        }

        // Extract elements from heap
        for (int i = n - 1; i >= 0; i--) {
            // Move current root to end
            int temp = arr[0];
            arr[0] = arr[i];
            arr[i] = temp;

            // Heapify the reduced heap
            heapify(arr, i, 0);
        }
    }

    private static void heapify(int[] arr, int n, int i) {
        int largest = i; // Initialize largest as root
        int left = 2 * i + 1;
        int right = 2 * i + 2;

        // If left child is larger than root
        if (left < n && arr[left] > arr[largest]) {
            largest = left;
        }

        // If right child is larger than largest so far
        if (right < n && arr[right] > arr[largest]) {
            largest = right;
        }

        // If largest is not root
        if (largest != i) {
            int temp = arr[i];
            arr[i] = arr[largest];
            arr[largest] = temp;

            // Recursively heapify the affected sub-tree
            heapify(arr, n, largest);
        }
    }

    public static void main(String[] args) {
        int[] arr = {12, 11, 13, 5, 6, 7};
        heapSort(arr);
        System.out.println("Sorted Array: " + java.util.Arrays.toString(arr));
    }
}
```

---

**Output**:
```
Sorted Array: [5, 6, 7, 11, 12, 13]
```

**Explanation**:
- The max heap is built, and the largest element (root) is repeatedly moved to the end while reducing the heap size.

---

### **Sorting Algorithm Summary**

| Algorithm       | Best Case   | Worst Case   | Average Case | Space Complexity | Stability |
|------------------|-------------|--------------|--------------|------------------|-----------|
| Quick Sort      | O(n log n)  | O(n²)        | O(n log n)   | O(log n)         | Unstable  |
| Heap Sort       | O(n log n)  | O(n log n)   | O(n log n)   | O(1)             | Unstable  |

---


###  **Advanced Sorting Algorithms**

---

#### **1. Radix Sort**

---

#### **What is Radix Sort?**
Radix Sort is a **non-comparative sorting algorithm** that processes numbers digit by digit, starting from the least significant digit (LSD) to the most significant digit (MSD). It uses a stable sorting algorithm (like counting sort) to maintain the relative order of numbers with equal significant digits.

---

#### **How It Works**:
1. Find the maximum number to determine the number of digits.
2. Iterate through each digit (starting from the least significant).
3. Use Counting Sort as a subroutine to sort numbers based on the current digit.

---

#### **Time Complexity**:
- **Best Case**: O(nk)  
- **Worst Case**: O(nk)  
- **Average Case**: O(nk)  
   *(where `n` is the number of elements and `k` is the number of digits in the largest number)*  

#### **Space Complexity**:
- O(n + k)  

---

#### **Implementation in Java**:
```java
import java.util.Arrays;

public class RadixSort {

    public static void radixSort(int[] arr) {
        int max = getMax(arr);
        for (int exp = 1; max / exp > 0; exp *= 10) {
            countingSort(arr, exp);
        }
    }

    private static int getMax(int[] arr) {
        int max = arr[0];
        for (int num : arr) {
            if (num > max) {
                max = num;
            }
        }
        return max;
    }

    private static void countingSort(int[] arr, int exp) {
        int n = arr.length;
        int[] output = new int[n];
        int[] count = new int[10];

        // Count occurrences
        for (int num : arr) {
            count[(num / exp) % 10]++;
        }

        // Update count array
        for (int i = 1; i < 10; i++) {
            count[i] += count[i - 1];
        }

        // Build output array
        for (int i = n - 1; i >= 0; i--) {
            int index = (arr[i] / exp) % 10;
            output[count[index] - 1] = arr[i];
            count[index]--;
        }

        // Copy sorted elements back to original array
        System.arraycopy(output, 0, arr, 0, n);
    }

    public static void main(String[] args) {
        int[] arr = {170, 45, 75, 90, 802, 24, 2, 66};
        radixSort(arr);
        System.out.println("Sorted Array: " + Arrays.toString(arr));
    }
}
```

---

**Output**:
```
Sorted Array: [2, 24, 45, 66, 75, 90, 170, 802]
```

**Explanation**:
- The algorithm sorts based on each digit, ensuring stability throughout the process.

---

#### **2. Counting Sort**

---

#### **What is Counting Sort?**
Counting Sort is a **non-comparative algorithm** used to sort integers by counting the occurrences of each element and placing them directly in the output array.

---

#### **How It Works**:
1. Find the range of input data.
2. Count the occurrences of each element.
3. Modify the count array to reflect positions in the output.
4. Place elements in the sorted order using the count array.

---

#### **Time Complexity**:
- **Best Case**: O(n + k)  
- **Worst Case**: O(n + k)  
- **Average Case**: O(n + k)  
   *(where `n` is the number of elements and `k` is the range of input)*  

#### **Space Complexity**:
- O(n + k)

---

#### **Implementation in Java**:
```java
import java.util.Arrays;

public class CountingSort {

    public static void countingSort(int[] arr) {
        int max = getMax(arr);
        int[] count = new int[max + 1];
        int[] output = new int[arr.length];

        // Count occurrences
        for (int num : arr) {
            count[num]++;
        }

        // Modify count array to store cumulative positions
        for (int i = 1; i < count.length; i++) {
            count[i] += count[i - 1];
        }

        // Build the output array
        for (int i = arr.length - 1; i >= 0; i--) {
            output[count[arr[i]] - 1] = arr[i];
            count[arr[i]]--;
        }

        // Copy sorted elements back to the original array
        System.arraycopy(output, 0, arr, 0, arr.length);
    }

    private static int getMax(int[] arr) {
        int max = arr[0];
        for (int num : arr) {
            if (num > max) {
                max = num;
            }
        }
        return max;
    }

    public static void main(String[] args) {
        int[] arr = {4, 2, 2, 8, 3, 3, 1};
        countingSort(arr);
        System.out.println("Sorted Array: " + Arrays.toString(arr));
    }
}
```

---

**Output**:
```
Sorted Array: [1, 2, 2, 3, 3, 4, 8]
```

**Explanation**:
- The algorithm counts each element and calculates their final positions in the sorted array.

---

#### **3. Bucket Sort**

---

#### **What is Bucket Sort?**
Bucket Sort is a **distribution-based sorting algorithm** that distributes elements into several buckets. Each bucket is then sorted individually (usually with another sorting algorithm), and the results are concatenated.

---

#### **How It Works**:
1. Divide the range of data into several buckets.
2. Distribute elements into buckets.
3. Sort each bucket individually.
4. Merge all buckets into a single sorted array.

---

#### **Time Complexity**:
- **Best Case**: O(n) (when elements are evenly distributed)  
- **Worst Case**: O(n²) (when all elements are in one bucket)  
- **Average Case**: O(n + k)  

#### **Space Complexity**:
- O(n + k)

---

# **Chapter 16: Recursion**

#### **What is Recursion?**
Recursion is a programming technique in which a function calls itself in order to solve smaller instances of the same problem. This technique is useful for problems that can be broken down into simpler subproblems of the same type.

A recursive function has two key components:
1. **Base Case**: The condition under which the function stops calling itself.
2. **Recursive Case**: The case where the function calls itself with a smaller or simpler problem.

---

#### **Advantages of Recursion**
1. **Simplifies Complex Problems**: Recursion can often provide a simpler and more elegant solution for problems that have a natural recursive structure (e.g., tree traversal, divide and conquer).
2. **Reduces Code Size**: Recursive solutions can often be more concise and easier to understand compared to iterative solutions.
3. **State Preservation**: Recursive functions maintain their state across recursive calls, which can be useful for certain types of problems, like backtracking algorithms.

---

#### **Limitations of Recursion**
1. **Memory Overhead**: Each recursive call adds a new layer to the call stack, leading to high memory usage, especially for deep recursion.
2. **Performance**: Recursion can be slower than iteration due to the overhead of function calls, especially if not optimized (e.g., using tail recursion).
3. **Stack Overflow**: Deep recursion can lead to a stack overflow error if the recursion depth exceeds the maximum call stack size.

---

#### **Recursive vs Iterative Solutions**
- **Recursive Solutions**: Involve function calls to solve subproblems. While they provide clean and concise solutions, they can suffer from performance issues due to repeated function calls and memory overhead.
  
- **Iterative Solutions**: Use loops to solve a problem, which is often more efficient in terms of memory usage and performance. However, they may be harder to understand or implement in certain problems compared to recursion.

### **Examples:**

#### 1. **Factorial Using Recursion**

The factorial of a non-negative integer `n` is the product of all positive integers less than or equal to `n`. The recursive formula for factorial is:

\[
\text{Factorial}(n) = n \times \text{Factorial}(n - 1)
\]

**Base Case**: Factorial of 0 is 1.

---

**Code** (Java):

```java
public class Factorial {

    // Recursive function to calculate factorial
    public static int factorial(int n) {
        if (n == 0) { // Base case
            return 1;
        }
        return n * factorial(n - 1); // Recursive case
    }

    public static void main(String[] args) {
        int num = 5;
        System.out.println("Factorial of " + num + " is: " + factorial(num));
    }
}
```

**Output**:
```
Factorial of 5 is: 120
```

**Explanation**:
- The recursive function calls itself until the base case (`n == 0`) is reached, and then multiplies all the values during the "return" phase of the recursion.

---

#### 2. **Fibonacci Series Using Recursion**

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, starting from 0 and 1. The recursive formula for Fibonacci is:

\[
\text{Fibonacci}(n) = \text{Fibonacci}(n - 1) + \text{Fibonacci}(n - 2)
\]

**Base Cases**:  
- Fibonacci(0) = 0  
- Fibonacci(1) = 1

---

**Code** (Java):

```java
public class Fibonacci {

    // Recursive function to find the nth Fibonacci number
    public static int fibonacci(int n) {
        if (n <= 1) { // Base case
            return n;
        }
        return fibonacci(n - 1) + fibonacci(n - 2); // Recursive case
    }

    public static void main(String[] args) {
        int num = 6;
        System.out.println("Fibonacci of " + num + " is: " + fibonacci(num));
    }
}
```

**Output**:
```
Fibonacci of 6 is: 8
```

**Explanation**:
- The function calls itself recursively until it reaches the base cases (n = 0 or n = 1), then sums up the results.

---

#### 3. **Tower of Hanoi Problem**

The Tower of Hanoi is a classic problem where you have three rods and a number of disks of different sizes. The goal is to move all the disks from one rod to another, following these rules:
1. Only one disk can be moved at a time.
2. A disk can only be placed on top of a larger disk or on an empty rod.
3. All disks start on the first rod and must end on the third rod.

---

**Code** (Java):

```java
public class TowerOfHanoi {

    // Recursive function to solve the Tower of Hanoi puzzle
    public static void solveHanoi(int n, String source, String auxiliary, String target) {
        if (n == 1) { // Base case: only one disk
            System.out.println("Move disk 1 from " + source + " to " + target);
            return;
        }
        solveHanoi(n - 1, source, target, auxiliary); // Move n-1 disks to auxiliary
        System.out.println("Move disk " + n + " from " + source + " to " + target); // Move the nth disk
        solveHanoi(n - 1, auxiliary, source, target); // Move the n-1 disks to target
    }

    public static void main(String[] args) {
        int disks = 3;
        solveHanoi(disks, "A", "B", "C");
    }
}
```

**Output**:
```
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C
```

**Explanation**:
- The `solveHanoi` function recursively moves disks between the rods by breaking down the problem into smaller subproblems.

---

### **Recursion in Practice**

While recursion is a powerful technique, it's important to consider its performance implications. For problems that require heavy recursion (e.g., deep recursion levels), consider the following:
- **Tail Recursion**: A form of recursion where the recursive call is the last operation in the function. Tail recursion is more memory-efficient since the compiler can optimize it.
- **Memoization**: Caching the results of recursive calls to avoid redundant calculations.
- **Iterative Solutions**: Some problems that can be solved recursively can also be solved iteratively, which may be more efficient in terms of memory usage.

---

### **Time and Space Complexity of Recursion**
- **Time Complexity**: Depends on the number of recursive calls and the work done in each call. For example, in Fibonacci, the time complexity is \(O(2^n)\) due to overlapping subproblems.
- **Space Complexity**: Space complexity is determined by the depth of recursion and the amount of memory used for each function call. For example, the space complexity of the recursive Fibonacci solution is \(O(n)\), as the maximum depth of recursion is \(n\).

---

#### **Conclusion**
Recursion is an essential concept in computer science that allows for elegant solutions to problems. However, it is important to weigh its advantages against its limitations, particularly when dealing with problems that have deep recursion levels. In such cases, techniques like memoization, tail recursion, or converting the solution to an iterative one can help optimize the performance.



# **Chapter 17: Dynamic Programming**

---

Dynamic Programming (DP) is a **problem-solving paradigm** used to solve optimization problems by breaking them down into smaller overlapping subproblems. It is particularly useful for problems with overlapping subproblems and optimal substructure properties.

---

#### **Key Concepts in Dynamic Programming**

1. **Overlapping Subproblems**:
   - A problem is said to have overlapping subproblems if it can be broken down into smaller subproblems that are reused multiple times.
   - Example: Fibonacci Sequence.

2. **Optimal Substructure**:
   - A problem exhibits an optimal substructure if the solution to the problem can be constructed efficiently from the solutions of its subproblems.
   - Example: Shortest Path in a Graph.

3. **Memoization (Top-Down Approach)**:
   - Store the results of previously solved subproblems in a data structure (e.g., array, map) to avoid redundant computation.
   - Example: Recursive Fibonacci with memoization.

4. **Tabulation (Bottom-Up Approach)**:
   - Build the solution iteratively using a table to store results of subproblems.
   - Example: Iterative Fibonacci.

---

#### **Time Complexity and Space Complexity**

- **Memoization**:
  - Time Complexity: O(n) (for most problems with linear overlapping subproblems).
  - Space Complexity: O(n) (to store results in memory).

- **Tabulation**:
  - Time Complexity: O(n).
  - Space Complexity: O(n) (can be reduced to O(1) for some problems).

---

### **Common Dynamic Programming Problems**

---

#### **1. Fibonacci Sequence**

---

**Problem**: Compute the `n-th` Fibonacci number.

---

**Recursive Approach with Memoization**:
```java
import java.util.HashMap;

public class FibonacciMemoization {

    private static HashMap<Integer, Integer> memo = new HashMap<>();

    public static int fibonacci(int n) {
        if (n <= 1) {
            return n;
        }
        if (!memo.containsKey(n)) {
            memo.put(n, fibonacci(n - 1) + fibonacci(n - 2));
        }
        return memo.get(n);
    }

    public static void main(String[] args) {
        int n = 10;
        System.out.println("Fibonacci of " + n + " is: " + fibonacci(n));
    }
}
```

**Output**:
```
Fibonacci of 10 is: 55
```

**Explanation**:
- The recursive function avoids redundant calculations by storing results in a `HashMap`.

---

**Iterative Approach with Tabulation**:
```java
public class FibonacciTabulation {

    public static int fibonacci(int n) {
        if (n <= 1) {
            return n;
        }
        int[] dp = new int[n + 1];
        dp[0] = 0;
        dp[1] = 1;

        for (int i = 2; i <= n; i++) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }

        return dp[n];
    }

    public static void main(String[] args) {
        int n = 10;
        System.out.println("Fibonacci of " + n + " is: " + fibonacci(n));
    }
}
```

**Output**:
```
Fibonacci of 10 is: 55
```

---

#### **2. Longest Common Subsequence (LCS)**

---

**Problem**: Given two strings `s1` and `s2`, find the length of their longest common subsequence.

---

**Recursive Approach with Memoization**:
```java
public class LCSMemoization {

    public static int lcs(String s1, String s2, int m, int n, int[][] memo) {
        if (m == 0 || n == 0) {
            return 0;
        }
        if (memo[m][n] != -1) {
            return memo[m][n];
        }
        if (s1.charAt(m - 1) == s2.charAt(n - 1)) {
            memo[m][n] = 1 + lcs(s1, s2, m - 1, n - 1, memo);
        } else {
            memo[m][n] = Math.max(lcs(s1, s2, m - 1, n, memo), lcs(s1, s2, m, n - 1, memo));
        }
        return memo[m][n];
    }

    public static void main(String[] args) {
        String s1 = "abcde";
        String s2 = "ace";
        int m = s1.length();
        int n = s2.length();
        int[][] memo = new int[m + 1][n + 1];
        for (int[] row : memo) {
            java.util.Arrays.fill(row, -1);
        }
        System.out.println("Length of LCS: " + lcs(s1, s2, m, n, memo));
    }
}
```

**Output**:
```
Length of LCS: 3
```

---

**Iterative Approach with Tabulation**:
```java
public class LCSTabulation {

    public static int lcs(String s1, String s2) {
        int m = s1.length();
        int n = s2.length();
        int[][] dp = new int[m + 1][n + 1];

        for (int i = 1; i <= m; i++) {
            for (int j = 1; j <= n; j++) {
                if (s1.charAt(i - 1) == s2.charAt(j - 1)) {
                    dp[i][j] = 1 + dp[i - 1][j - 1];
                } else {
                    dp[i][j] = Math.max(dp[i - 1][j], dp[i][j - 1]);
                }
            }
        }

        return dp[m][n];
    }

    public static void main(String[] args) {
        String s1 = "abcde";
        String s2 = "ace";
        System.out.println("Length of LCS: " + lcs(s1, s2));
    }
}
```

**Output**:
```
Length of LCS: 3
```

---

## **Advanced Dynamic Programming Concepts**

Dynamic Programming can be extended to solve more complex problems like optimization, multi-dimensional DP, and state-space problems. Below are advanced techniques and problem types commonly encountered in dynamic programming.

---

### **1. Matrix Chain Multiplication**

**Problem**: Given dimensions of matrices, find the minimum cost of multiplying the matrices in the most efficient order.

**Approach**:  
- Use a DP table to store the minimum number of scalar multiplications for each subproblem.

---

**Code**:
```java
public class MatrixChainMultiplication {

    public static int matrixChainOrder(int[] dims) {
        int n = dims.length;
        int[][] dp = new int[n][n];

        // Base case: cost is 0 when multiplying one matrix
        for (int i = 1; i < n; i++) {
            dp[i][i] = 0;
        }

        // l is the chain length
        for (int l = 2; l < n; l++) {
            for (int i = 1; i < n - l + 1; i++) {
                int j = i + l - 1;
                dp[i][j] = Integer.MAX_VALUE;
                for (int k = i; k < j; k++) {
                    int cost = dp[i][k] + dp[k + 1][j] + dims[i - 1] * dims[k] * dims[j];
                    dp[i][j] = Math.min(dp[i][j], cost);
                }
            }
        }

        return dp[1][n - 1];
    }

    public static void main(String[] args) {
        int[] dims = {1, 2, 3, 4};
        System.out.println("Minimum cost: " + matrixChainOrder(dims));
    }
}
```

**Output**:
```
Minimum cost: 18
```

**Explanation**:
- Each `dp[i][j]` represents the minimum cost to multiply matrices `i` to `j`.
- The inner loop tests every possible partition point `k`.

**Time Complexity**: \(O(n^3)\)  
**Space Complexity**: \(O(n^2)\)

---

### **2. Longest Increasing Subsequence (LIS)**

**Problem**: Find the length of the longest increasing subsequence in an array.

---

**Approach Using DP**:
```java
public class LongestIncreasingSubsequence {

    public static int lis(int[] nums) {
        int n = nums.length;
        int[] dp = new int[n];
        java.util.Arrays.fill(dp, 1);

        int maxLIS = 1;
        for (int i = 1; i < n; i++) {
            for (int j = 0; j < i; j++) {
                if (nums[i] > nums[j]) {
                    dp[i] = Math.max(dp[i], dp[j] + 1);
                }
            }
            maxLIS = Math.max(maxLIS, dp[i]);
        }

        return maxLIS;
    }

    public static void main(String[] args) {
        int[] nums = {10, 9, 2, 5, 3, 7, 101, 18};
        System.out.println("Length of LIS: " + lis(nums));
    }
}
```

**Output**:
```
Length of LIS: 4
```

**Explanation**:
- `dp[i]` stores the length of the LIS ending at index `i`.
- Transition: If `nums[j] < nums[i]`, update `dp[i]`.

**Time Complexity**: \(O(n^2)\)  
**Space Complexity**: \(O(n)\)

---

### **3. Knapsack Problem**

**Problem**: Given a list of weights and values, and a maximum weight capacity, determine the maximum value that can be obtained.

---

**Approach Using DP (0/1 Knapsack)**:
```java
public class Knapsack {

    public static int knapsack(int[] weights, int[] values, int capacity) {
        int n = weights.length;
        int[][] dp = new int[n + 1][capacity + 1];

        for (int i = 1; i <= n; i++) {
            for (int w = 0; w <= capacity; w++) {
                if (weights[i - 1] <= w) {
                    dp[i][w] = Math.max(dp[i - 1][w], dp[i - 1][w - weights[i - 1]] + values[i - 1]);
                } else {
                    dp[i][w] = dp[i - 1][w];
                }
            }
        }

        return dp[n][capacity];
    }

    public static void main(String[] args) {
        int[] weights = {1, 3, 4, 5};
        int[] values = {1, 4, 5, 7};
        int capacity = 7;
        System.out.println("Maximum value: " + knapsack(weights, values, capacity));
    }
}
```

**Output**:
```
Maximum value: 9
```

**Explanation**:
- `dp[i][w]` represents the maximum value achievable with the first `i` items and capacity `w`.

**Time Complexity**: \(O(n \cdot W)\)  
**Space Complexity**: \(O(n \cdot W)\)

---

### **4. Edit Distance (Levenshtein Distance)**

**Problem**: Find the minimum number of operations required to convert one string into another. Operations include insert, delete, and replace.

---

**Approach Using DP**:
```java
public class EditDistance {

    public static int editDistance(String s1, String s2) {
        int m = s1.length();
        int n = s2.length();
        int[][] dp = new int[m + 1][n + 1];

        for (int i = 0; i <= m; i++) {
            for (int j = 0; j <= n; j++) {
                if (i == 0) {
                    dp[i][j] = j; // All insertions
                } else if (j == 0) {
                    dp[i][j] = i; // All deletions
                } else if (s1.charAt(i - 1) == s2.charAt(j - 1)) {
                    dp[i][j] = dp[i - 1][j - 1];
                } else {
                    dp[i][j] = 1 + Math.min(dp[i - 1][j - 1], Math.min(dp[i - 1][j], dp[i][j - 1]));
                }
            }
        }

        return dp[m][n];
    }

    public static void main(String[] args) {
        String s1 = "horse";
        String s2 = "ros";
        System.out.println("Edit Distance: " + editDistance(s1, s2));
    }
}
```

**Output**:
```
Edit Distance: 3
```

**Explanation**:
- `dp[i][j]` represents the minimum edit distance between the first `i` characters of `s1` and the first `j` characters of `s2`.

**Time Complexity**: \(O(m \cdot n)\)  
**Space Complexity**: \(O(m \cdot n)\)

---

# **Chapter 18: Backtracking**

#### **Introduction to Backtracking**

Backtracking is a general algorithm for finding all (or some) solutions to problems that incrementally build candidates for solutions. It abandons a candidate as soon as it determines that the candidate cannot possibly lead to a valid solution. It is used for solving problems that require exhaustive search in a systematic manner, like constraint satisfaction problems (CSP), puzzles, and combinatorial problems.

Backtracking works by choosing a candidate, recursively trying to build a solution, and when it reaches a dead end, it undoes the previous choices (backtracks) and tries a new candidate. The algorithm continues this process until it finds a valid solution or exhausts all possible solutions.

---

#### **Basic Idea of Backtracking**

1. **Choice**: Make a decision or choose an option.
2. **Constraint**: Verify if the decision is valid by checking the constraints.
3. **Goal**: Check if the current choice leads to the goal. If yes, return the solution; if not, backtrack and make a different decision.

Backtracking is often implemented recursively, and it works best for problems where solutions involve exploration of multiple potential choices that can be abandoned early if they lead to dead ends.

---

#### **N-Queens Problem**

The N-Queens problem is a classic example of a constraint satisfaction problem. The task is to place **N queens** on an **N x N chessboard** so that no two queens threaten each other. This means that no two queens can share the same row, column, or diagonal.

##### **Steps to Solve N-Queens Problem Using Backtracking:**
1. Start by placing queens one by one in different columns.
2. For each queen, check if it is safe to place it in the current position (i.e., no other queens can attack it).
3. If placing the queen results in a valid configuration, recursively try to place the next queen.
4. If placing the queen results in an invalid configuration, backtrack by removing the queen and trying the next position.

---

##### **Code Implementation (Java):**

```java
public class NQueens {

    // Utility function to print the solution board
    public static void printBoard(int[][] board) {
        int N = board.length;
        for (int i = 0; i < N; i++) {
            for (int j = 0; j < N; j++) {
                System.out.print(board[i][j] == 1 ? "Q " : ". ");
            }
            System.out.println();
        }
        System.out.println();
    }

    // Function to check if a queen can be placed on board[row][col]
    public static boolean isSafe(int[][] board, int row, int col) {
        int N = board.length;
        
        // Check the column
        for (int i = 0; i < row; i++) {
            if (board[i][col] == 1) return false;
        }

        // Check the upper-left diagonal
        for (int i = row, j = col; i >= 0 && j >= 0; i--, j--) {
            if (board[i][j] == 1) return false;
        }

        // Check the upper-right diagonal
        for (int i = row, j = col; i >= 0 && j < N; i--, j++) {
            if (board[i][j] == 1) return false;
        }

        return true;
    }

    // Recursive function to solve the N-Queens problem
    public static boolean solveNQueens(int[][] board, int row) {
        int N = board.length;
        
        // If all queens are placed
        if (row >= N) {
            printBoard(board);  // Print the solution
            return true;
        }

        // Try all columns in the current row
        boolean res = false;
        for (int i = 0; i < N; i++) {
            if (isSafe(board, row, i)) {
                board[row][i] = 1;  // Place the queen
                res = solveNQueens(board, row + 1) || res;  // Recur to place the rest
                board[row][i] = 0;  // Backtrack
            }
        }
        return res;
    }

    public static void main(String[] args) {
        int N = 4;  // Change this to try larger boards
        int[][] board = new int[N][N];  // Initialize the board
        solveNQueens(board, 0);  // Solve the N-Queens problem starting from row 0
    }
}
```

##### **Explanation**:
- **`isSafe()`**: This function checks if it is safe to place a queen in the specified position `(row, col)`. It checks for conflicts in the column and diagonals.
- **`solveNQueens()`**: This is the backtracking function that attempts to place queens one by one in different columns and rows. If it finds a safe spot, it moves to the next row, else it backtracks.

##### **Output for N = 4**:
```
. Q . .
. . . Q
Q . . .
. . Q .
```

---

#### **Subset Sum Problem**

The Subset Sum problem is a classic example of a problem that can be solved using backtracking. The problem is to determine if there exists a subset of a given set of integers such that the sum of the subset is equal to a given target value.

##### **Steps to Solve Subset Sum Problem Using Backtracking:**
1. Start with an empty subset and try adding elements one by one.
2. At each step, decide whether to include the current element in the subset or exclude it.
3. If the sum of the selected subset matches the target, return true. If the sum exceeds the target, backtrack.

---

##### **Code Implementation (Java):**

```java
public class SubsetSum {

    // Function to check if there is a subset with the given sum
    public static boolean isSubsetSum(int[] arr, int n, int sum) {
        // Base case: sum becomes 0, subset found
        if (sum == 0) return true;
        
        // If no elements left or sum becomes negative, no subset found
        if (n == 0 || sum < 0) return false;
        
        // Include current element or exclude current element
        return isSubsetSum(arr, n - 1, sum) || isSubsetSum(arr, n - 1, sum - arr[n - 1]);
    }

    public static void main(String[] args) {
        int[] arr = {3, 34, 4, 12, 5, 2};
        int sum = 9;
        int n = arr.length;
        
        if (isSubsetSum(arr, n, sum)) {
            System.out.println("Found a subset with the given sum.");
        } else {
            System.out.println("No subset with the given sum.");
        }
    }
}
```

##### **Explanation**:
- The function `isSubsetSum()` checks if there is a subset of the array that adds up to the target sum. It makes recursive calls, either including or excluding each element.

##### **Output**:
```
Found a subset with the given sum.
```

---

#### **Applications of Backtracking (Puzzle Solving)**

Backtracking is widely used in solving puzzles. The ability to explore all possibilities and backtrack when a solution is not possible makes it an excellent fit for such problems. Some popular puzzle-solving problems where backtracking is used include:

1. **Sudoku Solver**: Fill a Sudoku grid by exploring all possible placements for each number.
2. **Crossword Puzzle Solver**: Solve a crossword by trying to place words into a grid.
3. **Maze Solving**: Find a path through a maze using backtracking.

##### **Example: Solving a Sudoku Puzzle Using Backtracking**

A Sudoku puzzle is a 9x9 grid, and the goal is to fill in the grid such that each row, column, and 3x3 subgrid contains the numbers 1-9 without repetition. This problem can be solved using backtracking by trying all possible placements of a number in an empty cell and backtracking when a number leads to an invalid state.

---

### **Conclusion**
Backtracking is a versatile algorithmic technique that can be applied to a wide range of problems, from puzzles to combinatorial problems. It is particularly useful when the solution space is large and there are constraints that can be used to prune the search space efficiently. However, backtracking can be computationally expensive, and its efficiency depends on the specific problem and the nature of the constraints.


# **Chapter 19: Advanced Data Structures**

In this chapter, we will explore some advanced data structures that are crucial for solving specific problems in computer science. These data structures provide efficient solutions to problems such as range queries, prefix matching, dynamic connectivity, and others. We will cover **Tries**, **Segment Trees**, **Fenwick Trees**, and **Disjoint Set Union (Union-Find)** in depth, including their structure, use cases, and practical implementations.

---

### **1. Tries (Prefix Trees)**

#### **What is a Trie?**

A **Trie**, also known as a **prefix tree**, is a tree-like data structure that is used to store a dynamic set of strings, where keys are usually strings. Unlike a binary tree, where each node represents a single character, a **Trie** stores strings in a way that common prefixes are shared.

Each node of a Trie represents a character of a string, and paths through the tree represent prefixes of strings. This allows for very efficient operations on strings such as search, insert, and delete.

#### **Operations in Trie:**
- **Insert**: Add a new string into the Trie.
- **Search**: Check if a string exists in the Trie.
- **Delete**: Remove a string from the Trie.
- **Prefix Search**: Check if there exists any string in the Trie with a given prefix.

#### **Time Complexity:**
- **Insert**: O(L) where L is the length of the string.
- **Search**: O(L) where L is the length of the string.
- **Space Complexity**: O(N * L) where N is the number of strings and L is the maximum length of any string.

#### **Code Implementation (Java):**

```java
class TrieNode {
    TrieNode[] children = new TrieNode[26];
    boolean isEndOfWord = false;
}

public class Trie {
    private TrieNode root;

    public Trie() {
        root = new TrieNode();
    }

    // Insert a word into the Trie
    public void insert(String word) {
        TrieNode node = root;
        for (char c : word.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                node.children[c - 'a'] = new TrieNode();
            }
            node = node.children[c - 'a'];
        }
        node.isEndOfWord = true;
    }

    // Search for a word in the Trie
    public boolean search(String word) {
        TrieNode node = root;
        for (char c : word.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                return false;
            }
            node = node.children[c - 'a'];
        }
        return node.isEndOfWord;
    }

    // Check if there is any word starting with the given prefix
    public boolean startsWith(String prefix) {
        TrieNode node = root;
        for (char c : prefix.toCharArray()) {
            if (node.children[c - 'a'] == null) {
                return false;
            }
            node = node.children[c - 'a'];
        }
        return true;
    }

    public static void main(String[] args) {
        Trie trie = new Trie();
        trie.insert("apple");
        trie.insert("app");
        System.out.println(trie.search("apple"));   // true
        System.out.println(trie.search("app"));     // true
        System.out.println(trie.startsWith("ap"));  // true
        System.out.println(trie.search("appl"));    // false
    }
}
```

---

### **2. Segment Trees**

#### **What is a Segment Tree?**

A **Segment Tree** is a binary tree used for storing intervals or segments. It allows efficient querying and updating of ranges in an array, making it ideal for problems where range queries or updates are required.

- **Range Query**: Find a specific property (like minimum, maximum, sum) of elements in a subarray or range.
- **Point Update**: Update a single element in the array and propagate the change to the tree.

Segment trees are most useful when you have an array and need to perform many **range queries** (like sum, min, max) and **point updates** efficiently.

#### **Time Complexity:**
- **Query**: O(log N)
- **Update**: O(log N)
- **Space Complexity**: O(4 * N)

#### **Code Implementation (Java):**

```java
class SegmentTree {
    int[] tree;
    int n;

    public SegmentTree(int[] arr) {
        n = arr.length;
        tree = new int[4 * n];
        buildTree(arr, 0, 0, n - 1);
    }

    // Build the segment tree
    private void buildTree(int[] arr, int node, int start, int end) {
        if (start == end) {
            tree[node] = arr[start];
        } else {
            int mid = (start + end) / 2;
            buildTree(arr, 2 * node + 1, start, mid);
            buildTree(arr, 2 * node + 2, mid + 1, end);
            tree[node] = Math.min(tree[2 * node + 1], tree[2 * node + 2]);  // For range minimum query
        }
    }

    // Range query: get minimum in the range [l, r]
    public int rangeQuery(int l, int r) {
        return rangeQuery(0, 0, n - 1, l, r);
    }

    private int rangeQuery(int node, int start, int end, int l, int r) {
        if (r < start || end < l) {
            return Integer.MAX_VALUE;  // Invalid range
        }
        if (l <= start && end <= r) {
            return tree[node];  // Fully within range
        }
        int mid = (start + end) / 2;
        int left = rangeQuery(2 * node + 1, start, mid, l, r);
        int right = rangeQuery(2 * node + 2, mid + 1, end, l, r);
        return Math.min(left, right);  // For range minimum query
    }

    // Update an element at index i
    public void update(int i, int val) {
        update(0, 0, n - 1, i, val);
    }

    private void update(int node, int start, int end, int i, int val) {
        if (start == end) {
            tree[node] = val;
        } else {
            int mid = (start + end) / 2;
            if (i <= mid) {
                update(2 * node + 1, start, mid, i, val);
            } else {
                update(2 * node + 2, mid + 1, end, i, val);
            }
            tree[node] = Math.min(tree[2 * node + 1], tree[2 * node + 2]);  // For range minimum query
        }
    }

    public static void main(String[] args) {
        int[] arr = {1, 3, 2, 7, 9, 11};
        SegmentTree segTree = new SegmentTree(arr);
        System.out.println(segTree.rangeQuery(1, 3));  // Min in range [1, 3] => 2
        segTree.update(1, 5);  // Update arr[1] to 5
        System.out.println(segTree.rangeQuery(1, 3));  // Min in range [1, 3] => 2 (after update)
    }
}
```

---

### **3. Fenwick Trees (Binary Indexed Trees)**

#### **What is a Fenwick Tree?**

A **Fenwick Tree** or **Binary Indexed Tree (BIT)** is a data structure that provides efficient methods for querying and updating prefix sums (range sums) in an array. It is often used to handle problems where both updates and range queries are required.

#### **Operations:**
- **Update**: Update a specific index in the array.
- **Prefix Sum**: Get the sum of elements from the start to the given index.

#### **Time Complexity:**
- **Update**: O(log N)
- **Query**: O(log N)
- **Space Complexity**: O(N)

#### **Code Implementation (Java):**

```java
class FenwickTree {
    int[] bit;
    int n;

    public FenwickTree(int size) {
        n = size;
        bit = new int[n + 1];  // Binary Indexed Tree is 1-based indexing
    }

    // Update the value at index idx
    public void update(int idx, int val) {
        while (idx <= n) {
            bit[idx] += val;
            idx += idx & (-idx);  // Move to the next index to update
        }
    }

    // Get the prefix sum up to index idx
    public int query(int idx) {
        int sum = 0;
        while (idx > 0) {
            sum += bit[idx];
            idx -= idx & (-idx);  // Move to the parent node
        }
        return sum;
    }

    public static void main(String[] args) {
        FenwickTree fenwickTree = new FenwickTree(5);
        fenwickTree.update(1, 1);
        fenwickTree.update(2, 2);
        fenwickTree.update(3, 3);
        System.out.println(fenwickTree.query(3));  // Prefix sum up to index 3 => 6
       

 fenwickTree.update(2, 3);  // Update index 2 with value 3
        System.out.println(fenwickTree.query(3));  // Prefix sum up to index 3 => 9
    }
}
```

---

### **4. Disjoint Set Union (Union-Find)**

#### **What is Union-Find?**

The **Disjoint Set Union (DSU)** or **Union-Find** data structure helps in solving problems related to **dynamic connectivity**. It maintains a collection of disjoint sets and provides efficient methods for:
- **Union**: Merging two sets.
- **Find**: Finding the representative or root of a set.

Union-Find is used in problems like finding connected components in graphs and determining if two nodes are in the same connected component.

#### **Operations:**
- **Find**: Find the representative of a set.
- **Union**: Merge two sets.
- **Path Compression**: Optimization to flatten the structure of the tree during **Find**.
- **Union by Rank**: Optimization to keep the tree shallow by attaching the smaller tree to the root of the larger tree.

#### **Time Complexity:**
- **Find/Union**: O(α(N)) where α is the inverse Ackermann function, which is almost constant.
- **Space Complexity**: O(N)

#### **Code Implementation (Java):**

```java
class UnionFind {
    int[] parent, rank;

    public UnionFind(int size) {
        parent = new int[size];
        rank = new int[size];
        for (int i = 0; i < size; i++) {
            parent[i] = i;
            rank[i] = 0;
        }
    }

    // Find the representative of the set containing x
    public int find(int x) {
        if (parent[x] != x) {
            parent[x] = find(parent[x]);  // Path compression
        }
        return parent[x];
    }

    // Union of two sets
    public void union(int x, int y) {
        int rootX = find(x);
        int rootY = find(y);

        if (rootX != rootY) {
            // Union by rank
            if (rank[rootX] > rank[rootY]) {
                parent[rootY] = rootX;
            } else if (rank[rootX] < rank[rootY]) {
                parent[rootX] = rootY;
            } else {
                parent[rootY] = rootX;
                rank[rootX]++;
            }
        }
    }

    public static void main(String[] args) {
        UnionFind uf = new UnionFind(5);
        uf.union(0, 1);
        uf.union(1, 2);
        System.out.println(uf.find(0) == uf.find(2));  // true
        uf.union(3, 4);
        System.out.println(uf.find(2) == uf.find(4));  // false
    }
}
```

---

### **Conclusion**

These advanced data structures—Tries, Segment Trees, Fenwick Trees, and Disjoint Set Union—are essential tools for solving various algorithmic problems. They are optimized for specific use cases like string matching, range queries, prefix sums, and dynamic connectivity. Understanding and implementing these data structures will greatly improve your ability to handle complex problems efficiently.


# **Chapter 20: Graph Algorithms**

In this chapter, we will delve into key **graph algorithms** used to solve fundamental graph problems efficiently. We will cover algorithms for finding **shortest paths**, **minimum spanning trees**, **topological sorting**, and **network flow**. These algorithms are widely used in applications ranging from route finding and network analysis to scheduling and resource allocation.

---

### **1. Shortest Path Algorithms**

#### **Dijkstra's Algorithm**

**Dijkstra's Algorithm** is a **greedy algorithm** used to find the shortest path between a starting node and all other nodes in a weighted graph with **non-negative edge weights**. The key idea is to iteratively select the node with the smallest tentative distance, and update the distances of its neighboring nodes.

##### **Steps:**
1. Initialize the distance of the source node to 0 and all other nodes to infinity.
2. Set the source node as the current node.
3. For each neighboring node, update the tentative distance if a shorter path is found.
4. Mark the current node as visited, and move to the unvisited node with the smallest tentative distance.
5. Repeat until all nodes are visited.

##### **Time Complexity:**
- **Using Min-Heap/Priority Queue:** O(E log V)
- **Without Priority Queue:** O(V^2)

##### **Code Implementation (Java):**

```java
import java.util.*;

class Dijkstra {
    static class Edge {
        int to, weight;
        Edge(int to, int weight) {
            this.to = to;
            this.weight = weight;
        }
    }

    public static void dijkstra(int n, List<List<Edge>> graph, int source) {
        int[] dist = new int[n];
        Arrays.fill(dist, Integer.MAX_VALUE);
        dist[source] = 0;
        PriorityQueue<int[]> pq = new PriorityQueue<>(Comparator.comparingInt(a -> a[1]));
        pq.add(new int[]{source, 0});

        while (!pq.isEmpty()) {
            int[] current = pq.poll();
            int u = current[0], currentDist = current[1];
            if (currentDist > dist[u]) continue;

            for (Edge edge : graph.get(u)) {
                int v = edge.to, weight = edge.weight;
                if (dist[u] + weight < dist[v]) {
                    dist[v] = dist[u] + weight;
                    pq.add(new int[]{v, dist[v]});
                }
            }
        }

        System.out.println("Shortest distances from source: ");
        for (int i = 0; i < n; i++) {
            System.out.println("Node " + i + ": " + (dist[i] == Integer.MAX_VALUE ? "INF" : dist[i]));
        }
    }

    public static void main(String[] args) {
        int n = 5;
        List<List<Edge>> graph = new ArrayList<>();
        for (int i = 0; i < n; i++) {
            graph.add(new ArrayList<>());
        }

        graph.get(0).add(new Edge(1, 10));
        graph.get(0).add(new Edge(2, 5));
        graph.get(1).add(new Edge(2, 2));
        graph.get(1).add(new Edge(3, 1));
        graph.get(2).add(new Edge(1, 3));
        graph.get(2).add(new Edge(3, 9));
        graph.get(3).add(new Edge(4, 4));

        dijkstra(n, graph, 0);
    }
}
```

---

#### **Bellman-Ford Algorithm**

The **Bellman-Ford Algorithm** is used to find the shortest paths from a source node to all other nodes in a graph. Unlike Dijkstra's algorithm, Bellman-Ford can handle graphs with negative weight edges and can detect negative weight cycles.

##### **Steps:**
1. Initialize the distance to the source node as 0 and all other distances as infinity.
2. For each edge, update the distances of the destination nodes if a shorter path is found.
3. Repeat the above step for V-1 iterations, where V is the number of vertices.
4. If any distance is updated in the V-th iteration, a negative weight cycle exists.

##### **Time Complexity:**
- **O(V * E)**

##### **Code Implementation (Java):**

```java
class BellmanFord {
    static class Edge {
        int u, v, weight;
        Edge(int u, int v, int weight) {
            this.u = u;
            this.v = v;
            this.weight = weight;
        }
    }

    public static void bellmanFord(int n, List<Edge> edges, int source) {
        int[] dist = new int[n];
        Arrays.fill(dist, Integer.MAX_VALUE);
        dist[source] = 0;

        for (int i = 1; i < n; i++) {
            for (Edge edge : edges) {
                if (dist[edge.u] != Integer.MAX_VALUE && dist[edge.u] + edge.weight < dist[edge.v]) {
                    dist[edge.v] = dist[edge.u] + edge.weight;
                }
            }
        }

        // Check for negative weight cycles
        for (Edge edge : edges) {
            if (dist[edge.u] != Integer.MAX_VALUE && dist[edge.u] + edge.weight < dist[edge.v]) {
                System.out.println("Graph contains a negative weight cycle");
                return;
            }
        }

        System.out.println("Shortest distances from source: ");
        for (int i = 0; i < n; i++) {
            System.out.println("Node " + i + ": " + (dist[i] == Integer.MAX_VALUE ? "INF" : dist[i]));
        }
    }

    public static void main(String[] args) {
        int n = 5;
        List<Edge> edges = new ArrayList<>();
        edges.add(new Edge(0, 1, -1));
        edges.add(new Edge(0, 2, 4));
        edges.add(new Edge(1, 2, 3));
        edges.add(new Edge(1, 3, 2));
        edges.add(new Edge(1, 4, 2));
        edges.add(new Edge(3, 2, 5));
        edges.add(new Edge(3, 1, 1));
        edges.add(new Edge(4, 3, -3));

        bellmanFord(n, edges, 0);
    }
}
```

---

#### **Floyd-Warshall Algorithm**

The **Floyd-Warshall Algorithm** is an **all-pairs shortest path** algorithm, which computes the shortest paths between all pairs of nodes in a weighted graph.

##### **Steps:**
1. Initialize the distance matrix for each pair of nodes. Set the distance of direct edges as their weight and other distances as infinity.
2. For each intermediate node, update the distance matrix by considering whether the path through the intermediate node offers a shorter path between any two nodes.
3. Repeat this for every node as an intermediate node.

##### **Time Complexity:**
- **O(V^3)**

##### **Code Implementation (Java):**

```java
class FloydWarshall {
    public static void floydWarshall(int[][] graph) {
        int V = graph.length;

        // Initialize distance matrix with the graph
        int[][] dist = new int[V][V];
        for (int i = 0; i < V; i++) {
            for (int j = 0; j < V; j++) {
                if (i != j && graph[i][j] == 0) {
                    dist[i][j] = Integer.MAX_VALUE;
                } else {
                    dist[i][j] = graph[i][j];
                }
            }
        }

        // Floyd-Warshall algorithm
        for (int k = 0; k < V; k++) {
            for (int i = 0; i < V; i++) {
                for (int j = 0; j < V; j++) {
                    if (dist[i][k] != Integer.MAX_VALUE && dist[k][j] != Integer.MAX_VALUE &&
                        dist[i][k] + dist[k][j] < dist[i][j]) {
                        dist[i][j] = dist[i][k] + dist[k][j];
                    }
                }
            }
        }

        // Print the solution
        System.out.println("Shortest distances between every pair of vertices:");
        for (int i = 0; i < V; i++) {
            for (int j = 0; j < V; j++) {
                System.out.print((dist[i][j] == Integer.MAX_VALUE ? "INF" : dist[i][j]) + "\t");
            }
            System.out.println();
        }
    }

    public static void main(String[] args) {
        int[][] graph = {
            {0, 3, 0, 0, 0},
            {3, 0, 1, 0, 0},
            {0, 1, 0, 7, 0},
            {0, 0, 7, 0, 2},
            {0, 0, 0, 2, 0}
        };

        floydWarshall(graph);
    }
}
```

---

### **2. Minimum Spanning Tree (MST)**

A **Minimum Spanning Tree (MST)** of a weighted graph is a subset of edges that connect all the vertices together, without any cycles, and with the minimum possible total edge weight.

#### **Kruskal's Algorithm**

Kruskal's algorithm is a **greedy algorithm** that finds the MST by sorting all edges in the graph by weight and adding

 them one by one to the MST, ensuring no cycles are formed.

##### **Time Complexity:**
- **O(E log E)** due to sorting of edges, where E is the number of edges.

##### **Code Implementation (Java):**

```java
import java.util.*;

class Kruskal {
    static class Edge implements Comparable<Edge> {
        int u, v, weight;
        Edge(int u, int v, int weight) {
            this.u = u;
            this.v = v;
            this.weight = weight;
        }
        
        @Override
        public int compareTo(Edge o) {
            return this.weight - o.weight;
        }
    }

    static class UnionFind {
        int[] parent, rank;

        public UnionFind(int size) {
            parent = new int[size];
            rank = new int[size];
            for (int i = 0; i < size; i++) {
                parent[i] = i;
                rank[i] = 0;
            }
        }

        public int find(int x) {
            if (parent[x] != x) {
                parent[x] = find(parent[x]);
            }
            return parent[x];
        }

        public void union(int x, int y) {
            int rootX = find(x);
            int rootY = find(y);

            if (rootX != rootY) {
                if (rank[rootX] > rank[rootY]) {
                    parent[rootY] = rootX;
                } else if (rank[rootX] < rank[rootY]) {
                    parent[rootX] = rootY;
                } else {
                    parent[rootY] = rootX;
                    rank[rootX]++;
                }
            }
        }
    }

    public static void kruskal(int n, List<Edge> edges) {
        Collections.sort(edges);

        UnionFind uf = new UnionFind(n);
        int mstWeight = 0;
        List<Edge> mst = new ArrayList<>();

        for (Edge edge : edges) {
            if (uf.find(edge.u) != uf.find(edge.v)) {
                uf.union(edge.u, edge.v);
                mst.add(edge);
                mstWeight += edge.weight;
            }
        }

        System.out.println("Edges in MST:");
        for (Edge edge : mst) {
            System.out.println(edge.u + " - " + edge.v + ": " + edge.weight);
        }
        System.out.println("Total weight of MST: " + mstWeight);
    }

    public static void main(String[] args) {
        int n = 5;
        List<Edge> edges = new ArrayList<>();
        edges.add(new Edge(0, 1, 10));
        edges.add(new Edge(0, 2, 6));
        edges.add(new Edge(0, 3, 5));
        edges.add(new Edge(1, 3, 15));
        edges.add(new Edge(2, 3, 4));

        kruskal(n, edges);
    }
}
```

---

#### **Prim's Algorithm**

Prim's algorithm is another **greedy algorithm** used to find the MST. It starts from any node and grows the MST by adding the minimum weight edge that connects a vertex inside the MST to a vertex outside the MST.

##### **Time Complexity:**
- **O(V^2)** (using adjacency matrix)
- **O(E log V)** (using adjacency list with a priority queue)

##### **Code Implementation (Java):**

```java
import java.util.*;

class Prim {
    static class Edge {
        int to, weight;
        Edge(int to, int weight) {
            this.to = to;
            this.weight = weight;
        }
    }

    public static void prim(int n, List<List<Edge>> graph) {
        boolean[] inMST = new boolean[n];
        int[] key = new int[n];
        Arrays.fill(key, Integer.MAX_VALUE);
        key[0] = 0;

        PriorityQueue<int[]> pq = new PriorityQueue<>(Comparator.comparingInt(a -> a[1]));
        pq.add(new int[]{0, 0});  // {node, weight}

        while (!pq.isEmpty()) {
            int[] current = pq.poll();
            int u = current[0];

            if (inMST[u]) continue;
            inMST[u] = true;

            for (Edge edge : graph.get(u)) {
                int v = edge.to, weight = edge.weight;
                if (!inMST[v] && weight < key[v]) {
                    key[v] = weight;
                    pq.add(new int[]{v, key[v]});
                }
            }
        }

        int mstWeight = 0;
        for (int i = 0; i < n; i++) {
            mstWeight += key[i];
        }
        System.out.println("Total weight of MST: " + mstWeight);
    }

    public static void main(String[] args) {
        int n = 5;
        List<List<Edge>> graph = new ArrayList<>();
        for (int i = 0; i < n; i++) {
            graph.add(new ArrayList<>());
        }

        graph.get(0).add(new Edge(1, 10));
        graph.get(0).add(new Edge(2, 6));
        graph.get(0).add(new Edge(3, 5));
        graph.get(1).add(new Edge(3, 15));
        graph.get(2).add(new Edge(3, 4));

        prim(n, graph);
    }
}
```

---

### **3. Topological Sorting**

Topological sorting is used in **directed acyclic graphs (DAGs)** to order the nodes such that for every directed edge u → v, node u comes before node v.

#### **Algorithm:**
1. Perform a **DFS** on the graph.
2. Once a node and all its descendants have been fully explored, push it onto a stack.
3. The topological order is the reverse of the stack.

##### **Time Complexity:**
- **O(V + E)**

##### **Code Implementation (Java):**

```java
import java.util.*;

class TopologicalSort {
    public static void topologicalSort(int n, List<List<Integer>> graph) {
        boolean[] visited = new boolean[n];
        Stack<Integer> stack = new Stack<>();

        for (int i = 0; i < n; i++) {
            if (!visited[i]) {
                dfs(graph, i, visited, stack);
            }
        }

        while (!stack.isEmpty()) {
            System.out.print(stack.pop() + " ");
        }
    }

    private static void dfs(List<List<Integer>> graph, int node, boolean[] visited, Stack<Integer> stack) {
        visited[node] = true;
        for (int neighbor : graph.get(node)) {
            if (!visited[neighbor]) {
                dfs(graph, neighbor, visited, stack);
            }
        }
        stack.push(node);
    }

    public static void main(String[] args) {
        int n = 6;
        List<List<Integer>> graph = new ArrayList<>();
        for (int i = 0; i < n; i++) {
            graph.add(new ArrayList<>());
        }

        graph.get(5).add(2);
        graph.get(5).add(0);
        graph.get(4).add(0);
        graph.get(4).add(1);
        graph.get(2).add(3);
        graph.get(3).add(1);

        topologicalSort(n, graph);
    }
}
```

---

### **4. Network Flow (Ford-Fulkerson)**

The **Ford-Fulkerson Algorithm** is used to find the **maximum flow** in a flow network. It repeatedly finds augmenting paths and updates the flow until no augmenting path can be found.

#### **Time Complexity:**
- **O(E * f)**, where f is the maximum flow.

##### **Code Implementation (Java)**:

```java
class FordFulkerson {
    static final int V = 6;

    // DFS to find if there's a path from source to sink
    public static boolean dfs(int[][] graph, int[] parent, int source, int sink) {
        boolean[] visited = new boolean[V];
        Stack<Integer> stack = new Stack<>();
        stack.push(source);
        visited[source] = true;

        while (!stack.isEmpty()) {
            int u = stack.pop();

            if (u == sink) return true;

            for (int v = 0; v < V; v++) {
                if (!visited[v] && graph[u][v] > 0) {
                    stack.push(v);
                    parent[v] = u;
                    visited[v] = true;
                }
            }
        }
        return false;
    }

    public static int fordFulkerson(int[][] graph, int source, int sink) {
        int[][] residualGraph = new int[V][V];
        for (int u = 0; u < V; u++) {
            for (int v = 0; v < V; v++) {
                residualGraph[u][v] = graph[u][v];
            }
        }

        int[] parent = new int[V];
        int maxFlow = 0;

        while (dfs(residualGraph, parent, source, sink)) {
            int pathFlow = Integer.MAX_VALUE;
            for (int v = sink; v != source; v = parent[v]) {
                int u = parent[v];
                pathFlow = Math.min(pathFlow, residualGraph[u][v]);
            }

            maxFlow += pathFlow;

            for (int v = sink; v != source; v = parent[v]) {
                int u = parent[v];
                residualGraph[u][v] -= pathFlow;
                residualGraph[v][u] += pathFlow;
            }
        }

        return maxFlow;
    }



    public static void main(String[] args) {
        int[][] graph = new int[][] {
            {0, 16, 13, 0, 0, 0},
            {0, 0, 10, 12, 0, 0},
            {0, 4, 0, 0, 14, 0},
            {0, 0, 9, 0, 0, 20},
            {0, 0, 0, 7, 0, 4},
            {0, 0, 0, 0, 0, 0}
        };

        int source = 0, sink = 5;
        System.out.println("Maximum Flow: " + fordFulkerson(graph, source, sink));
    }
}
```

---

### Summary:

- **Shortest Path Algorithms** (Dijkstra, Bellman-Ford, Floyd-Warshall) help find the shortest path between nodes in a graph.
- **Minimum Spanning Tree (MST)** algorithms (Kruskal, Prim) help find the tree that connects all nodes with the minimum possible total edge weight.
- **Topological Sorting** is used to order nodes in a Directed Acyclic Graph (DAG) in a linear order.
- **Network Flow** algorithms (Ford-Fulkerson) help find the maximum flow in a network.

Each algorithm has its own application and performance characteristics, making them suitable for different problems.

# **Chapter 21: String Matching Algorithms**

String matching is the process of finding one or more substrings (patterns) in a larger string (text). These algorithms are fundamental for tasks like searching in text, pattern recognition, and more.

#### **1. Naive Pattern Matching**

The naive pattern matching algorithm searches for a pattern in a text by checking every possible position in the text where the pattern could fit. It compares the pattern to the substring of the text starting at each position and moves one character at a time.

##### **Algorithm:**
1. Loop over all positions in the text where the pattern can fit.
2. For each position, check if the substring matches the pattern.
3. If a match is found, return the index.
4. Otherwise, move to the next character.

##### **Time Complexity:**
- **Worst-case time complexity**: **O((n - m + 1) * m)**, where:
  - **n** = length of the text
  - **m** = length of the pattern

##### **Code Implementation (Java):**

```java
public class NaivePatternMatching {
    public static void naivePatternMatch(String text, String pattern) {
        int n = text.length();
        int m = pattern.length();
        
        for (int i = 0; i <= n - m; i++) {
            int j = 0;
            while (j < m && text.charAt(i + j) == pattern.charAt(j)) {
                j++;
            }
            if (j == m) {
                System.out.println("Pattern found at index: " + i);
            }
        }
    }

    public static void main(String[] args) {
        String text = "ABABDABACDABABCABAB";
        String pattern = "ABAB";
        naivePatternMatch(text, pattern);
    }
}
```

#### **2. Knuth-Morris-Pratt (KMP) Algorithm**

The **KMP algorithm** improves on the naive approach by avoiding unnecessary re-comparison of characters. It preprocesses the pattern to create a **partial match table** (also known as the **prefix table**) which helps in skipping characters that are known to match already.

##### **Algorithm:**
1. Preprocess the pattern to create a prefix table, which indicates the longest proper prefix that is also a suffix for each position.
2. Use this table to skip unnecessary character comparisons during the matching phase.

##### **Time Complexity:**
- **O(n + m)** where:
  - **n** = length of the text
  - **m** = length of the pattern

##### **Code Implementation (Java):**

```java
public class KMP {
    public static int[] computeLPSArray(String pattern) {
        int m = pattern.length();
        int[] lps = new int[m];
        int length = 0;
        int i = 1;
        
        while (i < m) {
            if (pattern.charAt(i) == pattern.charAt(length)) {
                length++;
                lps[i] = length;
                i++;
            } else {
                if (length != 0) {
                    length = lps[length - 1];
                } else {
                    lps[i] = 0;
                    i++;
                }
            }
        }
        return lps;
    }

    public static void KMPAlgorithm(String text, String pattern) {
        int n = text.length();
        int m = pattern.length();
        
        int[] lps = computeLPSArray(pattern);
        int i = 0; // text index
        int j = 0; // pattern index
        
        while (i < n) {
            if (pattern.charAt(j) == text.charAt(i)) {
                i++;
                j++;
            }
            
            if (j == m) {
                System.out.println("Pattern found at index: " + (i - j));
                j = lps[j - 1];
            } else if (i < n && pattern.charAt(j) != text.charAt(i)) {
                if (j != 0) {
                    j = lps[j - 1];
                } else {
                    i++;
                }
            }
        }
    }

    public static void main(String[] args) {
        String text = "ABABDABACDABABCABAB";
        String pattern = "ABAB";
        KMPAlgorithm(text, pattern);
    }
}
```

#### **3. Rabin-Karp Algorithm**

The **Rabin-Karp algorithm** uses hashing to search for a pattern in the text. It hashes the pattern and the substrings of the text and compares the hashes instead of comparing the strings directly.

##### **Algorithm:**
1. Compute the hash of the pattern.
2. For each substring of the text that has the same length as the pattern, compute its hash.
3. If the hashes match, check if the actual substring matches the pattern (this step is necessary to handle hash collisions).
4. Continue until all substrings have been checked.

##### **Time Complexity:**
- **Average case**: **O(n + m)**
- **Worst case**: **O(n * m)**, due to hash collisions.

##### **Code Implementation (Java):**

```java
public class RabinKarp {
    public static void rabinKarpAlgorithm(String text, String pattern) {
        int n = text.length();
        int m = pattern.length();
        int d = 256; // number of characters in the input alphabet
        int q = 101; // a prime number
        
        int patternHash = 0; // hash value for pattern
        int textHash = 0; // hash value for text
        int h = 1;
        
        // Calculate h = d^(m-1) % q
        for (int i = 0; i < m - 1; i++) {
            h = (h * d) % q;
        }
        
        // Calculate the hash value of the pattern and the first window of text
        for (int i = 0; i < m; i++) {
            patternHash = (d * patternHash + pattern.charAt(i)) % q;
            textHash = (d * textHash + text.charAt(i)) % q;
        }
        
        // Slide the pattern over text one by one
        for (int i = 0; i <= n - m; i++) {
            if (patternHash == textHash) {
                int j = 0;
                while (j < m && text.charAt(i + j) == pattern.charAt(j)) {
                    j++;
                }
                if (j == m) {
                    System.out.println("Pattern found at index: " + i);
                }
            }
            
            // Calculate hash value for next window of text
            if (i < n - m) {
                textHash = (d * (textHash - text.charAt(i) * h) + text.charAt(i + m)) % q;
                if (textHash < 0) {
                    textHash = textHash + q;
                }
            }
        }
    }

    public static void main(String[] args) {
        String text = "ABABDABACDABABCABAB";
        String pattern = "ABAB";
        rabinKarpAlgorithm(text, pattern);
    }
}
```

#### **Applications of String Matching**

1. **Text Searching:** These algorithms are used in search engines, text editors, and word processors to search for a pattern in large texts.
2. **DNA Sequence Analysis:** In bioinformatics, string matching algorithms are used to find specific gene sequences in DNA data.
3. **Plagiarism Detection:** String matching is used in plagiarism detection systems to find similar sections of text in different documents.
4. **Spam Filtering:** It is used to identify specific keywords or patterns in emails to filter out spam.
5. **Security Applications:** Algorithms like Rabin-Karp and KMP can be used in security for searching patterns or signatures in network traffic or files.

---

### **Summary:**

- **Naive Pattern Matching** is a straightforward approach but can be inefficient for large texts.
- **KMP Algorithm** improves the naive approach by using a prefix table to skip unnecessary comparisons.
- **Rabin-Karp Algorithm** utilizes hashing for efficient string matching, especially useful for multiple pattern searches.
- These algorithms form the backbone of many text-related applications, from simple search engines to complex DNA analysis.



This structure provides a comprehensive journey through **Data Structures**, ensuring both theoretical understanding and practical applications. Each chapter is designed to build on the previous, culminating in advanced topics and real-world applications.
