 #Pumping Lemma
 
 The pumping lemma is a property held by regular sets.
 
 If a set is a regular it has pumping property and if there is an abscence of the pumping property then it is not a regular set. This relationship is captured with the following logic:
 
 $$
\mbox{p} \rightarrow \mbox{q} \equiv \neg \mbox{q} \rightarrow \neg \mbox{p}
$$

If L is a regular set
$$\exists {n} \mbox{ that is the number of states in the machine for } L$$
$$\forall z \in L \mbox{, where} \left| {z} \right| \geq n$$
$$\exists {v,w,x} \mbox{ s.t. } z = vwx \mbox{, s.t. } \left| {vw} \right| \leq n$$
$$\forall {i \geq 0} \mbox{ } vw^{i}x \mbox{ is also in } L$$

If not pumping property
$$\forall {n} \mbox{ that is the number of states in the machine for } L$$
$$\exists z \in L \mbox{, where} \left| {z} \right| \geq n$$
$$\forall {v,w,x} \mbox{ s.t. } z = vwx \mbox{, s.t. } \left| {vw} \right| \leq n$$
$$\exists {i \geq 0} \mbox{ } vw^{i}x \mbox{ is also in } L$$

