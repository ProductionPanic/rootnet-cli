# Rootnet CLI 🚀

A high-performance Go-based CLI for managing and connecting to project servers. It replaces messy Bash aliases with a single binary featuring a fuzzy-search TUI, clipboard integration, and partial-match resolution.

## Features
* **Fuzzy Search:** Built-in TUI (via Charm Bubbletea) that opens in search mode by default.
* **Partial Matching:** `rootnet-get` resolves partial names instantly if a unique match is found.
* **Portable:** Compiles to a single binary.

---

## Installation

### 1. Prerequisites
* **Go 1.21+**
* [Optional but recommended] **Fira Code** or any Nerd Font for the best TUI experience.

### 2. Build & Install
```bash
go install github.com/ProductionPanic/rootnet-cli@latest 
```