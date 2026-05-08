---
lang: sk-SK
kapitola: 2.2.2
---

# Invariantnosť stavu napätosti

Pri riešení problémov plasticity a teoretickom skúmaní otázok plastickej deformácie ako základu technologických tvárniacich procesov je obzvlášť dôležité určiť závislosť napäťového stavu od priestorovej orientácie zvoleného súradnicového systému. To isté platí pre určenie závislosti deformácie a rýchlosti deformácie od súradnicového systému.\
Vyberme ľubovoľný pravouhlý súradnicový systém $$X,Y,Z$$ orientovaný tak, aby jeho osi tvorili uhly s hlavnými osami $$\beta_{1},\beta_{2},\beta_{3}$$. Podľa analytickej geometrie možno projekcie hlavného normálneho napätia na smer zvolených súradnicových osí vypočítať z rovníc:

$$
\begin{aligned}
& \sigma_{\mathrm{nx}}=\sigma_{\mathrm{n}} \cdot \cos \beta_1 \\
& \sigma_{\mathrm{ny}}=\sigma_{\mathrm{n}} \cdot \cos \beta_2 \\
& \sigma_{\mathrm{nz}}=\sigma_{\mathrm{n}} \cdot \cos \beta_3
\end{aligned}
$$

Povrchy naklonené k osám $$X,Y,Z$$ tak, že na ne pôsobí iba normálové napätie $$\sigma_{n}$$, tvoria v priestore pravidelný osemsten, pretože normála týchto povrchov je zhodná s vektorom $$\sigma_{n}$$. Každá z týchto osemstenových rovín tvorí so súradnicovými rovinami $$XY, YZ, ZX$$ štvorsten. Podľa obr. 6 a v súlade s rovnicou (2.1) možno projekcie normálneho napätia do smerov zvolených súradnicových osí vypočítať z rovníc:

$$
\left.\begin{array}{l}
\sigma_{\mathrm{n}} \cdot \cos \beta_1=\sigma_{\mathrm{x}} \cdot \cos \beta_1+\tau_{\mathrm{yx}} \cdot \cos \beta_2+\tau_{\mathrm{zx}} \cdot \cos \beta_3 \\
\sigma_{\mathrm{n}} \cdot \cos \beta_2=\tau_{\mathrm{xy}} \cdot \cos \beta_1+\sigma_{\mathrm{y}} \cdot \cos \beta_2+\tau_{\mathrm{zy}} \cdot \cos \beta_3 \\
\sigma_{\mathrm{n}} \cdot \cos \beta_3=\tau_{\mathrm{xz}} \cdot \cos \beta_1+\tau_{\mathrm{yz}} \cdot \cos \beta_2+\sigma_{\mathrm{z}} \cdot \cos \beta_3
\end{array}\right\}
\tag{2.6}
$$

Na základe tohto systému lineárnych rovníc je možné skúmať závislosť napätia od orientácie zvoleného súradnicového systému, t. j. od uhlov $$\beta_1,\beta_2,\beta_3$$.Rovnica (2.6) sa dá modifikovať takto:

$$
\begin{aligned}
& \left(\sigma_{\mathrm{x}}-\sigma_{\mathrm{n}}\right) \cdot \cos \beta_1+\tau_{\mathrm{yx}} \cdot \cos \beta_2+\tau_{\mathrm{zx}} \cdot \cos \beta_3=0 \\
& \tau_{\mathrm{xy}} \cdot \cos \beta_1+\left(\sigma_{\mathrm{y}}-\sigma_{\mathrm{n}}\right) \cdot \cos \beta_2+\tau_{\mathrm{zy}} \cdot \cos \beta_3=0 \\
& \tau_{\mathrm{xz}} \cdot \cos \beta_1+\tau_{\mathrm{yz}} \cdot \cos \beta_2+\left(\sigma_{\mathrm{z}}-\sigma_{\mathrm{n}}\right) \cdot \cos \beta_3=0
\end{aligned}
$$

