##Permutations 
$$
P(n,k) = n \times (n - 1) \times \dots \times (n-k + 1) = {n \choose k} = \frac{n!}{(n-k)!}
$$

##Cobinations 
Also refered to as Binomial Coefficents
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

##Binomial Expansion
$$
\sum_{k=0}^{n} {{n \choose k} x^{n-k} + y^k} = (x + y)^n
$$