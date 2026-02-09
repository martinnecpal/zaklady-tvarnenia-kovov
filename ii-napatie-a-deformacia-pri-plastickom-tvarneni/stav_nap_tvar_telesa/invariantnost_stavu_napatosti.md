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

Z tvaru týchto lineárnych rovníc je zrejmé, že ich riešenie podľa $$\beta_1, \beta_2, \beta_3$$ nám dá reálne korene, ak determinant koeficientov pri $$\beta_1, \beta_2, \beta_3$$ (t. j. pri ich


STR 33



