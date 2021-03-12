# Sorting
[![](https://github.com/joeybodoia/sorting/workflows/tests/badge.svg)](https://github.com/joeybodoia/sorting/actions?query=workflow%3Atests)
[![](https://github.com/joeybodoia/sorting/workflows/extra_credit/badge.svg)](https://github.com/joeybodoia/sorting/actions?query=workflow%3Atests)

You will implement the merge and quick sort algorithms.

**Learning Objectives:**

1. understand how merge sort and quicksort work
1. practice recursion
1. practice using property-based tests

**Real-world application:**
Given a dataset, the first step of processing is almost always to sort the data.
This allows efficient lookups via binary search,
but it even makes sequential search significantly faster due to an optimization in modern CPUs called "branch prediction".
(See [the most upvoted stackoverflow question of all time](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) for details.)

In the real world, you will never implement your own sorting algorithm,
and will always use a built-in library routine.
The divide-and-conquer strategy used in merge/quick sort turns out to be the most fundamental tool for building your own fast algorithms.
Next week (after spring break), we will explore this strategy for massively parallel data analysis of multi-terabyte twitter data.
If you take CS148 (graph algorithms), you will explore many more variations of the divide and conquer technique.

## Tasks

Complete the following tasks:

1. Fork the [sorting repo](https://github.com/mikeizbicki/sorting) and enable github actions
1. Update the `README.md` file so that the test case badges point to your repo.
1. Implement the `_merged`, `merge_sorted`, and `quick_sorted` functions so that all test cases in `tests/test_main.py` pass.
   You must implement `merge_sorted` and `quick_sorted` recursively.
1. (optionally)
   You can receive 1 point of extra credit for implementing the `quick_sort` function and passing the tests in `tests/test_ec.py`.

## Submission

Submit the link to your forked repository on sakai.

## Collaboration Policy

**You are not allowed to look at another student's github repo.**

All other forms of collaboration with other students are encouraged.
You may use any other online resources you like to complete this assignment.
