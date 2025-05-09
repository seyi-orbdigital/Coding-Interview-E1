# Coding-Interview-E1


# 🧪 JavaScript Coding Challenge: Unique Words Counter

## Overview

This is a simple JavaScript coding challenge designed to assess your ability to work with strings, arrays, and basic logic. Your task is to implement a function that counts the number of **unique words** in a given string of text.

---

## 📝 Task

Write a JavaScript function named `countUniqueWords` that takes a string as input and returns an object of 2 keys, 
 - an array of each unique words `words`.
 - the number of unique words in it called `wordCount`.

### 🔧 Function Signature

```javascript
function countUniqueWords(text) {
  // Your implementation here
}
```

# ✅ Requirements
  - The comparison must be case-insensitive.

  - All punctuation should be ignored (e.g., commas, periods, exclamation marks, etc.).

  - Only plain JavaScript is allowed (no external libraries like Lodash or jQuery).

## Example

```javascript
countUniqueWords("Hello, hello! How are you?"); 
// Output: 
/*
{
  words: ["hello", "how", "are", "you"],
  wordCount: 4,
}
*/

countUniqueWords("One fish, two fish. Red fish, blue fish."); // Output: 5
// Unique words: "one", "fish", "two", "red", "blue"
// Output: 
/*
{
  words: ["one", "fish", "two", "red", "blue"],
  wordCount: 5,
}
*/

```
