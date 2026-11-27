# Metody řešení úloh statiky

## Vytváření silové výslednice a momentové výslednice

Díky znalosti z předchozí kapitoly o vektoru síly, je jasné že pokud posuneme sílu mimo její nositelku (řekněme například bod A), objeví se silvoá dvojice, jejíž moment je dán součinem síly a vzdáleností posunu "d". toto nazýváme momentem síly k bodu (A). 
Pokud takto přesuneme všechny síly do jednoho bodu, lze je tak složit do jediné výslednice, která je daná $\vec{F_v} = \sum \vec{F}$, kde $\sum \vec{F}$ je vektorový součet  osamělých sil. 

Stejně tak původní silové dvojice a nové silové dvojice vzniklé přesunutím osamělých sil lze obdobně sečíst do jediné výslednice $\vec{M_v} = \sum \vec{M}$ kde $\sum \vec{M}$ je vektorový součet momentů původních a nových silových dvojic. (V rovině se tak jedná pouze 
o součet kladných a záporných momentů, odpovídajících po/proti směru hodinových ručiček.)

Ve statice jsou tak všechny účinky v rovnováze, což vypadá

$$\sum \vec{F} = 0 , \sum \vec{M} = 0 .$$

Toto jsou podmínky rovnováhy, jsou splněny v klidu a za některých případů pohybu (rovnoměrného přímočarého pohybu kdy $\vec{v} = konst.$ a $\vec{a} = 0$. Což také řadíme do statiky.) Vzhledem k tomu že hledáme pouze vektoroév účinky , jsou na výběr dvě možnosti řešení, početní a grafické.
V obou případech však nepracujeme přímo s vektory silových účinků, ale s jejich průměty do zvolených souřadnicových os či rovin. 

## Početní řešení

V početním řešení promítneme vektory $\vec{F}$ a $\vec{M}$ promítneme do zvolených souřadnicových os. Platí tak:

$$ \sum F_x = 0 $$
$$ \sum F_y = 0 $$
$$ \sum F_z = 0 $$
$$ \sum M_x = 0 $$
$$ \sum M_y = 0 $$
$$ \sum M_z = 0 $$

Kde $F_x$, $F_y$ a $F_z$ jsou průměty všech osamělých sil (známých i neznámých) působících z okolí na vybraný hmotný útvar do příslušných souřadnicových os x,y a z s orientací $\pm$. 

$M_x$, $M_y$, $M_z$ jsou 

a) Průměty momentů psůobících silových dvojic do příslušných os včetně orientace. Například pokud silová dvojice otáčí tělesem v rovině xy, promítá se celou velikostí do osy z.

b) Průměty momentů osamělých sil k příslušným osám x,y,z včetně smyslů. 

Síla má nulý moment k dané ose, pokud touto osou prochází její nositelkou. 

Z rovnic rovnováhy lze tak zjisti až šest neznámých parametrů. V rovinně spočítáme parametry 3 (z rovnic x, y a Mz).
