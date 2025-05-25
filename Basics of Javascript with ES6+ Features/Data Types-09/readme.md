# 📚 JavaScript Data Types

JavaScript is a **dynamically typed language**, which means variables can hold any type of data, and types can change at runtime.

JavaScript data types are divided into two categories:
- **Primitive Types**
- **Non-Primitive (Reference) Types**

---

## 🔹 Primitive Data Types

These are immutable and stored by value.

### 1. `Number` (includes integer and float)

JavaScript has only one numeric type: `number`.

```javascript
let integer = 100;
let float = 3.14;
let negative = -42;

## 2.String

Represents a sequence of characters.

```javascript
let name = "Sunny";
let greeting = 'Hello';
let template = `Hi, ${name}!`;

## 3.Boolean

Represents logical values: true or false.

```javascript
let isOnline = true;
let isAdmin = false;
Often used in conditionals and control structures.

## 4.Undefined

Represents a variable that has been declared but **not assigned a value**.

```javascript
let score;
console.log(score); // undefined

## Null
Represents an intentional absence of value.

```javascript

let data = null;

Commonly used to reset or clear variables.
typeof null returns "object" — this is a known JavaScript quirk.

## 6.Symbol (ES6+)

A `Symbol` is a **unique and immutable primitive value**, introduced in ES6, often used as object property keys.

```javascript
let id = Symbol("id");
let anotherId = Symbol("id");

console.log(id === anotherId); // false

## 🔸 Non-Primitive (Reference) Data Types

These data types are **stored by reference** and can hold multiple values or complex data structures like objects and arrays.

---

## 7. Object

An `Object` is used to store **key-value pairs**. Keys are usually strings (or Symbols), and values can be of any data type.

```javascript
let person = {
  name: "Sunny",
  age: 22,
  isStudent: true
};

## 8. Array

An `Array` is a special type of object that stores an **ordered collection** of elements.

```javascript
let fruits = ["Apple", "Banana", "Mango"];
let numbers = [1, 2, 3, 4.5];


