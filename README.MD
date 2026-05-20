# DSA Learning Workspace

A collaborative repository for learning and sharing **Data Structures and Algorithms (DSA)** knowledge.

This repository provides:

- A structured place for **learning notes, examples, and revisions**
- A separate **boilerplate template branch** (`starting-boilerplate-template`) for starting DSA topics

---

## Purpose

- Build strong problem-solving skills
- Track concepts, patterns, and implementations
- Keep notes organized for quick revision
- Practice consistently and improve step by step

---

## Boilerplate Template Structure

The `starting-boilerplate-template` branch provides a minimal C++ setup:

- `.vscode/tasks.json` is the config file for VSCode Build Task
- `test.cpp` is the scratch file for writing and running solutions
- `input.txt` is the stdin source used for local runs
- `output.txt` captures program output after a run

---

## Notes and Topic Structure

Maintain topic notes as separate markdown files, one topic per file (for example, `Arrays.md`, `Graphs.md`).
See [CONTRIBUTING.md](CONTRIBUTING.md) for the note format, standards, and examples.

---

## Setup Guide

### 1. Fork & Clone the Repository
First, fork the repository to your own GitHub account to track your personal progress.
Then, clone it to your local machine:
```bash
git clone https://github.com/YOUR_USERNAME/DSA_learning.git
cd DSA_learning
```

### 2. Switch to the Boilerplate Branch
Start your new topics from the pre-configured boilerplate template:
```bash
git checkout starting-boilerplate-template
```

### 3. MinGW Installation (Windows C++ Users)
To compile C++ on Windows, install MinGW using the MSYS2 GUI:
1. Download, run the `mingw-get-setup.exe` from [sourceforge.net](https://sourceforge.net/projects/mingw/) and install.
2. After installation, a dialog-box will appear. Choose the required packages (g++/gcc, objective-c, ...) by marking them for installation.
3. Click "File" (on menu bar) > "Apply Changes" > "Apply".
4. Add the MinGW `bin` directory to your Windows environment `PATH` variable.
5. Verify installation by running `g++ --version` in your terminal.

---

## How to Use This Repository

1. Pick one topic at a time
2. Write the core concept in your own words
3. Add examples and dry runs
4. Implement the algorithm
5. Analyze complexity
6. Revisit and refine your notes regularly

---

## Final Motivation

> *"Burn the midnight oil until your limits crumble into ash. Rip through the complexity, shatter your boundaries, and rebuild your mind into an absolute weapon. Leave nothing behind."*
