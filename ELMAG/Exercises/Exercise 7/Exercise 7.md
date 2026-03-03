# 1)
## a)
In this scenario, the free charges are the charges on the surface of the parallell-plate capacitor connected to the battery, while the bound charges are the the charges that from the dielectric material's perspective are induced from the external field created by the free charges.

## b)
Gauss's law reads
$$
 \begin{equation} 
 \epsilon_{0} \nabla \cdot E = \rho = \rho_{b}+\rho_{f}=-\nabla \cdot P + \rho_{f}
 \end{equation} 
$$
which in terms of electric displacement reads:
$$
 \begin{equation} 
 \nabla \cdot D = \rho_{f} \ \ \ \\ \ \ | \ \ D=\epsilon_{0}E + P 
 \end{equation} 
$$
which in integral form reads
$$
 \begin{equation} 
 \oint_{}^{}D \cdot da = Q_{f_{enc}} 
 \end{equation} 
$$
and shows the relation between the electric displacement and the free charges enclosed in the volume. The bound charges are baked into $P$ which can be zero while stile having an electric displacement because of free charges!

## c)
Going through Gauss's law for E-fields when dielectrics are present leads to having multiple different areas you have to consider depending on where you place you Gaussian area. But using Gauss's law for D is often simpler as we only have to consider the surface area of the volume and the enclosed free charges which we controll. Then you can easily calculate E-field again by looking at the polarization of the material in different areas, and using:
$$
 \begin{equation} 
 D=\epsilon_{0}E+P 
 \end{equation} 
$$


# 2)
![[Pasted image 20260227143426.png]]
# 3)
## a)
$\chi_{e}$ is a scalar factor of how much the total electric field (external+internal) effects the polarization of the material. When an E-field is applied externally to a material, the nucleus inside the atoms of the material are shifted with the E-field while the electron cloud is shifted the opposite direction. This creates small dipoles across the material leading to polarization. If $\chi_{e}$ is large, that means the material is easilly polarized by external E-fields.

## b)
Inserting the polarization for a linear dielectric into the definition of electric displacement we get:
$$
 \begin{equation} 
 D=\epsilon_{0}E+\epsilon _{0}\chi_{e}E 
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies D=\epsilon_{0}(1+\chi_{e})E = \epsilon E 
 \end{equation} 
$$
where $\epsilon=\epsilon_{0}(1+\chi_{e})$ accounts for the permittivity of the material, while the relative permittivity or the dielectric constant looks at the ratio of the permittivity of the material compared to vacuum/free space:
$$
 \begin{equation} 
 \epsilon_{r}=\frac{\epsilon}{\epsilon_{0}} =(1+\chi_{e})
 \end{equation} 
$$
So $\epsilon$ shows the realistic permittivity of a material used when calculating, while $\epsilon_{r}$ shows the characteristic permittivity ($\chi_{e}$) or how much a given material's structure effect the permittivity of it.

## c)
if $\epsilon_{r} \gg 1$:
1.  THe polarization P inside the material will be very large, as $P=\epsilon_{0}\chi_{e}E$, and $\chi_{e}$ is the only factor that can make $e_{r}\gg 1$.
2. The electric field in the material will be smaller than in the vaccum, as $\epsilon\gg \epsilon_{0}$, which when using: 
$$
 \begin{equation} 
 E= \frac{D}{\epsilon _{0} } \ \ \\ \\ \ \ \text{ or   } \ \ \ \ \ E=\frac{D}{\epsilon }
 \end{equation} 
$$
	for electric field in vacuum and in the dielectric material will lead to E-field in vacuum to be larger.
3. Large dielectric constants is usefull in capacitors as the capacitance of a capacitor is increased by a factor of the dielectric constant if replacing vacuum between the plates: 
$$
 \begin{equation} 
 C=\epsilon_{r}C_{\text{vac}} 
 \end{equation} 
$$
	which is why this is a common way to beef up a capacitor.

# 4)
![[Pasted image 20260227161216.png]]
![[Pasted image 20260227161222.png]]

# 5)
## a)
Common values according to Wikipedia:
Air: 1.000 589 86
Paper: 1,4
Natural rubber: 7
Water: 87.9 -> 55.5 depending on temp
(https://en.wikipedia.org/wiki/Relative_permittivity)
And some more from googling:
Glass: 3.8 - 14.5
Plastics: 2-4
(https://www.specialchem.com/plastics/guide/dielectric-constant)
and Barium titanate: Up to 10,000
(https://www.academia.edu/130349280/Barium_titanate_and_the_dielectric_response_of_polystyrene_based_composites)

## b)
For what i found for water and glass, $\sqrt{ 3.8 }=1.94$ for glass and $\sqrt{ 55.5}=7.44$ which is alot higher then the typical optical values, but this all depends on alot of factors like wavelength and temperature of the material.

## c)
- For standard dielectrics no, but for some metals it seems to be possible.
- "Plasmonic metal nanoparticles
	Plasmonic metal nanoparticles are light-harvesting materials that
	interact with visible light through the excitation of localized surface
	plasmon resonance. LSPR is established when light of
	wavelengths longer than the size of the metal nanoparticles causes
	a resonant, collective oscillation of the free electrons in the metal
	nanoparticles. This physical process allows the nanoparticles to
	collect the energy of visible light, concentrate it near the surface of
	the particles, and ultimately convert light energy into the energy of
	excited charge carriers."
- If I understood correctly, its plasmon exitation, but I'm not explaing that, => https://www.proquest.com/docview/3225878885/fulltextPDF?accountid=12870&sourcetype=Scholarly%20Journals

# Question I have:
## Is anything of question 5 relevant for exams, as in lecture 27.10 it was mentioned that refractive index will not be in exams?
