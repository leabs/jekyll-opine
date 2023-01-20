---
layout: post
title: "Code Block Example"
date: 2023-01-20 07:35:33 -0500
comments: true
---

Add the `number` property of `array1` and `array2` where the `id` matches and declare as `array3` in javascript.

```javascript
let array1 = [
  { id: 1, number: 3 },
  { id: 3, number: 4 },
  { id: 2, number: 4 },
];
let array2 = [
  { id: 1, number: 3 },
  { id: 2, number: 5 },
  { id: 3, number: 3 },
];
let array3 = [];

for (let i = 0; i < array2.length; i++) {
  for (let j = 0; j < array1.length; j++) {
    if (array2[i].id === array1[j].id) {
      array3.push({
        id: array2[i].id,
        number: array1[j].number + array2[i].number,
      });
    }
  }
}
console.log(array3);
```
