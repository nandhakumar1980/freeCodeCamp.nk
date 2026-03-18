---
id: bd7123c9c441eddfaeb4bdef
title: Comment Your JavaScript Code
challengeType: 1
forumTopicId: 16783
dashedName: comment-your-javascript-code
---

# --description--

Comments are lines of code that JavaScript will intentionally ignore. Think of them like **sticky notes** attached to your code — they're reminders and explanations for you and anyone else reading your code later.

**Why use comments?**

Imagine coming back to code you wrote 6 months ago, or handing it to a teammate. Without comments, it can be very hard to understand *why* the code does what it does, even if how it works is clear. Comments solve that problem.

There are two ways to write comments in JavaScript:

**1. Single-line comment** — Using `//` tells JavaScript to ignore everything after it on that line:

```js
// This calculates the total price after tax
let total = price * 1.08;
```

Use single-line comments for short, quick notes next to a specific line.

**2. Multi-line comment** — Using `/*` to start and `*/` to end lets you write longer explanations across several lines:

```js
/*
  This function checks if a user is logged in.
  It returns true if they are, false if not.
  Written by: Alex, March 2024
*/
```

Use multi-line comments for more detailed explanations, such as describing what a whole function does.

**NOTE:** As you write code, you should regularly add comments to clarify the function of parts of your code. Good commenting can help communicate the intent of your code—both for others *and* for your future self.

# --instructions--

Try creating one of each type of comment.

# --hints--

You should create a `//` style comment that contains at least five letters.

```js
assert(code.match(/(\/\/)...../g));
```

You should create a `/* */` style comment that contains at least five letters.

```js
assert(code.match(/(\/\*)([^\/]{5,})(?=\*\/)/gm));
```

# --seed--

## --seed-contents--

```js

```

# --solutions--

```js
// Fake Comment
/* Another Comment */
```
