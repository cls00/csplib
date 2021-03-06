The problem can be modelled with a CSP variable associated with the occurrence of each number, and its value being its position in the sequence. Alternatively, we can consider a dual model in which a CSP variable is associated with each position in the sequence, and its value being the number assigned to this position. We can also have construct a representation of the problem with both the primal and dual models, and channelling constraints between the two.

L(2,3) has the unique solution up to reversal of 312132. This was supposedly found by Langford's child. L(2,4) also has an unique solution up to reversal, 41312432 found by Langford. L(2,n) only has solutions if n=4k or 4k-1. L(2,19) has 256,814,891,280 solutions, and it took [two months](http://www.dialectrix.com/langford/groth-L19.html) of computing in 1999 to count them. The number of solutions for L(2,n) is known for all n up to 30, but currently L(2,31) is not known.

L(3,n) is insoluble for n less than 9. L(3,9) has 3 solutions, whilst L(3,10) has 5 solutions. L(3,n) is insoluble for n between 11 and 16 inclusive. L(3,17), L(3,18) and L(3,19) have 13,440, 54,947 and 249,280 solutions respectively, whilst L(3,20) has no solutions.

John Edward Miller's [web pages](http://www.dialectrix.com/langford.html) on Langford's problem include a large table of results (about half way down the long page), as well as notes about when and by whom they were proved.

The number of solutions to Langford's problem is sequence [A014552](https://oeis.org/A014552) in the [On-Line Encyclopedia of Integer Sequences](https://oeis.org/). The lexicographically ordered solutions form sequence [A050998](https://oeis.org/A050998).
