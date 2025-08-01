📘 MCSE-204 – UNIT 3: Memory Allocation, Code Optimization & Data Flow Analysis

────────────────────────────────────
🔶 Q1. Techniques of Dynamic Storage Allocation

✅ Easy Definition:
Dynamic storage allocation is a method used to allocate memory at runtime (when the program is running).

🌍 Real-world Analogy:
Like booking a hotel room when you arrive at the destination — no pre-booking.

📌 Techniques:

1. **First Fit**:
   - Allocates the first block that is large enough
   - Fast, but may waste memory

2. **Best Fit**:
   - Allocates the smallest possible block that fits
   - Reduces wasted space but takes more time

3. **Worst Fit**:
   - Allocates the largest block available
   - Leaves larger free spaces but causes fragmentation

📌 Use Case:
Used in compilers, operating systems, and memory management units for variable storage, function calls, etc.

📌 Summary Bullets:
- Done during execution
- More flexible than static allocation
- May lead to fragmentation
- Efficient use of memory if managed properly

────────────────────────────────────
🔶 Q2. Unified Algorithm for Data Flow Analysis

✅ Easy Definition:
A single algorithm that can be adapted for multiple data flow problems such as reaching definitions, live variable analysis, etc.

🌍 Real-world Analogy:
Like a single Swiss knife tool used for cutting, opening, screwing — same base tool for different uses.

📌 Steps of the Unified Algorithm:
1. **Initialization**:
   - Set IN[B] and OUT[B] for each basic block B

2. **Iteration**:
   - Repeat until IN and OUT values stop changing:
     - IN[B] = ∪ OUT[P] for all predecessors P of B
     - OUT[B] = (IN[B] - Kill[B]) ∪ Gen[B]

3. **Apply to**:
   - Live variable analysis
   - Available expressions
   - Reaching definitions

📌 Benefits:
- Generic and reusable
- Simplifies implementation
- Reduces duplication

📌 Summary:
- Generalized data flow analysis technique
- Works on control flow graph
- Used for program optimization

────────────────────────────────────
🔶 Q3. Explain Concurrentisation and Vectorisation

✅ Easy Definition:
- **Concurrentisation**: Dividing program tasks to run in parallel.
- **Vectorisation**: Converting scalar operations into vector (array-based) operations.

🌍 Real-world Analogy:
- Concurrentisation = Multiple chefs cooking different dishes together.
- Vectorisation = One chef making 10 sandwiches at once instead of one-by-one.

📌 Concurrentisation:
- Used in multi-core processors
- Improves performance
- Needs dependency analysis

📌 Vectorisation:
- Used in scientific computing
- Increases speed using SIMD (Single Instruction Multiple Data)
- Requires loop analysis

📌 Benefits:
- Faster program execution
- Better CPU and memory usage
- Widely used in supercomputing and AI/ML

────────────────────────────────────
🔶 Q4. Loop-Carried vs Loop-Independent Dependencies

✅ Easy Definition:
- **Loop-Carried Dependency**: When current iteration depends on a previous one.
- **Loop-Independent Dependency**: No dependency between iterations.

🌍 Real-world Analogy:
- Carried: You can’t bake the second cake until the first one is done (uses same oven).
- Independent: You can iron multiple clothes independently on multiple boards.

📌 Loop-Carried:
- Slows down parallel execution
- Example:

📌 Why Important:
- Used in compiler optimization
- Helps in deciding parallel execution
- Reduces execution time if optimized

────────────────────────────────────
📝 Summary (Keywords to Remember):
- Dynamic Allocation = Memory at runtime
- First Fit, Best Fit, Worst Fit = Memory allocation methods
- Unified Algorithm = Generic data flow solution
- Concurrentisation = Task-level parallelism
- Vectorisation = Data-level parallelism
- Loop-Carried = Serial
- Loop-Independent = Parallel