Z tvaru týchto lineárnych rovníc je zrejmé, že ich riešenie podľa $$\beta_1, \beta_2, \beta_3$$ nám dá reálne korene, ak determinant koeficientov pri $$\beta_1, \beta_2, \beta_3$$ (t. j. pri ich kosínoch sa bude rovnať nule:

$$
\left|\begin{array}{lll}
\left(\sigma_{\mathrm{x}}-\sigma_{\mathrm{n}}\right) & \tau_{\mathrm{yx}} & \tau_{\mathrm{zx}}  \tag{(2.7}\\
\tau_{\mathrm{xy}} & \left(\sigma_{\mathrm{y}}-\sigma_{\mathrm{n}}\right) & \tau_{\mathrm{zy}} \\
\tau_{\mathrm{xz}} & \tau_{\mathrm{yz}} & \left(\sigma_{\mathrm{z}}-\sigma_{\mathrm{n}}\right)
\end{array}\right|=0
$$

Ak vyčistíme podľa známych pravidiel tento determinant, dostaneme rovnicu tretieho stupňa:

$$
\begin{equation*}
-\sigma_n^3+A_1 \cdot \sigma_n^2-A_2 \cdot \sigma_n+A_3=0 \tag{2.8}
\end{equation*}
$$

kde

$$
\begin{aligned}
\Lambda_1= & \sigma_{\mathrm{x}}+\sigma_{\mathrm{y}}+\sigma_{\mathrm{z}} \\
\Lambda_2= & \sigma_{\mathrm{x}} \cdot \sigma_{\mathrm{y}}+\sigma_{\mathrm{y}} \cdot \sigma_{\mathrm{z}}+\sigma_{\mathrm{z}} \sigma_{\mathrm{x}}-\left(\tau_{\mathrm{xy}}^2+\tau_{\mathrm{yz}}^2+\tau_{\mathrm{zx}}^2\right) \\
\Lambda_3= & \sigma_{\mathrm{x}} \cdot \sigma_{\mathrm{y}} \cdot \sigma_{\mathrm{z}}+2 \tau_{\mathrm{xy}} \cdot \tau_{\mathrm{yz}} \cdot \tau_{\mathrm{zx}}-\left(\sigma_{\mathrm{x}} \cdot \tau_{\mathrm{yz}}^2+\sigma_{\mathrm{y}} \cdot \tau_{\mathrm{zx}}^2+\right. \\
& \left.+\sigma_{\mathrm{z}} \cdot \tau_{\mathrm{xy}}^2\right)
\end{aligned}
$$

Rovnica (2.8) tretieho stupňa pre $$\sigma_{\mathrm{n}}$$ má tri reálne korene $$\sigma_{\mathrm{n}}=\sigma_1 ; \sigma_{\mathrm{n}}=\sigma_2 ; \sigma_{\mathrm{n}}=\sigma_3$$. Tieto korene sú vyjadrené pomocou koeficientov $$\Delta_1, \Delta_2, \Delta_3$$. Z tohoto je zrejmé, že nezávisí na orientácií súradnicových os $$X, Y, Z$$, lebo výrazy pre $$\Delta_1, \Delta_2, \Delta_3$$ obsahujú iba zložky napätia, ale nezobrazujú žiadny vzťah k uhlom $$\beta_1, \beta_2, \beta_3$$. Preto je možné z hľadiska matematiky označiť koeficienty $$A_1, A_2, A_3$$ za invarianty napätia, ako veličiny kde na súradnicovom systéme sú nezávislé.

Podľa týchto poznatkov je možné invarianty napätia vyjadriť i v systéme hlavných osí, a to pomocou hlavných normálových napätí. 

$$
\begin{align*}
& \Lambda_1=\sigma_1+\sigma_2+\sigma_3  \tag{2.9}\\
& \Lambda_2-\sigma_1 \cdot \sigma_2+\sigma_2 \cdot \sigma_3+\sigma_3 \cdot \sigma_1  \tag{2.10}\\
& \Lambda_3-\sigma_1 \cdot \sigma_2 \cdot \sigma_3 \tag{2.11}
\end{align*}
$$

Podľa tohto matematického vyjadrenia nazývame koeficient $$\Delta_1$$ lineárnym invariantom, $$\Delta_2$$ prvým kvadratickým invariantom a $$\Delta_3$$ kubickým invariantom stavu napätia.

Invarianty napätia (a ďalej aj invarianty deformácie a rýchlosti deformácie) majú veľký význam pri výpočtoch a riešení úloh z oblasti plasticity. Každý z týchto invariantov má určitý fyzikálny význam:
a) Lincarnov invariant $$A_1$$ určuje oktaedrické napätie, ktoré má význam stredného, priemerného hlavného normálneho napätia. V tvárnenom materiáli má analogický fyzikálny účinok a význam ako všestranný hydrostatický tlak.
b) Kvadratický invariant $$A_2$$ určuje tzv. intenzitu napätia, ktorá pri všeobecnom pôsobení napätia vyjadruje stav napätosti. Intenzita napätia potom priamo súvisí s intenzitou deformácie a s intenzitou rýchlosti deformácie. S ich pomocou je možné matematicky riešiť všeobecné prípady plasticity a veľkých deformácií pri technologických tvárniacich procesoch.
c) Kubická invariancia $$A_3$$ súvisí s tangenciálnou zložkou napätia a určuje jej polohu v rovine kolmickej na $$\sigma_n$$. Tým je možné presne určiť aj polohu výsledného napätia v rovinnom reze v valcovanom bode telesa, čo je nevyhnutné pre úplný matematický popis stavu napätia.


