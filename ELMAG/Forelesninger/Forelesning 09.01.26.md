Maxwells lover...

Boken: Introduction to electrodynamics, Griffiths
# Why do we care?
Using antennas
**Communication, networking,**

## Energy harvesting
**Photonics, nanotechnology**

## Electromagnetism is a universal concept
You can have antenna at the nano- or macroscale


# Chapter 1: Vector analysis
## Part 1
### 1.1.1 Book
Vector has direction and magnitude (aw yeeaah)

**i)** Addition of 2 vectors is commutative
$$
 \begin{equation} 
 A+B=B+A 
 \end{equation} 
$$
and associative
$$
 \begin{equation} 
 A+(C+B)=B+(A+C) 
 \end{equation} 
$$
$$
 \begin{equation} 
 A-B=A+ (-B) 
 \end{equation} 
$$
**ii)** Multiplication by scalar is distributive.
$$
 \begin{equation} 
 a(A+B)=aA+aB 
 \end{equation} 
$$
If its positive the magnitude is just scaled, if its negative its direction is also reversed.

**iii)** Dot product of 2 vectors
$$
 \begin{equation} 
 A\cdot B=AB\cos \theta 
 \end{equation} 
$$
so if they are normal on eachother the dot product is 0, if they are parallell its $AB$.


**iv)** Cross product 2 vectors
$$
 \begin{equation} 
 A\times B=AB\sin \theta \vec{n}  \ \ \\ \ \ \ \text{| unit vector} 
 \end{equation} 
$$
points to the normal on the plane of A and B, is another vector.
$$
 \begin{equation} 
 A\times(B+C)=A\times B+A\times C 
 \end{equation} 
$$
distributive^^.
$$
 \begin{equation} 
 (B\times A)=-(A\times B) 
 \end{equation} 
$$
Not commutative^^.

#### Problem 1.1
Using the definition of the dot and cross product, show that the dot and cross product of 3 co-planar vectors are distributive.

$$
 \begin{equation} 
 \cos \theta_{1} =\frac{x_{1}}{|B|}\implies x_{1}=|B|\cos \theta_{1}
 \end{equation} 
$$
$$
 \begin{equation} 
  x_{2}=|C|\cos \theta_{2}
 \end{equation} 
$$
$$
 \begin{equation} 
 x_{1}+x_{2}=|B+C|=\cos \theta_{3}
 \end{equation} 
$$
$$
 \begin{equation} 
 y_{1}=|B|\sin \theta_{1} 
 \end{equation} 
$$
$$
 \begin{equation} 
 y_{2}=|C| \sin \theta_{2}
 \end{equation} 
$$
$$
 \begin{equation} 
 y_{1}+y_{2} =|B+C|\sin \theta_{3}
 \end{equation} 
$$
Proof for dot product: $|A|$
$$
 \begin{equation} 
 |A| |B+C|\cos \theta_{3} =|A||B|\cos \theta_{1}+|A||C|\cos \theta_{2}
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies A\cdot(B+C)=A\cdot B+A\cdot C 
 \end{equation} 
$$
Proof for cross product: $|A|\vec{n}$
$$
 \begin{equation} 
 |A||B+C|\sin \theta_{3} \ \vec{n} = |A||B|\sin \theta_{1}\ \vec{n}+|A||C|\sin \theta_{2}\ \vec{n}
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies A\times(B+C)=A\times B+A\times C 
 \end{equation} 
$$
#### Problem 1.2 for homework

### 1.1.2 
Component form of vectors:
$$
 \begin{equation} 
 A= A_{x}+\hat{x}+A_{y}\hat{y}+A_{z}\hat{z} 
 \end{equation} 
$$
Dot product:
$$
 \begin{equation} 
 A\cdot B = (A_{x}+\hat{x}+A_{y}\hat{y}+A_{z}\hat{z} ) \cdot (B_{x}+\hat{x}+B_{y}\hat{y}+B_{z}\hat{z} )
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies A_{x}B_{x}+A_{y}B_{y}+A_{z}B_{z} 
 \end{equation} 
$$
Because of 
$$
 \begin{equation} 
 \hat{x} \cdot \hat{x} = \hat{y}\cdot \hat{y}=\hat{z}\cdot \hat{z}=1 
 \end{equation} 
$$
$$
 \begin{equation} 
 \hat{x}\cdot \hat{y}=\hat{x}\cdot \hat{z}=\hat{y}\cdot \hat{z}=0 
 \end{equation} 
$$
Cross product:
$$
 \begin{equation} 
 A\times B=(A_{x}+\hat{x}+A_{y}\hat{y}+A_{z}\hat{z} ) \times (B_{x}+\hat{x}+B_{y}\hat{y}+B_{z}\hat{z} )
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies (A_{y}B_{z}-A_{z}B_{y})\hat{x}+(A_{z}B_{x}-A_{x}B_{z})\hat{y} + (A_{x}B_{y}-A_{y}B_{x})\hat{z} 
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies \begin{pmatrix}
 A_{y}B_{z}-A_{z}B_{y} \\
A_{z}B_{x}-A_{x}B_{z} \\
A_{x}B_{y}-A_{y}B_{x}
\end{pmatrix}  
 \end{equation} 
$$

Because of
![[Pasted image 20260109114653.png]]
Can also be written as:
$$
 \begin{equation} 
 A\times B= \det \begin{pmatrix} \hat{x}  & \hat{y} & \hat{z} \\
A_{x} & A_{y} & A_{z} \\
B_{x} & B_{y} & B_{z}
\end{pmatrix}  
 \end{equation} 
$$
#### Example 1.2
$$
 \begin{equation} 
  A= \begin{pmatrix}1 \\
0 \\
1 
\end{pmatrix}  \ \ \ \\ B=\begin{pmatrix}0 \\
1 \\
1 
\end{pmatrix} 
 \end{equation} 
$$
In component form we get
$$
 \begin{equation} 
 A \cdot B=1\cdot 0 + 0 \cdot 1 + 1 \cdot 1 = 1
 \end{equation} 
$$
In abstract form we get
$$
 \begin{equation} 
 A\cdot B =AB\cos \theta = 2\cos \theta
 \end{equation} 
$$
therefore
$$
 \begin{equation} 
 \cos \theta=\frac{1}{2} \implies \theta=60^o 
 \end{equation} 
$$
