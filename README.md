# Experiment 26: Median

## Problem Statement

The median of a list of numbers is essentially its middle element after sorting.
Given a list of numbers with an **odd** number of elements, find the median.

## Input Format

* The first line contains an integer $n$ (size of the array).
* The second line contains $n$ space-separated integers.

## Output Format

In a new line, print the median of the array.

### Example 1

**Input:**

```text
7
0 1 2 4 6 5 3
```

**Output:**

```text
3
```

**Explanation:**
1.  Sort the array: `[0, 1, 2, 3, 4, 5, 6]`
2.  The middle element is at index `n/2` (integer division).
3.  For $n=7$, index is 3. The value is `3`.
