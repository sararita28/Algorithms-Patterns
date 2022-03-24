## Top K elements

Any problem that asks us to find the top/smallest/frequent ‘K’ elements among a given set falls under this pattern.
<b>The best data structure to keep track of ‘K’ elements is Heap.</b> This pattern will make use of the Heap to solve multiple problems dealing with ‘K’ 
elements at a time from a set of given elements. The pattern looks like this: <br> 
&#8226; Insert ‘K’ elements into the min-heap or max-heap based on the problem. <br>
&#8226; Iterate through the remaining numbers and if you find one that is larger than what you have in the heap, then remove that number and insert 
the larger one.<br>
There is no need for a sorting algorithm because the heap will keep track of the elements for you.

<img src="https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fimages%2FG9YRlqC9joZNTWsi1ul7tRkO6tv1-uuow3wb1.jpg&w=1920&q=75" />
