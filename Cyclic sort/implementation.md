## Cyclic sort

This pattern describes an interesting approach to deal with problems involving arrays containing numbers in a given range. The Cyclic Sort pattern 
iterates over the array one number at a time, and if the current number you are iterating is not at the correct index, you swap it with the number 
at its correct index. You could try placing the number in its correct index, but this will produce a complexity of O(n^2) which is not optimal, hence 
the Cyclic Sort pattern.


<img src="https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fimages%2FG9YRlqC9joZNTWsi1ul7tRkO6tv1-t8i13wdp.jpg&w=1920&q=75" />
