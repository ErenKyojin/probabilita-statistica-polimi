P(A \cup B) = P(A \cap B \setminus A) = P(A) + P(B \setminus A) + P(A \cap B) - P(A \cap B) 1. $P(\varnothing)$ 
   $$ \begin{align}
\Phi = &\Phi \cup \varnothing \cap \dots \implies P(\varnothing) = P\left( \bigcup_{i=1}^{\infty} \Phi\right) \\
&E_{1} \cup E_{2} \cup \dots = \sum_{i=1}^\infty P(\varnothing)  \\
&\implies P(\Phi) = \sum_{i=1}^{\infty} P(\varnothing) \implies \int _{P} P(\varnothing) > 0  \\
&\implies \sum P(\varnothing) = \infty `\unicode{x21af}` \implies P(\Phi) < 0 `\unicode{x21af}`&  \\
&\implies =0
\end{align}  $$

2. $P(A \cup B)$
$$ P(A \cup B \cup \varnothing \cup \varnothing \cup \dots) = P(A) + P(B) + P(\varnothing) + \dots = P(A) + P(B) $$

3. $A \subseteq B$
   $$\begin{align}
 &B \setminus A \implies B = A \cup(B \setminus A) \implies P(B) = P(A) + P(B \setminus A) \implies\\
&P(B \setminus A) = P(B) - P(A)
\end{align}$$

4. Se $A \subset B$ allora $P(A) \leq P(B)$
   $$ \begin{align}
&P(B) - P(A) \text{ è la }p(B \setminus A) \geq 0  \\
&Se\quad  A_{1} \subset A_{2} \subset \dots \subset A_{n} \subset \dots \implies \\
&P(A_{1}) \leq P(A_{2}) \leq \dots. \leq P(A_{n}) \leq \dots
\end{align}$$
$P$ momnotona crescente
5. #todo

6. $\neg B = \Omega \setminus B$ e $\neg B \subseteq \Omega$ allora $P(\neg B) = P(\Omega) - P(B) = 1 - P(B
7. $A,B$ hanno un intersezione, $P(A \cup B)$
   $$ \begin{align}
&P(A \cup B) = P(A \cap B \setminus A) = P(A) + P(B \setminus A) + P(A \cap B) - P(A \cap B) + P(B) \\
&P([A \cup B] \cup C) = P(A \cup B) + P(C) - P((A \cup B) \cap C) = \\
= &P(A) + P(B) - P(A \cap B) + P(C) + P((A \cap C) \cup (B \cap C))
\end{align}$$



## Calcolo della probabilità
Costruiamo la funzione $P$ nel caso di
$\Omega = \left\{ w_{1},w_{2},\dots,w_{n} \right\} \quad n \leq \infty$
$\mathcal{F} = \mathcal{P}(\Omega)$
1. Fissiamo dei pesi $p_{1}, p_{2},\dots,p_{n}$ tali che
	1. $p_{i} \geq 0$
	2. $\sum_{i= 1}^{n} p_{i} = 1$

2. Calcolo $P(A)$ con $A \subseteq R$ regola additiva, cioè
$$ P(A) := \sum_{\left\{ i :w_{i} \in A \right\} } P_{i} $$
$P(A)$ è effettivamente una funzione di probabi