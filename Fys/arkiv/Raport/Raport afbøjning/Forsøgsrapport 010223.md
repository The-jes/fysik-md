# Formål

Vores formål er at bestemme elektroners specifike ladning experimentielt dvs. $e/m$
hvori $e$ er elektronens ladning og $m$ står for massen


# Teori
I vores forsøg produceres i elektronkanon en stråle af ladede elektroner som i magnetfeltet afbøjes i følge af Lorenzkraften. ($F_M=q\times v \times B$)
Afbøgning eller bedre sagt radius af cirklen der opstår kan blive målt i på skalan som er med i forsøgsobygningen.

Afbøjningen som obstår gennem Lorenzkraften danner en cirkel hvori dens radius kan beregnes ved hjælp af formlen til Centripetalkraft: $F_C=m\times \frac{v^2}{r}$

Dvs. at den sammensatte formel er følgende hvor ladning er $e$:
$$e \times v \times B =\frac{m \times v^2}{r} $$

Hastigheden $v$ som opstår i elektronenkanonen er afhængig af spændingsforskelen som bruges i følgende formel:
$$E_{el}=E_{kin}$$
$$U\times q = \frac{1}{2} \times m \times v^2$$

$$v=\sqrt{\frac{2\times q \times U}{m}}$$
hvori $q=e$ dvs. 
$$v=\sqrt{\frac{2\times e \times U}{m}}$$

---

Det kan samles op til følgende:
$$e \times v \times B =\frac{m \times v^2}{r} $$
$$e \times B =\frac{m \times v}{r} $$
$$\frac{e}{m} =\frac{v}{r \times B} $$
$$\frac{e}{m} =\frac{\sqrt{\frac{2\times e \times U}{m}}}{r \times B} $$
$$\frac{e^2}{m^2} =\frac{2\times e \times U}{m \times r^2 \times B^2}$$
$$\frac{e}{m} =\frac{2\times U}{r^2 \times B^2}$$
Den magnetiske fluxtæthed er givet ved følgende:
$$B=\frac{8}{5\sqrt{5}}\times \frac{n \times \mu_0 \times I}{R} $$
$$B=\frac{8}{5\sqrt{5}}\times \frac{154 \times 1,257\times 10^{-6}T\times m/A \times I}{0,2m}$$
som kan forkortes til:
$$B=\frac{8}{5\sqrt{5}}\times \frac{1,93578\times10^{-4}T\times m/A \times I}{0,2m}$$

---
Elektonens elementarladning er defineret med $e = 1,602\times10^{-19} C$
Elektronens elementarmasser er defineret med $m_e = 9,109\times10^{-31} kg$

Dvs. at $e/m= $



# Forsøgsopstilling og anvendt apparatur
![[Versuchsaufbau-Kathodenstrahlroehre.png]] 
Ovenfor ses en skitze af forsøget, læg serlig mærke til skalan som rammes med elektronstrålen til at tage noglenlunde præcise målinger af radius, Kuglen er også fyld med Neongas som ioniseres af elektronerne og dermed gører strålen synlig.


![[A10.jpg]]
Her ses en billede af forsøgsopbygningen som ligner den som vi brugte men ikke har ledninger over det hele. Der er to stromforsyninger til hendholdsvis spolen og elektronkanonen og hver strømkredsløb har tilsluted amper hendholdsvis voltmeter.



# Fremgangsmåde
Vi tog den ferdig opbyget forsøg frem og sat den i stikkontakten,
der blev sat støm på både spolen og elektronkanon, nu ændred vi på både spændngen af elektronenkanonen og stromstyrke af spolerne som genererer magnetfeltet,
formålet med disse ændringer er at ramme makeringer som marker en kend radius.


# Måledata
Vores indstillte stromstyrke og spænding, opstilt efter radiusen
spænding | $r=2cm$ | $r=3cm$ | $r=4cm$ | $r=5cm$
-- | -- | -- | -- | --
100V | $I=2,87A$ | $I=1,85A$ | $I=1,35A$ | $I=1,03A$
200V | $I=3,75A$ | $I=2,37A$ | $I=1,76A$ | $I=1,39A$
251V | $I=4,33A$ | $I=2,73A$ | $I=2,0A$ | $I=1,58A$
151V |  $I=3,41A$ | $I=2,22A$ | $I=1,59A$ | $I=1,25A$
281V | $I=4,46A$ | $I=2,93A$ | $I=2,12A$ | $I=1,71A$

# Beregninger og Resultater
Ved hjælp af formlen som blev omstillet i [Teori delen](#Teori) og vores [Måledata](#Måledata) kan vi nu gennemføre vores beregninger, jeg starter ud med følgende data:
> [!example] Data:
> Radius: $2cm = 0,02m$
> Spænding: $100V$
> Stromstyrke: $I=2,87A$

som indsættes i formlen til fluxtætheden:
$$B=\frac{8}{5\sqrt{5}}\times \frac{1,93578\times10^{-4}T\times m/A \times I}{0,02m}$$
som resulter i
$$B=\frac{8}{5\sqrt{5}}\times \frac{1,93578\times10^{-4}T\times m/A \times 2,87}{0,02m}=\underline{1,98766\times 10^-3T}$$
og indsætter resultatet i den anden formel:
$$\frac{e}{m} =\frac{2\times 100V}{0,02m^2 \times (1,98766T\times 10^{-3})^2}=\underline{\underline{1,266\times10^{11}}}$$
som resulter i en afvegelse af tal% af den teoretiske verdi ifølge formelsammlingen:

###### Teoretiske verdi
$$\frac{e}{m}=\frac{1,602\times10^{-19}}{9,109\times10^{-31}}=1,7587\times10^{11}$$
###### Afvejning:
$$\frac{1,7587\times10^{11}-1,266\times10^{11}}{1,7587\times10^{11}}=28\%$$

Afvejningen ved de andre beregninger ligner og ligger også på ca. 30% dog er der enkelte som ligger meget længre udenfor

# Diskusion
En afvejning på ca. 30% er meget højt i forhold til hvor enkelt forsøget er.
Dog formoder jeg at en af det største fejlkilder er at vores multimeter og voltmeter nok ikke er de mest akurate, det kunne føre til nogle afvejser som ligger så tæt sammlet som de gør men ikke passer til resultatet, dvs. ikke særlig spredt. Ellers kunnde der også være fejl i beregningen.


# Konklusion
Vi fand ud af den Specifike ladning af elektroner men hæde en stor afvejning fra det teoretiske resultat som fører til at forsøget nok ikke lykkes




# Biledekilder
[Skitze af Forsøget](https://virtuelle-experimente.de/b-feld/b-feld/versuchsaufbau.php)
[Billede af Forsøgsopbygningen](https://www3.physik.uni-stuttgart.de/studium/praktika/ap/bilder/?Name=A10.jpg)


