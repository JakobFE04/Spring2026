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
## Bound charges:
$$
 \begin{equation} 
 \sigma_{b}=P\cdot \hat{n} 
 \end{equation} 
$$
$$
 \begin{equation} 
 \rho_{b}=-\nabla \cdot P 
 \end{equation} 
$$
## Dielectrics:
$$
 \begin{equation} 
 D=\epsilon_{0}E+P 
 \end{equation} 
$$
$$
 \begin{equation} 
 \nabla \cdot D=\rho_{f}  \ \ \text{or} \ \ \oint_{}^{} D\cdot d\alpha = Q_{f_{enc}} \ \ \text{Gauss's Law}
 \end{equation} 
$$
$$
 \begin{equation} 
 P=\epsilon_{0}\chi_{e}E \implies D=\epsilon E \ \ \ \ \epsilon=\epsilon_{0}(1+\chi_{e})
 \end{equation} 
$$
$$
 \begin{equation} 
 \epsilon_{r}=\frac{\epsilon}{\epsilon_{0}}=1+\chi_{e} 
 \end{equation} 
$$
## Work with diele|ctrics:
$$
 \begin{equation} 
 W=\frac{1}{2}\int_{}^{}D\cdot E \ d\tau 
 \end{equation} 
$$
# Chapter 5:
$$
 \begin{equation} 
 F_{mag}=Q(v\times B) \implies F=Q[E+(v\times B)] \ \ \text{Lorntz force law} 
 \end{equation} 
$$
$$
 \begin{equation} 
 W_{B}=0 \ \ \text{Magnetic force do not work} 
 \end{equation} 
$$
## Currents:
For 1D, the mobile and constant charge are the same expression: $I = \lambda v$, while

|              |        **2D**         |               **3D**               |
| :----------: | :-------------------: | :--------------------------------: |
| **Constant** | **$K=\frac{dI}{dl}$** | **$J=\frac{dI}{d\alpha_{\perp}}$** |
|  **Mobile**  |     $K=\sigma v$      |             $J=\rho v$             |
differ between the constant and mobile charge flow expressions.


$$
 \begin{equation} 
 F_{mag} = I \int_{}^{}(dl\times B) \text{ or } \int_{}^{}(K\times B) \ d\alpha  \text{ or } \int_{}^{}(J\times B) \ d\tau 
 \end{equation} 
$$
## Continuity equation
$$
 \begin{equation} 
\nabla \cdot J = -\frac{\partial \rho}{\partial t} = 0 \text{ for magnetostatics}
 \end{equation} 
$$
## Magnetic field of steady current
$$
 \begin{equation} 
 B(r)=\frac{\mu_{0}}{4\pi}\int_{}^{} \frac{I\times \hat{r}}{r^2} \ dl' = \frac{\mu_{0}}{4\pi}I\int_{}^{} \frac{dl'\times \hat{r}}{r^2} 
 \end{equation} 
$$
### Magnetic field a distance s from a straight wire:
![[Pasted image 20260502153009.png]]
$$
 \begin{equation} 
 B=\frac{\mu_{0}I}{4\pi s}(\sin\theta_{2}-\sin \theta_{1}) \implies B=\frac{\mu_{0}I}{2\pi s}\hat{\phi}
 \end{equation} 
$$
Force per unit of two wires next to each other:
$$
 \begin{equation} 
 \frac{F}{L}=\frac{\mu_{0}}{2\pi} \frac{I_{1}I_{2}}{d} 
 \end{equation} 
$$
## Amperes law:
$$
 \begin{equation} 
 \oint_{}^{}B \cdot dl = \mu_{0} I_{enc} \implies \nabla \times B=\mu_{0}J
 \end{equation} 
$$
# Chapter 6:
## Magnetic torque and force
$$
 \begin{equation} 
 T=m\times B 
 \end{equation} 
$$
$$
 \begin{equation} 
 F=\nabla(m\cdot B) 
 \end{equation} 
$$
$$
 \begin{equation} 
 F=I \oint_{}^{}(dl\times B)=0 
 \end{equation} 
$$
## Bound currents:
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

## Auxiliary field H:
From Maxwells equation $\nabla \times B=\mu_{0}J$ and $J=J_{f}+J_{b}$:

$$
 \begin{equation} 
 H=\frac{1}{\mu_{0}}B-M 
 \end{equation} 
$$

$$
  \begin{equation} 
 \nabla \times H=J_{f} \ \ \ \text{ or } \ \ \ \oint_{}^{} H \cdot dl = I_{f_{enc}} \ \ \text{Ampere's Law}
 \end{equation} 
$$
## Linear and nonlinear media:

$$
 \begin{equation} 
 M=\chi_{m}H 
 \end{equation} 
$$
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

## Ferromagnetism:
![[Pasted image 20260502115343.png]]


