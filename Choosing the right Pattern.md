🚧 This is a draft.

### Choosing the right patterns based on the type of question

The goal is to analyze the type of question we're dealing with and deduct (from the type of input/question) the pattern we could use. That way we only
consider the patterns that could fit our specific problem. Once we've analyzed one of main types of problems, we'll ask questions to narrow down our 
list of possibilities. For example: You are given an array problem. You know you're probably not gonna use a tree traversal approach, so only consider 
patterns appropriate to array-type problems. Ask yourself questions to further clarify the type of pattern you'll use. Example: Is the array sorted/rotated? 
Are we being asked to find the position of an element? or a subarray etc.... <br>
I was able to detect 8 types of questions (not including binary numbers' questions). <br>
They are:
  Array, String, Linked List, Matrix, Tree, Graph, Interval, Other/Misc.

So I came up with the following:
<table>
  <tr>
    <th>Type of question is:</th>
    <th></th>
  </tr>  
  <tr>
    <th>Array</th>
    <td>
    &#8226; Sorted: Use a variation of binary search or 2-pointers. <br>
    &#8226; Find the longest/shortest subarray or value : sliding window. <br>
    &#8226; Loop in an array: runner technique. <br>
    &#8226; Find the position of an element: runner technique. <br>
    &#8226; Find missing/duplicate/smallest number in sorted/rotated array: cyclic sort. <br>
    &#8226; Sorted array with numbers in a given range: cyclic sort.
    </td>
  </tr>
  <tr>
    <th>String</th>
    <td>
    &#8226; Find the longest/shortest substring or value: sliding window.<br>
    &#8226; Search among strings : Trie.<br>
    &#8226; Find a common substring among a set of strings: hashmap or trie.
    </td>
  </tr>
    <tr>
    <th>Linked List</th>
    <td>
    &#8226; Sorted : use a variation of binary search or 2-pointers(the latter only if it's doubly-linked). <br>
    &#8226; No extra space: runner technique. <br>
    &#8226; Find desired value: sliding window. <br>
    &#8226; Loop in a linked list: runner technique. <br>
      &#8226; Find the length of a list <b>or</b> the position of an element: runner technique.
    </td>
  </tr>
  <tr>
    <th>Matrix</th>
    <td>
    &#8226; Sorted : variation of binary search or 2-pointers.
    </td>
  </tr>
  <tr>
    <th>Tree</th>
    <td>
    &#8226; Traverse level-by-level: BFS. <br>
    &#8226; Traverse in-order/post-order/pre-order: DFS. <br>
    &#8226; Search for element where the node is close to a leaf: DFS. <br>
    &#8226; Binary Tree: two-heaps.
    </td>
  </tr>
    <tr>
    <th>Graph</th>
    <td>
    &#8226; BFS. <br>
    &#8226; DFS.
    </td>
  </tr>
  <tr>
    <th>Interval</th>
    <td></td>
  </tr>
  <tr>
    <th>Other/Misc.</th>
    <td>
    &#8226; Priority queue/scheduling: two-heaps. <br>
    &#8226; Find smallest/largest/median element of a set: two-heaps. <br>
    &#8226; Find combinations/permutations of a given set: subsets. <br>
    &#8226; Optimization (maximization/minimization) : Dynamic programming. <br>
    &#8226; Convert a recursive approach to an iterative one: use a stack. <br>
    &#8226; Try all permutations/Combinations of input: Recursive backtracking or iterative BFS. <br>
    &#8226; Top/Max/Min/Closest K elements among n elements: Heap.
    </td>
  </tr>
</table>
