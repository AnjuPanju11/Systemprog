📘 MCSE-204 – UNIT 2: Assemblers, Macro Processors & Symbol Tables

────────────────────────────────────
🔶 Q1. Structure of MDT (Macro Definition Table) and ALA (Argument List Array) with example

✅ Easy Definition:
- **MDT** stores macro definitions (like a recipe book).
- **ALA** is used to store the actual arguments passed to macros.

🌍 Real-world Analogy:
MDT = Cooking recipe → fixed steps  
ALA = Ingredients → customized per user

📌 Key Concepts:
- Macros: Reusable code blocks that save time.
- MDT: Stores body of the macro
- ALA: Temporarily stores arguments used in the macro call


➡️ MDT:
1. INCR &ARG  
2. A 1,&ARG  
3. MEND

➡️ ALA:
0 → X  
(If call is INCR X)

📌 Benefits:
- Reuse of code
- Simplifies repetitive operations
- Saves development time

────────────────────────────────────
🔶 Q2. Design of Single Pass Assembler

✅ Easy Definition:
A **Single Pass Assembler** scans the source code **only once** to translate it into machine code.

🌍 Real-world Analogy:
Like a person who packs their luggage and moves at the same time – no second trip.

📌 Steps in Design:
1. Read source instruction
2. Assign memory address (location counter)
3. Generate machine code
4. Update symbol table (if label is found)
5. Handle forward references (using backpatching)

📌 Advantages:
- Faster translation
- Requires less memory
- Ideal for small/simple programs

📌 Limitations:
- Difficult to handle complex instructions
- Handling forward references is tricky

────────────────────────────────────
🔶 Q3. Compare Binary Search vs Binary Tree for Symbol Table

✅ Easy Definition:
- **Binary Search Table**: Array-based, sorted entries
- **Binary Tree**: Node-based, each node has 2 children

🌍 Real-world Analogy:
- Binary search = Searching name in sorted list
- Binary tree = Navigating a family tree

📌 Comparison:

Binary Search:
- Fast access if sorted
- Static table
- Easy to implement
- Time: O(log n)

Binary Tree:
- Dynamic insert/delete
- More flexible
- Time: O(log n) average, but can go worse

📌 When to Use:
- Use Binary Search for small, sorted tables
- Use Binary Tree for large or dynamic symbol tables

────────────────────────────────────
🔶 Q4. Explain Relocating and Linking with Example

✅ Easy Definition:
- **Relocation**: Adjust program addresses when loaded in memory.
- **Linking**: Combine different object modules into one executable.

🌍 Real-world Analogy:
- Relocation = Adjusting address labels when shifting houses
- Linking = Combining parts of a machine before use

📌 Example:
- Module A compiled separately
- Module B compiled separately
- Linker combines A & B
- Relocation modifies addresses to suit memory position

📌 Types of Linkers:
- Static Linker: Links before execution
- Dynamic Linker: Links during execution

📌 Importance:
- Supports modular programming
- Efficient memory management
- Code reuse through libraries

────────────────────────────────────
🔶 Q5. Explain the role of Linking Loader and Linkage Editor

✅ Easy Definition:
- **Linking Loader**: Loads and links modules directly into memory.
- **Linkage Editor**: Produces a linked output file for future execution.

🌍 Real-world Analogy:
- Linking Loader = On-the-spot builder
- Linkage Editor = Pre-builder for future use

📌 Comparison:

Linking Loader:
- Links during load time
- Immediate execution
- Requires all modules at load time

Linkage Editor:
- Links before load time
- Produces executable
- More flexible and efficient

📌 Benefits:
- Simplifies program loading
- Handles address resolution
- Resolves external references

────────────────────────────────────
📝 Summary (Keywords to Remember):
- MDT = Macro definitions
- ALA = Macro arguments
- Single Pass Assembler = Fast, one scan
- Binary Tree = Dynamic symbol table
- Relocation = Address adjustment
- Linking = Module combination
- Linking Loader = Links at runtime
- Linkage Editor = Prepares linked file
