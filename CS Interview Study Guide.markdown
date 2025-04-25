# CS Interview Study Guide

## Session 1: Computer Architecture - What is a Computer and Why Do You Need to Know?

### Key Concepts
- **Definition of a Computer**: A programmable electronic device that processes data through input, processing, storage, and output.
- **Components**:
  - **CPU**: Executes instructions (fetch-decode-execute cycle).
  - **Memory**: RAM (volatile, fast), ROM (non-volatile), cache.
  - **Storage**: HDD, SSD for persistent data.
  - **I/O Devices**: Keyboard, mouse, monitor.
  - **Bus**: Communication system connecting components.
- **Von Neumann Architecture**: Stored program concept, sequential instruction execution.
- **Why It Matters**:
  - Understanding performance bottlenecks (e.g., CPU vs. memory-bound tasks).
  - Optimizing code for hardware (e.g., cache locality).
  - Debugging low-level issues (e.g., memory leaks, race conditions).

### Study Resources
- *Computer Organization and Design* by Patterson and Hennessy.
- Online: MIT OpenCourseWare (6.004 Computation Structures).
- Practice: Explain how a CPU processes an instruction in 2 minutes.

---

## Session 2: Algorithms and Data Structures Review - Part 1

### Key Topics
- **Arrays and Strings**:
  - Operations: Searching, sorting, reversing.
  - Common Problems: Two-pointer techniques, sliding window.
- **Linked Lists**:
  - Singly, doubly, circular.
  - Operations: Reverse, detect cycle, merge.
- **Stacks and Queues**:
  - LIFO (Stack), FIFO (Queue).
  - Applications: Expression evaluation, BFS.
- **Time/Space Complexity**:
  - Big-O notation for all operations.
  - Trade-offs (e.g., array vs. linked list).

### Common Problems
- Reverse a linked list.
- Valid parentheses (stack).
- Two-sum (hash map or two-pointer).

### Study Resources
- *Introduction to Algorithms* by Cormen (CLRS).
- LeetCode: Easy/Medium problems under "Array", "String", "Linked List".
- Practice: Solve 5 LeetCode problems daily (e.g., Merge Two Sorted Lists).

---

## Session 3: Algorithms and Data Structures Review - Part 2

### Key Topics
- **Trees and Graphs**:
  - Binary trees, BST, AVL trees, heaps.
  - Graph representations: Adjacency list/matrix.
  - Traversals: DFS (pre/in/post-order), BFS.
- **Advanced Algorithms**:
  - Divide and Conquer (e.g., merge sort).
  - Greedy algorithms (e.g., Kruskal’s).
  - Dynamic Programming (e.g., knapsack, longest common subsequence).
- **Hashing**:
  - Hash tables, collision resolution (chaining, open addressing).
  - Applications: Frequency counting, caching.

### Common Problems
- Invert a binary tree.
- Shortest path in a graph (Dijkstra’s, BFS).
- Longest palindromic substring (DP).

### Study Resources
- *Algorithms* by Sedgewick and Wayne.
- LeetCode: Medium/Hard problems under "Tree", "Graph", "Dynamic Programming".
- Practice: Implement DFS/BFS for a graph.

---

## Session 4: Operating Systems

### Key Concepts
- **Processes and Threads**:
  - Process: Program in execution (PCB, states).
  - Thread: Lightweight process, shares memory.
  - Multithreading vs. multiprocessing.
- **Scheduling**:
  - FCFS, SJF, Round Robin.
  - Context switching, starvation.
- **Memory Management**:
  - Virtual memory, paging, segmentation.
  - Page replacement (LRU, FIFO).
- **Synchronization**:
  - Race conditions, critical sections.
  - Locks, semaphores, monitors.
- **Deadlocks**:
  - Conditions, prevention, detection.

### Study Resources
- *Operating System Concepts* by Silberschatz, Galvin, Gagne.
- Online: Stanford CS140 (Operating Systems).
- Practice: Explain how virtual memory works in 3 minutes.

---

## Session 5: Linux

### Key Concepts
- **File System**:
  - Structure: `/`, `/home`, `/etc`.
  - Commands: `ls`, `cd`, `mkdir`, `rm`.
- **Processes**:
  - Monitoring: `ps`, `top`, `htop`.
  - Control: `kill`, `fg`, `bg`.
- **Permissions**:
  - `chmod`, `chown`, `sudo`.
  - Read/write/execute for user/group/others.
- **Shell Scripting**:
  - Basics: Variables, loops, conditionals.
  - Tools: `grep`, `awk`, `sed`.
- **Networking**:
  - Commands: `ping`, `netstat`, `curl`.

### Practice
- Write a shell script to find and delete files older than 7 days.
- Debug a process consuming high CPU using `top` and `strace`.

### Study Resources
- *The Linux Command Line* by William Shotts.
- Online: Linux Journey (linuxjourney.com).
- Practice: Set up a Linux VM and run 10 common commands.

---

## Session 6: Low-Level Programming - C/C++

### Key Concepts
- **C Basics**:
  - Pointers, memory allocation (`malloc`, `free`).
  - Structs, unions, enums.
  - Preprocessor directives (`#define`, `#include`).
- **C++ Basics**:
  - OOP: Classes, inheritance, polymorphism.
  - STL: Vectors, maps, sets.
  - Smart pointers (`unique_ptr`, `shared_ptr`).
- **Memory Management**:
  - Stack vs. heap.
  - Buffer overflows, dangling pointers.
- **Performance**:
  - Inline functions, const correctness.
  - Move semantics (C++).

### Practice
- Implement a linked list in C.
- Write a C++ class for a binary tree with traversal methods.

