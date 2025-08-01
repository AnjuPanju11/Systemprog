# 📘 MCSE-204 – UNIT 4: Distributed Operating Systems

---

## 🔶 🔥 Q1. DESIGN ISSUES IN DISTRIBUTED OPERATING SYSTEMS

✅ **Easy Definition**: A Distributed Operating System (DOS) manages multiple computers and presents them as a single system to the user.

🌍 **Real-world Analogy**: Like a manager handling teams in different cities, making it feel like one company.

📌 **Major Design Issues**:

* **Transparency**: Access, Location, Replication
* **Fault Tolerance**
* **Resource Management**
* **Security**
* **Scalability**

📌 **Summary Bullets**:

* Hides system complexity
* Manages distributed hardware
* Provides a unified interface
* Ensures consistent performance and reliability

---

## 🔶 🔥 Q2. GOALS OF DISTRIBUTED OS & HOW DEADLOCKS OCCUR

✅ **Easy Definition**: Goals define the purpose of a Distributed OS; deadlocks are situations where processes get stuck waiting on each other forever.

🌍 **Real-world Analogy**: Like team members all waiting on each other to move first – no one progresses.

📌 **Goals**:

* **Transparency**
* **Resource Sharing**
* **Fault Tolerance**
* **Scalability**
* **High Performance**

📌 **Causes of Deadlock**:

* Mutual Exclusion
* Hold and Wait
* No Preemption
* Circular Wait

📌 **Deadlock Handling Methods**:

* Centralized Detection
* Hierarchical Detection
* Timeout and Rollback

📌 **Summary**:

* Deadlocks must be detected or prevented
* Goals ensure effective and smooth operation

---

## 🔶 🔥 Q3. KERNEL ACTIONS DURING PAGE-IN AND PAGE-OUT

✅ **Easy Definition**: Page-In loads a memory page from disk to RAM; Page-Out writes a page from RAM back to disk.

🌍 **Real-world Analogy**: Borrowing a book from the library (page-in), and returning it later (page-out).

📌 **Page-In Steps**:

* Locate the required page
* Allocate memory in RAM
* Load the page from disk
* Update page table and TLB

📌 **Page-Out Steps**:

* Choose a page to evict
* If modified, write it to disk
* Update memory map

📌 **Summary**:

* Improves memory efficiency
* Key part of virtual memory systems

---

## 🔶 🔥 Q4. SECURITY ATTACKS IN DISTRIBUTED SYSTEMS

✅ **Easy Definition**: Unauthorized activities aimed at accessing or damaging data in a distributed network.

🌍 **Real-world Analogy**: Like a thief breaking into one office and trying to access the entire organization’s system.

📌 **Types of Attacks**:

* **Eavesdropping**: Listening to communication
* **Masquerading**: Impersonating a legitimate user
* **Replay Attacks**: Resending old messages
* **Denial of Service (DoS)**: Flooding to disrupt service
* **Modification**: Altering data

📌 **Prevention Techniques**:

* Authentication (e.g., passwords, biometrics)
* Encryption (SSL/TLS)
* Firewalls and Intrusion Detection Systems (IDS)

📌 **Summary**:

* Secure data at rest and in transit
* Implement robust authentication and monitoring

---

## 🔶 🔥 Q5. MULTIPROCESSOR OS STRUCTURE (WITH EXAMPLE)

✅ **Easy Definition**: A multiprocessor OS manages multiple CPUs that share memory and devices, ensuring coordination and task distribution.

🌍 **Real-world Analogy**: Like multiple chefs working in one kitchen, sharing utensils and space efficiently.

📌 **Structures**:

* **Master-Slave**: One CPU controls the others
* **Symmetric Multiprocessing (SMP)**: All CPUs are treated equally

📌 **Benefits**:

* Increased speed and parallelism
* Fault Tolerance
* Load balancing

📌 **Summary**:

* Allows better resource use
* Enhances system performance through concurrency
