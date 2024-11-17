Here’s a comprehensive chapter-wise structure for a **Data Structures** guide, covering topics from basics to advanced concepts in depth:

---

### **Chapter 1: Introduction to Data Structures**
- What are Data Structures?
- Importance and Applications of Data Structures
- Types of Data Structures (Linear and Non-Linear)
- Choosing the Right Data Structure

---

### **Chapter 2: Arrays**
- Introduction to Arrays
- Types of Arrays (1D, 2D, Multi-dimensional)
- Operations on Arrays (Traversal, Insertion, Deletion, Searching)
- Advantages and Limitations of Arrays

---

### **Chapter 3: Strings**
- String Basics
- Common String Operations (Concatenation, Substrings, Reversal)
- String Manipulation Algorithms
- Applications of Strings in Real-world Problems

---

### **Chapter 4: Linked Lists**
- Introduction to Linked Lists
- Types of Linked Lists:
  - Singly Linked List
  - Doubly Linked List
  - Circular Linked List
- Operations on Linked Lists (Insertion, Deletion, Traversal)
- Use Cases of Linked Lists

---

### **Chapter 5: Stacks**
- What is a Stack?
- LIFO Principle
- Stack Operations (Push, Pop, Peek)
- Implementation of Stacks (Array and Linked List)
- Applications of Stacks (Undo Feature, Expression Evaluation)

---

### **Chapter 6: Queues**
- What is a Queue?
- FIFO Principle
- Types of Queues:
  - Simple Queue
  - Circular Queue
  - Priority Queue
- Queue Operations (Enqueue, Dequeue, Peek)
- Applications of Queues (Task Scheduling, BFS)

---

### **Chapter 7: Hashing**
- Introduction to Hashing
- Hash Tables and Hash Functions
- Collision Handling (Chaining, Open Addressing)
- Applications of Hashing (Database Indexing, Caching)

---

### **Chapter 8: Trees**
- Basics of Trees
- Binary Trees
- Binary Search Trees (BST)
- AVL Trees and Red-Black Trees
- Applications of Trees (File Systems, Databases)

---

### **Chapter 9: Heaps**
- Introduction to Heaps
- Types of Heaps (Min-Heap, Max-Heap)
- Heap Operations (Insert, Delete, Heapify)
- Priority Queues using Heaps
- Applications of Heaps (Sorting, Scheduling)

---

### **Chapter 10: Graphs**
- Basics of Graphs
- Types of Graphs (Directed, Undirected, Weighted)
- Graph Representations (Adjacency Matrix, Adjacency List)
- Traversal Techniques (BFS, DFS)
- Applications of Graphs (Navigation, Social Networks)

---

### **Chapter 11: Searching Algorithms**
- Linear Search
- Binary Search
- Interpolation Search
- Advanced Searching Techniques

---

### **Chapter 12: Sorting Algorithms**
- Bubble Sort
- Selection Sort
- Insertion Sort
- Quick Sort
- Merge Sort
- Heap Sort
- Time Complexity Analysis of Sorting Algorithms

---

### **Chapter 13: Recursion**
- What is Recursion?
- Advantages and Limitations
- Recursive vs Iterative Solutions
- Examples: Factorial, Fibonacci, Tower of Hanoi

---

### **Chapter 14: Dynamic Programming**
- Basics of Dynamic Programming
- Difference Between Recursion and DP
- Common Problems:
  - Longest Common Subsequence (LCS)
  - Knapsack Problem
  - Matrix Chain Multiplication

---

### **Chapter 15: Backtracking**
- Introduction to Backtracking
- N-Queens Problem
- Subset Sum Problem
- Applications of Backtracking (Puzzle Solving)

---

### **Chapter 16: Advanced Data Structures**
- Tries (Prefix Trees)
- Segment Trees
- Fenwick Trees (Binary Indexed Trees)
- Disjoint Set Union (Union-Find)

---

### **Chapter 17: Graph Algorithms**
- Shortest Path Algorithms (Dijkstra, Bellman-Ford, Floyd-Warshall)
- Minimum Spanning Tree (Kruskal, Prim)
- Topological Sorting
- Network Flow (Ford-Fulkerson)

---

### **Chapter 18: String Matching Algorithms**
- Naive Pattern Matching
- Knuth-Morris-Pratt (KMP) Algorithm
- Rabin-Karp Algorithm
- Applications of String Matching

---

### **Chapter 19: Complexity Analysis**
- Time Complexity and Space Complexity
- Big O Notation
- Amortized Analysis
- Best, Worst, and Average Case Scenarios

---

### **Chapter 20: Applications of Data Structures**
- Real-World Use Cases
- Data Structures in System Design
- Competitive Programming Problems
- Future Trends in Data Structures

---

**Chapter 1: Introduction to Data Structures.**  

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

Here is the enhanced **Chapter 2: Arrays**, with **time and space complexities** and explanatory comments in the Java programs.

---

# **Chapter 2: Arrays**

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

## **Chapter 2: Arrays**

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

# **Chapter 3: Strings**

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

# **Chapter 4: Linked Lists in Java (Using Collection Framework)**

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

# **Chapter 5: ArrayList in Java**

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

# **Chapter 6: Stack in Java**

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

# **Chapter 7: Queue in Java**

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

Got it! Let's correct the sequence and focus on **Chapter 8: Hashing in Java**, which you are referring to.

---

# **Chapter 8: Hashing in Java**

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


This structure provides a comprehensive journey through **Data Structures**, ensuring both theoretical understanding and practical applications. Each chapter is designed to build on the previous, culminating in advanced topics and real-world applications.
