# HashMap Implementation in Java

## Overview

This repository contains an implementation of a **HashMap** (also known as a Hash Table) in **Java**. The code demonstrates how HashMap works, including various methods and functions for inserting, retrieving, updating, and manipulating key-value pairs.

HashMap is a widely used data structure that stores key-value pairs and allows efficient lookup, insertion, and deletion operations, all typically with an average time complexity of **O(1)**.

### Key Concepts Explained

This code demonstrates the following methods and concepts associated with HashMap:

1. **`put(key, value)`** - Inserts or updates a key-value pair in the HashMap. If the key already exists, the associated value is updated with the new value.
2. **`get(key)`** - Retrieves the value associated with the given key.
3. **`remove(key)`** - Removes the key-value pair with the specified key.
4. **`containsKey(key)`** - Checks if a key is present in the HashMap.
5. **`containsValue(value)`** - Checks if a value is present in the HashMap.
6. **`keySet()`** - Returns a Set view of all the keys in the HashMap.
7. **`values()`** - Returns a Collection view of all the values in the HashMap.
8. **`entrySet()`** - Returns a Set view of all the key-value pairs in the HashMap.
9. **`isEmpty()`** - Checks if the HashMap is empty.
10. **`size()`** - Returns the number of key-value pairs in the HashMap.

### Key Methods and Functions

1. **`put(key, value)`**: Adds or updates the key-value pair.
   ```java
   m.put(101, "Dens");
