##Permutations 
The number of different arrangements of a k-element subset of the n-element set S.
$$
P(n,k) = n \times (n - 1) \times \dots \times (n-k + 1) = \frac{n!}{(n-k)!}
$$

##Cobinations 
The number of unique, ordered arrangements of a k-element subset of the n-element set S. Also referred to as Binomial Coefficients
$$
C(n,k) = {n \choose k} = \frac{n!}{k!(n-k)!} 
$$

##Pascal's Triangle
$$
\newcommand\cn[2]{\llap{#1}\rlap{#2}\,}
    \begin{array}{c}
    &&&&&&\cn{1}{}\\
    &&&&&\cn{1}{}&\cn{}{}&\cn{1}{}\\
    &&&&\cn{1}{}&\cn{}{}&\cn{2}{}&\cn{}{}&\cn{1}{}\\
    &&&\cn{1}{}&\cn{}{}&\cn{3}{}&\cn{}{}&\cn{3}{}&\cn{}{}&\cn{1}{}\\
    &&\cn{1}{}&\cn{}{}&\cn{4}{}&\cn{}{}&\cn{6}{}&\cn{}{}&\cn{4}{}&\cn{}{}&\cn{1}{}\\
\end{array}
$$



##Permutations of multisets
The number of arrangements of the n-element multiset,M in which each element appears exactly as often as the multiplicity.
$$
{n \choose k_1,k_2, \dots ,k_i} = \frac{n}{k_1!k_2! \dots k_i!}
$$