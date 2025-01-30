# I) extension du produit scalaire à l‘espace
## 1/ Définition du produit scalaire
### A. Du plan dans l‘espace
Soient u et v deux vecteurs dans l‘espace et a, b, c des points tels que AB = u et AC = v : 
$$
\vec{u} = \vec{ab}
$$
$$
\vec{v} = \vec{ac}
$$
- Il existe au moins un plan P contenant abc qui est unique si a, b et c sont alignés
- $$
\vec{u} \cdot\vec{v} = \vec{ab} \cdot\vec{ac}
$$
#### Définitions
$$
\vec{u} \cdot \vec{v} = ||\vec{u}|| * ||\vec{v}||*\cos θ
$$
##### Remarques : 
- Si u ou v est un vecteur nul, le produit scalaire est égal à **0**
- Le produit scalaire de u et u est appelé **carré scalaire** de u $$
\vec{u}^2 = \vec{u} \cdot\vec{u} = ||\vec{u}||^2
$$
##### Conséquences : 
- Même sens : θ = 0 $$
\vec{u} \cdot \vec{v} = ||\vec{u}|| \cdot ||\vec{v}||
$$
- Sens contraire : θ = pi$$
\vec{u} \cdot \vec{v} = -||\vec{u}|| \cdot ||\vec{v}||
$$
#### Projeté orthogonal 
Soit H le projeté orthogonal de C sur (AB) et K celui de B sur (AC
$$
\vec{AB} \cdot\vec{AC} = \vec{AB}\cdot\vec{AH} = \begin{matrix}
AB \cdot AH \text{ si } \vec{MB} \text{ et } \vec{AH} \text{ de meme sens}\\ -AB \cdot AH \text{ si } \vec{MB} \text{ et } \vec{AH} \text{ de sens contraire}
\end{matrix}
$$
### B. Propriétés du produit scalaire
#### Propriété : 
- $$
\vec{u} \cdot\vec{v} = \vec{v} \cdot\vec{u}
$$
- $$
\vec{u} \cdot(\vec{v}+\vec{w}) = \vec{u} \cdot\vec{v}+\vec{e} \cdot\vec{w}
$$
- $$
\vec{u} \cdot x\vec{v} = x\vec{u} \cdot\vec{v} = x\vec{u} \cdot\vec{v}
$$
- $$
(\vec{u}+\vec{v})^2 = \vec{u}^2 + 2\vec{u} \cdot\vec{v} + \vec{v}^2
$$
- $$
(\vec{u} - \vec{v})^2 = \vec{u}^2 - 2\vec{u} \cdot\vec{v} + \vec{v}^2
$$
- $$
(\vec{u}+\vec{v})(\vec{u}-\vec{v}) = \vec{u}^2 - \vec{v}^2
$$
#### Formules de polarisation : 
- $$
\vec{u}\cdot \vec{v} = \frac{1}{2}((\vec{u}+\vec{v})^2-\vec{u}^2-\vec{v}^2)
$$
- $$
\vec{u}\cdot \vec{v} = \frac{1}{2}(\vec{u}^2+\vec{v}^2-(\vec{u}-\vec{v})^2)
$$
- $$
\vec{u}\cdot \vec{v} = \frac{1}{4}((\vec{u}+\vec{v})^2-(\vec{u}-\vec{v})^2)
$$ 
## 2/ Vecteurs orthogonaux

#### Définition : 
- Deux vecteurs du plan sont orthogonaux si leur produit scalaire est nul, le vecteur nul est orthogonal à tout autre vecteur de l‘espace

#### Propriété : 
- Soit le repère orthonormé et les vecteurs
$$
(0; \vec{i}; \vec{j}; \vec{k}) \text{, } \vec{u}\begin{pmatrix}
x\\y\\z
\end{pmatrix}\text{, } \vec{o}\begin{pmatrix}
x'\\y'\\z'
\end{pmatrix}
$$
- $$
\vec{u}\cdot \vec{v} = xx'+yy'+zz'
$$
# II) Orthogonalité de droites et plans
## 1) Orthogonalité de deux droites 
#### Définition : 
- Deux droite sont orthogonales si leurs parallèles respectives passant par un point quelconque de l‘espace sont perpendiculaires
- Deux droites orthogonales ne sont pas nécessairement coplanaires
- Deux droites orthogonales ne sont pas forcément perpendiculaires
#### Propriétés : 
- Deux droites d et Δ de l‘espace de vecteurs directeurs u et v si $$
\vec{u} \cdot \vec{v} = 0
$$
- Si deux droites sont parallèles, toute droite orthogonales à l‘une est orthogonale à l‘autre
- Si deux droites sont orthogonales, toute droite parallèle à l‘une est orthogonale à l‘autre
## 2) Orthogonalité d‘une droite et d‘un flan
### 1/
#### Définition : 
- Une droite d de vecteur directeur w est perpendiculaire à un plan p dirigé par (u, v) si $$
\vec{u}\cdot \vec{w} = \vec{v}\cdot \vec{w} = 0 
$$
#### Propriétés
- Une droite d est orthogonale à un plan p si elle est orthogonale à deux droite sécantes de p
- Si une droite d est orthogonale à un plan p alors elle est orthogonale à toute droite incluse dans p
- Si une droite est orthogonale à deux plans, alors ces deux plan sont parallèles
### 1/
#### Définition : 
- Soit le plan P dirigé par le couple de vecteurs non-colinéaires (u, v), d de vecteur directeur w, orthogonale à P et Δ une droite incluse dans P de vecteur directeur t. D orthogonale à P donc $$
\vec{w}\cdot \vec{v} = \vec{w}\cdot \vec{u} = 0 
$$
- Δ C P donc u, v, t coplanaires et $$
\vec{t} = x\vec{u}+y\vec{v}
$$
- Alors$$
\vec{w}\cdot \vec{t} = \vec{w}\cdot (x\vec{u}+y\vec{v}) = x\vec{w}\cdot\vec{u}+y\vec{w}\cdot \vec{v} = 0
$$
#### Propriétés
- Si deux droites sont parallèles alors tout plan orthogonal à l‘une est orthogonale à l‘autre
- Si deux plan sont parallèles alors toute droite orthogonale à l‘un est orthogonale à l‘autre
- Si une droite est orthogonale à deux plans, alors ces deux plan sont parallèles
### 3/

#### Définition 
- Un vecteur normal n à un plan P est le vecteur directeur d‘une droite orthogonale à P

#### Remarques 
- Un plan contient une infinité de vecteurs normaux tous colinéaires entre eux
- Un vecteur normal à un plan est un vecteur directeur de toutes les droites orthogonales à ce plan
- Il existe un unique plan avec un vecteur normal donné passant par un point donné
- Deux plans parallèles ont les mêmes vecteurs normaux
- Pour tout point M, N de P avec v comme vecteur normal$$
\vec{MN}\cdot \vec{v} = 0
$$
#### Définition 
- Deux plans sont orthogonaux si leurs vecteurs normaux sont orthogonaux

#### Conséquence, position relative : 
##### Pour une droite et un plan : 
- Une droite d de vecteur directeur w et un plan P de vecteur normal n sont parallèles si $$
\vec{w}\cdot \vec{n} = 0
$$ et sécants sinon
##### Pour deux plans : 
- P1 de vecteur normal n1 et P2 de vecteur normal n2 sont parallèles si n1 et n2 sont colinéaires, sécants sinon
- P1 et P2 sont orthogonaux si $$
\vec{n_{1}}\cdot\vec{n_{2}} = 0
$$
#### Définition, projeté orthogonal d‘un point : 
- ##### sur un droite : 
	- Soit A un point de l‘espace et une droite d
	- Il existe un unique plan orthogonal à d passant par A
	- La droite d est sécante à ce plan en H, appelé projeté orthogonal de A sur d
	- AH est la distance la plus courte entre A et un point de d
	- AH est la distance entre A et d
- ##### sur un plan : 
	- Soit A un point de l‘espace et P un plan
	- Il existe une unique droite passant par A et orthogonale à P
	- Cette droite est sécante à P en un point H appelé projeté orthogonal de A sur P
	- AH est la plus courte distance entre A et un point de P
	- AH est la distance de A à P

#### Définition, plan médiateur d‘un segment : 
- Le plan médiateur d‘un segment [AB] est le plan de vecteur normal AB passant par le milieu I de [AB], ce plan est l’ensemble des point équidistants de A et B

# III) Equations cartésiennes d‘un plan
#### Propriété, caractérisation d‘un plan : 
- Soit le plan P de vecteur normal n et le point A de P 
- P est l‘ensemble des points M de l‘espace tel que $$
\vec{AM}\cdot \vec{n} = 0
$$
- Dans un repère orthonormé, le plan P admet une équation cartésienne de la forme $$
ax+by+cz+d = 0
$$
- Ou (a, b, c) sont les coordonnées d‘un vecteur normal à P



