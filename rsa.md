# RSA Cryptography

Ronald L Rivest, Leonard M. Adleman, and Adi Shamir began working on a method of cryptography known as public key cryptography after reading a paper on the Diffie-Hellman key exchange. The heart of the algorithm, later named RSA after their names, is based on the fact that the computation of the encryption function takes little time. The computation of the decryption method is based on integer factorization which is computationally hard; that in itself means that the amount of time to perform the computation is greater than what is reasonable unless certain information is known.

A proof for the algorithm’s correctness lies in the understanding of Euler’s Theorem, Fermat’s Little Theorem, and the Chinese Remainder Theorem.

Essentially, the algorithm generates a public and private key that are asymmetric or inversely related. The private decryption key can undo the operation applied by the encryption key. A function built on knowing the prime factorization of a very large number must be developed due to fact that the algorithm relies on a one way function that is computationally hard to compute one way and computationally easy in another. Such a function can be developed by examining Euler’s Theorem.

The encryption function is the procedure of raising a base, $$M$$, to an exponent, $$e$$, and then dividing by a modulus, $$N$$, that shares no common factors with $$M$$ and outputting the remainder, $$c$$. Since applying the encryption method and outputting a remainder takes little computational power, and knowing all values except $$M$$ turns an easy computation into a computationally hard problem, the discrete logarithm provides a one way function. In order to understand how this one way function works, I will formulate an example.

First, multiply two prime numbers, $$p1$$ and $$p2$$, together to generate a larger composite number, $$N$$. Given that $$\Phi(N)$$ is the number of numbers that share no factors with $$N$$, Phi of any prime number $$p$$ is $$p-1$$. In addition, the Phi function is multiplicative and therefore follows that


$$
\Phi(N) = (p1 - 1)\times (p2 - 1)
$$


Since the prime factors of N are known, then $$\Phi(N)$$ takes little computational power.\[Note $$p1$$ and $$p2$$ are private and solve factorization of N\] Generate a value for e that is co-prime to $$N$$, meaning they share no common factors. $$N$$, $$e$$, and the encryption function, $$m^e\mod{N}$$, together make an unlocked lock and are public. Send the unlocked lock to a recipient.

The recipient will generate a message, $$M$$, and using the lock, apply the encryption function to $$M$$ to generate a message, $$c$$, as follows: 
$$
c = M^{e}\mod{N}\ 
$$


The encrypted message, $$c$$, must be sent back to the sender of the lock. In order for the encrypted message to be decrypted, a value for $$d$$ must be derived that satisfies the following: 
$$
M = c^d\mod{N}\
$$


The sender of the lock needs to know how many times $$c$$ must be multiplied by itself, and then divided by $$N$$, in order for the remainder to be the original message $$M$$. However, since $$N$$ was generated as the product of $$p1$$ and $$p2$$, we can easily determine this number by applying Euler’s Theorem:


$$
m^{k \Phi(n)}\equiv 1\mod{n}\
$$


By applying algebra, 
$$
1^k=1
$$
 
$$
m*m^k = m^{k+1}
$$

$$
 m^{k \Phi(n)+1}\equiv m\mod{n}\ 
$$


Now the sender of the lock can apply the encryption and decryption functions together, and because of the Chinese Remainder Theorem, it follows that


$$
c^d\equiv M^{e*d} = M^{k \Phi(n)+1}\mod{N}\
$$


Thus, 
$$
ed = k \Phi(N) +1
$$
 and, 
$$
d = \frac{k \Phi(N) +1}{e}
$$


$$d$$ is a key to the lock, which can decrypt $$c$$. Since the prime factorization of $$N$$ is known by the sender of the lock, it is computationally easy to evaluate $$\Phi(N)$$ and the value of $$d$$. For anyone else trying to solve for the value of $$d$$, computing $$\Phi(N)$$ would be computationally hard since prime factorization would result in trial and error. Arriving at the secret, original message is as easy as computing: 
$$
M = c^{\frac{k \Phi(N) +1}{e}}\mod{N}\ 
$$


The significance of the RSA algorithm still impacts, not only the field of computer science, but our entire society. The implications of this method of cryptography is currently the foundation for all secure, online transactions. Due to its importance, Rivest was awarded the Turning Award and a place in history as one of the world’s greatest cryptographers.

