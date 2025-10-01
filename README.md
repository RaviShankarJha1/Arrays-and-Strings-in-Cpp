# Experiment 7: Arrays and Strings in C++

## Aim
To study and implement the concepts of **Arrays** and **Strings** in C++ programming through practical examples.

---

## Software Used
* Visual Studio Code  
* Language: C++  

---

## Theory

### Arrays
An **array** in C++ is a collection of elements of the same type stored in **contiguous memory locations**. Each element can be accessed directly using an **index**. Arrays are useful when dealing with large amounts of similar data.

**Types of Arrays:**
1. **One-Dimensional Array** – Stores data in a single row (e.g., `int arr[5];`).
2. **Multi-Dimensional Array** – Stores data in tables or matrices (e.g., `int arr[3][3];`).

---

### Strings
Strings in C++ can be represented in two ways:  
1. **Character Arrays (`char str[]`)** – Simple but limited in functionality.  
2. **C++ `string` Class (STL)** – Provides flexibility with built-in functions like `length()`, `append()`, `compare()`, etc.  

The `string` class is more powerful and preferred for most applications.

---

## Implementation

### 1. Basic Array Declaration and Traversal
**Objective:** Input and display 5 integer values.  
**Algorithm:**  
1. Declare an array of size 5.  
2. Take input for all 5 elements.  
3. Traverse the array using a loop and print each element.  

---

### 2. Array Element Search
**Objective:** Search for a specific element entered by the user.  
**Algorithm:**  
1. Initialize the array with values.  
2. Input the key element to be searched.  
3. Loop through the array:  
   - If the element matches the key, display its index.  
   - If not found, display "Element not present".  

---

### 3. Find Maximum and Minimum in Array
**Objective:** Identify the largest and smallest elements.  
**Algorithm:**  
1. Take input values into the array.  
2. Initialize `min` and `max` as the first element.  
3. Traverse the array:  
   - If element > max, update max.  
   - If element < min, update min.  
4. Display min and max.  

---

### 4. Reverse Array Elements
**Objective:** Display the array in reverse order.  
**Algorithm:**  
1. Input values into the array.  
2. Traverse the array from the last index to the first.  
3. Print each element in reverse order.  

---

### 5. Sum and Average of Array Elements
**Objective:** Calculate sum and average of elements.  
**Algorithm:**  
1. Initialize `sum = 0`.  
2. Input all array values.  
3. Add each element to sum.  
4. Compute average as `sum / total elements`.  
5. Display both sum and average.  

---

### 6. Concatenating Strings
**Objective:** Join two input strings into one.  
**Algorithm:**  
1. Input two strings from the user.  
2. Concatenate them using `+` operator.  
3. Display the concatenated result.  

---

### 7. Palindrome Check
**Objective:** Check if a string reads the same forwards and backwards.  
**Algorithm:**  
1. Input a string.  
2. Reverse the string.  
3. Compare original and reversed strings:  
   - If equal → Palindrome.  
   - Else → Not a Palindrome.  

---

## Conclusion
In this experiment, I learned how to declare and manipulate **arrays** for tasks such as searching, reversing, and computing values like minimum, maximum, sum, and average. I also practiced working with **strings** using both character arrays and the STL `string` class to perform operations such as concatenation and palindrome checking. These exercises improved my understanding of data storage, manipulation, and algorithm design in C++.
