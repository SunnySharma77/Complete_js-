# Variables and Keywords in JavaScript: `var`, `let`, and `const`

Variables in JavaScript are containers used to store data values. JavaScript provides three main keywords to declare variables:

- `var`
- `let`
- `const`

Each has different behavior and scope rules, important for writing clean, bug-free code.

---

## 1. `var`

- Introduced in **early versions** of JavaScript.
- Has **function scope** or **global scope** if declared outside a function.
- Variables declared with `var` are **hoisted** to the top of their scope (meaning you can use them before declaration, but their value will be `undefined` until assigned).
- Can be **redeclared** and **updated** within the same scope.

### Example:

```javascript
var message = "Hello, var!";
console.log(message); // Hello, var!

var message = "Updated var";
console.log(message); // Updated var

function testVar() {
  var x = 1;
  if (true) {
    var x = 2; // Same variable!
    console.log(x); // 2
  }
  console.log(x); // 2
}
testVar();

