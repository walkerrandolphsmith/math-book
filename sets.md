#Sets

##Set
A set is an unordered collection of elements where elements are referred to as members of the set.
$$
S
$$

##Set Membership
s is a member of the set S.
$$
s \in S
$$

#Set Membership
s is not a member of the set S.
$$
s \not \in S
$$

#Roster Notation
Roster notation desribes a set by listing the set's elements
$$
S = \{s_1, \ldots, s_n\}
$$

#Set Builder Notation
Set builder notation determines membership an element s in a set S based on a property or properties, P(s)
$$
S = \{s\mid\text{P(s)}\}
$$

#Null Set
The null set, $\emptyset$, contains no elements
$$
\{ \}
$$

#Singleton Set
The singleton set contains exaclty one element, the null set
$$
\{ \emptyset\}
$$

#Subset
The set A is a subset of set B, denoted $$A \subseteq B$$,
is true 
if all members of A are also members of B
and false 
if there is a single $$a \in A$$ such that $$x \not \in B$$
$$
\forall x (x \in A \rightarrow x \in B)
$$

#Proper Subset
The set A is a proper subset of a set B, denoted $A \subset B$,
is true 
if A is a subset of B 
and 
there exists an x of B that is not an element of A
$$
\forall x (x \in A \rightarrow x \in B) \wedge \exists x (x \in B \wedge x \not \in A)
$$

#Set Equality
Two sets are equal, denoted $$A = B$$,
if and only if
they have the same elements
$$
\forall x(x \in A \leftrightarrow x \in B)
$$

#Cardinality
The set A with n distinct elements, where n is a non negative integer,
has a cardinality or size of n.

$$
\left| {A} \right|
$$

#Power Set
Given a set A, the power set of A is the set of all subsets of the set A 

$$
\mathcal P \left({S}\right)
$$

#Ordered n-tuples
An ordered collection $$(a_1, a_2, \ldots, a_n)$$ has $$a_1$$ as its first element, $$a_2$$ as its second element, $$\ldots$$, and $$a_n$$ as its last element.
$$
(a_1, a_2, \ldots, a_n)
$$

#Ordered n-tuples Equality
Two ordered n-tuples, $$(a_1, a_2, \ldots, a_n)$$ and $$(b_1, b_2, \ldots, b_n)$$ are equal
if and only if $$a_i = b_i$$ for $$i = 1,2,\ldots,n$$

$$
(a_1, a_2, \ldots, a_n) = (b_1, b_2, \ldots, b_n)
$$

#Cartesian Poduct
The cartesian product is the set of all ordered pairs (a,b), where a $$\in$$ A and b $$\in$$ B
$$
A \times B = \{(a,b)\mid\text{a $\in$ A $\wedge$ b $\in$ B}\}
$$

#Cartesian Poduct of Many Sets
The cartesian product of the sets $$A_1,A_2,\ldots,A_n$$,
denoted $$A_1 \times A_2 \times \cdots \times A_n$$,
is 
the set of ordered n-tuples ($$a_1,a_2,\ldots,a_n$$)
where $$a_i$$ belongs to $$A_i$$ for $$i = 1,2,\ldots,n$$
$$
A_1 \times A_2 \times \cdots \times A_n =\\ 
\{ (a_1,a_2,\ldots,a_n)\mid\text{ $a_i \in A_i$ for $i = 1,2,\ldots,n$} \}
$$


#Union
The of union of set A and B , denoted 
is the set containing members of the set A or B
$$
\mbox{A} \cup \mbox{B} = \{s\mid\text{s $\in$ A $\lor$ s $\in$ B}\}
$$

#Intersect
The of intersect of set A and B 
is the set containing members of sets A and B
$$
\mbox{A} \cap \mbox{B} = \{s\mid\text{s $\in$ A $\wedge$ s $\in$ B}\}
$$

#Disjoint Sets
Two sets are disjoint if their intersect is the set containing no elements
$$
\mbox{A} \cap \mbox{B} = \emptyset
$$

#Difference
The of difference of set $$A$$ and $$B$$ is the set containing members of sets $$A$$ that are members of $$B$$
$$
\mbox{A} - \mbox{B} = \{ s \in A \mid\text{s $\not \in$ B} \}
$$

#Truth Set
Given a predicate $$P$$ and domain $$D$$, the truth set of $$P$$ is the set of elements $$x$$ in $$D$$ for which $$P(x)$$ is true
$$
\{ x \in D \mid\text P(x) \}
$$

#Universal Quantification Over a Set
$\forall$ x $\in$ S(P(x)) is shorthand notation that denotes
the universal quatification of $$P(x)$$ over all the elements in the set $$S$$.
Statement is true over domain $$U$$ if and only if the truth set of $$P = U$$

$$
\forall x \left( x \in S \rightarrow P(x) \right)
$$

#Existential Quantification Over a Set
$$\exists x \in S(P(x))$$ is shorthand notation that denotes
the existential quatification of $$P(x)$$ over all the elements in the set $$S$$

$$
\exists x \left( x \in S \rightarrow P(x) \right)
$$
