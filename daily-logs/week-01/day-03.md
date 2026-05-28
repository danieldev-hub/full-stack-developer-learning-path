# Day 3: Trees (Binary, BST, AVL)

## 📚 Learning Objectives
- [ ] Understand tree structure
- [ ] Master Binary Trees
- [ ] Master Binary Search Trees
- [ ] Understand AVL trees (balanced)

## 🎥 Resources
- Abdul Bari - Trees Complete Tutorial
- GeeksforGeeks - Tree Data Structure
- LeetCode - Tree problems (Easy/Medium)

## 📖 Key Concepts

### Binary Trees
- Each node has max 2 children
- Tree traversals: Inorder, Preorder, Postorder, Level Order
- Height & Depth
- Balanced vs Unbalanced

### Binary Search Trees (BST)
- Left child < Parent < Right child
- Search: O(log n) average, O(n) worst
- Insert/Delete: O(log n) average
- In-order traversal gives sorted order

### AVL Trees
- Self-balancing BST
- Balance factor: |-1, 0, 1|
- Rotations: Left, Right, Left-Right, Right-Left
- All operations: O(log n)

## 🔨 Practice Activity

### Task 1: Implement Binary Tree (30 mins)
- Create Node class
- Insert values
- All 4 traversal methods

### Task 2: Implement BST (30 mins)
- Insert maintaining BST property
- Search method
- Delete method
- In-order traversal

### Task 3: LeetCode Problems (60 mins)
1. Binary Tree Level Order Traversal
2. Validate BST
3. Find Lowest Common Ancestor

## ✅ Quiz
1. BST property: **Left < Parent < Right**
2. Time for BST search: **O(log n) average**
3. Traversal that gives sorted order: **In-order**

## 📝 Commit
```bash
git commit -m "feat(day-3): trees, BST, and AVL implementation"
```

*Time Spent: ___ mins | Confidence: __/10*