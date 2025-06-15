# Learn Programming: A Personal Knowledge Base

Welcome! This repository is my personal wiki and knowledge base for timeless, language-agnostic programming concepts, system design patterns, and computer science fundamentals.

The purpose is to create a structured, interconnected library of notes to solidify my understanding and serve as a reference for my future self.

---

![Repo status](https://img.shields.io/badge/status-in%20progress-green?style=for-the-badge)

![GitHub last commit](https://img.shields.io/github/last-commit/mayknxyz/learn-programming?style=for-the-badge)

<a href="https://www.linkedin.com/in/mikenavales/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

---

## Table of Contents

### Foundational Concepts
* **[Programming Paradigms](./01-programming-paradigms/)**: Notes on different ways to approach programming (OOP, Functional, etc.).
* **[Data Structures](./02-data-structures/)**: The fundamental ways of organizing data.
* **[Algorithms](./03-algorithms/)**: Core algorithms and complexity analysis (Big O).

### Systems & Architecture
* **[System Design](./04-system-design/)**: Concepts and case studies for designing scalable systems.
* **[Networking Basics](./05-networking-basics/)**: How computers communicate (OSI, TCP/IP, HTTP).
* **[Database Fundamentals](./06-database-fundamentals/)**: Core concepts of SQL, NoSQL, indexing, and transactions.
* **[Software Architecture](./07-software-architecture/)**: High-level patterns like Microservices, Monoliths, and Event-Driven design.

### Professional Practices
* **[Developer Practices](./08-developer-practices/)**: Best practices around clean code, testing, version control, and more.

---

### Workflow
I capture quick, unsorted ideas in the `00-inbox/` folder and later refine them into structured notes within the appropriate category. Each note aims to be atomic and linked to related concepts.


* Learn Something New: Read a blog post about the CAP Theorem.
* Create a New Note:
  * Navigate to the right folder: cd 04-system-design/
  * Create a new file: cap-theorem.md
* Use the Template: Copy the content from template.md into cap-theorem.md.
* Write Note: Fill out the sections. Explain the theorem.
* Connect Knowledge: In the Related Concepts section, think about what relates to the CAP Theorem. Might add:
  * [Database Fundamentals](../06-database-fundamentals/)
  * [SQL vs NoSQL](../06-database-fundamentals/sql-vs-nosql.md)
  * [Microservices](../07-software-architecture/monolithic-vs-microservices.md)
* Commit Work: Use a clear commit message.

```
git add 04-system-design/cap-theorem.md
git commit -m "docs: Add new note on the CAP Theorem"
git push
```
