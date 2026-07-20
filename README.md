# 🐍 Python Core Fundamentals Reference & Cheat Sheet

A comprehensive, all-in-one Python reference manual featuring topic-by-topic breakdowns, fully runnable code snippets, and expected console outputs derived from the *CodeWithHarry* Python course series.

---

## 📌 Table of Contents
1. [Print Statements & Output Formatting](#1-print-statements--output-formatting)
2. [Comments & Docstrings](#2-comments--docstrings)
3. [Variables & Primitive Data Types](#3-variables--primitive-data-types)
4. [Built-in Data Collections (Lists, Tuples, Dicts)](#4-built-in-data-collections-lists-tuples-dicts)
5. [Arithmetic Operators](#5-arithmetic-operators)
6. [Explicit & Implicit Typecasting](#6-explicit--implicit-typecasting)
7. [User Input Handling](#7-user-input-handling)
8. [Strings, Multiline Strings & Indexing](#8-strings-multiline-strings--indexing)
9. [String Slicing & Negative Slicing](#9-string-slicing--negative-slicing)
10. [Built-in String Methods](#10-built-in-string-methods)
11. [Conditional Logic (If / Elif / Else)](#11-conditional-logic-if--elif--else)
12. [Working with Time (`time` Module)](#12-working-with-time-time-module)
13. [Pattern Matching (`match-case`)](#13-pattern-matching-match-case)
14. [For Loops & `range()`](#14-for-loops--range)
15. [While Loops & `while-else`](#15-while-loops--while-else)
16. [Loop Control Statements (`break` & `continue`)](#16-loop-control-statements-break--continue)
17. [Functions & Function Arguments](#17-functions--function-arguments)
18. [List Operations, Slicing & Comprehension](#18-list-operations-slicing--comprehension)
19. [List Methods](#19-list-methods)
20. [Tuples Overview](#20-tuples-overview)

---

## 1. Print Statements & Output Formatting

The `print()` function outputs data to standard output. It supports control arguments such as `sep` (separator) and `end` (ending sequence).

```python
from types import MappingProxyType

# Basic Print Statements
print('hello world')
print('hello world')
print("hello, vaishali!")
print("welcome to python with codewithherry")

# Escape Sequences (\n, \')
print("hey i am a good boy\nand this viewer is also a good boy/girl")
print('hey i am a \'good boy\' and this viewer is also a good boy/girl')

# Custom Separator (sep) and Ending (end)
print("hey", 6, 7, sep="~")
print("vaishali")
print("hey", 6, 7, sep="~", end="009")
print("vaishali")
print("hey", 6, 7, sep="~", end="009\n")
print("vaishali")
