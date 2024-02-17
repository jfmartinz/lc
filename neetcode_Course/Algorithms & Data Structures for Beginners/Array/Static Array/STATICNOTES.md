# Notes 

## Static Array
A static array is a type of data structure in computer programming where the size or the length of the array is fixed. This means that once the array is created, you cannot change its size. The elements in a static array are stored in contiguous memory locations, and you can access these elements using an index.topic

**Example:**

For example, if you declare an array of integers with a size of 5, it will create space in memory to store 5 integers. You can access each integer using an index from 0 to 4. If you try to store more than 5 integers in this array, it will result in an error because the size of the array is fixed at 5.

Example:

```js
let numbers = new Array(5); // creates an empty array with a fixed size of 5
numbers[0] = 1;
numbers[1] = 2;
numbers[2] = 3;
numbers[3] = 4;
numbers[4] = 5;
console.log(numbers); // outputs: [1, 2, 3, 4, 5]
```

In the above example, we created a static array called numbers with a fixed size of 5. We then assigned values to each index of the array. Note that we cannot add more elements to this array because its size is fixed.

When it comes to data structures and algorithms, static arrays are useful for solving problems that require storing a fixed number of elements, such as sorting algorithms or searching for an element in a list. However, if you need to store a variable number of elements, you might want to consider using a dynamic array instead.


Things to remember about Static Array:

- They have a fixed size that cannot be changed once they are created.
- Elements in a static array are stored in contiguous memory locations.
- They offer constant-time access to elements (i.e., accessing elements by index is fast).