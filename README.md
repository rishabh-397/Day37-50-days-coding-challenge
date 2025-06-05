# Day37-50-days-coding-challenge
Zigzag Level Order Traversal & First Palindromic String

📅 Challenge: #50DaysOfCoding  
🏷️ Tag: #DrGViswanathanchallenge  
📍 Day: 37/50

---------------------------------------------------

🔹 Problem 1: Zigzag Level Order Traversal of Binary Tree

🧩 Problem Statement:
Given the root of a binary tree, return the zigzag level order traversal of its nodes' values.  
That means:  
- First level: left to right  
- Second level: right to left  
- Third level: left to right  
... and so on.

✅ Example 1:
Input: root = [3,9,20,null,null,15,7]  
Output: [[3],[20,9],[15,7]]

✅ Example 2:
Input: root = [1]  
Output: [[1]]

✅ Example 3:
Input: root = []  
Output: []

🔍 Constraints:
- Number of nodes: [0, 2000]
- Node values: [-100, 100]

🧠 Approach:
- Perform a level-order (BFS) traversal using a queue.
- Use a boolean flag (`left_to_right`) to reverse the node order for alternating levels.
- Append the list to the result after reversing if needed.

---------------------------------------------------

🔹 Problem 2: First Palindromic String in an Array

🧩 Problem Statement:
Given an array of strings `words`, return the first palindromic string.  
A string is palindromic if it reads the same forwards and backwards.

✅ Example 1:
Input: words = ["abc","car","ada","racecar","cool"]  
Output: "ada"

✅ Example 2:
Input: words = ["notapalindrome","racecar"]  
Output: "racecar"

✅ Example 3:
Input: words = ["def","ghi"]  
Output: ""

🔍 Constraints:
- 1 <= words.length <= 100
- 1 <= words[i].length <= 100
- All words contain lowercase English letters only.

🧠 Approach:
- Traverse each word.
- Check if it’s equal to its reverse.
- Return the first match.

---------------------------------------------------

✨ Summary & Learning:

✔ Learned how to implement zigzag traversal using queue and control logic. 
✔ Strengthened both tree traversal and string processing skills.
