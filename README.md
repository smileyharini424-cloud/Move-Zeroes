# Move Zeroes

## Explanation

The Move Zeroes problem requires moving all zero values to the end of an array while maintaining the relative order of the non-zero elements.

For example:

```text
Input:
[0, 1, 0, 3, 12]

Output:
[1, 3, 12, 0, 0]
```

## Problem Statement

Given an integer array `nums`, move all `0`s to the end of the array while maintaining the relative order of the non-zero elements.

The operation should be performed in-place.

## Features

* Moves all zeroes to the end
* Maintains the order of non-zero elements
* Uses an in-place approach
* Does not create another array
* Efficient solution

## How It Works

The program uses an `index` variable to keep track of the position where the next non-zero element should be placed.

First, the program traverses the array and moves every non-zero value toward the beginning.

After all non-zero values are placed, the remaining positions are filled with zeroes.

## Technologies Used

* Arrays
* Loops
* Conditional statements
* Methods
* In-place array manipulation

## Data Structure Used

The program uses an integer array.

No additional array is required.

## Methods Used

### moveZeroes()

Moves all zero values to the end of the given array.

### main()

Creates the sample input, calls `moveZeroes()`, and displays the result.

## Program Flow

```text
Start
↓
Read array
↓
Set index to 0
↓
Traverse array
↓
Is current element non-zero?
↓
Yes → Place element at index
↓
Increase index
↓
Continue traversal
↓
Fill remaining positions with zeroes
↓
Display array
↓
End
```

## Sample Input

```text
nums = [0, 1, 0, 3, 12]
```

## Sample Output

```text
Result: 1 3 12 0 0
```

## Time Complexity

```text
O(n)
```

The array is traversed a constant number of times.

## Space Complexity

```text
O(1)
```

The program uses only a few variables and does not create another array.

## Key Learning

This problem teaches how to modify an array in-place while maintaining the order of its non-zero elements.

## File Location

```text
Arrays/MoveZeroes.java
```

## Repository Structure

```text
Move-Zeroes/
├── README.md
└── Arrays/
    └── MoveZeroes.java
```

## Author

**V.Harini**
