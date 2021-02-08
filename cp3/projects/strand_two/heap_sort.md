# Heap Sort
Write an Heap sort Python function that sorts the provided array from smallest to greatest.

## What is Heap sort?
Heap sort is a *recursive* sorting algorithm that sorts data using a Binary Search Tree. Heap sort takes the input data and builds a binary search tree by placing the largest element at the top.
* Rather than thinking iteratively like we have with all the other sorting algorithms, heap sort creates *heaps* of data that you can visualize like a Binary Search Tree.
* Heap sort is an efficient sorting algorithm that works much faster than Bubble, Selection, and Insertion sorts
* See the [Wikipedia page](https://en.wikipedia.org/wiki/heapsort) on Heap sort for more information

![Heap sort](../images/Heap_sort.gif)

<sub><sup>By Swfung8 - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=14957305</sub></sup>
d
## Instructions
Write a Heap sort function that:
* Sorts this [numbers.txt](./numbers.txt) file from smallest to greatest
* Prints out the total time it took to sort the numbers rounded to two decimal places (ex: 10.32 seconds)
* You will be [combining all your sorting functions](./sorting_algorithms.md) in one program later on, so save your code!

## Hints
* See [this page](https://www.geeksforgeeks.org/Heap-sort/) for a sample solution. **Do not copy/paste this solution.** Instead, use it as a reference as you write your own function.
* To track the time it takes to sort, use the `time` module. At the start of your code, create a `start` variable that is equal to `time.time()`. This will track the time your function started running.
* At the end of your code, create an `end` variable that is equal to `time.time()`. This will track the time your function finished running.
* To get the total amount of time, simply subtract `end` - `start`. **Remember to round this number to two decimal places!**
