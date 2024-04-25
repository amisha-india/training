# Problem in programming-
    Its like puzzle to solve.
## Step to solve problem:
    1.Define
    2.Analyze
    3.Design
    4.Outcomes
    5.Decide
    6.Implement(coding)
    7.Follow up(testing, deployment, feedback, etc)
![image](/solve%20prblm%20step.png)

## Programming skills required:
    1.Analytical ability
    2.Analysis
    3.Design
    4.Technical knowledge
    5.Programming ability
    6.Testing
    7.Quality planning(peer to peer review then team lead review)
    8.Innovation(keep on)
    9.Team working(Important equally with knowledge)
    10.Communication(ability to communicat freely and clearly)

## Performance measure(Hike increase):
    1.Timeliness
    2.Quality of work(code should be adaptable)
    3.Customer orientation
    4.Optimal solution(work it then better it)
    5.Team satisfaction

## Problem classification(Types):
### 1.Concurret-
    Task can be performed parallely.
  * Single thread-  One user
  * Multiple thread- Multiple user
#### Example -
![image](/concurreEg.png)
### 2. Sequential-
    Task performed step by step in order.
#### Example -
![image](/seqEg.png)
### 3. Distribution-
    It use the distributed systems.
#### Example- Cloud,git,torent,etc.
### 4. Event based-
    It work based on event.
#### Example-ClicK on like is event and reel is action.

## Problem solving method-
### 1.Heuristic approach/ Brute force technique-
    It is fundamental method which work on trial and error way.(Try all possible solution one by one)
   #### Example-for opening pattern lock it go for all possible key
- Slowest / Costing
- Starting point
- Time taking
### 2.Greedy approach-
    It can solve any type of optimition problem like minimum or maximum approach types.

#### Example- To find shortest distance between start and     destination(In each step it will go with the shortest distance )
### 3.Divide and conquer-
    In this first it divide in sub problem then solve it and most important is to find technique to sub divide.

#### Example- Quick sort
### 4.Dynamic programming-(Divide and conquer plus table)
    It work similar as divide and conquer but additionally it contain table to store the value of subproblem for future reference and to avoid repetation.
    Storing the value in table is known as chaching the result.

## Modeling tools:
* Flow chart
* Data flow diagram(cloud)
* Entity relationship diagram(Database)
* Unitied modeling language(python)

# Algorithm-
Sequence of ***unambiguous*** (no confusion) instuction for solving a problem i.e. for obtaining a required output for any legitimate input in ***finite amount of time***.
### Properties of Algorithm:
* Input
* Output
* Clear instruction
* finitness
* Language independent(Psuedo code - write the description  of program in normal language)
* Workable
### Different pattern:
* sequencial
* selection
* loop
#### Example-
    Sequencial:
    BEGIN:
    step01-read name
    step02-display name
    END

    Selection:
    BEGIN:
    step01-read name , makes
    step02-sum
    step03-avg
    step04-compare less or more
    step05-display pass or fail
    END

    Loop:
    BEGIN:
    step01:Initialize no_of_students
    step02:Initialize counter=1
    step03:while counter<=no_of_student
        step3.1:get input for eng marks
        step3.2:get input for maths marks
        step3.3:get input for sci marks
        step3.4:cal avg=(eng+math+sci)/3
        step3.5:if avg<65 then print fail
        step3.6:else print passed
        step3.7:increment counter

# Data structure:
* Increase performance
* Alogorithm applied on structured data
* It focus on data representation and manipulation
* Understanding data structure is fundamental to computer programming
>Types of data structure

* Linear / static(fixed size)
* Non linear / dynamic(not fixed size)
  
![image](/ds%20type.png)
## Linear data structure
>Array

Arrays are linear data structures where elements are stored sequentially in contiguous memory locations.
Elements are accessed using an index, and they have a fixed size.
#### Examples: One-dimensional arrays, multi-dimensional arrays.
>Linked list 

It store data in non-continuous memory.It is dynamic structure and fast.

>Stack(first in last out) 

Attribute of stack -
* maxTop(The maxmimum size of stack)
* top(The index of the top element)

operation of stack -
* isEmpty-True/False[Top=0]
* isfull-True/False[top=maxTop]
* top-return the element at the top
* push-add an element to the top of stack
* pop-delete the element from the top of the stack
* display stack-print all the data in the stack

