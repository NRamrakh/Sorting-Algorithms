# Analysis of Sorting Algorithms

## Problem Statement:
**Perform the complexity analysis of different sorting algorithms and answer the following questions based  on your analysis:**
1) Which sorting algorithm works best if the input array is already sorted and if the dataset is small?
2) Which sorting algorithm works best for large number of inputs?
3) Which sorting algorithm works best for the random inputs(not sorted) ?
4) In which case, Heap Sort is better than Merge sort?

This Repository contains complexity analysis of following algorithms based on the number of inputs.
a) Insertion Sort (Using an array)
b) Merge Sort(Using an array)
c) Vector based Heap Sort(Using a vector and array)
d) In-place Quick Sort(Using an array)
e) Modified Quick Sort(Using an array)
Time taken for each algorithm is computed by the function timeit.default_timer(). Also, each algorithm is given random input, sorted input and reverse sorted input to test the complexity of each algorithm.

**Answers to the above questions:**

1) Insertion sort works best if the input array is already sorted and if the dataset is small. Best case complexity of Insertion sort is O(n). However, if the array is reverse sorted, the complexity of Insertion sort becomes O(n2) because of the number of swaps between elements. Also, for random input array, complexity for Insertion sort is O(n2).
2) Merge Sort works best for large number of inputs. Complexity of merge sort is same for all the cases because it is independent of distribution of the data. However, Merge sort is not an in-place algorithm as it requires extra space to merge the sorted subarrays.
3) Quicksort works best for the random input. For a sorted/reverse sorted input array, the complexity of Quicksort becomes O(n2). Quicksort is faster than merge sort because there is no extra juggling as in mergesort.
4) Heap Sort also has the same complexity for all the cases. Heap Sort is suitable for input size less than 1M. Heap Sort and Merge sort are comparatively faster algorithms. However, Merge sort is the most suitable algorithm for huge datasets(>1M).

![image](https://user-images.githubusercontent.com/70915043/137656852-13a121d0-46bf-43c6-a5a5-1e62bf8772aa.png)

## Comparison Plots

![image](https://user-images.githubusercontent.com/70915043/137657914-9ed316c6-027b-4187-97b5-132f3459f26b.png)
![image](https://user-images.githubusercontent.com/70915043/137657932-15f97152-486a-4679-b0b3-c4425aa2b252.png)
![image](https://user-images.githubusercontent.com/70915043/137657953-d989bde6-5ecd-42c3-b7c3-038eb6c3b6d2.png)
![image](https://user-images.githubusercontent.com/70915043/137657976-a4b76dc9-f548-4c26-abd6-575ee8f287fc.png)
![image](https://user-images.githubusercontent.com/70915043/137658002-9a2b0c0a-2f75-443a-ab04-7fbb6b7aa7dc.png)
![image](https://user-images.githubusercontent.com/70915043/137658040-99929782-bef2-444c-8c76-dda5498359a6.png)
![image](https://user-images.githubusercontent.com/70915043/137658063-9976cc28-841c-4044-ba47-8ffc11facbc5.png)
![image](https://user-images.githubusercontent.com/70915043/137658083-1262bfc5-d005-4bf3-93aa-fd9c6f3ca2a4.png)

 **This repository contains the jupyter file of Python code and the instruction file to run the code.**


