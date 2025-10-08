# Strings

## Overview
String manipulation and pattern matching are common interview topics. Strings are immutable in many languages, which affects solution approaches.

## Key Concepts
- String traversal and character manipulation
- Palindromes
- Anagrams and permutations
- Pattern matching
- String building and concatenation
- Character frequency counting

## Common Problems

### Easy
- [ ] Valid Palindrome
- [ ] Valid Anagram
- [ ] Implement strStr() / Find Needle in Haystack
- [ ] Longest Common Prefix
- [ ] Reverse String
- [ ] First Unique Character in a String

### Medium
- [ ] Longest Substring Without Repeating Characters
- [ ] Longest Palindromic Substring
- [ ] Group Anagrams
- [ ] Decode String
- [ ] String to Integer (atoi)
- [ ] Zigzag Conversion

### Hard
- [ ] Minimum Window Substring
- [ ] Valid Number
- [ ] Regular Expression Matching
- [ ] Wildcard Matching

## Time & Space Complexity Patterns
- Linear scan: O(n) time
- Two pointer: O(n) time, O(1) space
- Sliding window: O(n) time, O(k) space (k = window size)
- Hash map for frequency: O(n) time, O(k) space (k = alphabet size)

## Tips
- Use hash maps for character frequency counting
- Sliding window technique for substring problems
- Consider two-pointer approach for palindrome problems
- Be aware of string immutability in your programming language
- ASCII vs Unicode considerations
