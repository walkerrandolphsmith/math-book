#Base Conversion

$$
10_{10} = (1*10^1)+(0*10^0) =
$$

$$
1010_{2} = (1*2^3)+(0*10^2)+(1*2^1)+(0*2^0)
$$

$$
d_{n} d_{2} d_{1} d_{0} = (d_{n}*b^n)+(d_{2}*b^2)+(d_{1}*b^1)+(d_{0}*b^0)
$$


```
procedure convertN(n,b where b >1)
q := n
k := 0
while(q != 0)
	ak := q mod b
	q := q div b
result{ak-1,...,a0}

```