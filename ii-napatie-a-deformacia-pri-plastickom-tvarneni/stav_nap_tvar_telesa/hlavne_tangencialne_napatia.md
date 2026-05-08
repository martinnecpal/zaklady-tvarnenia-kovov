---
lang: sk-SK
kapitola: 2.2.3
---

# Hlavné tangenciálne napätia

Pre plastický stav kovov má osobitný význam tangenciálne (šmykové) napätie, ktoré ako jediné môže vyvolať plastické deformácie. Ak sa rezy, v ktorých leží tangenciálne napätie, zhodujú s kĺzavými kryštalografickými rovinami kovových zŕn, predstavujú tangenciálne napätia šmykové napätia, ktoré môžu vyvolať kĺzanie na kĺzavých rovinách, a tým aj plastickú deformáciu jednotlivých zŕn. Preto musíme hľadať extrémne hodnoty týchto napätí potrebných na vyvolanie plastickej deformácie jednotlivých kryštálov aj kovového telesa ako celku.

Všeobecný stav napätia v bode telesa $$A[x, y, z]$$ je daný tromi zložkami normálnych napätí $$\sigma_{\mathrm{x}}, \sigma_{\mathrm{y}}, \sigma_{\mathrm{z}}$$ a tromi zložkami tangenciálnych napätí $$\tau_{\mathrm{xy}}, \tau_{\mathrm{yz}}, \tau_{\mathrm{zx}}$$. Podľa obrázku 7 má normála $$N$$ k ľubovoľnej elementárnej ploche $$d U$$ vo zvolenom bode $$A$$ smerové uhly $$\alpha_{\mathrm{x}}, \alpha_{\mathrm{y}}, \alpha_{\mathrm{z}}$$. Vzdialenosť $$\overline{O A}$$ sa rovná veľkosti polomerového vektora $$\bar{r}$$ bodu $$A$$. Tento polomerový vektor leží v smere normály $$N$$ a má preto rovnaké smerové uhly.

Celkové napätie na elementárnej ploche $d U$ je $$S$$ a rozkladá sa na tri zložky $$S_{\mathrm{x}}, S_{\mathrm{y}}, S_{\mathrm{z}}$$, ktoré sa vypočítajú z rovnice (2.1). Pre veľkosť normálneho napätia bola odvodená rovnica (2.2). Medzi normálnym napätím v bode $A$ a polomerovým vektorom tohto bodu platí známy vzťah

$$
\sigma_{\mathrm{n}} \cdot r^2=\text { konst }=C
$$

Tento vzťah vyplýva z predstavy ekvipotenciálnych plôch napätia, na ktorých je normálne napätie úmerné druhej mocnine polomerového vektora (Coulombov zákon).

Tangenciálne napätie je možné vypočítať z rovnice (2.5). Zo vzťahu, že súčet štvorcov smerových kosínusov sa rovná jednej. To vyplýva pre smerový kosínus napríklad tretieho hlavného normálneho napätia výraz:

$$
\cos ^2 \alpha_3=1-\left(\cos ^2 \alpha_1+\cos ^2 \alpha_2\right)
$$

Ak tento výraz dosadíme do rovnice (2.5), dostaneme pre výpočet tangenciálneho napätia túto rovnicu:

$$
\begin{aligned}
\tau^2= & \sigma_1^2 \cdot \cos ^2 \alpha_1+\sigma_2^2 \cdot \cos ^2 \alpha_2+\sigma_3^2\left(1-\cos ^2 \alpha_1-\cos ^2 \alpha_2\right)- \\
& -\left[\sigma_1 \cdot \cos ^2 \alpha_1+\sigma_2 \cdot \cos ^2 \alpha_2+\sigma_3\left(1-\cos ^2 \alpha_1-\cos ^2 \alpha_2\right)\right]^2= \\
& =\left(\sigma_1^2-\sigma_3^2\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2^2-\sigma_3^2\right) \cdot \cos ^2 \alpha_2+\sigma_3^2- \\
& -\left[\left(\sigma_1-\sigma_3\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2-\sigma_3\right) \cdot \cos ^2 \alpha_2+\sigma_3\right]^2
\end{aligned}
$$

