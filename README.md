# JS-Concepts
Important questions theory

# Differences between let, var, and const:

• Scope: let and const are block-scoped, meaning they are limited to the block (a pair of curly braces {}) in which they are defined. On the other hand, var is function-scoped, which means it is accessible throughout the entire function in which it is defined.

• Hoisting: Variables declared with var are hoisted to the top of their scope. This means you can use the variable before it is declared in the code. In contrast, variables declared with let and const are not hoisted and will result in a ReferenceError if you try to use them before they are declared.

• Reassignment: Variables declared with const cannot be reassigned once they are assigned a value. On the other hand, both let and var allow reassignment of values.

• Initialization: Variables declared with var are initialized with a value of undefined if no initial value is assigned explicitly. Similarly, variables declared with let are also initialized with undefined if no value is assigned. However, variables declared with const must be assigned a value during declaration; otherwise, it will result in a SyntaxError.

• Temporal Dead Zone (TDZ): The TDZ refers to the period between the creation of a variable and its declaration, during which accessing the variable will throw a ReferenceError. let and const variables are subject to the TDZ, whereas var variables are not.

• Global object property: Variables declared with var become properties of the global object (e.g., window in browsers, global in Node.js). In contrast, let and const variables do not become properties of the global object.

These are the key differences between let, var, and const in JavaScript.

=========================
