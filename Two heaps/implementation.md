## Two Heaps

In many problems, we are given a set of elements such that we can divide them into two parts. To solve the problem, we are interested in knowing 
the smallest element in one part and the biggest element in the other part. This pattern is an efficient approach to solve such problems.
This pattern uses two heaps; A Min Heap to find the smallest element and a Max Heap to find the biggest element. The pattern works by storing 
the first half of numbers in a Max Heap, this is because you want to find the largest number in the first half. You then store the second half of 
numbers in a Min Heap, as you want to find the smallest number in the second half. At any time, the median of the current list of numbers can be 
calculated from the top element of the two heaps.

The two heaps pattern is commonly used to perform tasks such as:
<ul>
<li>Scheduling - find the earliest meeting at any given time, latest meeting at any given time. </li>
<li>Finding the median in a large collection.</li>
<li>Largest and smallest values in a set.</li>
<li>To implement a priority queue, etc.</li>
  </ul>
