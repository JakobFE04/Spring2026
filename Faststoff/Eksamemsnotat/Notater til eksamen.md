 
# 1 - Bølger og bølgefunksjoner (1-3)
## Ulike former for bølger 
Mekaniske bølger:
- Trenger et "medium" for å propagere
	- Eks:
		- Streng
		- Vannbølge
		- Lydbølge

Elektromagnetisk bølger
- Tregner  **IKKE** et "medium" for å propagere
	- Eks:
		- Synlig lys
		- Radiobølger
		- Røntgenstrålinger

Deler hvordan bølgen beveger seg i to:
- Transverse bølge: Beveger seg opp og ned for å gå sidelengs.
	- Vannbølger er transversale hovedsakelig.
	- Alle EM bølger er transversale i vakum.
- Longitudinal bølge: Komprimerer og strekker seg i samme retning som bevegelsen.
	- Lydbølge beveger seg longitudinalt
	- EM bølger kan være longitdunale i hvisse stoffer.

## Bølgelikninga i ein dimensjon 
$$
 \begin{equation} 
 \frac{1}{v^2} \frac{\partial^2y}{\partial dt^2}=\frac{\partial^2y}{\partial dx^2} 
 \end{equation} 
$$
Alle bølgefenomener vil tilfredstille denne differensial likningen.
## Harmoniske bølger 
Harmonisk bølge
$$
 \begin{equation} 
 y(x)=A\cos(kx-\omega T+\phi) = \mathrm{Re}\{Ae^{i(kx-\omega t+\phi)}\}
 \end{equation} 
$$
Der $k$ er "romfrekvensen" eller bølgetallet, hvor ofte noe skjer i rom, $k= \frac{2\pi}{\lambda} [\frac{1}{meter}]$
Der $\omega$ er "vinkelfrekvensen", $\omega =2\pi f \ [\frac{radianer}{sekund}]$
Der $f$ er "Frekvensen", hvor ofte noe skjer i tid, $f=\frac{1}{T} \ \left[ \frac{1}{sekund} \right]$
Og $T$ er "Perioden", $T=\frac{1}{\lambda}$

## Ståande bølger 
Stående bølger vil si bølger som kun "svinger opp og ned" eller transverse bølger, altså at det ikke er noen longitudinale bølger eller at den beveger seg fram og tilbake i rommet. Kan oppnå ved å feste fast endepunktene i en fjær som svinger eller bølgefunksjonene i en uendelig kvantebrønn over tid.

## Bølgepakker 
Max Plank som kom med ideen om at lys kom oppgitt som bølgepakker. Bølgepakker består av flere bølger avgrenset i rom og tid (lokalisert) som beskriver sannsynligheten for å finne et foton eller et elektron med en gitt energi som Einstein fant ved fotoelektrisk effekt: $E = \hbar \omega$. 

## Schrödingerlikninga 
$$
 \begin{equation} 
  i\hbar \frac{\partial \Psi(x,t)}{\partial t}=\left( -\frac{\hbar^2}{2m} \frac{\partial^2}{\partial x^2}+ U(x,t) \right)\Psi(x,t)
 \end{equation} 
$$
Som dersom:
$$
 \begin{equation} 
 \Psi(x,t) =e^{-i\omega t}\psi(x)
 \end{equation} 
$$
Gir den tidsuavhengige S.E:
$$
 \begin{equation} 
 \hbar \omega \psi(x)=\left( -\frac{\hbar^2}{2m} \frac{\partial^2}{\partial x^2}+U(x) \right)\psi(x) \implies \hat{H}\psi(x)=E\psi(x)
 \end{equation} 
$$
Der $\Psi$ er en funksjon som gir sannsynligheten for å finne en partikkel i punktet x ved tiden t. $U(x,t)$ er et mål på potensialet ved posisjon x og tiden t. $\hat{H}$ er den Hamiltonske operatoren Vi kan bruke S.E. til å beregne for eksempel partikkel i brønn.
Generell løsning:
$$
 \begin{equation} 
 \Psi(x,t)=\int_{-\infty}^{\infty}dk \ \Phi(k)e^{i(kx-\omega t)} 
 \end{equation} 
