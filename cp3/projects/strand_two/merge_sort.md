# Merge Sort
Write an Merge sort Python function that sorts the provided array from smallest to greatest.

## What is Merge sort?
Merge sort is a *recursive* sorting algorithm that builds a sorted list by dividing the unsorted list into individual units, then merging each unit together.
* The smallest number in the unsorted array is *selected* by the algorithm and moved to the front of the unsorted list
* Merge sort is an efficient sorting algorithm that works much faster than Bubble, Selection, and Insertion sorts
* See the [Wikipedia page](https://en.wikipedia.org/wiki/Merge_sort) on Merge sort for more information

![Merge sort](../images/Merge_sort.gif)

<sub><sup>By Swfung8 - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=14961648</sub></sup>

## Instructions
Write a Merge sort function that:
* Sorts this [numbers.txt](./numbers.txt) file from smallest to greatest
* Prints out the total time it took to sort the numbers rounded to two decimal places (ex: 10.32 seconds)
* You will be [combining all your sorting functions](./sorting_algorithms.md) in one program later on, so save your code!

## Hints
* See [this page](https://www.geeksforgeeks.org/Merge-sort/) for a sample solution. **Do not copy/paste this solution.** Instead, use it as a reference as you write your own function.
* To track the time it takes to sort, use the `time` module. At the start of your code, create a `start` variable that is equal to `time.time()`. This will track the time your function started running.
* At the end of your code, create an `end` variable that is equal to `time.time()`. This will track the time your function finished running.
* To get the total amount of time, simply subtract `end` - `start`. **Remember to round this number to two decimal places!**
