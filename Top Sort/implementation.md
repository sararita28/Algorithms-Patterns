## Top sort (a.k.a topological sort)

Topological Sort is used to find a linear ordering of elements that have dependencies on each other. For example, if event ‘B’ is dependent on event ‘A’, 
‘A’ comes before ‘B’ in topological ordering. <br>
This pattern defines an easy way to understand the technique for performing topological sorting of a set of elements.<br>

The pattern works like this:<br>
<ol>
<li> Initialization <br>
a) Store the graph in adjacency lists by using a HashMap <br>
b) To find all sources, use a HashMap to keep the count of in-degrees. Build the graph and find in-degrees of all vertices
  </li>
  <li> Build the graph from the input and populate the in-degrees HashMap.
  </li> 
<li> Find all sources <br>
a) All vertices with ‘0’ in-degrees will be sources and are stored in a Queue.
  </li>
<li> Sort <br>
a) For each source, do the following things: <br>
—i) Add it to the sorted list. <br>
— ii)Get all of its children from the graph. <br>
— iii)Decrement the in-degree of each child by 1. <br>
— iv)If a child’s in-degree becomes ‘0’, add it to the sources Queue. <br>
b) Repeat (a), until the source Queue is empty.
  </ol>
  
  <img src="https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fphotos%2FG9YRlqC9joZNTWsi1ul7tRkO6tv1-ve1473wvg&w=1920&q=75" />
  
#### How to identify the Topological Sort pattern:
&#8226; The problem will deal with graphs that have no directed cycles <br>
&#8226; If you’re asked to update all objects in a sorted order <br>
&#8226; If you have a class of objects that follow a particular order

#### Problems featuring the Topological Sort pattern:
&#8226; Task scheduling (medium)
&#8226; Minimum height of a tree (hard)
