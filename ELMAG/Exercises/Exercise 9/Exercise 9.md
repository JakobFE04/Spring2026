# 1)
## a)
In 1D: Charge density gives how much charge there is over a line per unit length, while the line current density gives how much charge is passing over a given time per unit length (current per unit length).
In 2D: Charge density gives how much charge theres is over a surface per unit area, while the surface current density describes how much of the current running parallel to the flow is going through a "ribbon" on said surface, giving a current per unit width. 
In 3D: Charge density gives how much charge there is in a bulk per unit volume, while the volume current density describes how much of the current running parallel to the flow is going through a "tube" in said bulk, giving a current per unit area.  

## b)
For a wire: Mobile charges are described with $\lambda$ meaning the density of charges moving across the wire, correlating to the current.
For a thin conducting sheet: Mobile charges are described with $\sigma$ meaning the density of charges moving across the sheet, correlating to the current.
For a bulk conducting material: Mobile charges are described with $\rho$ meaning the density of charges moving through the material, correlating to the current.

## c)
For a wire: $I = \lambda v$ is the current for a mobile charge.
For a thin conducting sheet: $K = \sigma v$ is the current for a mobile charge.
For a bulk conducting material: $J = \rho v$ is the current for a mobile charge.

## d)
For a wire:
$$
 \begin{equation} 
 B(r)=\frac{\mu_{0}}{4\pi} I \int_{}^{} \frac{dl\times \hat{r}}{r^2} 
 \end{equation} 
$$
For thin conducting sheet:
$$
 \begin{equation} 
  B(r)=\frac{\mu_{0}}{4\pi} \int_{}^{} \frac{K(r')\times \hat{r}}{r^2} d\alpha  
 \end{equation} 
$$
For a bulk conducting material:
$$
 \begin{equation} 
   B(r)=\frac{\mu_{0}}{4\pi} \int_{}^{} \frac{J(r')\times \hat{r}}{r^2} d\tau 
 \end{equation} 
$$
## e)
For 1D, the mobile and constant charge are the same expression: $I = \lambda v$, while

|              |        **2D**         |               **3D**               |
| :----------: | :-------------------: | :--------------------------------: |
| **Constant** | **$K=\frac{dI}{dl}$** | **$J=\frac{dI}{d\alpha_{\perp}}$** |
|  **Mobile**  |     $K=\sigma v$      |             $J=\rho v$             |
differ between the constant and mobile charge flow expressions.

## f)
$\lambda$, $\sigma$ and $\rho$ can appear in both electrostatics and magnetostatics as forms of representation of charges in 1D, 2D and 3D respectively. However they differ in terms of how the charges are over time, we assume constant charges densities in electrostatics while mobile in magnetostatics.

# 2)
## a)
If more charge flows out through the surface of a volume, then the charge inside the volume will decrease.

## b)
The flux through the surface S is given as
$$
 \begin{equation} 
 \oint_{S}^{}J \cdot d\alpha = - \frac{\partial }{\partial t} \int_{V}^{} \rho \ d\tau
 \end{equation} 
$$
and must be equal to the negative change of charge density over time. Using the divergence theorem we get:

$$
 \begin{equation} 
  \int_{V}^{} (\nabla \cdot J) d\tau = - \frac{\partial}{\partial t} \int_{V}^{}\rho \ d\tau
 \end{equation} 
$$
Which should be the same for any volume so we can remove the integrals and get:
$$
 \begin{equation} 
 \nabla \cdot J = - \frac{\partial \rho}{\partial t}
 \end{equation} 
$$

## c)
The divergence of the current through the volume is equal to the negative change of charge density through time. This means that the rate of the current's flux through the volume is the same as the change of charge density through time.

## d)
In magnetostatics, we work with steady currents that give constant magnetic fields (aka magnetostatics.) This means that the change of charge density is zero.
$$
 \begin{equation} 
 \implies \nabla \cdot J = - \frac{\partial \rho}{\partial t} =0
 \end{equation} 
$$
## e)
If the divergence of the volumetric current is not 0 in some region, the magnetic field created would not be constant. This could be for example an inductor given AC current, making the current wary from time and frequency.


# 3)
## a)
$$
 \begin{equation} 
 J = \frac{dI}{d\alpha_{\perp}} = \frac{I}{ab}
 \end{equation} 
$$
## b)
$$
 \begin{equation} 
 I=\int_{S}^{}J(x)  \cdot d\alpha = \int_{0}^{b}\int_{0}^{a}kx  \ dxdy = \frac{k}{2}a^2b
 \end{equation} 
$$

# 4)
![[Pasted image 20260317150513.png]]


# 5)
Using the formula for magnetic force from last task for an infinite long wire, the angles $\theta_{1}$ and $\theta_{2}$ becom $-\frac{\pi}{2}$ and $\frac{\pi}{2}$ respectively, leading to:

$$
 \begin{equation} 
 B(s)=\frac{\mu_{0}I}{2\pi s} \hat{k} 
 \end{equation} 
$$
By using the right hand rule to determine the direction of the two magnetic fields and summingen them we can calculate the magnetic fields and then use Lorentz force law for line integral over a unit length L to find the force per unit length:
![[Pasted image 20260317150536.png]]
Since the currents are in the opposite direction, they will repell eachother.