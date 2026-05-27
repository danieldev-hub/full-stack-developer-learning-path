# Day 1: Data Structures Introduction - Arrays & Linked Lists

## 📚 Learning Objectives
- [ ] Understand what a data structure is
- [ ] Master array data structure and operations
- [ ] Understand linked list concepts and structure
- [ ] Compare time and space complexity of arrays vs linked lists

## 🎥 Resources to Study
- **Video:** Abdul Bari - Arrays (10 mins) - https://www.youtube.com/watch?v=tZq6RWh19K4
- **Video:** Traversy Media - JavaScript Arrays (15 mins)
- **Reading:** GeeksforGeeks - Array Data Structure
- **Interactive:** LeetCode - Array problems (Easy)

## 📖 Key Concepts to Understand

### Arrays
- Contiguous memory allocation
- Fixed size (in some languages)
- Direct access via index: O(1)
- Insertion/Deletion at end: O(1)
- Insertion/Deletion at beginning: O(n)

### Linked Lists
- Non-contiguous memory allocation
- Dynamic size
- Access via traversal: O(n)
- Insertion/Deletion at beginning: O(1)
- Insertion/Deletion at position: O(n)

## 🔨 Practice Activity

### Task 1: Implement Array Operations (30 mins)
```javascript
class CustomArray {
  constructor() {
    this.data = [];
  }
  
  // Implement these methods:
  // push(value)
  // pop()
  // shift()
  // unshift(value)
  // insert(index, value)
  // delete(index)
  // search(value)
}
```

### Task 2: Implement Linked List (45 mins)
```javascript
class Node {
  constructor(value) {
    this.value = value;
    this.next = null;
  }
}

class LinkedList {
  constructor() {
    this.head = null;
  }
  
  // Implement these methods:
  // insert(value)
  // delete(value)
  // search(value)
  // traverse()
  // reverse()
}
```

### Task 3: Solve LeetCode Problems (45 mins)
1. LeetCode #1 - Two Sum
2. LeetCode #88 - Merge Sorted Array
3. LeetCode #206 - Reverse Linked List

## ✅ Self-Assessment Quiz

1. **What is the time complexity of accessing an array element by index?**
   - A) O(1) ✓
   - B) O(n)
   - C) O(log n)
   - D) O(n²)

2. **What is the time complexity of inserting at the beginning of a linked list?**
   - A) O(1) ✓
   - B) O(n)
   - C) O(log n)

3. **Which data structure is better for frequent insertions at the beginning?**
   - A) Array
   - B) Linked List ✓

4. **What is the space complexity of both array and linked list?**
   - Answer: O(n)

## 📝 Coding Challenges

- [ ] Create your own Array class with 6+ methods
- [ ] Create your own Linked List class with 5+ methods
- [ ] Test both with custom test cases
- [ ] Compare performance manually

## 🎯 Commit Your Work

```bash
git add .
git commit -m "feat(day-1): implement arrays and linked lists"
git push origin main
```

## 📊 Progress Check
- [ ] Watched all videos
- [ ] Understood array concepts
- [ ] Understood linked list concepts
- [ ] Completed both implementations
- [ ] Solved 3 LeetCode problems
- [ ] Committed code to Git

## 📌 Notes & Observations
Write your own notes here about what you learned and what was confusing:

---

## 🔗 Related Topics for Tomorrow
- Stacks & Queues (built on top of arrays/linked lists)
- Big O Notation (to measure complexity better)

---

*Time Spent: _____ mins | Confidence Level: ___/10 | Questions for Next Review: _____*