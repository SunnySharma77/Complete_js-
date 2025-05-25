# Logging with JavaScript

Logging in JavaScript is primarily done using the **`console`** object provided by web browsers and Node.js environments. Logging helps developers **track the flow of code execution**, **inspect values**, and **debug issues**.

---

## Common Console Methods for Logging

| Method                 | Description                                  | Example                                  |
|------------------------|----------------------------------------------|------------------------------------------|
| `console.log()`        | General-purpose logging                      | `console.log("Hello World!");`           |
| `console.info()`       | Informational message (similar to log)      | `console.info("Info message");`          |
| `console.warn()`       | Warning message, often highlighted in yellow| `console.warn("Warning: Check this out");`|
| `console.error()`      | Error message, often highlighted in red     | `console.error("Error occurred!");`      |
| `console.debug()`      | Debug-level message (may be hidden by default) | `console.debug("Debugging...");`      |
| `console.table()`      | Displays tabular data in a table format     | `console.table([{name:"Alice"}, {name:"Bob"}]);` |
| `console.group()`      | Starts a collapsed group of logs             | `console.group("Details");`               |
| `console.groupEnd()`   | Ends the current group                       | `console.groupEnd();`                      |
| `console.time()`       | Starts a timer                               | `console.time("Timer1");`                  |
| `console.timeEnd()`    | Ends a timer and logs elapsed time           | `console.timeEnd("Timer1");`               |
| `console.clear()`      | Clears the console                           | `console.clear();`                         |

---

## Basic Usage

```javascript
console.log("Hello, JavaScript logging!");

let count = 5;
console.log("Count is:", count);