### Study Resources
- *C Programming Language* by Kernighan and Ritchie.
- *Effective C++* by Scott Meyers.
- LeetCode: Solve problems in C/C++ (e.g., Reverse String).

---

## Session 7: High-Level Programming - Comparison between JavaScript, Python, Go

### Key Comparisons
- **JavaScript**:
  - Strengths: Event-driven, asynchronous (Promises, async/await), web development.
  - Weaknesses: Dynamic typing, browser quirks.
  - Use Case: Front-end (React), back-end (Node.js).
- **Python**:
  - Strengths: Readable syntax, extensive libraries, data science/AI.
  - Weaknesses: Slower execution, GIL for threading.
  - Use Case: Scripting, ML (TensorFlow), web (Django).
- **Go**:
  - Strengths: Concurrency (goroutines), simplicity, fast compilation.
  - Weaknesses: Limited libraries, no generics (pre-Go 1.18).
  - Use Case: Cloud services, microservices (Kubernetes).

### Practice
- Write a REST API server in each language.
- Compare performance of a sorting algorithm in all three.

### Study Resources
- *Eloquent JavaScript* by Marijn Haverbeke.
- *Learning Python* by Mark Lutz.
- Go Docs: tour.golang.org.

---

## Session 8: Networking

### Key Concepts
- **OSI Model**:
  - Layers: Physical, Data Link, Network, Transport, Application.
  - Protocols: TCP, UDP, IP, HTTP.
- **TCP/IP**:
  - Three-way handshake, connection termination.
  - Reliability vs. speed (TCP vs. UDP).
- **DNS**:
  - Domain to IP resolution.
  - Records: A, CNAME, MX.
- **HTTP**:
  - Methods: GET, POST, PUT, DELETE.
  - Status codes: 200, 404, 500.
- **Sockets**:
  - Client-server communication.
  - Blocking vs. non-blocking.

### Practice
- Write a TCP client-server in Python.
- Explain the difference between HTTP/1.1 and HTTP/2.

### Study Resources
- *Computer Networking: A Top-Down Approach* by Kurose and Ross.
- Online: Beej’s Guide to Network Programming.

---

## Session 9: Database - Part 1

### Key Concepts
- **Relational Databases**:
  - Tables, rows, columns.
  - SQL: SELECT, INSERT, UPDATE, DELETE.
  - Joins: INNER, LEFT, RIGHT, FULL.
- **Normalization**:
  - 1NF, 2NF, 3NF.
  - Trade-offs: Performance vs. redundancy.
- **Indexing**:
  - B-trees, hash indexes.
  - Clustered vs. non-clustered.
- **Transactions**:
  - ACID properties.
  - Isolation levels (read uncommitted, serializable).

### Practice
- Write SQL queries for a sample e-commerce database.
- Design a schema for a blogging platform.

### Study Resources
- *SQL in 10 Minutes, Sams Teach Yourself* by Ben Forta.
- Online: Mode Analytics SQL Tutorial.

---

## Session 10: Database - Part 2

### Key Concepts
- **NoSQL Databases**:
  - Types: Key-value (Redis), Document (MongoDB), Column (Cassandra), Graph (Neo4j).
  - CAP Theorem: Consistency, Availability, Partition Tolerance.
- **Scaling**:
  - Vertical vs. horizontal scaling.
  - Sharding, replication.
- **Caching**:
  - In-memory stores (Redis, Memcached).
  - Cache eviction policies (LRU, LFU).
- **ORMs**:
  - Tools: SQLAlchemy (Python), Mongoose (JavaScript).
  - Pros: Abstraction; Cons: Performance overhead.

### Practice
- Design a MongoDB schema for a social media app.
- Set up Redis for caching API responses.

### Study Resources
- *NoSQL Distilled* by Pramod Sadalage.
- Online: MongoDB University.

---

## Session 11: Security - Basic Concepts for System Design Interviews

### Key Concepts
- **Authentication**:
  - Passwords, OAuth, JWT.
  - Multi-factor authentication.
- **Authorization**:
  - Role-based access control (RBAC).
  - Permissions and policies.
- **Encryption**:
  - Symmetric (AES) vs. asymmetric (RSA).
  - TLS/SSL for secure communication.
- **Common Vulnerabilities**:
  - SQL injection, XSS, CSRF.
  - Mitigation: Input validation, secure headers.
- **Secure Design**:
  - Principle of least privilege.
  - Defense in depth.

### Practice
- Implement JWT authentication in a Node.js app.
- Identify vulnerabilities in a given API endpoint.

### Study Resources
- *Hacking: The Art of Exploitation* by Jon Erickson.
- Online: OWASP Top 10 (owasp.org).

---

## Session 12: Discussion - What We Think About Trends in Software Engineering

### Key Trends
- **AI and ML Integration**:
  - AI-powered tools (e.g., GitHub Copilot).
  - Ethical concerns: Bias, privacy.
- **Cloud-Native Development**:
  - Microservices, serverless, Kubernetes.
  - Challenges: Complexity, observability.
- **Low-Code/No-Code Platforms**:
  - Democratizing development.
  - Limitations: Scalability, customization.
- **Web3 and Blockchain**:
  - Decentralized apps, smart contracts.
  - Hype vs. practical use cases.
- **DevOps and Automation**:
  - CI/CD pipelines, IaC (Terraform).
  - Focus on reliability (SRE).

### Discussion Points
- How do these trends impact hiring and skill requirements?
- Which trends are overhyped vs. truly transformative?
- How to stay relevant as a software engineer?

### Study Resources
- Blogs: Martin Fowler, ThoughtWorks.
- Podcasts: Software Engineering Daily, The Changelog.
- Practice: Research one trend and present its pros/cons in 5 minutes.