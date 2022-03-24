# Algorithms-Patterns

🚧 This repo is under construction. It's meant for note-taking purposes only (for now). Later, when it's more organized, feel free to use it as you see fit, but please do your own due diligence.
This repo will cover some of the patterns one can use when solving data structures and algorithms questions. The language used in this repo (if any) is <b>Javascript</b>.

<table>
  <tr>
    <th>Type of problem</th>    
    <th>Potential pattern</th>
  </tr>
  <tr>
    <td>If the given input is sorted (array, list, or matrix)</td>
    <td>Use a variation of binary search or a two-pointers strategy.</td>
  </tr>
   <tr>
    <td>If you're dealing with top/max/min/closest.. elements among n elements</td>
    <td>Use a heap</td>
  </tr> 
   <tr>
    <td>If you need to try all combinations/permutations of the input</td>
    <td>Use recursive backtracking or iterative bfs.</td>
  </tr> 
   <tr>
    <td>If it's a tree or graph problem</td>
    <td>Try bfs or dfs</td>
  </tr> 
   <tr>
    <td>If you need to convert a recursive problem to an iterative one</td>
    <td>Use a stack</td>
  </tr> 
   <tr>
    <td>If there's a O(n^2) time and O(1) space solution</td>
    <td>There must be 2 other solutions: <br> A. Using a Map/Set for O(n) time and space.<br>
     B. Using sorting for O(n logn) time and O(1)space.</td>
  </tr> 
   <tr>
    <td>If you're asked for optimization (e.g maximization or minimization)</td>
    <td>Use dynamic programming</td>
  </tr> 
   <tr>
    <td>If you need to find some common substring among a set of strings</td>
    <td>Use a hashmap or a trie.</td>
  </tr> 
   <tr>
    <td>If you need to search among a bunch of strings</td>
    <td>Use a trie</td>
  </tr> 
   <tr>
    <td>If the problem involves a linked list and you can't use extra space</td>
    <td>Use the runner technique (a.k.a fast & slow approach)</td>
  </tr> 
</table>


<h2>Identify if a problem might be solved using a particular pattern</h2>
<table>
  <tr>
    <th>Pattern</th>
    <th>Ways to identify if it might be required:</th>
    <th>Common problems featuring this pattern</th>
  </tr>
  <tr>
    <th>Sliding window</th>
    <td>&#8226; The problem input is a linear data structure such as a linked list, array, or string. <br>
      &#8226; You’re asked to find the longest/shortest substring, subarray, or a desired value</td>
    <td>&#8226; Maximum sum subarray of size ‘K’ (easy) <br>
&#8226; Longest substring with ‘K’ distinct characters (medium)<br>
&#8226; String anagrams (hard)</td>
  </tr>
  <tr>
    <th>Two-pointer</th>
    <td>&#8226; It will feature problems where you deal with sorted arrays (or Linked Lists) and need to find a set of elements that fulfill certain constraints.<br>
&#8226; The set of elements in the array is a pair, a triplet, or even a subarray. <br>
    &#8226; There are some cases where you shouldn’t use the Two Pointer approach such as in a singly linked list where you can’t move in a backwards direction. An example of when to use the Fast and Slow pattern is when you’re trying to determine if a linked list is a palindrome.
</td>
    <td>&#8226; Squaring a sorted array (easy) <br>
      &#8226; Triplets that sum to zero (medium) <br>
      &#8226; Comparing strings that contain backspaces (medium)</td>
  </tr>
  <tr>
    <th>Fast and slow pointer</th>
    <td>&#8226; The problem will deal with a loop in a linked list or array <br>
&#8226; When you need to know the position of a certain element or the overall length of the linked list.</td>
    <td>&#8226; Linked List Cycle (easy) <br>
&#8226; Palindrome Linked List (medium)<br>
&#8226; Cycle in a Circular Array (hard)</td>
  </tr>
  <tr>
    <th>Merge Intervals</th>
    <td>&#8226; If you’re asked to produce a list with only mutually exclusive intervals.<br>
      &#8226; If you hear the term “overlapping intervals”.</td>
    <td>&#8226; Intervals Intersection (medium) <br>
&#8226; Maximum CPU Load (hard)</td>
  </tr>
  <tr>
    <th>Cyclic sort</th>
    <td>&#8226; They will be problems involving a sorted array with numbers in a given range. <br>
&#8226; If the problem asks you to find the missing/duplicate/smallest number in an sorted/rotated array.</td>
    <td>&#8226; Find the Missing Number (easy) <br>
&#8226; Find the Smallest Missing Positive Number (medium)</td>
  </tr>
  <tr>
    <th>Tree BFS </th>
    <td>&#8226; If you’re asked to traverse a tree in a level-by-level fashion (or level order traversal).</td>
    <td>&#8226; Binary Tree Level Order Traversal (easy) <br>
      &#8226; Zigzag Traversal (medium)</td>
  </tr>
  <tr>
    <th>Tree DFS</th>
    <td>&#8226; If you’re asked to traverse a tree with in-order, preorder, or postorder DFS. <br>
&#8226; If the problem requires searching for something where the node is closer to a leaf</td>
    <td>&#8226; Sum of Path Numbers (medium) <br>
&#8226; All Paths for a Sum (medium)</td>
  </tr>
  <tr>
    <th>Two-heaps</th>
    <td>&#8226; Useful in situations like Priority Queue, Scheduling.<br>
&#8226; If the problem states that you need to find the smallest/largest/median elements of a set.<br>
&#8226; Sometimes, useful in problems featuring a binary tree data structure</td>
    <td>&#8226; Find the Median of a Number Stream (medium)</td>
  </tr>
  <tr>
    <th>Subsets</th>
    <td>&#8226; Problems where you need to find the combinations or permutations of a given set</td>
    <td>&#8226; Subsets With Duplicates (easy)<br>
&#8226; String Permutations by changing case (medium)</td>
  </tr>
</table>
