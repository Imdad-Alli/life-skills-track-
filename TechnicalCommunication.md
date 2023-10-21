# Data Types
In Java 
* Datatypes  tell the compiler about a specific container and it defines the range.
* We use data type for type safety.
## 1. Primitive Data Types. 
Primitive Datatypes are the keywords in Java that have specific types and certain ranges.
1. Number : 
* Non-Decimal: byte, int, long
* Decimal: float, double
2. Character: char
3. Boolean: true, false
## 2. Non-Primitive Data Types
Non-primitive data types are the custom class that is used based on the requirement. 
* String
* Arrays
* user-defined classes
# Data structures
in Java, a data structure is a way of storing and organizing data so that it can be used efficiently.
Efficient data structures are key to designing efficient algorithms.

### Types 
#### 1. Linear Data Structures
1. Arrays: An array is a linear data structure representing a group of similar elements, accessed by an index. The size of an array must be provided before storing data. Listed below are       
```
public class Test {
  public static void main(String[] args) {
    int[] numbers = {1, 2, 3, 4, 5};
    String[] names = new String[3];
    names[0] = "imdad";
    names[1] = "asad";
    names[2] = "chinna";
  }
}
```
2. Linked List: Linked list stores the data in the form of a node
```
ArrayList<String> fruits = new ArrayList<>();
fruits.add("Apple");
fruits.add("Banana");
fruits.add("Cherry");
```
4. Stacks: Stack is a linear data structure that follows the LIFO approach
```
Stack<String> stack = new Stack<>();
stack.push("First");
stack.push("Second");
String top = stack.pop(); // Removes and retrieves "Second"
```
6. Queues: it follows the first in first out approach
``` 
import java. util.LinkedList;
LinkedList<String> queue = new LinkedList<>();
queue.offer("First");
queue.offer("Second");
String first = queue.poll(); // Removes and retrieves "First"
```
### Non-Linear Data Structures
1. Binary Trees
Binary Tree is a hierarchical tree data structure in which each node has at most two children, which are referred to as the left child and the right child. Each binary tree has the following groups of nodes:
2. Heaps
A binary Heap is a complete binary tree, which answers to the heap property. In simple terms it is a variation of a binary tree with the following properties:
* Heap is a complete binary tree
* Follows heap property
* Min Binary Heap
* Max Binary Heap    
3. Hash Tables
A Hashtable (or Hash Table) is a data structure in Java that provides a way to store and retrieve key-value pairs. It is part of the Java Collections Framework and is often used for efficient data retrieval based on a unique key. Here are some key characteristics of a Hashtable









https://medium.com/edureka/data-types-in-java-98c8dcd5176
https://medium.com/edureka/data-structures-algorithms-in-java-d27e915db1c5#:~:text=Searching%20Algorithms-,Data%20Structures%20in%20Java,key%20to%20designing%20efficient%20algorithms.
