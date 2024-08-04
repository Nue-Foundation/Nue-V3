# Nue-V3 
 **Is A Programming Language**
 
Nue is an innovative, interpreted programming language designed to address the challenges of modern software development and future technological trends.

## Nue Features

- 🚀 Asynchronous programming with async/await
  `let add = async fn(a, b) { a + b }`

- 🔍 LINQ-style querying capabilities
  `result = linq.from(mm).where(x => x % 2 == 0).select(x => x + 2).toSlice()`

- 🌐 Built-in web service creation
  `// (Placeholder for web service example)`

- 🧠 Intuitive and expressive syntax
  `let z = (x,y) => x * y + 5`

- 🛠️ Versatile for both backend and data processing tasks
  `// (Placeholder for versatile task example)`

- 🔢 Support for regular expressions
  `if "abc 123	mnj" =~ ``\d+\t`` { println("matched") }`

- 🔄 Pipe operator for function chaining
  `x = ["hello", "world"] |> strings.join(" ") |> strings.upper()`

- 🎭 User-defined operators
  `void =@(x, y) { return x + y * y }`

- 🔐 Exception handling with try-catch-finally
  `try { throw "SUMERROR" } catch e { printf("Caught: %s\n", e) }`

- 📦 Optional types (similar to Java 8)
  `op1 = safeDivision?(10, 0)`

- 🏷️ Const and enum support
  `const PI = 3.14159`

- 🔀 Rich control flow statements
  `if (a > b) { println("a > b") } elif a == b { println("a = b") }`

- 📚 Versatile data structures (arrays, hashes, tuples)
  `arr = [1, 2, 3]; hash = {"key": "value"}; tup = (1, "two", 3.0)`

- 🔧 Powerful string manipulation
  `str = "Hello" + " " + "World"`

- 📝 File I/O operations with 'using' statement
  `using (infile = newFile("./file.demo", "r")) { /* ... */ }`

- 🔢 Bitwise operations and flags
  `flag = LogOption.Ldate | LogOption.Ltime`

- 🧮 Math and logical operations on primitive types
  `result = (10 + 5) * 2; isTrue = (5 > 3) && (10 != 9)`

- 🏗️ Object-oriented programming
  `class Animal { let name = ""; void init(name) { this.name = name } }`

- 🔌 Command execution capabilities
  `out = `ls -la``

- 🔄 Type conversion functions
  `x = str(10); y = int("20")`

- 🏭 Simple macro processing
  `#ifdef DEBUG { println("Debugging...") }`

## Design Philosophy

Nue aims to combine simplicity, expressiveness, and performance to tackle complex programming challenges in areas such as:

- Distributed systems
- Machine learning and AI
- Internet of Things (IoT)
- Cloud computing
- Data processing and analytics

✨ **Features**:
- All features present in AeroScript && NueScript2 && NueScript3.
- For more info on builtin stuff visit [Builtin Functions](BUILTIN_GUNCTIONS.md)!

## New Update

* Currently adding features.
* Adding more libs on [`pkg server for Nue`](https://github.com/NuePkgs).
* Fixed known bugs.
* Fixed some more known bugs.

## Credits

- **Yuri-DaBang**:
  - This project is based on my [AeroScript](https://github.com/Yuri-DaBang/AeroScript-v2-Stable) project.

## License

This project is licensed under the MIT License. <LOL>

## History

🛠️🌟 **NueScript** was a superset of AeroScript.
🛠️🌟 **NueScript3** was the modified version of NueScript.
🛠️🌟 **Nue-V3** is the modified version of NueScript3.
