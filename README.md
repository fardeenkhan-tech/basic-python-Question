# Python Interview Practice Questions

This repository contains Python programming questions and solutions that are commonly asked in fresher interviews, internships, coding rounds, and technical assessments.

## Topics Covered

### Pattern Printing
- Star Pattern
- Reverse Star Pattern
- Pyramid Pattern
- Number Pattern
- Square Pattern

### Number Problems
- Even or Odd Number
- Count Even and Odd Numbers
- Print Even Numbers (1–100)
- Prime Number Check
- Factorial
- Fibonacci Series

### String Problems
- Vowel or Consonant Check
- Count Vowels
- Count Vowels and Consonants
- Palindrome Check
- Reverse String
- Anagram Check

### Searching Algorithms
- Linear Search
- Binary Search

### Array Problems
- Largest Number
- Second Largest Number
- Frequency Count
- Remove Duplicates
- Missing Number

### Binary Tree Problems
- Create Binary Tree
- Count Total Nodes
- Tree Height
- Find Maximum Value
- Find Minimum Value
- Count Leaf Nodes

## Technologies Used

- Python 3
- Jupyter Notebook

## Repository Structure

```text
📂 Python-Interview-Practice
│
├── Pattern_Questions.ipynb
├── Basic_Coding_Questions.ipynb
├── Tree_Questions.ipynb
└── README.md
```

## Example

### Even or Odd Number

```python
num = 89

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")
```

### Count Vowels

```python
s = "Python Programming"

count = 0

for ch in s:
    if ch.lower() in "aeiou":
        count += 1

print(count)
```

### Count Nodes in Binary Tree

```python
def count_nodes(root):
    if root is None:
        return 0

    return 1 + count_nodes(root.left) + count_nodes(root.right)
```

## Who Can Use This Repository?

- Python Beginners
- Computer Science Students
- Data Science Students
- Machine Learning Freshers
- Software Engineering Interns
- Interview Preparation Candidates

## Learning Outcomes

After completing these questions, you will understand:

- Loops and Conditions
- Functions
- Recursion
- String Manipulation
- Arrays and Lists
- Searching Algorithms
- Binary Trees
- Problem Solving Techniques

## Author

**Fardeen Khan**

Aspiring Data Scientist & Machine Learning Engineer 