$$
Der $e^{i(kx-\omega t)}$ er en planbølge og $\Phi(k)$ er faktoren for amplituden til planbølgen. 

## Bølgefunksjonen 
Hva mener han her? $\Psi$ liksom? Ja!^^^

## Heisenbergs uskarpleiksrelasjon 
Heisenbergs usikkerhets prinsipp sier at det er umulig å måle nøyaktig posisjon og bevegelse for en partikkel. Dette er beskrevet ved formelen:
$$
 \begin{equation} 
 \Delta p\Delta x = \sigma_{p}\sigma_{x}\geq \frac{\hbar}{2} 
 \end{equation} 
$$
Det vil si at ting kan oppføre seg både som bølge og som en partikkel, men at en ren bølge kan en ikke måle posisjonen til, og at en ren partikkel kan ikke måle bevegelsesmengden ($p=k \hbar$). 

## Dobbeltspalteeksperimentet 
Viser sammenhengen mellom kvanteobjekt, bølger og partikler. Dersom sender inn rene partikler gjennom 2 spalter så vil få ingen mønster. Men hvis du sender inn en bølge vil du få et interferens mønster som gir et sett med striper. Dersom du sender et kvante objekt så vil det oppføre seg som en bølge til det blir obeservert og få en gitt posisjon...,

![[Pasted image 20260427140550.png|500]]

# 2 - Kvantebrønner (4-8)
## Bundne og spreiande tilstandar 
![[Pasted image 20260427142944.png|400]]
![[Pasted image 20260427143003.png|400]]

## Uendeleg djup kvantebrønn i 1D 
Definerer et område enten fra 0 til L eller -a til a som har ingen potensiale når er innenfor, men uendelig stort når er utenfor området. Dermed for å at en partikkel skal kunne befinne seg utenfor området, må det ha uendelig energi for å komme seg "over veggen" som ikke går  ann. Løsningne for S.E må derfor ligge innenfor området og være $\psi(x)=0$ for x utenfor området. Vi kan løse TISE for inne området og få f.eks for x=0->L:
$$
 \begin{equation} 
 \psi(x)= \sqrt{ \frac{2}{L} }\sin\left( \frac{n\pi}{L}x \right)
 \end{equation} 
$$
Og får da at:
$$
 \begin{equation} 
 E = \frac{(n\pi \hbar)^2}{2mL^2} \implies E_{min}=\frac{\pi^2\hbar^2}{2mL^2} \implies E_{n}=n^2 \cdot E_{min} 
 \end{equation} 
$$

## Målepostulatet 
Målepostulatet sier to ting:
1. Vi vil __kun__ måle en av egenverdiene for en gitt måling. F.eks. hvis vi prøver å måle energien (bevegelsesmengde) vil en få enten $E_1, E_{2}, E_{3}\dots$ 
   Sannsynligheten for å måle en gitt energi $E_i$ er $p_{i}=|\alpha_{i}|^2=\int_{}^{}\Psi_{i}^*\Psi \ dx$
   Det vil si hvor stor projeksjon $\Psi_{i}$ er i $\Psi$.
   ![[Pasted image 20260429144112.png]]
2. Etter at utfallet $q_{i}$ er målt blir tilstanden til systemet den målte tilstanden: $$
 \begin{equation} 
 \psi(x)=\psi_{i}(x) \implies\text{Bølgefunksjon kollaps} 
 \end{equation} 
$$
![[Pasted image 20260429144431.png|500]]

## Endeleg kvantebrønn 
I en endelig kvantebrønn vil det være mye likt med en uendelig, men nå er potensialet for å slippe ut av brønnen en satt verdi. Dette kan brukes som en modell for et elektron bundet til en atomkjerne hvor den må få nok energi til å slippe fri fra atomkjernen/kvantebrønnen. Vi vil lete etter bundede tilstander:
![[Pasted image 20260501092530.png]]
- Dersom et kvanteobjekt oppfinner seg i det klassiske forbudt området (Region I eller III men energi mindre enn brønnen) så vil den ha negativ kinetisk energi.
- Bølgefunksjonen i K.F.O vil bli dempet, jo dypere brønnen er til den går mot 0 for en uendelig kvantebrønn.
Vi vil få to typer løsninger:
- Trigonometriske løsninger for region II
- Eksponentielle løsninger for region I og III
![[Pasted image 20260501093903.png]]
![[Pasted image 20260501093729.png]]

