📅 Day X – JavaScript (Advanced MCQs & Edge Cases) 🚀
📌 Key Topics Covered
🧠 JavaScript Weird Behaviors
Floating point precision (0.1 + 0.2 !== 0.3)
Type coercion in comparisons (==)
Truthy/Falsy edge cases ([0] == false, but [0] is truthy)
NaN behavior (NaN !== NaN, indexOf(NaN) === -1)
⚙️ Functions & Hoisting Edge Cases
Function vs variable hoisting priority
Duplicate parameters (allowed in non-strict, not in arrow functions)
Arrow functions don’t have arguments
Function expression vs declaration scope
🔄 Async & Event Loop Deep Dive
setTimeout(0) still goes to queue
Microtasks (Promises) run before macrotasks
forEach + async doesn’t wait
try-catch doesn’t catch async errors
📦 Arrays & Objects Internals
Sparse arrays (empty slots vs undefined)
delete does not reduce array length
Default sorting is lexicographical
Spread operator doesn’t work on non-iterables
🔐 ES6+ Advanced Concepts
Destructuring limitations (...rest must be last)
Default parameters behavior
Computed property names
Symbol uniqueness vs Symbol.for()
🧬 Classes & OOP
new.target behavior
super keyword in inheritance
Difference between static and instance methods
Getter/Setter pitfalls (infinite recursion risk)
🔢 Type & Memory Concepts
Wrapper objects vs primitives (new Number(0) is truthy)
Objects are compared by reference
Strings are immutable
🔁 Generators & Iterators
yield vs return behavior
Generators stop after return
Iterators maintain state
🌐 Misc Advanced Topics
JSON.stringify ignores:
undefined
functions
symbols
Set removes duplicates but treats NaN as same
Symbol cannot be used with new
🧠 Key Takeaways
JavaScript has many hidden edge cases
Async code ≠ sequential execution
Type coercion can lead to unexpected results
Understanding internals is crucial for interviews
