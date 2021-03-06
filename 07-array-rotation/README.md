# Array Rotation

Given an array, and a number of rotations, "rotate" the array to change the location of the elements the appropraite number of times.

For futher detail, a left rotation operation on an array shifts each of the array's elements 1 unit to the left. For example, if 2 left rotations are performed on array `[1, 2, 3, 4, 5]`, then the array would become `[3, 4, 5, 1, 2]`.

Example Input:
```javascript
rotate_left([1, 2, 3, 4, 5], 4)
=> [5, 1, 2, 3, 4]
rotate_left([1, 2, 3, 4, 5], 6)
=> [2, 3, 4, 5, 1]
```

Notes:
If the rotation number is greater than the length of the array, rotation should continue as shown in the second example above.

## Source
[HackerRank](https://www.hackerrank.com/challenges/ctci-array-left-rotation/problem?h_l=interview&playlist_slugs%5B%5D=interview-preparation-kit&playlist_slugs%5B%5D=arrays)