## Tunnellering 
![[Pasted image 20260501101259.png|500]]
Kan finne kvantepartikler selvom klassisk fysikk sier har for lite energi til å komme over barrieren.

## Perturbasjonsteori
Tidsuavhengig perturbasjonsteori for ikke-degenererte system er det vi har sett på.
- Systematisk metode til å finne tilnærmet løsninger til perturberte kvantemekaniske system.
	- Perturberte system vil si små endringer fra "perfekte" kjente system, som endring av potensialet inni en kvantebrønn er en form for perturbasjon.
**Krav for å kunne anvende pert. teori:**
- Perturbasjon er liten, jo mindre jo bedre løsninger
- Løsningene for upertuberte systemet er kjent.
Vi vil altså finne
$$
 \begin{equation} 
 \hat{H}\psi_{n}=E_{n}\psi_{n} \ , \ \ \text{der }\hat{H} \text{ er Hamiltionian for pert. system} 
 \end{equation} 
$$
Vi kjenner:
$$
 \begin{equation} 
 \hat{H}^{(0)} \psi_{n}^{(0)} = E_{n}^{(0)}\psi_{n}^{(0)}
 \end{equation} 
$$
Og får f.eks at:
$$
 \begin{equation} 
 \hat{H} = \hat{H}^{(0)}+\hat{u}_{pert} \ \ \text{ der }\hat{u}_{pert}=\begin{cases}
 u_{0} \ \text{for } x<|b| \\
 0 \ \text{ for} x > |b|
 \end{cases}
 \end{equation} 
$$
i et system som
![[Pasted image 20260429145542.png]]

Perturbasjonsteorien gir oss den totale energien og bølgeeffekten som summer av ulike termer:
$$
 \begin{equation} 
 E_{n}=E_{n}^{(0)}+E_{n}^{(1)}  +E_{n}^{(2)} +E_{n}^{(3)} +\dots
 \end{equation} 
$$
_(Total E for pert. system = Eksakt energi for upert. system + korreksjonsledd pga perturbasjon....)_
$$
 \begin{equation} 
 \implies \psi_{n}= \psi_{n}^{(0)} +\psi_{n}^{(1)} +\psi_{n}^{(2)} +\psi_{n}^{(3)} +\dots
 \end{equation} 
$$

# 3- Atom og bindinger (9-11)
## Kvantebrønn i 3D (partikkel i boks) 
Likt en endelig kvantebrønn men nå med 3 dimensjonsakser og kvantetall $(n_{i})$. Får da:
$$
 \begin{equation} 
 \psi(x,y,z)=\sqrt{ \frac{8}{a^3} } \sin\left( \frac{n_{x}\pi x}{a} \right) \sin\left( \frac{n_{y}\pi y}{a} \right) \sin\left( \frac{n_{z}\pi z}{a} \right) 
 \end{equation} 
$$
$$
 \begin{equation} 
 \implies E_{n_{x}n_{y}n_{z}} =\frac{\pi^2\hbar^2}{2ma^2}(n_{x}^2+n_{y}^2+n_{z}^2)
 \end{equation} 
$$
Bølgefunksjonen i 3D og tid:
$$
 \begin{equation} 
 \Psi(x,y,z,t)=\psi(x,y,z)e^{-i\omega t} 
 \end{equation} 
$$
NB! $E=\hbar \omega$ gjør at bølgefunksjoner med høyere energi vil spinne raskere, grunntilstanden er 4 ganger så treg som neste bølgefunksjonen som har 4 ganger så mye energi. Forskjellen i frekvensen til de to bølgefunksjonene (rød og grønn) gir frekvensen til sannsynlighetsfordelingen (blå og lime ball).
![[Pasted image 20260501105253.png]]


