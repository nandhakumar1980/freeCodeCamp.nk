---
id: bd7123c9c441eddfaeb5bdef
title: Understanding Boolean Values
challengeType: 1
forumTopicId: 301176
dashedName: understanding-boolean-values
---

# --description--

Another data type is the <dfn>Boolean</dfn>. Booleans may only be one of two values: `true` or `false`.

**Real-world analogy:** Think of a Boolean like a **light switch** — it's either ON (`true`) or OFF (`false`). There's no in-between.

These two states are mutually exclusive, meaning a value can't be both `true` and `false` at the same time.

**Where you'll use Booleans:**

Booleans show up constantly in real applications. For example:
- Is the user logged in? → `true` or `false`
- Has the form been submitted? → `true` or `false`
- Is the shopping cart empty? → `true` or `false`

```js
let isLoggedIn = true;
let isCartEmpty = false;
```

**Common mistake to avoid:**

**Note:** Boolean values are never written with quotes. The strings `"true"` and `"false"` are not Boolean and have no special meaning in JavaScript.

```js
let correct = true;      // ✅ This is a Boolean
let wrong = "true";      // ❌ This is just a string — not a Boolean!
```

# --instructions--

Modify the `welcomeToBooleans` function so that it returns `true` instead of `false`.

# --hints--

The `welcomeToBooleans()` function should return a Boolean (`true` or `false`) value.

```js
assert(typeof welcomeToBooleans() === 'boolean');
```

`welcomeToBooleans()` should return `true`.

```js
assert(welcomeToBooleans() === true);
```

# --seed--

## --after-user-code--

```js
welcomeToBooleans();
```

## --seed-contents--

```js
function welcomeToBooleans() {
  // Only change code below this line

  return false; // Change this line

  // Only change code above this line
}
```

# --solutions--

```js
function welcomeToBooleans() {
  return true; // Change this line
}
```
