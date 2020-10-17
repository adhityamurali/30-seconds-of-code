---
title: consoleObjects
tags: console,logging,debugging,beginner
---

Snippets to log in different formats(Developer tools)

- Use `log()` to Output a message to the console.
- Use `table()` to Display tabular data as a table
- Use `time()` to Start a timer (can track how long an operation takes).
- Use `timeEnd()` to Stop a timer that was previously started by console.time()
- Use `trace()` to Output a stack trace to the console
- Use `info()` to Output an informational message to the console
- Use `warn()` to Output a warning message to the console
- Use `error()` Outputs an error message to the console.
- Use `clear()` to Clear the console.
- Press F12 to see the consoles in developer tools console tab

```js
console.log();
console.table();
console.time();
console.timeEnd();
console.trace();
console.info();
console.warn();
console.error();
console.clear();
```

```js
console.log("Elon Musk"); // "Elon Musk"
console.table([{ num: "1"}, { num: "2"}, { num: "3" }]); // Press F12 to see the console printed in a table format
console.time("Timer 1"); // timer starts
console.timeEnd("Timer 1"); // Timer ends
function d(a) { 
  console.trace();
  return a;
} // prints function trace
console.info("Starting Server"); // Press F12 to see the console printed as information
console.warn("Server not responding"); // Press F12 to see the console printed as warning
console.error("Server stopped"); // Press F12 to see the console printed as error
console.clear(); // Clears the console
```
