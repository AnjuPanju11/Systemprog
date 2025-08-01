📘 MCSE-204 – UNIT 4: Distributed Operating Systems

────────────────────────────────────
🔶 Q1. Design Issues in Distributed Operating Systems

✅ Easy Definition:
A **Distributed Operating System (DOS)** manages a group of independent computers and makes them appear to the users as a single system.

🌍 Real-world Analogy:
Like a manager coordinating work between multiple branches of a company.

📌 Major Design Issues:

1. **Transparency**:
   - Access Transparency: Remote & local resources look the same
   - Location Transparency: User doesn't know where resource is located
   - Replication Transparency: Multiple copies managed efficiently

2. **Fault Tolerance**:
   - System should recover from failures without major disruptions

3. **Resource Management**:
   - Efficient allocation of CPU, memory, I/O across nodes

4. **Security**:
   - User authentication, data protection, secure communication

5. **Scalability**:
   - Should support growing number of nodes and users

📌 Summary Bullets:
- Distributed coordination is key
- System must hide complexity from users
- Resource sharing must be smooth & secure

────────────────────────────────────
🔶 Q2. Goals of Distributed Operating System & How Deadlocks Occur

✅ Easy Definition:
Goals define what a Distributed OS must achieve; deadlock is a condition where processes wait forever due to resource hold.

🌍 Real-world Analogy:
- Goal = Like goals in team sports: teamwork, coordination, success
- Deadlock = Everyone holding one item and waiting for the next — no progress

📌 Goals of Distributed OS:
- Transparency (Access, Location, Migration, Replication)
- Reliability and fault tolerance
- Scalability
- Resource Sharing
- High Performance

📌 Deadlocks in Distributed Systems:
- Circular waiting among processes across nodes
- Caused by:
  • No preemption
  • Hold and wait
  • Mutual exclusion

📌 Deadlock Prevention:
- Centralized deadlock detection
- Hierarchical deadlock detection
- Timeouts and rollback mechanisms

📌 Summary:
- Goals = Efficiency + Simplicity
- Deadlocks = Wait chains that never resolve
- Use detection or prevention mechanisms

────────────────────────────────────
🔶 Q3. Kernel Actions During Page-In and Page-Out

✅ Easy Definition:
**Page-In** loads a page from disk into memory.  
**Page-Out** saves a page from memory back to disk.

🌍 Real-world Analogy:
- Page-In = Taking a book from the shelf to read
- Page-Out = Returning the book to the shelf when done

📌 Actions during Page-In:
- Identify required page
- Locate it on secondary storage
- Allocate space in RAM
- Load the page into memory
- Update page tables and TLB

📌 Actions during Page-Out:
- Identify page to be removed
- Check if it’s modified
- Write back to disk if dirty
- Update page tables

📌 Summary:
- Involves memory management
- Crucial in virtual memory systems
- Optimized to reduce delays

────────────────────────────────────
🔶 Q4. Security Attacks in Distributed Systems

✅ Easy Definition:
Security attacks are unauthorized actions that aim to steal, modify, or destroy data in a distributed environment.

🌍 Real-world Analogy:
Like a thief trying to break into one branch of a company and get access to all branches.

📌 Common Types of Attacks:
1. **Eavesdropping**:
   - Intercepting data during transmission

2. **Masquerading**:
   - Pretending to be someone else (identity theft)

3. **Replay Attack**:
   - Resending valid data to gain unauthorized access

4. **Denial of Service (DoS)**:
   - Flooding system with traffic to crash it

5. **Modification Attack**:
   - Changing content in transmission

📌 Preventive Measures:
- Authentication (passwords, biometrics)
- Encryption (SSL, TLS)
- Firewalls and Intrusion Detection Systems (IDS)

📌 Summary:
- Protect data in motion and at rest
- Use strong security protocols
- Regularly audit and update

────────────────────────────────────
🔶 Q5. Multiprocessor Operating System Structure (with Example)

✅ Easy Definition:
A **Multiprocessor OS** manages a system with two or more CPUs working together, sharing the same memory and I/O.

🌍 Real-world Analogy:
Like a team of cooks in one kitchen – working together but sharing the same space and tools.

📌 Types of Structures:
1. **Master-Slave**:
   - One CPU is master, others assist
   - Master assigns tasks and controls

2. **Symmetric Multiprocessing (SMP)**:
   - All CPUs are equal
   - Share workload equally

📌 Benefits:
- Increased speed and throughput
- Fault tolerance
- Load balancing

📌 Summary:
- Multiprocessor OS increases parallelism
- Proper scheduling and synchronization required

────────────────────────────────────
📝 Summary (Keywords to Remember):
- DOS = Manages many systems as one
- Design issues = Transparency, Fault Tolerance
- Page-In/Out = Load and remove memory pages
- Security = Preventing eavesdropping, DoS
- Multiprocessor = Many CPUs sharing memory
