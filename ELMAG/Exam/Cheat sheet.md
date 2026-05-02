# Chapter 2:
## E-field
$$
 \begin{equation} 
 F= \frac{1}{4\pi \epsilon_{0}} \frac{qQ}{r^2} \hat{r} \ \ \text{ Coloumb's law}
 \end{equation} 
$$
$$
 \begin{equation} 
 F =QE \implies E(r)=\frac{1}{4\pi \epsilon_{0}} \sum_{i=1}^{n} \frac{q_{i}}{r_{i}^2} \hat{r_{i}} \ \ \text{ or } \ \ E(r)=\frac{1}{4\pi \epsilon_{0}}\int_{}^{} \frac{1}{r^2} \hat{r} \ dq
 \end{equation} 
$$
where dq=
- 1D: $\lambda dl'$
- 2D: $\sigma d\alpha'$
- 3D:$\rho d\tau'$
$$
 \begin{equation} 
 \int_{S}^{}(\nabla \times E)d\alpha=\oint_{}^{}E\cdot dl =0 \implies \nabla \times E=0
 \end{equation}
$$
$$
 \begin{equation} 
 \oint_{}^{}E\cdot d\alpha = \frac{1}{\epsilon_{0}}Q_{enc } \ \ \text{ Gauss Law}
 \end{equation} 
$$
$$
 \begin{equation} 
 Q_{enc}= \int_{V}^{}\rho \ d\tau \implies \nabla \cdot E = \frac{1}{\epsilon_{0}}\rho 
 \end{equation} 
$$

## Electric potential
$$
 \begin{equation} 
 V(r)=-\int_{O}^{r}E\cdot dl 
 \end{equation} 
$$
$$
 \begin{equation} 
 E=-\nabla V 
 \end{equation} 
$$
![[Pasted image 20260502131737.png]]

## Work
$$
 \begin{equation} 
 W=\int_{a}^{b}F\cdot dl = -Q\int_{a}^{b}E\cdot dl=Q(V(b)-V(a)) \implies V(b)-V(a)=\frac{W}{Q} 
 \end{equation} 
$$
Point charges:
$$
 \begin{equation} 
 W=\frac{1}{2}\sum_{i=1}^{n}q_{i}V(r_{i}) =\frac{1}{2}\sum_{i=1}^{n}q_{i}\left( \sum_{j\neq i}^{n} \frac{1}{4\pi \epsilon_{0}} \frac{q_{j}}{r_{ij}}\right)
 \end{equation} 
$$
Continuous charge distribution:
$$
 \begin{equation} 
 W=\frac{1}{2}\int_{}^{}Vdq 
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies W\approx \frac{\epsilon_{0}}{2}\int_{}^{}E^2 \ d\tau  \ \text{ Electrostatic work}
 \end{equation} 
$$
# Chapter 4:
## Induced dipole:
$$
 \begin{equation} 
 p=\alpha E  \ \ \text{ or } \ \ p = \alpha_{\perp}E_{\perp} + \alpha_{\lvert  \rvert } + E_{\lvert  \rvert }
 \end{equation} 
$$
where $\alpha$ is atomic polarizability. For 3D:
![[Pasted image 20260502133009.png]]

## Torque:
$$
 \begin{equation} 
 T=(r_{+}\times F_{+})+(r_{-}\times F_{-})=qd\times E = p\times E
 \end{equation} 
$$
$$
 \begin{equation} 
 F=(p\cdot \nabla)E 
 \end{equation} 
$$

# Chapter 5:

# Chapter 6:

## Ferromagnetism:
![[Pasted image 20260502115343.png]]

## Formulas:
$$
 \begin{equation} 
 B=\mu_{0}(H+M)=\mu_{0}(1+\chi_{m})H = \mu H
 \end{equation} 
$$
$$
 \begin{equation} 
 \mu_{r}=\frac{\mu}{\mu_{0}}=1+\chi_{m} 
 \end{equation} 
$$
$$
 \begin{equation} 
 M=\chi_{m}H 
 \end{equation} 
$$
$$
 \begin{equation} 
 H=\frac{1}{\mu_{0}}B-M 
 \end{equation} 
$$
$$
 \begin{equation} 
 \nabla \times H=J_{f} \ \ \ \text{ or } \ \ \ \oint_{}^{} H \cdot dl = I_{f_{enc}}
 \end{equation} 
$$
$$
 \begin{equation} 
 J_{b}=\nabla \times M=\nabla \times(\chi_{m}H)=\chi_{m}J_{f} 
 \end{equation} 
$$
$$
 \begin{equation} 
 K_{b}=M\times \hat{n} 
 \end{equation} 
$$
$$
 \begin{equation} 
 \nabla \cdot J_{b}=0 
 \end{equation} 
$$
$$
 \begin{equation} 
 F=\nabla(m\cdot B) 
 \end{equation} 
$$
$$
 \begin{equation} 
 T=m\times B 
 \end{equation} 
$$

