# 1-2 Den røde tråden
![[Pasted image 20260107091409.png]]

# 1-3 Bølger intro
Når har en bølge i en fjær f.eks som svinger, så er "nullpunktene" eller der som materialet ikke svinger kalt for  **node**, mens punktet på linjen hvor har maksimal utsving er **anti-node**. 

Lengden på bølgen kan beskrives med **bølgelengden**, som er avstand fra to like punkter, som topp til topp. Bruker som oftest $\lambda$ for dette.

# 1-4 Bølgelikningen - utledning

VI tar for oss et lite utsnitt av en bølge og ser på kreftene i y retning på endene.
T = snorkraft, $\mu$ = massetetthet \[kg/m]
$\implies m=\mu \cdot \Delta x$
For små vinkler får vi:
$$
 \begin{equation} 
 F_{y}=-T\sin \theta+T\sin(\theta+\Delta \theta) \approx T\Delta \theta 
 \end{equation} 
$$
For å fjerne $\Delta \theta$ gjør vi triks med å si
$$
 \begin{equation} 
 \tan \theta= \frac{\partial y}{\partial x}\implies \frac{1}{\cos^2\theta} \frac{d\theta}{dx}= \frac{\partial^2y}{\partial x^2} 
 \end{equation} 
$$
som for små $\theta$ og $\Delta x\to 0$:
$$
 \begin{equation} 
 \Delta \theta = \Delta x \frac{\partial^2y}{\partial x^2} 
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies m\cdot a=F \implies \mu \Delta x \frac{\partial ^2y}{\partial t^2}= T\Delta x \frac{\partial^2y}{\partial x^2}
 \end{equation} 
$$

$$
 \begin{equation} 
 \frac{\mu}{T} \frac{\partial^2y}{\partial t^2}=\frac{\partial^2y}{\partial x^2} \implies f(x\pm ct) \ \ \ \ \text{der} \ \ \ c=\sqrt{ \frac{T}{\mu} }
 \end{equation} 
$$
der $c$ har dimensjon m/s og blir ofte skrevet om på formen
$$
 \begin{equation} 
 \frac{1}{v^2} \frac{\partial^2y}{\partial t^2}=\frac{\partial^2y}{\partial x^2}
 \end{equation} 
$$


# 1-5