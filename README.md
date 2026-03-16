Merge Sort in C

Description

This project implements the Merge Sort algorithm using the C programming language.

Merge Sort is a divide and conquer algorithm used to sort elements efficiently.
It divides the array into smaller parts, sorts them recursively, and then merges them together.

---

Algorithm Explanation

Divide Step

The array is divided into two halves until each subarray contains only one element.

Example:

Array:
8 3 5 2

Divide:

8 3 5 2
8 3 | 5 2
8 | 3 | 5 | 2

---

Combine Step

After dividing, the algorithm merges the elements while sorting them.

Combine:

8 | 3 | 5 | 2
3 8 | 2 5
2 3 5 8

---

Files

- merge_sort.c → Implementation of Merge Sort using C.

---

Compilation

To compile the program:

gcc merge_sort.c -o merge_sort

---

Run the program

./merge_sort

---

Example

Input:

12 11 13 5 6 7

Output:

5 6 7 11 12 13

---

Merge Sort Visualization

Example of how Merge Sort works:

        8 3 5 2
       /       \
    8 3         5 2
   /   \       /   \
  8     3     5     2
   \   /       \   /
    3 8         2 5
        \     /
         2 3 5 8

The algorithm recursively divides the array and then merges the sorted subarrays.

---

Time Complexity

Case| Complexity
Best Case| O(n log n)
Average Case| O(n log n)
Worst Case| O(n log n)

---

Author

Mohamed Khoualdia

---

Language Used

C programming language.
