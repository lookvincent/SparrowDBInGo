# SparrowDB 🐦

> A tiny, educational relational database built from scratch in Go — under 3000 lines of code.

SparrowDB is a minimal, self-contained database implemented entirely in **Go**, with **zero external dependencies**. It’s designed to demystify how real databases work: from parsing SQL and managing tables, to storing data on disk and executing queries.

Small like a sparrow, but built to teach you the core ideas behind systems like SQLite, PostgreSQL, and MySQL — one commit at a time.

## ✨ Features (Current)
- Simple SQL parser supporting:
  - `CREATE TABLE name (col1 TYPE, col2 TYPE, ...)`
  - `INSERT INTO table VALUES (...)`
  - `SELECT * FROM table`
- In-memory table representation with typed columns (`INT`, `TEXT`)
- Persistent storage via serialized data files
- Interactive REPL for live experimentation
- Clean, idiomatic Go code (~3000 LoC total)

> 💡 **Not for production** — built for learning, curiosity, and deep understanding.

## 🧠 Why Build This?
Many developers use databases every day—but few know what happens when you type `SELECT *`.  
SparrowDB follows the philosophy:

> **“What I cannot create, I do not understand.”** — Richard Feynman

By building a database from scratch, you’ll gain intuition about:
- Query parsing & ASTs
- Data layout in memory and on disk
- The cost of full table scans
- How transactions and indexes *could* work (future!)

## 🚀 Quick Start

Make sure you have [Go 1.20+](https://golang.org/dl/) installed.
