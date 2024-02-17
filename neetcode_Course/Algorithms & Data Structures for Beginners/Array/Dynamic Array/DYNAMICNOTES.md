# Notes


## Dynamic Array
A dynamic array is a type of data structure in computer programming where the size of the array can be changed dynamically. This means that you can add or remove elements from the array as needed, unlike a static array where the size is fixed.

Dynamic arrays are implemented behind the scenes in programming languages like JavaScript and Python. When you create an array in these languages, you are actually creating a dynamic array.
~
Example:
```js
// Creating a dynamic array
let dynamicArray = [];

// Adding elements to the array
dynamicArray.push(10);
dynamicArray.push(20);
dynamicArray.push(30);

// Accessing elements of the array
console.log(dynamicArray[1]); // Output: 20

// Modifying elements of the array
dynamicArray[1] = 25;
console.log(dynamicArray); // Output: [10, 25, 30]

// Adding more elements
dynamicArray.push(40);
dynamicArray.push(50);
console.log(dynamicArray); // Output: [10, 25, 30, 40, 50]
```

We start with an empty array called **dynamicArray**.
We use the push() method to add elements to the end of the array **dynamically**.
We access elements of the array using index notation **(dynamicArray[index])**.
We can also modify elements of the array using index notation **(dynamicArray[index] = value)**.
The array automatically resizes itself as we add more elements.


Here are some key points to remember about dynamic arrays:

- They can change their size dynamically during runtime.
- Elements in a dynamic array are stored in contiguous memory locations.
- They offer constant-time access to elements (i.e., accessing elements by index is fast).
- Dynamic arrays are often implemented using a fixed-size buffer with a length property to keep track of the number of elements in the array.
- Elements can be added and removed from the end of the array in constant time.
- In JavaScript, dynamic arrays are typically implemented using the Array object.