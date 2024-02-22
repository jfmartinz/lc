# Notes 

## Stacks
A stack is a linear data structure that follows the Last In, First Out (LIFO) principle. It means that the element which is added last is the first one to be removed.

### Operations:

**Push:** Adds an element to the top of the stack.<br>
**Pop:** Removes the top element from the stack.<br>
**Peek (or Top):** Returns the top element of the stack **without removing it.<br>
**isEmpty:** Checks if the stack is empty.<br>
**size (or length):** Returns the number of elements in the stack.

Examples:

Creating a Stack:
```js
const stack = new Stack();
```

Pushing elements onto the Stack:
```js
stack.push(10);
stack.push(20);
stack.push(30);
```

Popping elements from the Stack:
```js
console.log(stack.pop()); // Output: 30
console.log(stack.pop()); // Output: 20
```

Peeking the top element of the Stack:
```js
console.log(stack.peek()); // Output: 10
```

Checking if the Stack is empty:

```js
console.log(stack.isEmpty()); // Output: false
```

```js
console.log(stack.size()); // Output: 1
```

### Conclusion:
This notes cover the basics of implementing a Stack data structure in JavaScript including its operations and examples. Stacks are widely used in various algorithms and applications such as expression evaluation, backtracking, and browser history management.