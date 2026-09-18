# C-Program
# 🚀 100-Day C Programming Mastery

A comprehensive, project-based roadmap to master C programming in 100 days. Complete with structured lessons, mini-projects, and capstone applications.

## 📊 Repository Structure

```
C-Learning-100Days/
│
├── README.md (this file)
├── ROADMAP.md (complete learning path)
├── PROGRESS.md (tracking template)
├── RESOURCES.md (learning materials)
│
├── Level-1-Foundations/ (Days 1-15)
│   ├── README.md
│   ├── Day-01-Variables-IO/
│   ├── Day-02-Operators/
│   ├── Day-03-to-07-Conditionals-Loops/
│   ├── Day-08-to-14-ControlFlow/
│   ├── Day-15-Functions/
│   └── Project-PersonalInfoSystem/
│
├── Level-2-Intermediate/ (Days 16-40)
│   ├── README.md
│   ├── Day-16-to-18-Arrays/
│   ├── Day-19-to-21-2D-Arrays-Strings/
│   ├── Day-22-to-24-Strings-Advanced/
│   ├── Day-25-to-30-Sorting-Searching/
│   ├── Day-31-to-40-Pointers-Structs/
│   └── Project-InventoryManager/
│
├── Level-3-Advanced/ (Days 41-70)
│   ├── README.md
│   ├── Day-41-to-45-LinkedLists/
│   ├── Day-46-to-50-Stack-Queue/
│   ├── Day-51-to-55-Recursion/
│   ├── Day-56-to-65-FileIO-Memory/
│   ├── Day-66-to-70-Advanced-Concepts/
│   └── Project-BankingSystem/
│
├── Level-4-Expert/ (Days 71-100)
│   ├── README.md
│   ├── Day-71-to-75-BinaryTrees/
│   ├── Day-76-to-80-BinarySearchTrees/
│   ├── Day-81-to-85-Graphs-Part1/
│   ├── Day-86-to-90-Graphs-Part2/
│   ├── Day-91-to-95-Hashing-Advanced/
│   ├── Day-96-to-100-Algorithms/
│   └── Project-HospitalManagement/
│
└── Level-5-Industry/
    ├── README.md
    ├── Advanced-DSA/
    ├── Systems-Programming/
    ├── Network-Programming/
    └── Competitive-Programming/
```

## 🎯 What You'll Learn

### Level 1: Foundations (Days 1-15) ⭐
- Variables, Data Types & I/O
- Operators & Expressions
- Conditionals (if/else/switch)
- Loops (for, while, do-while)
- Pattern Programming
- Functions & Scope

**Project:** Personal Information Management System

### Level 2: Intermediate (Days 16-40) ⭐⭐
- 1D & 2D Arrays
- Strings & Text Processing
- Pointers & Memory
- Structures & Typedef
- Sorting Algorithms (Bubble, Selection, Insertion)
- Searching (Linear, Binary)

**Project:** Inventory Management System

### Level 3: Advanced (Days 41-70) ⭐⭐⭐
- Linked Lists
- Stacks & Queues
- Recursion & Backtracking
- File I/O & Data Persistence
- Dynamic Memory Management
- Advanced Pointer Concepts

**Project:** Banking System with Transactions

### Level 4: Expert (Days 71-100) ⭐⭐⭐⭐
- Binary Trees & Traversals
- Binary Search Trees
- Graphs (DFS, BFS, Dijkstra)
- Hashing & Hash Tables
- Advanced Sorting (Merge, Quick Sort)
- Algorithm Optimization

**Project:** Hospital Management System

### Level 5: Industry-Ready (Days 101+) ⭐⭐⭐⭐⭐
- Advanced Data Structures
- Concurrency & Threads
- Systems Programming
- Network Programming
- Embedded C Basics

## 📋 Daily Structure

Each day follows this pattern (60-110 minutes):

```
🌅 MORNING (15-20 min)
├── Review previous concept
├── Read topic notes
└── Understand key ideas

💻 CODING SESSION (30-50 min)
├── Write solution
├── Test with cases
├── Debug issues
└── Optimize code

📚 PROJECT WORK (30-40 min) [Days 51+]
├── Implement feature
├── Write functions
└── Test integration

🌙 EVENING (15-20 min)
├── Document learning
├── Commit to GitHub
└── Plan next day
```

## 🚀 Quick Start

### Prerequisites
- **Compiler:** GCC or Clang
- **Editor:** VS Code, Sublime, or CLion
- **Version Control:** Git
- **Terminal:** Bash or similar

### Setup on Linux/Mac
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/C-Learning-100Days.git
cd C-Learning-100Days

# Navigate to Day 1
cd Level-1-Foundations/Day-01-Variables-IO

# Compile
gcc -o solution solution.c

# Run
./solution
```

### Setup on Windows
```bash
# Using MinGW or TDM-GCC
gcc -o solution.exe solution.c
solution.exe
```

## 📂 Each Day Folder Contains

```
Day-XX-Topic/
├── README.md          # Concept explanation
├── theory.txt         # Key learnings
├── problem.md         # Problem statement
├── solution.c         # Main solution
├── solution_v2.c      # Optimized version
├── test_cases.txt     # Input/output examples
└── notes.txt          # Personal notes
```

## 🏗️ Project Structure

Each project contains:

```
Project-Name/
├── src/               # Source files
│   ├── main.c
│   ├── functions.c
│   └── utils.c
├── include/           # Header files
│   ├── functions.h
│   └── constants.h
├── data/              # Data files
│   ├── sample.txt
│   └── config.dat
├── Makefile           # Build automation
├── README.md          # Project documentation
└── FEATURES.md        # Feature list & specs
```

## 📊 Progress Tracking

Track your progress in `PROGRESS.md`:

```markdown
## Week 1: Variables & I/O (Days 1-7)
- [x] Day 1: Variables & Data Types
- [x] Day 2: Constants & sizeof
- [x] Day 3: Arithmetic Operators
- [ ] Day 4: Comparison Operators
- [ ] Day 5: Logical Operators
- [ ] Day 6: Assignment Operators
- [ ] Day 7: Operator Precedence

