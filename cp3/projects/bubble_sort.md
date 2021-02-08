# Bubble Sort
Write a Bubble sort Python function that sorts the provided array from smallest to greatest.

## What is Bubble sort?
Bubble sort is a sorting algorithm that compares adjacent values and, if necessary, swaps them into their correct order.
* The highest number will "bubble" top the top each time it runs
* Bubble sort is an inefficient way of sorting data, but is useful for beginners who are learning about sorting algorithms
* See the [Wikipedia page](https://en.wikipedia.org/wiki/Bubble_sort) on Bubble sort for more information

![Bubble sort](../images/bubble_sort.gif)

<sub><sup>https://commons.wikimedia.org/wiki/File:Bubble-sort-example-300px.gif</sub></sup>

## Instructions
Write a Bubble sort function that:
* Sorts this [numbers.txt](./numbers.txt) file from smallest to greatest
* Prints out the total time it took to sort the numbers rounded to two decimal places (ex: 10.32 seconds)
* You will be [combining all your sorting functions](./sorting_algorithms.md) in one program later on, so save your code!

## Hints
* See [this page](https://www.geeksforgeeks.org/bubble-sort/) for a sample solution. **Do not copy/paste this solution.** Instead, use it as a reference as you write your own function.
* To track the time it takes to sort, use the `time` module. At the start of your code, create a `start` variable that is equal to `time.time()`. This will track the time your function started running.
* At the end of your code, create an `end` variable that is equal to `time.time()`. This will track the time your function finished running.
* To get the total amount of time, simply subtract `end` - `start`. **Remember to round this number to two decimal places!**
