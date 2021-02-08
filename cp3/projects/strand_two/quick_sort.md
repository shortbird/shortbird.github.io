# Quick Sort
Write an Quick sort Python function that sorts the provided array from smallest to greatest.

## What is Quick sort?
Quick sort is a *recursive* sorting algorithm that sorts data using a Binary Search Tree. Quick sort selects a 'pivot' in the data and recursively sorts the remaining data around the pivot. This is done recursively, resulting in very fast sorting that uses very little computer memory
* Quick sort is widely known as the most efficient, fast, and useful sorting algorithm available for use.
* See the [Wikipedia page](https://en.wikipedia.org/wiki/Quicksort) on Quick sort for more information

![Quick sort](../images/Quick_sort.gif)

<sub><sup>By Matt Chan (jacky&#039;s brother) - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=14961785</sub></sup>

## Instructions
Write a Quick sort function that:
* Sorts this [numbers.txt](./numbers.txt) file from smallest to greatest
* Prints out the total time it took to sort the numbers rounded to two decimal places (ex: 10.32 seconds)
* You will be [combining all your sorting functions](./sorting_algorithms.md) in one program later on, so save your code!

## Hints
* See [this page](https://www.geeksforgeeks.org/Quick-sort/) for a sample solution. **Do not copy/paste this solution.** Instead, use it as a reference as you write your own function.
* To track the time it takes to sort, use the `time` module. At the start of your code, create a `start` variable that is equal to `time.time()`. This will track the time your function started running.
* At the end of your code, create an `end` variable that is equal to `time.time()`. This will track the time your function finished running.
* To get the total amount of time, simply subtract `end` - `start`. **Remember to round this number to two decimal places!**
