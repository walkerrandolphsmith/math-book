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

##Binomial Expansion
$$
\sum_{k=0}^{n} {{n \choose k} x^{n-k} + y^{k}} = (x + y)^{n}
$$

##Permutations of multisets  
The number of arrangements of the n-element multiset,M in which each element appears exactly as often as the multiplicity.
$$
{n \choose k_1,k_2, \dots ,k_i} = \frac{n}{k_1!k_2! \dots k_i!}
$$