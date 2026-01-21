---
lang: sk-SK
kapitola: 2.2.1
---

# Obecný stav napätosti tvárneného telesa

Všeobecný stav napätosti telesa materiálu sa v bode sa vzhľadom na ľubovoľnú rovinu prechádzajúcu týmto bodom. Na určenie polohy zvoleného bodu a roviny v priestore môžeme použiť rôzne súradnicové systémy: karteziánsky, valcový alebo sférický. Riešenia v týchto rôznych súradnicových systémoch sú ekvivalentné, ale líšia sa svojím matematickým vyjadrením. Spravidla volíme súradnice, ktoré podľa technologickej povahy tvárniaceho procesu poskytujú najilustratívnejšie a najjednoduchšie matematické vyjadrenie a riešenie. Napríklad pre kovanie medzi paralelnými plochými kovadlinami je vhodné použiť karteziánske súradnice, pre extrudovanie vo valcovom extrudéri valcové súradnice a pre ťahanie v kužeľovej matrici sférické súradnice.\
V dalším bude uveden způsob vyjádření obecného stavu napjatosti v ortogonálních souřadnicích.\
V oblasti plastických deformácií, ako aj v oblasti elastických deformácií, ktoré zohľadňujú pružnosť a pevnosť, je možné v ľubovoľnom bode telesa určiť všeobecný stav napätia  pomocou troch zložiek vektorov normálneho napätia $$\sigma_x, \sigma_y, \sigma_z$$ a šiestimi zložkami tangenciálnych (šmykových) napäťových vektorov $$\tau_{xy}, \tau_{yx}, \tau_{yz}, \tau_{zy}, \tau_{zx}, \tau_{xz}$$. Združené tangenciálne napätia  $$\tau_{xy}$$ a $$\tau_{yx}$$ atď. sú rovnaké čo do veľkosti. Preto môžeme pre vyjadrenie stvu napätosti uvažovať len s tromi zložkami napätia: $$\tau_{xy}, \tau_{yz}, \tau_{zx}$$. Obecný stav napätosti je teda definovaný šiestimi zložkami napätia.\
Pokiaľ je stav napätia rovnaký vo všetkých bodoch materiálu telesa alebo tvárneného objemu, tento stav označujeme ako stav homogénneho napätia. Takýto stav zvyčajne existuje len v jednoduchých prípadoch zaťaženia telesa a zvyčajne len v oblasti elastických a malých plastických deformácií. Príkladom je napätie v skúšobnej tyči počas ťahovej skúšky; pokiaľ sa tyč miestami nezúži, nevytvorí sa známy „krčok“. Vo všeobecnosti sa však napätia v jednotlivých bodoch materiálu telesa líšia veľkosťou a priestorovou orientáciou. Ide potom o nehomogénny stav napätia.\
V ľubovoľnej rovine v karteziánskom súradnicovom systéme $$X, Y, Z$$, ktorá pretína bod telesa, v ktorom skúmame napätie, zložky normálového a tangenciálneho napäťového vektora dávajú výsledné normálne napätie $$\sigma$$ a výsledné tangenciálne napätie $$\tau$$ (obr. 6). 

<figure><img src="../../.gitbook/assets/zlozly_nap_v_boe_tel.webp" alt=""><figcaption></figcaption></figure>
<p align="center">Obr. 6. Zložky napätia v bode telesa</p>

Táto rovina vytvára v pravouhlých súradniciach trojuholník $$a,b,c$$ ktorý je jednou stenou štvorstenu. Predpokladajme, že veľkosť plochy tohto trojuholníka je rovná jednej. Smerové uhly normály $$N$$ plochy trojuholníka určujú sklon zvolenej roviny k súradnicovým osiam a sú $$\alpha_x, \alpha_y, \alpha_z$$.\


Výsledné sily v uvažovanom bode telesa v smere jednotlivých súradnicových osí sú pri jednotkovej veľkosti šikmej stany štvorstena rovnaké ako napätie v danom smere.Sily v uvažovanom bode telesa teda môžu byť určené z nasledujúcich rovníc:

$$
\begin{aligned}
S_x &= \sigma_x \cos\alpha_x + \tau_{yx} \cos\alpha_y + \tau_{zx} \cos\alpha_z \\
S_y &= \tau_{xy} \cos\alpha_x + \sigma_y \cos\alpha_y + \tau_{zy} \cos\alpha_y \\
S_z &= \tau_{xz} \cos\alpha_x + \tau_{yz} \cos\alpha_y + \sigma_z \cos\alpha_z
\end{aligned}
\tag{2.1}
$$

Tento systém troch lineárnych rovníc teda predstavuje matematický výraz všeobecného stavu napätosti v bode telesa v pravouhlom súradnicovom systéme.\
Celkové napätie $$S$$ na jednotke plochy ľubovolnej roviny, preloženej zvoleným bodom telesa je dané geometrickým súčtom vektorov zložiek napätia $$S_x, S_y, S_z$$ (obr. 7). Priemet výsledného napätia $$S$$ do smeru normály $$N$$ ku zvolenej rovine sa označuje ako normálové napätia $$\sigma_n$$.

<figure><img src="../../.gitbook/assets/nap_na_elem_ploche.png" alt=""><figcaption></figcaption></figure>
<p align="center">Obr. 7. Napätia na elementárnej ploche</p>

Veľkosť $$\sigma_n$$ je možné vypočítať z rovnice:



