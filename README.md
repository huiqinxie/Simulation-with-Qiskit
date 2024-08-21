## Explanation
1. This is an example of simulating Algorithm 2， which is proposed for finding high-probability truncated differentials.
2. Taking function F(x1,x2,x3,x4) as an example. The truth table of F is as follows.

<div align="center">
  
| x1 | x2 | x3 | x4 |  F|
|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0000 |
| 0 | 0 | 0 | 1 |  0010 |
| 0 | 0 | 1 | 0 | 0110|
| 0 | 0 | 1 | 1 | 1101 |
| 0 | 1 | 0 | 0 | 1111|
| 0 | 1 | 0 | 1 |  1101 |
| 0 | 1 | 1 | 0 | 1000|
| 0 | 1 | 1 | 1 | 0011 |
| 1 | 0 | 0 | 0 | 1001 |
| 1 | 0 | 0 | 1 |  1111 |
| 1 | 0 | 1 | 0 | 1111 |
| 1 | 0 | 1 | 1 | 0000 |
| 1 | 1 | 0 | 0 | 0111 |
| 1 | 1 | 0 | 1 |  0001 |
| 1 | 1 | 1 | 0 | 0000 |
| 1 | 1 | 1 | 1 | 1111 |

</div>