## Degenerasjon 
I en 3D kvantebrønn med alle sider som har lengde a, vil vi få:
$$
 \begin{equation} 
 E_{112}=E_{121}=E_{211} \ \text{ , alle vil ha en faktor 6} 
 \end{equation} 
$$
Men! 
$$
 \begin{equation} 
 \psi_{112} \neq  \psi_{121} \neq \psi_{211}
 \end{equation} 
$$
Når flere kvantetilstander svarer til samme energi, kaller vi det for **degenererte tilstander**. Dette kommer som resultat av symmetri i systemet. Men vi vet ikke hva $\psi$ er basert på energinivået når vi har degenrerte tilstander.
![[Pasted image 20260501110507.png|500]]


## Hydrogenatomet 
Hydrogen atomet regner vi med ulike kvantetall:
$$
 \begin{equation} 
 \psi_{nlm}(r,\theta,\phi) 
 \end{equation} 
$$
- n - hoved-kvantetall: Relaterer til total energi, (langt fra kjernen) -> 1,2,3,4
- l - det orbitale kvantetallet: Relaterer til drivmoment (farten spinner rundt) -> 0,1,2,3,4,...,n-1
- m - magnetiske kvantetallet: relaterert til z-komponenten til drivmomentet, eller retningen til drivmomentet. -> -l,...0,...,l eller -(n-1),...,0,...n-1
![[Pasted image 20260501111304.png]]

Kan tegne energi og bølgefunskjonene for 1D ved bruk av rotasjonssymetrisk potensiale uten uendelige grenser -> Coulomb potensiale:
![[Pasted image 20260501111604.png]]

##### Tilstander i hydrogen-atomet:
![[Pasted image 20260501111841.png|500]]

## Det periodiske system 
![[Pasted image 20260501112116.png|500]]
![[Pasted image 20260501112842.png|500]]
![[Pasted image 20260501112526.png|500]]
Alle trinnene har samme form, men $m$ endrer orienteringen på "blobbene"/Orbitalene.
- Flere elektron i forskjellige orbitaler i superposisjon i stoffer!


## Elektronkonfigurasjon 
Måten elektroner fordeler seg i orbitaler.
![[Pasted image 20260501113925.png]]

Notasjon: Antall i eksponenten, tilstanden er potensen.
- Oksygen (O): $(1s^2)2s^22p^4$ => parantes vanligvis ikke med, tilsvarer Helium (første edelgass), så sier har $^2$ 2s orbitaler + $^4$ 2p orbitaler som lander da på oksygen!
- Magnesium (Mg): $3s^2$ => fylte opp til Ne = $2s^22p^6$ også $3s^2$ til.
- For edelgeass nr n: $ns^2np^6$ er en ekstra stabil konfigurasjon fordi da er alle orbitalene samlet i en stor ball og vil være vanskelig trekke ut et elektron eller tiltrekke et nytt fordi elektronskyen "skjermer" den ladde atomkjernen. Lite elektriske krefter for andre elektroner å binde seg til.
## Bindingar i faste stoff 
![[Pasted image 20260501115800.png|500]]

## Dobbel kvantebrønn 
![[Pasted image 20260501132933.png|500]]
![[Pasted image 20260501135213.png|500]]
![[Pasted image 20260501135147.png|500]]


## Det interatomære potensiale
![[Pasted image 20260501141137.png]]
$U(r)$ blir veldig stor for små $r$ fordi det krever veldig høy energi å plassere atomene veldig
tett. Her frastøter atomene hverandre fordi de ikke kan okkupere nøyaktig det samme området samtidig. Når $r$ er veldig stor går $U(r)$ mot 0 fordi atomene er for langt unna hverandre til at de påvirker hverandre. For visse $r$ rundt $r_{0}$ er $U(r)<0$, som betyr at det er energimessig gunstig for atomene å binde seg. Vi får negativ $U(r)$ fordi vi også har en elektrostatisk tiltrekning mellom atomene. Dette kan enkelt forstås i forbindelse med ionebindinger, men også for netto nøytrale atomer er tiltrekningen elektrostatisk fordi tettheten av elektroner rundt atomkjernen vil variere.
$r_{0}$ representerer bindingslengden, og $U_{0}$ representerer bindingsenergien.

