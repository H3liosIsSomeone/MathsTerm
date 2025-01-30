[PDF du cours](Maths/cours-denombrement.pdf)
E = {e1, …, en} : card (E) = N 
## K uplets : 
- ### **ordre** 
	- **tirage successif*** : 
		- Avec remise : 
			- Nombre de k-uplets de E 
			- $$
n^k
$$
		- Sans remise : 
			- Nombre de k-uplets d‘élements distincts de E
			- $$
\frac{n!}{(n-k)!}
$$
			- Si k = n : 
				- $$
n!
$$
## Combinaisons 
- ### **pas d‘ordre**
	- **tirage simultané** : 
		- Nombre de parties à k éléments de E : 
			- $$\begin{pmatrix} n \\ k \end{pmatrix} = \frac{n!}{k!(n-k)!}
$$
				-  Propriétés : 
					- Symétrie : $$
\begin{pmatrix} n \\ k \end{pmatrix} = \begin{pmatrix} n \\ n-k \end{pmatrix}
$$
					- Formule de Pascal : $$
\begin{pmatrix} n+1 \\ k+1 \end{pmatrix} = \begin{pmatrix} n \\ k \end{pmatrix} + \begin{pmatrix} n \\ k+1 \end{pmatrix}
$$
					- $$
(a+b)^n = \sum_{k=0}^{n}\begin{pmatrix} n \\ k \end{pmatrix}a^{n-k} *b^k  = 1  
$$

