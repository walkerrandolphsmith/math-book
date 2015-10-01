#Number Theory

##Division
If m and n are integers where m $$\not =$$ 0,m divides n if there is an integer k such that $$n = mk $$

$$ m \mid\ n$$ Equivalently $$\frac{n}{m}$$ is an integer

If m divides n, m is a factor of n and n is a multiple of m 


##Divisibilty of Integers
If a $$\mid$$ b and a $$\mid$$ c then a $$\mid$$ (b+c)

If a $$\mid$$ b, then a $$\mid$$ bc for all integers c

If a $$\mid$$ c and b $$\mid$$ c, then a $$\mid$$ c




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
Let $$a$$ be an even prefect number.
$$a$$ is of the $$2^{p-1}(2^p - 1)$$ where $$2^p - 1$$ is prime.

Thus 
$$
a = (2^p - 1)2^{p-1}
  = (2^p - 1)\frac{2^p}{2}
  = \frac{n(n + 1)}{2} \text{where } n = 2^p - 1$$