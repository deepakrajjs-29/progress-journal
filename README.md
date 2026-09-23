# Progress Journal 📖

[![Daily Updates](https://img.shields.io/badge/Updates-Daily%20(Automated)-brightgreen?style=flat-square&logo=githubactions)](https://github.com/deepakrajjs-29/progress-journal)
[![Curriculum](https://img.shields.io/badge/Curriculum-CS%20%26%20Software%20Engineering-blue?style=flat-square)](https://github.com/deepakrajjs-29/progress-journal)
[![Progression](https://img.shields.io/badge/Progression-Beginner%20%E2%86%92%20Advanced-orange?style=flat-square)](https://github.com/deepakrajjs-29/progress-journal)
[![Grounding](https://img.shields.io/badge/Grounding-Authoritative%20Docs-blueviolet?style=flat-square)](https://github.com/deepakrajjs-29/progress-journal)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](LICENSE)

A living, structured, daily developer learning journal and technical reference notebook.

Every entry captures a core engineering mechanism, fundamental computer science concept, or systems principle in a high-density, **1–3 minute read format**.

---

## 🧭 Table of Contents

| Category | Focus Areas | Directory Link |
| :--- | :--- | :--- |
| 💻 **Programming** | Variables, data types, control flow, functions, testing, modular code | [`programming/`](programming/) |
| 🔀 **Git & Version Control** | Repository internals, staging, branching, merging, remote workflows | [`git/`](git/) |
| 🗄️ **Databases** | Relational models, SQL, indexing strategies, query planning, ACID | [`databases/`](databases/) |
| 🌐 **Networking** | TCP/UDP, DNS, IP addressing, HTTP/HTTPS, TLS, sockets | [`networking/`](networking/) |
| 🌍 **Web Architecture** | Client-server lifecycle, REST APIs, JSON, sessions & cookies | [`web/`](web/) |
| 🐧 **Linux & Systems** | Filesystem hierarchy, shell, process model, permissions, pipes | [`linux/`](linux/) |
| 🐳 **Docker & Containers** | Images, containers, Dockerfiles, volumes, port mapping | [`docker/`](docker/) |
| 🛡️ **Security** | Authentication vs authorization, hashing, secrets, least privilege | [`security/`](security/) |
| 🧠 **Computer Science** | Execution, concurrency, memory models, data structures, Big-O | [`computer-science/`](computer-science/) |

---

## 🎯 Note Anatomy & Structure

Every note in this notebook follows a strict, distraction-free **4-part template** designed for maximum retention and rapid lookup:

```markdown
# [Concept Name]

## Question
The core technical mechanism or problem to solve.

## Short Answer
A concise, direct explanation in 2–5 sentences explaining the "why" and "how".

## Simple Example
A minimal, copy-pasteable code snippet, terminal command, or ASCII diagram.

## Key Point
The single primary takeaway to remember.
```

### Real Note Example
Here is an excerpt from [`programming/python-variables-and-data-types.md`](programming/python-variables-and-data-types.md):

> **Question**: What are Python Variables and Data Types and why are they used?  
> **Short Answer**: In Python, variables are named references pointing to objects in computer memory rather than fixed storage boxes. Python is dynamically typed, meaning variable types such as integers, floats, strings, and booleans are determined automatically at runtime without explicit type declarations. Assigning a value to a variable simply binds that name to the corresponding object.  
> **Simple Example**:
> ```python
> count = 42          # Integer
> price = 19.99       # Float
> is_active = True    # Boolean
> user_name = 'Alice' # String
> ```
> **Key Point**: Variables are labels pointing to memory objects, and their types are resolved dynamically at runtime.

---

## 📈 Learning Progression Model

The journal moves methodically through three distinct stages of technical depth:

```
┌─────────────────────────────────────────────────────────────┐
│ 1. BEGINNER FOUNDATIONS (Level 1)                           │
│    Core syntax, primitive definitions, component roles      │
└──────────────────────────────┬──────────────────────────────┘
                               │ (Threshold: 30+ entries, 6+ categories)
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 2. INTERMEDIATE MECHANISMS (Level 2)                        │
│    Execution models, trade-offs, protocols, best practices   │
└──────────────────────────────┬──────────────────────────────┘
                               │ (Threshold: 60+ entries, foundation markers met)
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 3. ADVANCED INTERNALS (Level 3)                             │
│    Concurrency primitives, kernel interactions, systems design│
└─────────────────────────────────────────────────────────────┘
```

- **Curriculum Prerequisite Gates**: Advanced concepts are not introduced until foundational prerequisites have been published.
- **Breadth-First Rotation**: Rotates through key disciplines (Computer Science, Programming, Git, Databases, Networks, Web, Linux, Docker, Security) to maintain balanced engineering growth.

---

## ⚡ Guiding Principles

1. **Authoritative Documentation**: All notes are extracted and verified against official documentation (Python Docs, Git SCM, PostgreSQL, MDN Web Docs, Linux man pages, Docker Docs).
2. **Zero Hallucination / Zero AI Fluff**: No buzzwords, no vague metaphors, and no filler text.
3. **No Empty Commits**: Every commit represents a real, validated markdown entry.
4. **Permanent & Self-Contained**: This repository contains exclusively human-readable markdown files. It has no build scripts, no web server requirements, and zero third-party lock-in.

---

## ⚙️ Powered By

This repository is automatically populated by **[`progress-engine`](https://github.com/deepakrajjs-29/progress-engine)** — a private, deterministic content generation and validation engine running via scheduled GitHub Actions.

---

## 👤 Author

**DEEPAK RAJ J.S**
- GitHub: [@deepakrajjs-29](https://github.com/deepakrajjs-29)
- Email: [deepakrajjs2909@gmail.com](mailto:deepakrajjs2909@gmail.com)

---

## 📄 License

This repository is open source and available under the [MIT License](LICENSE).
