## 01: Programming Paradigms
* **Declarative vs. Imperative Programming:** The fundamental difference between telling a computer *what* to do vs. *how* to do it.
* **Logic Programming:** A mind-bending paradigm, with Prolog as the classic example.
* **Event-Driven Programming:** The core model behind GUIs and modern backends like Node.js.

## 02/03: Data Structures & Algorithms
* **Trees:**
    * **Binary Search Trees (BST):** The foundation for ordered data.
    * **Tries (Prefix Trees):** Essential for features like autocomplete.
    * **Heaps (Min/Max Heaps):** The structure behind priority queues.
* **Graphs:**
    * **Graph Representation:** Adjacency List vs. Adjacency Matrix.
    * **Graph Traversal Algorithms:** Breadth-First Search (BFS) vs. Depth-First Search (DFS).
* **Hash Table Internals:** How do they really work? (Hashing functions, collision resolution).
* **Dynamic Programming:** A powerful technique for solving complex problems by breaking them into smaller, simpler subproblems.

## 04: System Design
* **Concepts:**
    * **Idempotency:** Why is it critical for reliable APIs?
    * **Rate Limiting:** Algorithms (Token Bucket, Leaky Bucket) and strategies.
    * **Content Delivery Network (CDN):** How they work to speed up the web.
    * **Proxies:** Forward Proxy vs. Reverse Proxy.
    * **Replication & Sharding:** Strategies for scaling databases horizontally.
    * **Consistent Hashing:** A technique used in load balancing and distributed systems.
* **Case Studies ("How would you design..."):**
    * **A URL Shortener (like TinyURL):** A classic system design interview question.
    * **A Web Crawler (like Googlebot):** A study in concurrency, politeness, and data processing.
    * **A Distributed Key-Value Store (like DynamoDB):** Explores consistency, availability, and partitioning.
    * **The "Typeahead" Autocomplete for a Search Bar:** A great use case for Tries.
    * **A Real-time Notification System:** Involves WebSockets, message queues, and fan-out patterns.

## 05: Networking Basics
* **The OSI Model vs. TCP/IP Model:** The two fundamental layered models of networking.
* **How DNS Works:** The process of translating a domain name to an IP address.
* **TCP vs. UDP:** The trade-offs between reliability and speed.
* **HTTP/1.1 vs. HTTP/2 vs. HTTP/3:** The evolution of the web's primary protocol.
* **REST vs. GraphQL vs. gRPC:** Different paradigms for building APIs.
* **WebSockets:** For persistent, bidirectional communication.

## 06: Database Fundamentals
* **Database Indexing Internals:** How do B-Tree indexes actually work to speed up queries?
* **ACID Transactions:** The properties that guarantee database reliability (Atomicity, Consistency, Isolation, Durability).
* **Database Normalization:** The process of organizing data to reduce redundancy (1NF, 2NF, 3NF).
* **The N+1 Query Problem:** A common performance bottleneck in applications using an ORM.
* **Connection Pooling:** Why it's essential for performant database access.

## 07: Software Architecture
* **CQRS (Command Query Responsibility Segregation):** Separating read and write operations for scalable systems.
* **Serverless Architecture:** The pros and cons of using functions-as-a-service (FaaS).
* **Hexagonal Architecture (Ports and Adapters):** A pattern for creating decoupled and testable applications.
* **Service Discovery in Microservices:** How do services find each other in a dynamic environment?

## 08: Developer Practices
* **SOLID Principles:** A mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable.
* **The Twelve-Factor App:** A methodology for building robust, scalable software-as-a-service apps.
* **Test-Driven Development (TDD) vs. Behavior-Driven Development (BDD):** Different philosophies for how testing drives the development process.
* **The Art of Debugging:** Systematic approaches to finding and fixing bugs.
* **How to Read and Review Code Effectively:** A critical skill for team collaboration and learning.
* **Mental Models for Problem Solving:** Exploring concepts like "First-Principles Thinking" or "Thinking in Bets" as they apply to software.
