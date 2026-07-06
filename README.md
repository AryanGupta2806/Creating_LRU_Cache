# LRU Cache (Least Recently Used Cache)

## Project Description

The **LRU Cache** is a C++ project that implements the **Least Recently Used (LRU)** caching algorithm, a widely used technique for efficient memory management. The cache stores a fixed number of key-value pairs and automatically removes the least recently accessed item when the cache reaches its maximum capacity.

This project is built using a combination of a **Hash Map (`unordered_map`)** and a **Doubly Linked List** to achieve **O(1)** time complexity for both `get()` and `put()` operations. The hash map provides instant access to cache entries, while the doubly linked list maintains the order of usage, allowing recently accessed items to be moved to the front and least recently used items to remain at the end.

### Key Features

* Fast **O(1)** lookup and insertion.
* Automatic eviction of the least recently used item when the cache is full.
* Efficient memory management using a custom doubly linked list.
* Supports `get(key)` and `put(key, value)` operations.
* Demonstrates the practical use of **Data Structures** such as Hash Maps and Linked Lists.

### Technologies Used

* **Language:** C++
* **Data Structures:** `unordered_map`, Doubly Linked List
* **Concepts:** Caching, Hashing, Pointers, Object-Oriented Programming (OOP), Time Complexity Optimization

### Learning Outcomes

This project demonstrates how combining multiple data structures can optimize performance for real-world applications. It provides hands-on experience with pointer manipulation, dynamic memory management, and designing efficient algorithms with constant-time operations.

### Applications

* Operating system page replacement algorithms
* Database query caching
* Web browser caching
* CPU cache management
* API response caching
* In-memory key-value stores