# 4 - Krystallografi og fonon (12 - 15 & 22-23)
## Faste stoff 
![[Pasted image 20260501132933.png|500]]
Ulike typer faste stoff:
![[Pasted image 20260501114819.png]]
Ordnet fast stoff: Krystallinske  Mellomting: flere systematiske, lokal orden  Uordnet fast stoff:                                                                                                                                    "tilfeldig" ordning


## Krystallar, basis og gitter 
### Basis + gitter = krystall
- Atomer stoffet er sammensatt av. (Basis)
- Mattematiske punkt kan plassere basiser. (Gitter)
- Sammensetting av basis i gitter. (Krystall)


## Einingsceller og Bravaisgitter
### Enhetscelle:
- Minste byggeklossen som beskriver gitteret
- Kan __ikke__ roteres, og har 1/4 eller 1/8 elektron i hjørnene
- Kjenner til hele krystallen om en kam enhetscellen
- Skal fylle rommet uten hull
Kan ha primitiv enhetsceller og konvensjonelle:
Konvensjonell:
- "Vanlige"
- Kan inneholde flere gitterpunkter
Primitve:
- Inneholder bare et gitterpunkt
- Har 1/4 eller 1/8 deler av gitterpunkt.
##### Eks: SCC
![[Pasted image 20260501152948.png]]
##### EKS: BCC
![[Pasted image 20260501153254.png|500]]
##### Eks: FCC
![[Pasted image 20260501151059.png]]
### Bravaisgitter
Et Bravais-gitter et et matematisk gitter hvor man kan bevege seg langs translasjonsvektorene
og treffe alle punkt i gitteret. Gitteret ser identisk ut fra alle gitterpunkt. Man kan finne Bravais
gittere i flere dimensjoner ved å se på de mulige symmetrioperasjonene. Vi finner for eksempel i
3D at vi har 14 ulilke Bravais-gittere. Alle repeterende krystaller i 3D vil tilhøre ett av disse.

## Kubiske gitter (fcc, bcc, sc) 
- Primitiv / SC: Kun i hjørnene av kube
- Body centered / BCC: Hjørner og i midten
- Face centered / FCC: 5 terning på alle sider (4 hjørner 6 i midten på sidene)
![[Pasted image 20260501150635.png]]

## Miller indeksar 
![[Pasted image 20260501153635.png|500]]
![[Pasted image 20260501153741.png|500]]
## Wigner-Setiz cella
Systematisk måte å finne primitve enhetsceller
- Finnes ved å konstruere vektorer fra et gitt gitterpunkt til "alle andre" for deretter å konstruere linjer (2D) eller plan (3D) på "midtpunktet" til disse vektorene.
- Første firkant/boks blir 1. orden W-S cellen
- Så øker til 2. orden når tar med resten av trekantene
- Arealet av alle ordnene er like.
![[Pasted image 20260501154133.png]]
##### Eks BCC:
![[Pasted image 20260501154156.png]]

 
## Reelt og resiprokt gitter
![[Pasted image 20260501154456.png|500]]

Når vi har en linje med gitterpunkt bortover, så vil de tilsvare en romlig frekvens som varier med posisjon $x$ som vi kan finne ved å ta fourier av reele rommet! Kan også finne ved **diffraksjon**, som vil si at om vi sender f.eks. røntgenstråling (bølger) på krystallen så vil det føre til interferens. Mønsteret får ut da er det resiproke rommet.

- Reelt rom avstand $a$ => Resiprokt rom $\frac{2\pi}{a}$
- SC => SC
- FCC => BCC
- BCC => FCC

![[Pasted image 20260501162346.png|500]]
![[Pasted image 20260501162750.png|500]]

## Fonon
![[Pasted image 20260501163331.png|500]]
![[Pasted image 20260501163419.png]]
![[Pasted image 20260501163438.png]]

