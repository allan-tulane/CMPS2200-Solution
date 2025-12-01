# CMPS 2200  Recitation 03

**Name (Team Member 1):**_________________________  
**Name (Team Member 2):**_________________________

## Recommendation Systems


## a)-solution


  It merges two sorted lists into a sorted list, like merge sort does. Along the way, it keeps track of additional disagreements introduced when merging the two lists.


## b)-solution

$W(n) = 2 W(n/2) + n$

## c)-solution

$O(n \lg n)$

Brick method: balanced. worst level costs $n$. $\lg n$ levels.
\end{solution}

## d)-solution
  S(n) = S(n/2) + n


## e)-solution
Brick method: root dominated -> $O(n)$



## f)-solution

If \texttt{ranks} is a list of size \(n\), Netflix says it will give
you \(\lg n\) processors to run your algorithm in parallel. What is the
upper bound on the runtime \(T_{\lg n}\).


$T_P  < W/P + S$

$T_{\lg n} < \frac{n \lg n}{\lg n} + n = 2n$
