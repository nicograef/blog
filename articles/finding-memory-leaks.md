# Finding Memory Leaks in Web Apps and NodeJS Apps

Finding memory leaks is hard. Writing code that causes memory leaks is not. A bad combination, right?

**Here's what we will cover:**

1. Garbage Collection in JavaScript
2. What are Memory Leaks?
3. Are we leaking? - How to identifying a Memory Leak
4. Where is the leak? - Finding the Memory Leak
5. Fixing the Memory Leak
6. My Learnings and Tips

## 1. Garbace Collection in JavaScript

## 2. What are Memory Leaks?

## 3. Are we leaking? - How to identifying a Memory Leak

## 4. Where is the leak? - Finding the Memory Leak

## 5. Fixing the Memory Leak

## 6. My Learnings and Tips

- Use Allocation Timeline Profile
  - focus on single szenario
  - Ignore first page visit (or other interaction)
- Strip down page or build up from scratch to isolate parts
- Look for retainers/references other than VueComponent
- There might be multiple leaks in one place that cover each other
- Futures should be canceled; Observables should be unsubscribed
  - Check the cleanup function
