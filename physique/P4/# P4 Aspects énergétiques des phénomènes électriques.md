# P4: Aspects énergétiques des phénomènes électriques

## 1. Intensité du courant électrique.

Les porteurs de charges électriques capables de se déplacer sont : 
* les **électrons libres** dans les métaux
* les **ions**  dans les solutions

Sous l’effet d’une tension électrique, les porteurs de charges sont mis *collectivement* en mouvement et forment un courant électrique.

> <img align=right src="./doc/courant.png" alt="courant" style="zoom:33%;" /> L’intensité du courant, est un **débit** de charges électriques. On note $Q$ la charge électrique totale qui traverse une section d’un fil pendant la duré $\Delta t$	
> $$
> \fbox{$I=\frac{Q}{\mathrm{\Delta t}}$}
> $$
>  avec $Q$ en C (coulomb) , $\Delta t$ en (s) et $I$ en (A)

## 2. Sources de tension.

Une source de tension est un dispositif qui délivre une tension électrique entre ses bornes que l'on note P (positive) et N (négative). Celle peut être une pile ou une batterie par exemple.

### A. Source idéale.

* <img align=right src=".\doc\source_ideale2.png" alt="source_ideale"/> Une source idéale de tension est un générateur qui maintient une tension **constante** quelle que soit l’intensité du courant.
* On a donc $\fbox{$U_{PN} = E$}$

### B. Source réelle.
* <img align=right src=".\doc\source_reelle2.png" alt="source_réelle2"/>Une source réelle a une tension qui **diminue** lorsque l’intensité du courant augmente. 
* La caractéristique tension-courant est une fonction affine.
  $$
  \fbox{$U_{PN} = E - r.I$}
  $$

> On *modélise* une source réelle par l'association d’un générateur *idéal* de tension E (appelée **force électromotrice**) en série avec une résistance  r (appelée **résistance interne**)
>
> ![modélisation2](.\doc\modélisation2.png)

## 3. Puissance et énergie.

### A. Les définitions

> La puissance électrique est une mesure de la « vitesse » de transformation de l'énergie.
>
> $$
> \fbox{$P=\frac{E}{\mathrm{\Delta t}}$}
> $$
> où P est la puissance en watt (W) , E l’énergie en joule (J) et Δt la durée en seconde.

**Exemples de puissances :** lampe 50 W ; console de jeux 500 W ; chauffage électrique 5000 W

> La puissance électrique fournie ou reçue par un dipôle est : $ \fbox{$P=U\times I$} $

### B. L'effet joule.

> L’effet joule est la **transformation** totale d’énergie électrique en transfert thermique (chaleur) dans un conducteur ohmique.

Pour un conducteur ohmique de résistance $R$ en $(\Omega)$ la puissance transformée par effet Joule est : $P_J = R.I^2$

### C. Bilan de puissance et rendement d’un convertisseur.

Dans un **bilan énergétique** pour un convertisseur, on fait apparaître sur un diagramme, les énergies *reçues* et les énergies *transformées.*

**Exemple :** Une ampoule reçoit de l’énergie électrique et fournit de l’énergie lumineuse un transfert thermique (chaleur) au milieu extérieur.

<img src="./doc/bilan_ampoule.png" alt="diagramme" style="zoom:50%;" />

Seule une partie de l’énergie fournie par le convertisseur est l’énergie est **"utile"**.

> Par définition le **rendement** d’un convertisseur est:
> $$
> \fbox{$\eta=\frac{P_{utile}}{P_{reçue}}$}
> $$
* Le rendement est compris entre 0 et 1 et s’exprime souvent en %
* Dans l'expression du rendement on peut remplacer les puissances par les énergies.
* Exemples de rendement : panneau solaire 22 %	batterie 96 %	moteur électrique 80 % thermique 30 %