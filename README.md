# HashMap Implementation in Java

This repository contains an implementation of a **HashMap** (also known as a Hash Table) in **Java**. The code demonstrates how HashMap works, including various methods for inserting, retrieving, updating, and manipulating key-value pairs.

HashMap is a widely used data structure that stores key-value pairs and allows efficient lookup, insertion, and deletion operations, all typically with an average time complexity of **O(1)**.

## Key Concepts Explained

This code demonstrates the following methods and concepts associated with HashMap:

- **`put(key, value)`** - Inserts or updates a key-value pair in the HashMap. If the key already exists, the associated value is updated with the new value.
- **`get(key)`** - Retrieves the value associated with the given key.
- **`remove(key)`** - Removes the key-value pair with the specified key.
- **`containsKey(key)`** - Checks if a key is present in the HashMap.
- **`containsValue(value)`** - Checks if a value is present in the HashMap.
- **`keySet()`** - Returns a Set view of all the keys in the HashMap.
- **`values()`** - Returns a Collection view of all the values in the HashMap.
- **`entrySet()`** - Returns a Set view of all the key-value pairs in the HashMap.
- **`isEmpty()`** - Checks if the HashMap is empty.
- **`size()`** - Returns the number of key-value pairs in the HashMap.

## Example Usage

Here's an example of how you can use this HashMap implementation:

```java
import java.util.HashMap;

public class Main {
    public static void main(String[] args) {
        // Create a new HashMap
        HashMap<Integer, String> m = new HashMap<>();

        // Adding key-value pairs
        m.put(101, "Dens");
        m.put(102, "David");
        m.put(103, "Suresh");

        // Retrieve a value
        System.out.println(m.get(102));  // Output: David

        // Check if a key exists
        System.out.println(m.containsKey(101));  // Output: true

        // Check if a value exists
        System.out.println(m.containsValue("Dens"));  // Output: true

        // Remove a key-value pair
        m.remove(103);

        // Check if the HashMap is empty
        System.out.println(m.isEmpty());  // Output: false

        // Get all keys
        System.out.println(m.keySet());  // Output: [101, 102]

        // Get all values
        System.out.println(m.values());  // Output: [Dens, David]

        // Get all key-value pairs
        System.out.println(m.entrySet());  // Output: [101=Dens, 102=David]

        // Get the size of the HashMap
        System.out.println(m.size());  // Output: 2
    }
}
