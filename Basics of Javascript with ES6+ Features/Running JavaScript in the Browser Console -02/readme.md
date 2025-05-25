# Running JavaScript in the Browser Console

The **browser console** is a powerful tool built into every modern web browser (like Chrome, Firefox, Edge, Safari) that allows you to **write, test, and debug JavaScript code directly** in the browser.

---

## Why Use the Browser Console?

- Quickly test small pieces of JavaScript code without creating HTML or JS files.
- Debug errors and inspect variables in your web applications.
- Interact with the currently loaded webpage programmatically.
- Learn and experiment with JavaScript in a hands-on way.

---

## How to Open the Browser Console

### Shortcut Keys (Most Browsers)

| Browser | Windows/Linux | Mac            |
|---------|---------------|----------------|
| Chrome  | `Ctrl + Shift + J` | `Cmd + Option + J` |
| Firefox | `Ctrl + Shift + K` | `Cmd + Option + K` |
| Edge    | `Ctrl + Shift + J` | `Cmd + Option + J` |
| Safari  | Enable Develop Menu, then `Cmd + Option + C` | `Cmd + Option + C` |

---

## Running JavaScript Code in the Console

Once the console is open:

1. Click the **console tab** if not already selected.
2. Type any JavaScript code directly.
3. Press **Enter** to run the code and see the result immediately.

### Example:

```javascript
// Print a message
console.log("Hello from the console!");

// Perform arithmetic
5 + 7;

// Define and call a function
function greet(name) {
  return `Hello, ${name}!`;
}
greet("Sunny Sharma");
