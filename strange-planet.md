#Strange Planet

$$
\sum_{x=1}^{n+1} x = \frac{(n+1)(n+2)}{2}
$$



$$
f(n) =
\begin{cases}
\bigg\lfloor\frac{(n+1)(n+2)}{9}\bigg\rfloor + 1, & \text{if }n\mod 3 = 0 \\[2em]
\bigg\lfloor\frac{(n+1)(n+2)}{9}\bigg\rfloor, & \text{if }n\mod 3 \not= 0
\end{cases}
$$



Terminal states are "must-fail" states and are dictated by the rules. Cycles that contain no terminal elements have states that are all "can't-fail" states. If a path contains a terminal state and has no cycles all states in that path are "might-fail" states. If a path contains a terminal state and has a cycle the elements of the path that are also members of the cycle and all states with paths to the cycle are "might-fail" and the remaining states are "must-fail".  



Total number of 2-tuples each possessing the property the sum of it's elements is equal to n. 
$$
n + 1
$$

Total number of distinct 2-tuples each possessing the property the sum of it's elements is equal to n.
