📘 MCSE-204 – UNIT 4: Distributed Operating Systems

════════════════════════════════════
🔶 🔥 Q1. DESIGN ISSUES IN DISTRIBUTED OPERATING SYSTEMS
════════════════════════════════════

✅ Easy Definition:
A Distributed Operating System (DOS) manages multiple computers and presents them as a single system to the user.

🌍 Real-world Analogy:
Like a manager handling teams in different cities, making it feel like one company.

📌 Major Design Issues:
- **Transparency**
  • Access, Location, Replication
- **Fault Tolerance**
- **Resource Management**
- **Security**
- **Scalability**

📌 Summary Bullets:
- Hides system complexity
- Handles resources across nodes
- Provides security and coordination

════════════════════════════════════
🔶 🔥 Q2. GOALS OF DISTRIBUTED OS & HOW DEADLOCKS OCCUR
════════════════════════════════════

✅ Easy Definition:
Goals define what the system aims to achieve; deadlocks are situations where processes get stuck waiting on each other forever.

🌍 Real-world Analogy:
- Goals = Running a smooth business across locations
- Deadlock = Everyone waiting on someone else to act first

📌 Goals:
- Transparency
- Resource Sharing
- Fault Tolerance
- Scalability
- High Performance

📌 Deadlock Causes:
- Mutual Exclusion
- Hold and Wait
- No Preemption
- Circular Wait

📌 Solutions:
- Centralized/Hierarchical Detection
- Timeout/Rollback

📌 Summary:
- Must ensure smooth coordination
- Deadlock prevention is critical

════════════════════════════════════
🔶 🔥 Q3. KERNEL ACTIONS DURING PAGE-IN AND PAGE-OUT
════════════════════════════════════

✅ Easy Definition:
Page-In brings data from disk to memory. Page-Out sends unused memory back to disk.

🌍 Real-world Analogy:
- Page-In = Taking a book off the shelf to read  
- Page-Out = Returning the book after reading

📌 Page-In Actions:
- Locate the page
- Find on disk
- Load into RAM
- Update memory map

📌 Page-Out Actions:
- Pick unused page
- Check if changed
- Save to disk if needed
- Update records

📌 Summary:
- Efficient memory use
- Part of virtual memory handling

════════════════════════════════════
🔶 🔥 Q4. SECURITY ATTACKS IN DISTRIBUTED SYSTEMS
════════════════════════════════════

✅ Easy Definition:
Unauthorized attempts to access or damage systems in a distributed network.

🌍 Real-world Analogy:
Like a hacker entering one branch to steal data from the entire organization.

📌 Types of Attacks:
- Eavesdropping
- Masquerading
- Replay Attacks
- DoS (Denial of Service)
- Data Modification

📌 Defense Techniques:
- Authentication (Passwords, Biometrics)
- Encryption (TLS, SSL)
- Firewalls, IDS (Intrusion Detection)

📌 Summary:
- Protect data in transit and at rest
- Regular security updates are vital

════════════════════════════════════
🔶 🔥 Q5. MULTIPROCESSOR OS STRUCTURE (WITH EXAMPLE)
════════════════════════════════════

✅ Easy Definition:
An OS designed to run on systems with more than one CPU, sharing memory and devices.

🌍 Real-world Analogy:
Like multiple chefs cooking in one kitchen—sharing tools and ingredients.

📌 Structures:
- **Master-Slave** → One main CPU controls the rest
- **SMP (Symmetric Multiprocessing)** → All CPUs are equal

📌 Benefits:
- Speed and performance
- Load balancing
- Fault tolerance

📌 Summary:
- Manages shared memory and resources
- Better efficiency with parallel execution

════════════════════════════════════
📝 QUICK RECALL:
- DOS = One OS over many systems
- Deadlocks = Wait chains
- Page-In/Out = Memory swapping
- Security = Protect from attacks
- Multiprocessor = Parallel CPU operations