## Debyemodellen
![[Pasted image 20260501163457.png]]


## Varmeledning, varmekapasitet og termisk ekspansjon
![[Pasted image 20260501163518.png]]
![[Pasted image 20260501163528.png|500]]


# 5 - Kronig-Penney modellen (16-19)
## Kronig-Penney modellen – som modell for 1D gitter 
![[Pasted image 20260501173143.png]]

## Forenklingar i Kronig-Penney modellen 
Vi forenkler Kronig-Penney modellen ved å ha rektangulære potensialer istedet for Coulomb potensialer som går i uendelig i begge retninger. 

## Bloch’s teorem 
Energi egentilstandene (bølgefunksjonene) i en perfekt krystall vil ha formen:
$$
 \begin{equation} 
 \psi(x)=e^{ikx}u(x) 
 \end{equation} 
$$
Der $e^{ikx}$ er en plabølge.
Og $u(x)$ er en funksjon med samme periodisitet som krystallen ($u(x)=u(x+R)$).
## Løysingane til Kronig-Penney modellen 
![[Pasted image 20260501174117.png|500]]

## Dispersjonsrelasjonen, E(k) 
Dispersjonsrelasjonen er navnet på funksjonen for E(k). 
$$
 \begin{equation} 
 k = \frac{2\pi}{\lambda} \implies E(k)=\frac{\hbar^2k^2}{2m}
 \end{equation} 
$$
## Effektiv masse
$$
 \begin{equation} 
 E= \frac{\hbar^2k^2}{2m} \implies \frac{d^2E}{dk^2}=\frac{\hbar^2}{m} \implies m_{e}^*=\frac{\hbar^2}{d^2E/dk^2}
 \end{equation} 
$$
For 1. Brillouinsone er krumningen ikke konstant som fører til at den effektive massen endrer seg utifra krumningen på energien. Dersom det er stor krumning, så har elektronet/hullet liten masse, dersom krumningen er liten får en stor effektiv masse. **NB!** Dette er for massen når er inni en krystall! Justerer massen slik at påvirkningen i krystallen blir tatt hensyn til.

# 6 - Båndstruktur (20-21)
## Båndstruktur 
![[Pasted image 20260502101021.png|500]]
På grunn av aliasing beveger oss rundi \[$-\pi/a, \pi/a$]  som fører til at vi ser ting som "snurrer" feil vei eller står i ro fordi vi kan ikke skille mellom båndene. Når beveger deg fra 0 til $\pi/a$ så er det det samme som om du hadde bevegd deg fra $-2\pi/a$ til $-\pi/a$. 

## Fermi-Dirac fordelinga 

| ![[Pasted image 20260502103119.png\|500]] | ![[Pasted image 20260502103133.png\|500]] |
| ----------------------------------------- | ----------------------------------------- |




## Tilstandstettleik (DOS) 
![[Pasted image 20260502103157.png]]
![[Pasted image 20260502103215.png|500]]

## Elektron og hull i båndstrukturen 

| ![[Pasted image 20260502104659.png\|500]]<br> | ![[Pasted image 20260502104823.png\|500]]<br> |
| --------------------------------------------- | --------------------------------------------- |
| ![[Pasted image 20260502104713.png\|500]]<br> |                                               |

## Båndstruktur i 3D 
![[Pasted image 20260502104021.png]]
Eksempel med silisium:
![[Pasted image 20260502103414.png]]

## Direkte og indirekte båndgap 
![[Pasted image 20260502103654.png]]
- Direkte båndgap er godt egnet for å lage laser og LED fordi elektronene kan hoppe rett fra maksimum i valensbåndet til minimum i ledningsbåndet og sender så ut lys som resultat.
- Indirekte båndgap krever at det er fonon (gittervibrasjoner) som forskyver elektronene i rommet som gjør det mindre energieffektivt i form av varme, og brukes i integrerte kretser som med silisium og germanium.
## Forenkla bånddiagram
![[Pasted image 20260502103104.png|500]]
![[Pasted image 20260502103445.png]]



