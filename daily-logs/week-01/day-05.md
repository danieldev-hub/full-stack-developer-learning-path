# Day 5: Big O Notation & Complexity Analysis

## 📚 Learning Objectives
- [ ] Master Big O Notation
- [ ] Understand Time Complexity
- [ ] Understand Space Complexity
- [ ] Analyze algorithm complexity

## 🎥 Resources
- Big O Notation Explained (Video)
- GeeksforGeeks - Big O Analysis
- Complexity Analysis Guide

## 📖 Key Concepts

### Big O Notation (Worst Case)
- O(1) - Constant
- O(log n) - Logarithmic
- O(n) - Linear
- O(n log n) - Linearithmic
- O(n²) - Quadratic
- O(n³) - Cubic
- O(2ⁿ) - Exponential
- O(n!) - Factorial

### Rules for Analysis
1. Drop constants: O(2n) → O(n)
2. Drop lower order terms: O(n² + n) → O(n²)
3. Count loop iterations
4. Multiply nested loops
5. Watch for early termination

## 🔨 Practice Activity

### Task 1: Analyze Algorithms (45 mins)
For each, determine Big O:
- Simple loop: O(n)
- Nested loops: O(n²)
- Binary search: O(log n)
- Merge sort: O(n log n)
- Bubble sort: O(n²)

### Task 2: Code Analysis (45 mins)
Analyze 10 code snippets
Write complexity analysis for each
Compare with expected results

### Task 3: Practice Problems (30 mins)
1. Determine complexity of given algorithm
2. Optimize algorithm to reduce complexity
3. Compare two algorithms

## ✅ Quiz
1. Big O for single loop: **O(n)**
2. Big O for nested loops: **O(n²)**
3. Big O for binary search: **O(log n)**
4. Best for time complexity: **O(1)**
5. Drop constants rule: **O(2n) = O(n)**

## 📝 Commit
```bash
git commit -m "feat(day-5): Big O notation and complexity analysis"
```

*Time Spent: ___ mins | Confidence: __/10*