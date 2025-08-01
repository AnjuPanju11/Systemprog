📘 MCSE-204 – UNIT 4: Distributed Operating Systems

────────────────────────────────────
🔶 **Q1. Design Issues in Distributed Operating Systems**

✅ Easy Definition:
A Distributed Operating System (DOS) manages a group of independent computers and makes them appear as one system.

🌍 Real-world Analogy:
Like a manager coordinating work between multiple office branches.

📌 Major Design Issues:
- **Transparency**
  • Access, Location, Replication
- **Fault Tolerance**
- **Resource Management**
- **Security**
- **Scalability**

📌 Summary Bullets:
- Coordination between nodes is key
- Must hide complexity from users
- Secure and efficient resource sharing

────────────────────────────────────
🔶 **Q2. Goals of Distributed Operating System & How Deadlocks Occur**

✅ Easy Definition:
Goals define the purpose of a Distributed OS; deadlocks happen when processes wait indefinitely.

🌍 Real-world Analogy:
- Goal = Like team goals (collaboration, performance)
- Deadlock = Everyone waiting on each other endlessly

📌 Goals:
- Transparency
- Resource Sharing
- Fault Tolerance
- High Performance
- Scalability

📌 Deadlock Causes:
- Mutual Exclusion
- Hold and Wait
- No Preemption
- Circular Wait

📌 Deadlock Handling:
- Centralized or hierarchical detection
- Rollback or timeout

📌 Summary:
- Good design avoids deadlocks
- Use detection/prevention techniques

────────────────────────────────────
🔶 **Q3. Kernel Actions During Page-In and Page-Out**

✅ Easy Definition:
Page-In loads memory from disk. Page-Out saves memory to disk.

🌍 Real-world Analogy:
Page-In = Taking a book from the shelf  
Page-Out = Returning the book to the shelf

📌 Page-In Actions:
- Identify required page
- Find it on disk
- Load into memory
- Update tables

📌 Page-Out Actions:
- Select page to remove
- Check if modified
- Save to disk
- Update status

📌 Summary:
- Vital for memory management
- Optimized to reduce delays

────────────────────────────────────
🔶 **Q4. Security Attacks in Distributed Systems**

✅ Easy Definition:
Security attacks are attempts to steal, destroy or alter data in distributed systems.

🌍 Real-world Analogy:
Like a cyber-thief breaking into one office and accessing the whole company.

📌 Common Attacks:
- Eavesdropping
- Masquerading
- Replay Attack
- Denial of Service (DoS)
- Data Modification

📌 Prevention:
- Authentication
- Encryption
- Firewalls & IDS

📌 Summary:
- Secure data during transfer and storage
- Use strong security protocols

────────────────────────────────────
🔶 **Q5. Multiprocessor Operating System Structure (with Example)**

✅ Easy Definition:
Multiprocessor OS manages systems with multiple CPUs sharing memory and I/O.

🌍 Real-world Analogy:
Like multiple chefs sharing the same kitchen space.

📌 Structures:
1. Master-Slave
2. Symmetric Multiprocessing (SMP)

📌 Benefits:
- High speed
- Fault tolerance
- Balanced workload

📌 Summary:
- Parallel processing
- Careful scheduling needed

────────────────────────────────────
📝 Summary (Keywords to Remember):
- DOS = Manages multiple systems as one
- Design issues = Transparency, Fault Tolerance
- Page-In/Out = Memory management
- Security = Protect data and system
- Multiprocessor = Shared workload
