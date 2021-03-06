# DSA
Data Structures and Algorithms
The following have been implemented so far:

##Data Structures
1. Arrays
		An array is a linear collection of elements.
		Array elements can be accessed via indices.
		Array index is usually integer value used to compute offsets.
		The first element in an array has the index of 0.

2. Lists
		A list is an ordered sequence of data.

		Each data item stored in a list is called an element.
		A list with no elements is an *empty* list.

		The number of elements stored in a list is called the length of the list.

		We can *append* an element to the end of a list, or we can insert an element into a list after an existing element or at the beginning of a list.

		Elements are deleted from a list using a remove operation.
		We can also clear a list so that all of its current elements are removed.

		The elements of a list are displayed using either a toString() operation.
		getElement() operation displays the value of the current element.

		We can move from one element of a list to the next element using the next() operation, and we can move backward through a list using the prev() operation.

		We can also move to a numbered position in a list using the moveTo(n) operation, where n specifies the position to move to.
		The currentPosition property indicates the current position in a list.

3. Linked Lists
		A linked list is a collection of objects called *nodes*.

		Each node is linked to a successor node in the list using an object reference.
		The reference to another node is called a *link*.

		To insert a new node, the link of the node before the inserted node is changed to point to the new node, and the new node's link is set to the node the previous node was pointing to.

		To remove an item from a linked list, the link of the node before the removed node is redirected to point to the node the removed node is pointing to, while also pointing the removed node to null.

4. Stacks
		A stack is a list of elements that are accessible only from one end of the list, which is called the *top*.

		The stack is known as a *last-in, first-out (LIFO)* data structure.
		To build a stack, we will use an array in our implementation.

5. Queues
		The two primary operations involving queues are inserting a new element into a queue and removing an element from a queue.

		The insertion operation is called *enqueue*, and the removal operation is called *dequeue*.

		The enqueue operation inserts a new element at the *end* of a queue, and the dequeue operation removes an element from the front of a *queue*.

6. Simple Trees
		A *tree* is a nonlinear data structure that is used to store data in a hierarchical manner.

		Tree data structures are used to store hierarchical data, such as the files in a file system.

		A tree is made up of a set of *nodes* connected by *edges*.

		Special types of trees, called *binary trees*, restrict the number of child nodes to no more than two.

		A tree can be broken down into *levels*.

		The *root* node is at level 0, its children are at level 1, those nodes' children are at level 2, and so on.


7. Graphs and Graphs Algorithms
		A *graph* consists of a set of vertices and a set of *edges*.
		Edges are defined as a pair (v1, v2), where v1 and v2 are two vertices in a graph. A vertex can also have a weight, which is sometimes called a cost.
		A graph whose pairs are ordered is called a directed graph, or just a *digraph*. When pairs are ordered in a directed graph, an arrow is drawn from one pair to another pair.
		Directed graphs indicate the flow direction from vertex to vertex.

8. Heaps

##Algorithms
9. Bubble Sort Algorithm
		The elements during the bubble sorting is like bubbles in the water floating up to the surface.

		When sorting a set of numbers into ascending order, larger values float to the right of the array and lower values float to the left.

		The algorithm moves through the array many times, compares adjacent values, and swaps them if the value to the left is greater than the value to the right.

10. Selection Sort Algorithm
		The sorting algorithm works by starting at the beginning of the array and comparing the first element with the remaining elements.
		After examining all the elements, the smallest element is placed in the first position, and the algorithm moves to the second position.
		This process continues until the algorithm arrives at the next to last position in the array.
		Nested loops are used in the selection sort algorithm.
		The outer loop moves from the first element in the array to the next to last element; the inner loop moves from the second array element to the last element.

11. Insertion Sort Algorithm
		- The insertion sort has two loops. The outer loop moves element by element through
		the array, while the inner loop compares the element chosen in the outer loop to the
		element next to it in the array.
		- If the element selected by the outer loop is less than the
		element selected by the inner loop, array elements are shifted over to the right to make
		room for the inner-loop element

12. Shell Sort Algorithm
		- Shellsort works by defining a gap sequence that indicates how far apart compared elements
		are when starting the sorting process.
		- The gap sequence can be defined dynamically, but for most practical applications, you can predefine the gap sequence the algorithm will use.
		- There are several published gap sequences that produce different results.

13. Merge Sort Algorithm
		- The Mergesort algorithm is so named because it works by merging sorted sublists together
		to form a larger, completely sorted list.
		- In theory, this algorithm should be easy
		to implement. We need two sorted subarrays and a third array into which we merge the
		two subarrays by comparing data elements and inserting the smallest element value.
		- In practice, however, Mergesort has some problems because if we are trying to sort a very
		large data set using the algorithm, the amount of space we need to store the two merged
		subarrays can be quite large.
		- Since space is not such an issue in these days of inexpensive
		memory, it is worth implementing Mergesort to see how it compares in efficiency to
		other sorting algorithms.

14. Quick Sort Algorithm
		- The Quicksort algorithm is one of the fastest sorting algorithms for large data sets.
		- Quicksort is a divide-and-conquer algorithm that recursively breaks a list of data into
		successively smaller sublists consisting of the smaller elements and the larger elements.
		- The algorithm continues this process until all the data in the list is sorted.
		- The algorithm divides the list into sublists by selecting one element of the list as a pivot.
		- Data is sorted around the pivot by moving elements less than the pivot to the bottom
		of the list and elements that are greater than the pivot to the top of the list.

Other Algorithms
  - Dijkstra's Algorithm - Find shortest path between any two points on a graph.
	-