>Queue(Last in first out)

Attribute of stack-
* front/rear-index[front=0,rear=last]
* counter-current size
* max size-capacity

Operation in Queue -
* Enqueue-The insertion end is called rear
* Dequeue-The deletion end is called front
* IsEmpty-true/false[front==rear]
* IsFull-true/false[rear==maxsize]
* display Queue-print all
## Non-Linear Data Structures:

1. Trees:
Trees are non-linear data structures consisting of nodes connected hierarchically.
Each node can have zero or more child nodes, forming a tree-like structure.

**Examples:** Binary trees, AVL trees, B-trees, Trie.

2. Graphs:
Graphs are non-linear data structures consisting of nodes (vertices) connected by edges.
Nodes can have multiple connections, and edges can be directed or undirected.

**Examples:** Directed graph, undirected graph, weighted graph.

3. Sets:
Sets are non-linear data structures that store unique elements without any particular order.
They ensure that no duplicate elements are stored, making them suitable for various mathematical and computational operations.

**Examples:** Hash sets, tree sets, bit sets.

## Searching method-
> Searching Algorithms:

- ***Linear Search:***

    It goes step by step and also slow campare to other.
**Example:** Searching for a specific number in an unsorted list of numbers.

- ***Binary Search:***
        Binary search is a divide-and-conquer algorithm that requires the list to be sorted.
        It repeatedly divides the search interval in half until the target element is found or the search interval is empty.
**Example:** Searching for a specific number in a sorted list of numbers.

## Sorting Algorithms-
![image](/sorting.png)

- ***Bubble Sort:***
    Bubble sort compares adjacent elements and swaps them if they are in the wrong order.
    It repeatedly passes through the list until the list is sorted.Higher element upfront.
**Example:** Sorting an array of numbers in ascending order.

``` Given list [77, 42, 35, 12, 100, 5] in increasing order:
Step 1:
Compare adjacent elements and swap if necessary:
[42, 77, 35, 12, 100, 5]
[42, 35, 77, 12, 100, 5]
[42, 35, 12, 77, 100, 5]
[42, 35, 12, 77, 100, 5]
[42, 35, 12, 77, 5, 100]
Step 2:
Compare adjacent elements and swap if necessary:
[35, 42, 12, 77, 5, 100]
[35, 12, 42, 77, 5, 100]
[35, 12, 42, 5, 77, 100]
[35, 12, 42, 5, 77, 100]
Step 3:
Compare adjacent elements and swap if necessary:
[12, 35, 42, 5, 77, 100]
[12, 35, 5, 42, 77, 100]
[12, 35, 5, 42, 77, 100]
Step 4:
Compare adjacent elements and swap if necessary:
[12, 5, 35, 42, 77, 100]
[12, 5, 35, 42, 77, 100]
Step 5:
Compare adjacent elements and swap if necessary:
[5, 12, 35, 42, 77, 100]
Now, the list is sorted in increasing order: [5, 12, 35, 42, 77, 100].
```

