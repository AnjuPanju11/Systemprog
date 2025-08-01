📘 MCSE-204 – UNIT 1: Language Processors, Compiler Structure & Assemblers

────────────────────────────────────
🔶 Q1. What is a Language Processor? Give examples and features.

✅ Easy Definition:
A language processor is software that translates a program written in a high-level or assembly language into machine code that a computer can understand and execute.

🌍 Real-world Analogy:
It works like Google Translate – converting our code (English-like) into machine code (binary).

📌 Examples & Features:
- Assembler: Converts assembly code to machine code.
- Compiler: Converts high-level code (e.g., C) into machine code.
- Interpreter: Executes code line-by-line (e.g., Python).
- Features:
  • Translates source code
  • Detects syntax and logic errors
  • Acts as a bridge between human & machine
  • Improves program execution
  • Reduces manual effort

────────────────────────────────────
🔶 Q2. Explain the analysis and synthesis phases of a compiler.

✅ Easy Definition:
Compiler has two main phases:
1. Analysis: Understands and checks the code.
2. Synthesis: Generates optimized machine-level code.

🌍 Real-world Analogy:
Like a chef reading a recipe (analysis) and then cooking it (synthesis).

📌 Bullet Breakdown:
🔹 Analysis Phase (Front-End):
- Lexical Analysis → Tokens
- Syntax Analysis → Grammar rules
- Semantic Analysis → Meaning/type checking
- Intermediate Code Generation

🔹 Synthesis Phase (Back-End):
- Code Optimization
- Code Generation
- Linking & Relocation

────────────────────────────────────
🔶 Q3. Compare Local and Global Optimization.

✅ Easy Definition:
- Local Optimization: Small code block improvements.
- Global Optimization: Whole program optimizations.

🌍 Real-world Analogy:
Local: Fixing a single bulb.  
Global: Rewiring the whole house for efficiency.

📌 Comparison:
Local:
- Works on basic blocks
- Simple and fast
- Example: Constant folding

Global:
- Uses full control flow
- Complex, needs data analysis
- Example: Loop unrolling

────────────────────────────────────
🔶 Q4. Explain different approaches to compiler development.

✅ Easy Definition:
Methods to design compilers depending on language and performance needs.

🌍 Real-world Analogy:
Like different ways of building a house – quick prefab, detailed blueprint, or modular.

📌 Approaches:
- Single-Pass Compiler: Fast but limited (e.g., Pascal).
- Multi-Pass Compiler: Multiple scans, better error checking (e.g., C, Java).
- Load-and-Go Compiler: Compiles + Loads together.
- Just-in-Time (JIT) Compiler: Compiles during runtime (e.g., Java, .NET).

────────────────────────────────────
🔶 Q5. What kinds of errors are detected during code generation?

✅ Easy Definition:
These are machine-level errors found just before final code execution.

🌍 Real-world Analogy:
Like checking for typos just before printing a book.

📌 Common Errors:
- Wrong register allocation
- Stack overflow/underflow
- Memory mismanagement
- Type mismatch
- Invalid jump/branch targets

────────────────────────────────────
📝 Summary (Keywords to Remember):
- Language processor = translator
- Compiler = Analysis + Synthesis
- Local optimization = Basic block level
- Global optimization = Whole program level
- Errors = Final machine-level problems
