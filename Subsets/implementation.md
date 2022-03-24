## Subsets

A huge number of coding interview problems involve dealing with Permutations and Combinations of a given set of elements. The pattern Subsets 
describes an efficient Breadth First Search (BFS) approach to handle all these problems.

The pattern looks like this:
<ul>
  <li>Given a set of [1, 5, 3]</li>
  <li>Start with an empty set: [[]]</li>
  <li>Add the first number (1) to all the existing subsets to create new subsets: [[], [1]]</li>
  <li>Add the second number (5) to all the existing subsets: [[], [1], [5], [1,5]]</li>
  <li>Add the third number (3) to all the existing subsets: [[], [1], [5], [1,5], [3], [1,3], [5,3], [1,5,3]] </li>
</ul>

  Here is a visual representation of the Subsets pattern:
  <img src="https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fimages%2FG9YRlqC9joZNTWsi1ul7tRkO6tv1-hemg3w8d.jpg&w=1920&q=75" />
