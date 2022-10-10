# Sorting-Algorithms-in-Python

## In this repository I will explain some of the popular sorting algorithms.

1. Bubble Sort
2. Selection Sort
3. Insertion Sort
4. Merge Sort
5. Quicksort

# 1. Bubble sort is a sorting algorithm that compares two adjacent elements and swaps them until they are in the intended order.

Just like the movement of air bubbles in the water that rise up to the surface, each element of the array move to the end in each iteration. Therefore, it is called a bubble sort.

Working of Bubble Sort
Suppose we are trying to sort the elements in ascending order.

# (Compare and Swap)

1. Starting from the first index, compare the first and the second elements.
2. If the first element is greater than the second element, they are swapped.
3. Now, compare the second and the third elements. Swap them if they are not in order.
4. The above process goes on until the last element


# 2. Selection Sort
Selection sort is a sorting algorithm that selects the smallest element from an unsorted list in each iteration and places that element at the beginning of the unsorted list.

1. Set the first element as minimum.
2. Compare minimum with the second element. If the second element is smaller than minimum, assign the second element as minimum. Compare minimum with the third element. Again, if the third element is smaller, then assign minimum to the third element otherwise do nothing. The process goes on until the last element.
3. After each iteration, minimum is placed in the front of the unsorted list.
4. For each iteration, indexing starts from the first unsorted element. Step 1 to 3 are repeated until all the elements are placed at their correct positions.

# 3. Insertion Sort
