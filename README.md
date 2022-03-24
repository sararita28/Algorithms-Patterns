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
