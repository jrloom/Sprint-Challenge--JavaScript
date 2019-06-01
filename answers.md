## 1. Describe the biggest difference between `.forEach` & `.map`.

> .`forEach` returns undefined - i.e. doesn't return anything. `.map` returns a new array.

## 2. What is the difference between a function and a method?

> A method is a function attached to a function (or object or array). And a function is a method on the Window object...

## 3. What is closure?

> A nested/inner function has access to the outer function's scope. The outer function does not have access to the inner function's scope, only to whatever the inner function returns.

## 4. Describe the four rules of the `this` keyword.

> Global Binding: In the global scope, `this` will be the Window object.
> Implicit Binding: When a function is called by a preceding dot, the object to the left of the dot is `this`.
> Explicit Binding: `this` is explicitly defined by `.apply`, `.bind`, or `.call`.
> New Binding: `this` refers to the specific instance of an object when a constructor function is used.

## 5. Why do we need `super()` in an extended class?

> `super()` is used to call a parent class and the parent class' parameters.
