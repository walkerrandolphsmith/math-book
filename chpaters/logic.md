# Propositional Logic

###Proposition
A proposition is a declartive sentence 
that is either true or false.
$$
\mbox{p}
$$

###Negation of p
The negation of p has the opposite truth value of p.
$$
\neg \mbox{p}
$$

###Conjunction of p and q
The conjunction of p and q is true when both p and q are true and false otherwise.
$$
\mbox{p} \wedge \mbox{q}
$$

###Disjunction of p and q
The disjunction of p and q is false when both p and q are false and true otherwise.
$$
\mbox{p} \lor \mbox{q}
$$

###Exclusive or of p and q
The exclusive or of p and q is true when exactly one of p and q are true and false otherwise.
$$
\mbox{p} \oplus \mbox{q}
$$

###Conditional statement
The conditional statement if p then q
is false
when
p is true and q is false
and true otherwise.
$$
\mbox{p} \rightarrow \mbox{q}
$$

###Converse
The converse of p $\rightarrow$ q
is the conditional statement

$$
\mbox{q} \rightarrow \mbox{p}
$$

###Contrapositive
The contrapositive of p $\rightarrow$ q
is the conditional statement

$$
\neg \mbox{q} \rightarrow \neg \mbox{p}
$$

###Inverse
The inverse of p $\rightarrow$ q
is the conditional statement

$$
\neg \mbox{p} \rightarrow \neg \mbox{q}
$$

###Biconditional statement
The biconditional statement p if and only if q
is true
when
p and q have the same truth value
and false otherwise.
$$
\mbox{p} \leftrightarrow \mbox{q}
$$

###Logical Equivalence
compound propositions p and q are logically equivalent if 
p if and only if q is a tautology,
that is the compound proposition is true 
no matter the truth values of the propositional variables.

$$
\mbox{p} \equiv \mbox{q}
$$

###Propositional Function
Value of a propositional function P at x.
Function defined by it's predicate,P and subject, x
where
x is the subject of the statement and
P refers to a property that the subject has.
$$
P(x)
$$

###Propositional Multivariable Function
Value of a propositional function P at the n-tuple $$(x_{1},x_{2},\dots,x_{n})$$.
$$
P(x_{1},x_{2},\dots,x_{n})
$$

###Universal Quantification
Universal quantification of P(x)
is true
when
P(x) is true for every x
and false
when
there is an x for which P(x) is false.
$$
\forall x P(x)
$$


###Existential Quanification
Existential quantification of P(x)
is true
when
there exists an element x in the domain such that P(x)
and false
when
P(x) is false for every x.
$$
\exists x P(x)
$$

###Quantifaction Equivalences
Statement is true
when
there is an x for which P(x) is false
and
false 
when
P(x) is true for every x.

$$
\neg \forall x P(x)\equiv\exists x \neg P(x)
$$
Statement is true when for every x P(x) is true and false when there is an x for which P(x) is true.
$$
\neg \exists x P(x)\equiv\forall x \neg P(x)
$$

###Quantification of Two Variables
P(x,y) is true for every pair x,y and false when there is a pair x,y for which P(x,y) is false.


$$
\forall x \forall y P(x,y)
$$
$$
\forall y \forall x P(x,y)
$$
For every x there is a y for which P(x,y) is true. There is an x such that P(x,y) is false for every y.
$$
\forall x \exists y P(x,y)
$$
There is an x for which P(x,y) is true for every y.For every x there is a y for which P(x,y) is false.
$$
\exists x \forall y P(x,y)
$$
There is a pair x,y for which P(x,y) is true. P(x,y) is false for every pair x,y.
$$
\exists x \exists y P(x,y)
$$

$$
\exists y \exists x P(x,y)
$$

