#Number Theory

##Division
If m and n are integers where m $$\not =$$ 0,m divides n if there is an integer k such that $$n = mk $$

$$ m \mid\ n$$ Equivalently $$\frac{n}{m}$$ is an integer

If m divides n, m is a factor of n and n is a multiple of m 


##Divisibilty of Integers
If a $$\mid$$ b and a $$\mid$$ c then a $$\mid$$ (b+c)

If a $$\mid$$ b, then a $$\mid$$ bc for all integers c

If a $$\mid$$ c and b $$\mid$$ c, then a $$\mid$$ c

##Prime
A prime number, p, is a positive integer that has exactly two divisors: p and 1.

##Composite
A composite number, c, is a positive integer that has more than two divisors.

##Tau Function
The tau function is the total number of positive integer divisors of its input.

Let $$n \in \mathbb{Z}$$ such that $$n \geq 1$$

$$
\tau(n) = \sum_{d\backslash{n}}1
$$

where $$\sum_{d\backslash{n}}1$$ is the sum over all divisors of n.

##GCD
The greatest common divisor of two integers $$i$$ and $$j$$, such that at least one is non-zero, is the largest positive integer, $$m$$ such that $$m \mid i$$ and $$m \mid j$$. 

##LCM
The least common multiple of two integers $$i$$ and $$j$$ is the smallest number that is a multiple of both $$i$$ and $$j$$.

The $$LCM(i,j)$$ can be computed by obtaining the prime factorization of $$i$$ and $$j$$, take the union of the two resulting sets and return the smallest value of the new set..
##Coprime
Integers m and n are relatively prime if 
$$
\gcd (m,n) = 1
$$

##Euler's Theorm
If n and m are relatively prime for some m,n $$\in$$ $$\mathbb{Z}^+$$

$$
n^{\Phi(m)}\equiv 1\mod{m}
$$

$$
n^{\Phi(m)} - 1\equiv 0\mod{m}
$$

##Prime Counting Function

$$
\lim_{x\to\infty} \frac{\pi(x)}{x/ln(x)} = 1
$$

##Perfect Number
A perfect number is a positive integer that is twice the value of its positive divisors.

The factors of 6 are 1,2,3,6 and the sum of its factor is
$$1 + 2 + 3 + 6 = 12 = 2 \times 6$$

The factores of 28 are 1,2,4,7,14,28 and the sum of its factors is
$$1 + 2 + 4 + 7 + 14 + 28 = 56 = 2 \times 28$$

##Triangle Numbers
A triangle number, n, is computed by the sum of the natural numbers 1 to n counts. 

$$
\sum_{k=1}^{n} k = \frac{n(n + 1)}{2}
$$

##Even Perfect numbers are triangular
Let $$a \in \mathbb{N} $$ be an even prefect number.
$$a$$ is of the form $$2^{p-1}(2^p - 1)$$ where $$2^p - 1$$ is prime.

Thus 
$$
a = (2^p - 1)2^{p-1}
  = (2^p - 1)\frac{2^p}{2}
  = \frac{n(n + 1)}{2} \text{where } n = 2^p - 1
$$
  
##Perfect and Prime Relationship
Let 
$$n \in \mathbb{N}$$

Let $$2^n - 1$$ be prime

Then $$2^{n - 1}(2^n -1) \text{is perfect.}$$ 

##Mersenne Prime
A mersenne prime is a prime number of the ofrm $$2^p - 1$$ where $$p$$ is a prime number.