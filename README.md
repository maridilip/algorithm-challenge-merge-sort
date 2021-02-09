# algorithm-challenge-merge-sort
khan academy merge sort implementation

Implement merge sort
The mergeSort function should recursively sort the subarray array[p..r] i.e. after calling mergeSort(array,p,r) the elements from index p to index r of array should be sorted in ascending order.

To remind you of the merge sort algorithm:
-If the subarray has size 0 or 1, then it's already sorted, and so nothing needs to be done.
-Otherwise, merge sort uses divide-and-conquer to sort the subarray.

Use merge(array, p, q, r) to merge sorted sub arrays array[p..q] and array[q+1..r].

Once implemented, uncomment the Program.assertEqual() at the bottom to verify that the test assertion passes.
