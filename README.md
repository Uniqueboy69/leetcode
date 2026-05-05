# LeetCode Solutions 🚀

![LeetCode](https://img.shields.io/badge/LeetCode-Solutions-orange?logo=leetcode) 
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python) 
![Java](https://img.shields.io/badge/Java-11+-red?logo=java)
![C++](https://img.shields.io/badge/C++-17+-green?logo=cplusplus)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

A comprehensive collection of **LeetCode problem solutions** organized by programming language and difficulty level. This repository contains personal solutions, explanations, and optimal approaches for interview preparation and skill development.

---

## 📋 Table of Contents

- [About](#about)
- [Repository Structure](#repository-structure)
- [Quick Start](#quick-start)
- [Problem Statistics](#problem-statistics)
- [Supported Languages](#supported-languages)
- [How to Use This Repo](#how-to-use-this-repo)
- [Naming Convention](#naming-convention)
- [Solution Template](#solution-template)
- [Contributing](#contributing)
- [Resources](#resources)
- [Contact](#contact)

---

## 💡 About

This repository documents my journey solving **LeetCode problems** across multiple programming languages. Each solution includes:

✅ **Optimized Code** — Clean, efficient implementations  
✅ **Complexity Analysis** — Time and space complexity breakdown  
✅ **Multiple Approaches** — When applicable, alternative solutions  
✅ **Test Cases** — Edge cases and example test inputs  
✅ **Explanations** — Detailed comments and problem-solving approach  

Perfect for **interview preparation**, **coding practice**, and **algorithm learning**.

---

## 📁 Repository Structure

```
leetcode/
│
├── python/
│   ├── easy/
│   ├── medium/
│   └── hard/
│
├── java/
│   ├── easy/
│   ├── medium/
│   └── hard/
│
├── cpp/
│   ├── easy/
│   ├── medium/
│   └── hard/
│
├── javascript/
│   ├── easy/
│   ├── medium/
│   └── hard/
│
├── notes/
│   └── (Problem explanations & diagrams)
│
├── tests/
│   └── (Test harnesses & utilities)
│
└── README.md
```

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Uniqueboy69/leetcode.git
cd leetcode
```

### 2. Choose Your Language & Navigate
```bash
cd python/easy
# or
cd java/medium
# or
cd cpp/hard
```

### 3. Run a Solution
#### Python
```bash
python3 1-two-sum.py
```

#### Java
```bash
javac -d out 1-two-sum/Solution.java
java -cp out Solution
```

#### C++
```bash
g++ -std=c++17 -O2 -o solution 1-two-sum.cpp
./solution
```

#### JavaScript
```bash
node 1-two-sum.js
```

---

## 📊 Problem Statistics

| Difficulty | Count | Status |
|-----------|-------|--------|
| Easy      | TBD   | ⏳ In Progress |
| Medium    | TBD   | ⏳ In Progress |
| Hard      | TBD   | ⏳ In Progress |
| **Total** | **TBD** | |

---

## 🔧 Supported Languages

| Language | Version | Path |
|----------|---------|------|
| Python | 3.8+ | `./python/` |
| Java | 11+ | `./java/` |
| C++ | C++17 | `./cpp/` |
| JavaScript | ES6+ | `./javascript/` |

---

## 📖 How to Use This Repo

### For Learning
1. **Browse solutions by difficulty** (Easy → Medium → Hard)
2. **Read the problem explanation** in comments
3. **Study the approach** and complexity analysis
4. **Run test cases** to verify understanding

### For Interview Prep
1. **Filter by topic** (Hash Table, Trees, DP, etc.)
2. **Practice on LeetCode first** before checking solutions
3. **Review multiple approaches** if available
4. **Time yourself** on similar problems

### For Code Review
1. Check `notes/` for detailed problem writeups
2. Compare approaches across languages
3. Analyze trade-offs and optimizations

---

## 📝 Naming Convention

Files follow this pattern:

```
{PROBLEM_ID}-{problem-name-in-kebab-case}.{ext}
```

**Examples:**
- `1-two-sum.py`
- `2-add-two-numbers.java`
- `3-longest-substring.cpp`
- `15-three-sum.js`

**File Header Template:**
```python
"""
Problem: Two Sum
LeetCode: https://leetcode.com/problems/two-sum/
Difficulty: Easy
Time Complexity: O(n)
Space Complexity: O(n)

Approach: Hash map to store complement values
"""
```

---

## 💻 Solution Template

Use this template when adding new solutions:

### Python Template
```python
"""
Problem: [Problem Title]
LeetCode: https://leetcode.com/problems/[slug]/
Difficulty: [Easy/Medium/Hard]
Time Complexity: O(?)
Space Complexity: O(?)

Approach:
- [Explain your approach]
- [Key insight]
"""

class Solution:
    def solve(self, ...):
        # Solution code here
        pass

# Test cases
if __name__ == "__main__":
    sol = Solution()
    print(sol.solve(...))  # Expected: ...
```

### Java Template
```java
/**
 * Problem: [Problem Title]
 * LeetCode: https://leetcode.com/problems/[slug]/
 * Difficulty: [Easy/Medium/Hard]
 * Time Complexity: O(?)
 * Space Complexity: O(?)
 */

class Solution {
    public void solve(...) {
        // Solution code here
    }
}

// Test cases
class Main {
    public static void main(String[] args) {
        Solution sol = new Solution();
        // Test here
    }
}
```

---

## 🤝 Contributing

Contributions are **welcome**! Here's how:

### Adding New Solutions
1. **Fork** the repository
2. **Create a feature branch**: `git checkout -b add/problem-xyz`
3. **Follow naming conventions** and add complexity analysis
4. **Include test cases** in your solution
5. **Submit a PR** with a clear description

### Guidelines
- ✅ One solution per file
- ✅ Clear, readable code with comments
- ✅ Accurate complexity analysis
- ✅ Organized in correct difficulty folder
- ✅ Verify your solution passes on LeetCode

---

## 🎓 Resources

- **LeetCode**: https://leetcode.com
- **Blind 75**: Essential coding interview questions
- **NeetCode**: https://neetcode.io (Great explanations)
- **Algorithm Notes**: See `/notes/` directory for detailed writeups

### Topic-wise Practice
- Arrays & Hashing
- Two Pointers
- Sliding Window
- Stack & Queue
- Linked Lists
- Trees & Graphs
- Heaps
- Backtracking
- Dynamic Programming
- Greedy Algorithms

---

## 👨‍💻 Contact

- **GitHub**: [@Uniqueboy69](https://github.com/Uniqueboy69)
- **LeetCode**: [Your LeetCode Profile]

Feel free to reach out with questions, suggestions, or improvements!

---

## 📄 License

This repository is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## ⭐ Show Your Support

If this repo helps you prepare for interviews or learn algorithms, please **star it** ⭐ and **share** with others!

**Happy Coding!** 🎉
