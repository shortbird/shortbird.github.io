# Selection Sort
Write an Selection sort Python function that sorts the provided array from smallest to greatest.

## What is Selection sort?
Selection sort is a sorting algorithm that builds a sorted list by selecting the smallest element from the unsorted list and moving it to the beginning.
* The smallest number in the unsorted array is *selected* by the algorithm and moved to the front of the unsorted list
* Selection sort is slightly more efficient than Insertion sort, but still not widely useful compared to other options.
* See the [Wikipedia page](https://en.wikipedia.org/wiki/Selection_sort) on Selection sort for more information

![Selection sort](../images/selection_sort.gif)
<sub><sup>https://stackabuse.com/selection-sort-in-javascript/</sub></sup>

## Instructions
Write a Selection sort function that:
* Sorts this [numbers.txt](./numbers.txt) file from smallest to greatest
* Prints out the total time it took to sort the numbers rounded to two decimal places (ex: 10.32 seconds)
* You will be [combining all your sorting functions](./sorting_algorithms.md) in one program later on, so save your code!

## Hints
* See [this page](https://www.geeksforgeeks.org/selection-sort/) for a sample solution. **Do not copy/paste this solution.** Instead, use it as a reference as you write your own function.
* To track the time it takes to sort, use the `time` module. At the start of your code, create a `start` variable that is equal to `time.time()`. This will track the time your function started running.
* At the end of your code, create an `end` variable that is equal to `time.time()`. This will track the time your function finished running.
* To get the total amount of time, simply subtract `end` - `start`. **Remember to round this number to two decimal places!**