Aby sme našli extrémnu hodnotu $$\tau$$, derivujeme túto rovnicu podľa $$\alpha_1$$ a $$\alpha_2$$ a nastavíme prvé derivácie na nulu:

$$
\begin{aligned}
& \left(\sigma^2-\sigma_3^2\right) \cdot \cos \alpha_1-2\left[\left(\sigma_1-\sigma_3\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2-\sigma_3\right) \cdot \cos ^2 \alpha_2+\right. \\
& \left.+\sigma_3\right] \cdot\left(\sigma_1-\sigma_3\right) \cdot \cos \alpha_1=0 \\
& \left(\sigma_2^2-\sigma_3^2\right) \cdot \cos \alpha_2-2\left[\left(\sigma_1-\sigma_3\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2-\sigma_3\right) \cdot \cos ^2 \alpha_2+\right. \\
& \left.+\sigma_3\right] \cdot\left(\sigma_2-\sigma_3\right) \cdot \cos \alpha_2=0
\end{aligned}
$$

Po úprave budú mať rovnice tvar:
$$
\begin{aligned}
& \left\{\sigma_1-\sigma_3-2\left[\left(\sigma_1-\sigma_3\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2-\sigma_3\right) \cdot \cos ^2 \alpha_2\right]\right\} \cdot \cos \alpha_1=0 \\
& \left\{\sigma_2-\sigma_3-2\left[\left(\sigma_1-\sigma_3\right) \cdot \cos ^2 \alpha_1+\left(\sigma_2-\sigma_3\right) \cdot \cos ^2 \alpha_2\right]\right\} \cdot \cos \alpha_2=0
\end{aligned}
$$

Tieto rovnice môžu mať rôzne riešenia, čím dostaneme priestorový zväzok rovín s extrémnymi hodnotami tangenciálnych napätí.

Tangenciálne napätie má jednu extrémnu hodnotu v rovine, ktorá je kolmá na $$\sigma_3$$ (alebo analogicky aj na os $$\sigma_2$$ resp. $$\sigma_1$$). Je to nulová hodnota $$\tau$$, a predstavuje teda prvý extrém. Maximálnu hodnotu ako druhý extrém má tangenciálne napätie v ostatných rovinách, ktoré prechádzajú niektorou z hlavných osí a polia uhol dvoch ďalších hlavných osí. Z tohto poznatku je možné odvodiť výrazy pre druhý extrém tangenciálnych napätí, t. j. pre ich maximum.

Ak dosadíme do rovnice (2.5) za smerové kosiny hodnoty $$\pm \frac{1}{\sqrt{2}}$$, dostaneme vzťahy:

$$
\begin{aligned}
& \tau_1^2=\frac{\sigma_1^2+\sigma_2^2}{2}-\left(\frac{\sigma_1+\sigma_2}{2}\right)^2 \\
& \tau_2^2=\frac{\sigma_2^2+\sigma_3^2}{2}-\left(\frac{\sigma_2+\sigma_3}{2}\right)^2 \\
& \tau_3^2=\frac{\sigma_3^2+\sigma_1^2}{2}-\left(\frac{\sigma_3+\sigma_1}{2}\right)^2
\end{aligned}
$$

Po úprave týchto rovníc dostávame:

$$
\left.\begin{array}{l}
\tau_1=\frac{\sigma_1-\sigma_2}{2}  \tag{2.12}\\
\tau_2=\frac{\sigma_2-\sigma_3}{2} \\
\tau_3=\frac{\sigma_3-\sigma_1}{2}
\end{array}\right\}
$$

Toto sú známe vzťahy, ktoré možno odvodiť aj z Mohrových kružníc napätia. Platia algebraicky.

Rovnica (2.12) predstavuje výraz na určenie hlavných šmykových napätí. Tieto hlavné šmykové napätia sú navzájom prepojené vzťahom vyplývajúcim z vyššie uvedenej rovnice:

$$
\begin{equation*}
\tau_1\left|\tau_2\right| \tau_3 \quad 0 \tag{2.13}
\end{equation*}
$$

Je to dôležitý poznatok, ktorý odlišuje zložky hlavných šmykových napätí od zložiek hlavných normálnych napätí, ktorých súčet nie je nulový.