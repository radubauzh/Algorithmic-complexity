# Time Complexities of Algorithms

| Algorithm      | Best Time Ω | Worst Time O | Average Time Θ | Worst Space | Recc.               |
| -------------- | ----------- | ------------ | -------------- | ----------- | ------------------- |
| Linear Search  | O(1)        | O(n)         | O(n)           | O(1)        | T(n)=T(n-1) + B     |
| Binary Search  | O(1)        | O(logn)      | O(logn)        | O(1)        | T(n)=T(n/2)+1       |
| Bubble Sort    | O(n)        | O(n^2)       | O(n^2)         | O(1)        |          -          |
| Selection Sort | O(n^2)      | O(n^2)       | O(n^2)         | O(1)        | T(n)=T(n-1) -1      |
| Insertion Sort | O(n)        | O(n^2)       | O(n^2)         | O(1)        | T(n)=T(n−1)+n       |
| Merge Sort     | O(nlogn)    | O(nlogn)     | O(nlogn)       | O(n)        | T(n)=2T(n/2)+n      |
| Quick Sort     | O(nlogn)    | O(n^2)       | O(nlogn)       | O(n)        | T(n)=T(n-1)+O(n)    |
| Quick Lomuto   | O(nlogn)    |  O(n^2)      | O(nlogn)       | O(n)        | T(n)=T(n-1)+O(n)    |
| Quick Hoare    | O(nlogn)    |  O(n^2)      | O(nlogn)       | O(n)        | T(n)=T(n-1)+O(n)    |
| Build Heap     | O(n)        | O(n)         | O(n)           | O(n)        |          -          |
| Heap Sort      | O(nlogn)    | O(nlogn)     | O(nlogn)       | O(1)        | T(n)=O(n) + nO(lgn) |
| Heapify        |      -      |       -      |        -       | O(logn)     | T(n)=T(2n/3)+O(1)   |
| Radix Sort     | O(nk)       | O(nk)        | O(nk)          | O(n+k)      |          -          |
| Tim Sort       | O(n)        | O(nlogn)     | O(nlogn)       | O(1)        |          -          |

# Time Complexities of Data Structures

| Data Structure     | avg. Indexing | avg. Search | avg. Insertion | avg. Deletion | Worst: Indexing | Worst: Search | Worst: Insertion | Worst: Deletion | Worst: Space |
| ------------------ | ------------- | ----------- | -------------- | ------------- | --------------- | ------------- | ---------------- | --------------- | ------------ |
| array              | O(1)          | O(n)        | O(n)           | O(n)          | O(1)            | O(n)          | O(n)             | O(n)            | O(n)         |
| Dynamic Array      | O(1)          | O(n)        | O(n)           | O(n)          | O(1)            | O(n)          | O(n)             | O(n)            | O(n)         |
| Singly linked list | O(n)          | O(n)        | O(1)           | O(1)          | O(n)            | O(n)          | O(1)             | O(1)            | O(n)         |
| doubly linked list | O(n)          | O(n)        | O(1)           | O(1)          | O(n)            | O(n)          | O(1)             | O(1)            | O(n)         |
| Hash Table         | /             | O(1)        | O(1)           | O(1)          | /               | O(n)          | O(n)             | O(n)            | O(n)         |
| BST                | O(logn)       | O(logn)     | O(logn)        | O(logn)       | O(n)            | O(n)          | O(n)             | O(n)            | O(n)         |
| Stack              | O(n)          | O(n)        | O(1)           | O(1)          | O(n)            | O(n)          | O(1)             | O(1)            | O(n)         |
| Queue              | O(n)          | O(n)        | O(1)           | O(1)          | O(n)            | O(n)          | O(1)             | O(1)            | O(n)         |
| Cartesian Tree     | /             | O(logn)     | O(logn)        | O(logn)       | /               | O(n)          | O(n)             | O(n)            | O(n)         |
| RBT                | O(logn)       | O(logn)     | O(logn)        | O(logn)       | O(logn)         | O(logn)       | O(logn)          | O(logn)         | O(n)         |
| AVL Tree           | O(logn)       | O(logn)     | O(logn)        | O(logn)       | O(logn)         | O(logn)       | O(logn)          | O(logn)         | O(n)         |
| B-Tree             | O(logn)       | O(logn)     | O(logn)        | O(logn)       | O(logn)         | O(logn)       | O(logn)          | O(logn)         | O(n)         |
