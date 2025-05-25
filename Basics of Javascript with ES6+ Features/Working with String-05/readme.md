# Working with Strings in JavaScript

Strings are one of the most commonly used data types in JavaScript. JavaScript provides many built-in methods to manipulate and work with strings efficiently.

---

## Important String Methods and Concepts

### 1. `splice` (Note: **Not available on strings**)
- **Important:** `splice()` is an **array method**, not a string method.
- To modify parts of a string, use other string methods like `slice()`, `substring()`, or `replace()`.
- If you want to modify a string similarly to `splice`, you have to convert it to an array first (e.g., with `split()`), manipulate, then join back.

---

### 2. `slice(start, end)`

- Extracts a **substring** from the original string.
- `start` is the starting index (inclusive).
- `end` is the ending index (exclusive).
- Does **not** modify the original string; returns a new substring.

#### Example:

```javascript
const str = "Hello, World!";
console.log(str.slice(7, 12)); // Output: World
console.log(str.slice(7));     // Output: World!
console.log(str.slice(-6, -1)); // Output: World