- ***Selection Sort:***
Selection sort divides the input list into two parts: sorted and unsorted.
It repeatedly selects the smallest (or largest) element from the unsorted part and moves it to the sorted part.
**Example:** Sorting an array of numbers in ascending order.
```
given list [75, 28, 65, 30, 20].
Selection Sort works by repeatedly finding the minimum element from the unsorted part of the list and swapping it with the first unsorted element. Here's how it works step by step:
Step 1:
Find the minimum element in the entire list and swap it with the first element.
The minimum element is 20, so swap it with 75.
The list becomes [20, 28, 65, 30, 75].
Step 2:
Find the minimum element in the sublist starting from the second element and swap it with the second element.
The minimum element is 28, so leave it as it is.
The list remains [20, 28, 65, 30, 75].
Step 3:
Find the minimum element in the sublist starting from the third element and swap it with the third element.
The minimum element is 30, so swap it with 65.
The list becomes [20, 28, 30, 65, 75].
Step 4:
Find the minimum element in the sublist starting from the fourth element and swap it with the fourth element.
The minimum element is 65, so leave it as it is.
The list remains [20, 28, 30, 65, 75].
Step 5:
There is only one element left, so no action is needed.
Now, the list [75, 28, 65, 30, 20] is sorted using the Selection Sort algorithm. The sorted list is [20, 28, 30, 65, 75].
```
- ***Insertion Sort:***
Insertion sort builds the final sorted list one element at a time by repeatedly taking the next element and inserting it into the proper position in the already sorted part.
**Example:** Sorting an array of numbers in ascending order.
```
given list [12, 10, 36, 6, 24].
Step 1:
Start with the second element (10).
Compare it with the element to its left (12).
Since 10 is smaller than 12, swap them.
The list becomes [10, 12, 36, 6, 24].
Step 2:
Start with the third element (36).
Compare it with the elements to its left (12 and 10).
Since 36 is larger than both 12 and 10, leave it as it is.
The list remains [10, 12, 36, 6, 24].
Step 3:
Start with the fourth element (6).
Compare it with the elements to its left (36, 12, and 10).
Since 6 is smaller than 36, shift 36 to the right.
Continue comparing with 12 and 10 and shift them to the right accordingly.
Insert 6 into its correct position.
The list becomes [6, 10, 12, 36, 24].
Step 4:
Start with the fifth element (24).
Compare it with the elements to its left (36 and 12).
Since 24 is smaller than 36, shift 36 to the right.
Insert 24 into its correct position.
The list becomes [6, 10, 12, 24, 36].
Now, the list [12, 10, 36, 6, 24] is sorted using the Insertion Sort algorithm. The sorted list is [6, 10, 12, 24, 36].
```
- ***Merge Sort:***
Merge sort is a divide-and-conquer algorithm that divides the input list into smaller sublists, sorts them, and then merges them back together.
It is a stable sorting algorithm and guarantees O(n log n) time complexity.

**Example:** Sorting an array of numbers in ascending order.
```
Divide:
Split the list [75, 28, 65, 30, 20] into two halves: [75, 28] and [65, 30, 20].
Recursively sort:
Apply Merge Sort to each half:
For [75, 28]: Split into [75] and [28], no further split needed.
For [65, 30, 20]: Split into [65] and [30, 20], then split [30, 20] into [30] and [20].
Now, merge the sorted sublists: [20, 30].
Merge:
Merge the sorted sublists [75] and [28] back together: [28, 75].
Merge the sorted sublists [65] and [20, 30] back together: [20, 30, 65].
Now, merge the two sorted halves [28, 75] and [20, 30, 65]: [20, 28, 30, 65, 75].
```
- ***Quick Sort:***
Quick sort is a divide-and-conquer algorithm that selects a pivot element and partitions the input list into two sublists: elements smaller than the pivot and elements larger than the pivot.
It then recursively sorts the two sublists.

**Example:** Sorting an array of numbers in ascending order.
```
Quick Sort algorithm on the list [2, 1, 3, 5, 4] with the pivot element set to 3.
Partitioning Step:
Start with the list [2, 1, 3, 5, 4].
Choose the pivot element 3.
Partition the list around the pivot:
Elements less than 3 (1, 2) on the left side.
Pivot element 3 in the middle.
Elements greater than 3 (4, 5) on the right side.
The partitioned list becomes [2, 1, 3, 5, 4] (left sublist) | 3 (pivot) | [5, 4] (right sublist).
Recursive Sorting:
Apply Quick Sort recursively to the left and right sublists.
Left sublist [2, 1]:
Choose the pivot element 2.
Partition the sublist around the pivot:
Elements less than 2 (1) on the left side.
Pivot element 2 in the middle.
Elements greater than 2 (empty) on the right side.
The partitioned sublist becomes [1] (left sublist) | 2 (pivot) | [] (right sublist).
Since both left and right sublists are sorted, no further action is needed.Right sublist [5, 4]:
Choose the pivot element 5.
Partition the sublist around the pivot:
Elements less than 5 (4) on the left side.
Pivot element 5 in the middle.
Elements greater than 5 (empty) on the right side.
The partitioned sublist becomes [4] (left sublist) | 5 (pivot) | [] (right sublist).
Since both left and right sublists are sorted, no further action is needed.
Result:
Combine the sorted sublists [1, 2, 3, 4, 5].
So, the sorted list using Quick Sort with the pivot element set to 3 is [1, 2, 3, 4, 5].