Problems Solved: 12/50
Time Spent: 5h 30m
Notes: Struggling with format specifiers
```

## 🎓 Learning Resources

See `RESOURCES.md` for:
- 📚 Recommended Books
- 🎥 Video Tutorials
- 🌐 Online Platforms
- 🛠️ Development Tools
- 💡 Problem Solving Sites

## 📝 Typical Day Workflow

### Example: Day 1 - Variables & I/O

```bash
# 1. Navigate to day folder
cd Level-1-Foundations/Day-01-Variables-IO

# 2. Read theory
cat README.md
cat theory.txt

# 3. Code solution
vim solution.c
# or use your editor
code solution.c

# 4. Compile
gcc -Wall -o solution solution.c

# 5. Test
./solution
# Input test cases from test_cases.txt

# 6. Commit
git add .
git commit -m "Day 1: Variables & I/O - Personal Info Card"
git push

# 7. Document
echo "Learned: scanf, printf, data types" >> notes.txt
```

## 🔍 Code Quality Standards

All code should follow:

```c
// 1. Include guards in headers
#ifndef FILENAME_H
#define FILENAME_H
// content
#endif

// 2. Meaningful variable names
int student_age;  // good
int sa;           // bad

// 3. Comments for logic
// Calculate BMI using formula: weight(kg) / height²(m)
float bmi = weight / (height * height);

// 4. Function documentation
/**
 * Calculates the factorial of a number
 * @param n: non-negative integer
 * @return: factorial of n
 */
int factorial(int n) { }

// 5. Error handling
if (ptr == NULL) {
    printf("Memory allocation failed\n");
    return -1;
}
```

## 🐛 Debugging Tips

### Using GCC Flags
```bash
# Compile with debug info
gcc -g -o solution solution.c

# Add all warnings
gcc -Wall -Wextra -o solution solution.c

# Memory checking
gcc -g -o solution solution.c
valgrind ./solution
```

### Using GDB Debugger
```bash
gdb ./solution
(gdb) break main
(gdb) run
(gdb) print variable_name
(gdb) next
(gdb) step
```

## 💾 GitHub Workflow

### Daily Commit Template
```bash
# Format: Day N: Topic - Description
git commit -m "Day 1: Variables & I/O - Personal Info Card"
git commit -m "Day 5: Loops - Pyramid Patterns"
git commit -m "Project: Banking System - Transaction Management"
```

### Commit Frequency
- **Per day:** One main commit after solving
- **Per project:** One commit per feature
- **Weekly:** Push to origin main

## 🏆 Milestones

```
✅ Week 1-2:   Foundation concepts clear (40 problems)
✅ Week 3-4:   Comfortable with arrays & functions (80 problems)
✅ Week 5-8:   First project complete (Inventory Manager)
✅ Week 9-12:  Advanced concepts mastered (150 problems)
✅ Week 13-14: Capstone project (Banking System)
✅ Week 15-16: Expert level completed (Hospital Management)
```

## 📈 Expected Progress

| Level | Duration | Problems | Projects | Status |
|-------|----------|----------|----------|--------|
| Level 1 | 2 weeks | 50+ | 1 | ⭐ Beginner |
| Level 2 | 4 weeks | 100+ | 3 | ⭐⭐ Intermediate |
| Level 3 | 4 weeks | 150+ | 2 | ⭐⭐⭐ Advanced |
| Level 4 | 4 weeks | 200+ | 1 | ⭐⭐⭐⭐ Expert |
| Level 5 | Ongoing | 250+ | 2+ | ⭐⭐⭐⭐⭐ Industry |

## 🤝 Contributing

Have better solutions? Found bugs? Want to add problems?

1. Fork the repository
2. Create feature branch: `git checkout -b improve/day-01`
3. Commit changes: `git commit -m "Improve: Day 1 solution"`
4. Push to branch: `git push origin improve/day-01`
5. Open Pull Request

## 📞 Support & Discussions

- **Issues:** Report bugs and problems
- **Discussions:** Ask questions and share tips
- **Wiki:** Collaborative learning notes

## 📄 License

This project is licensed under MIT License - see LICENSE file for details.

## 🌟 Show Your Support

- ⭐ Star this repository
- 🍴 Fork to customize for yourself
- 📢 Share with friends learning C
- 💬 Discuss solutions and approaches

## 📅 Timeline

```
Start Date: [Your Start Date]
Day 1: [Date]
Day 50: [Date] - Halfway point 🎉
Day 100: [Date] - Mastery achieved! 🏆
```

## ✨ Final Goal

By Day 100, you will have:
- ✅ Solved 200+ coding problems
- ✅ Built 5+ real-world projects
- ✅ Mastered core data structures
- ✅ Understood algorithms & optimization
- ✅ Created a professional portfolio
- ✅ Ready for interviews & industry

---

**Let's begin the journey! Start with Day 1 and commit daily. See you at Day 100! 🚀**

*Last Updated: 2026*
