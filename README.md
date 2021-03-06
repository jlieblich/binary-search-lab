---
title: Searching Lab
type: lab
duration: "1:25"
creator: James Davis (NYC)
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Searching Lab

## Introduction

> ***Note:*** _This lab should be completed in small groups of 2-3._

This lab will help you get more practice with searching.

## Exercise

### Whiteboard Practice

You are given 3 arrays to search. Write your solutions on a whiteboard, showing the steps for each search. Take photos of the answers. For example:

1, 2, 3, 4, 5, 6, 7, 8, 9, 10

To find the number 7 in the array above, the steps are:

```
1, 2, 3, 4, 5, 6, 7, 8, 9, 10 // midpoint 5 is < 7
               6, 7, 8, 9, 10 // midpoint 8 is > 7
               6, 7           // midpoint 6 < 7
                  7           // midpoint 7 == 7; done!
```

---

Search the following sorted arrays using **binary search**:

- 3, 5, 6, 8, 11, 12, 14, 15, 17, 18 || Find 16

- 1, 4, 6, 7, 12, 13, 15, 18, 19, 20, 22, 24 || Find 20

- -22, -9, 0, 0, 2, 7, 12, 12, 33, 34, 54, 54, 66, 80, 90, 94, 103 || Find 34


Draw a **binary search tree** with the following data:

- 3, 5, 6, 8, 11, 12, 14, 15, 17, 18

**Bonus:**

With the following set, show the steps of the binary search, **as well as the sorting beforehand**. Sort in any way you feel is best:

- 94, 103, 34, 54, 12, 54, 80, 90, 2 || Find 80

**Bonus #2**

In either pseudocode or Java, write the algorithm for binary search *recursively*. Save it in a file and submit it as a pull request.

#### Deliverable

Pictures of each of your solutions and the Java file if you complete the bonus.

---

## Licensing
1. All content is licensed under a CC­BY­NC­SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact [legal@ga.co](mailto:legal@ga.co).
