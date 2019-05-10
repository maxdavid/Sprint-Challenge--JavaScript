# Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

1. Describe the biggest difference between `.forEach` & `.map`.

  The chief difference between the `.forEach` and `.map` Array methods is that `.forEach` executes a function for each element in the array and returns nothing. `.map` returns a new array filled with the results of calling a function for each element in the starting array.

2. What is the difference between a function and a method?

  Functions and methods operate nearly the same, except that methods are part of a class. Methods must be invoked with 'dot notation' on an existing object, while functions have global scope and can invoked on their own.

3. What is closure?

  Closure is a function/method having access to and modifying variables in a parent scope.

4. Describe the four rules of the 'this' keyword.

  1. Global object binding
    * When called in the global context, 'this' refers to the global window object.
  2. Implicit binding
    * When calling a method, 'this' will refer to the receiver (the object preceding the dot).
  3. `New` binding
    * When using constructors, 'this' refers to the specific object instance created.
  4. Explicit binding
    * Using 'call' or 'apply' can set a new context that 'this' refers to.

5. Why do we need super() in an extended class?

  The super() function allows us to call functions on a class's parent. Calling it without a method (as in, just super()) calls the parent's constructor method and allows our extended classes to inherit methods and objects.
