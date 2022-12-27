# Multithreading-in-Merge-Sort-Python-Implementation
<br>
In this example, the merge_sort function is recursive, and it uses the threading module to create two separate threads to sort the left and right halves of the input list concurrently. The join method is used to wait for both threads to finish before merging the sorted halves together.
Note that the overhead of creating and managing multiple threads may make the multithreaded version of the merge sort algorithm slower for small lists or on systems with a small number of CPU cores. It is generally more effective to use multithreading for algorithms that have a high degree of parallelism, such as those that operate on large data sets or have long running times.
