# Formål

Formålet med forsøget er at i første skridt med en kend gitter finde laserens bølgelængde og efterfølgende regne omvend  og finde gitterkonstanten til en ukend gitter

# Teori
En gitter betejner en trasperente eller reflekterende overflade som i striber i $\micro$m størlsen eller mindre er underbrudt. Pga. det bliver lyset sorteret efter bølgelængden. Det sørger for at der en række af prikker på vægen.

Prikkerne er der pga. ifølge hygens princip spreder lyset sig i alle retninger, men pga. interfenrencen og difraktion reduceres mønstert til prikker.

Bergniningen er rent geometrisk, Interferensen dannes med lige mellemrum.
Højdepunkterne er altid vis mindst to af lystålerne rammer vægen det punkt de er lige langt i deres bølge.

det betyder at en lystråle er lige precist en bølgelængde videre end den anden.


I tegningen kan der ses at forskellen mellem linjen BC og AC er et stykke med længden $x$

Denne længde er i vores forsøg lige med bølgelængden og kan beregnes ved hjælp af trigeometrien.

![[Pasted image 20230612084437.png]]
 vinklen $a$ kan beregnes ved følgende formel ud fra den stripplede trekants størelser.

 $$a=90°-tan^{-1}\left(\frac{h}{g}\right)$$

og den lille trekant kan beregnes ved sinusrelationer

$$\lambda=sin(a)\cdot d$$
det betyder at for at beregne bølgelængden er formlen følgende

$$\lambda\cdot n=d\cdot\sin\left(\tan^{-1}\left(\frac{h}{g}\right)\right)$$
eller omstilt efter d:
$$d=\frac{\lambda\cdot n}{\sin\left(\tan^{-1}\left(\frac{h}{g}\right)\right)}$$

$n$ er hele tal og angiver den orden som bliver brugt 

# Forsøgsopstilling
Forsøget består af en laser som lyskilde, en gitter som stå med lidt afstand foran, og en overflæde som fungerer som lærred på et større kend afstand. Både gitter og lærred står ortogonalt til lasern.

I vores tilfelde stod gittern på en afstand af ca. 5cm til lasern, men denne afstand er ikke relevant til forsøget.

Afstanden til vægen lå på 8,26m under hele forsøget.

![[Pasted image 20230602121740.png]]


# Fremgangsmåde
Forsøget stilles op, dvs. lasern stilles op og pejes ortagonalt på en skærm/lærred
så sættes der en gitter med kende gitterkonstant parallelt med lærred lig foran lasern og afstanden mellem gitter og lærred måles

Nu kan der ses flere prikker på vægen, den miderste (lige stråle fra lasern) kaldes 0-orden og dem ved siden af 1 hendholdsvis -1 orden og så vider.

Der måles afstanden mellem 0 og første/anden.. orden og samme måling til den modsatte (-først/-anden). I Teorien skulle 0 til 1 og 0 til -1 værre samme tal.
Målinger skrives ned og der laves evt. billeder af forsøgsopstilling.

Bagefter skiftes gittert som helst skal stå samme sted, eller afstanden skal måles igen og forsøget gentages med andet gitter.

Ved brug af gitter med kend gitterkonstant kan laserens bølgelængde bestemmes, og ved brug af gitter med ukend gitterkonstant kan gennem at kende Bølgelængden af lasern kan gitterkonstanten beregnes.

# Måledata
afstand til vægen er i alle forsøg 8,26m

### Gitter 1: 300/mm

Orden | s
--- | ---
1 | 1,24


### Gitter 2: 600/mm

Orden | s
--- | ---
1 | 3,33m
2 | 6,66m

### Gitter 3: ukend

Orden | s
--- | ---
1 | 10,5cm
2 | 21cm
## Gitter 4: ukend

Orden | s
--- | ---
1 | 5,5cm
2 | 6cm

# Beregninger og Resultater
Der skal i første omgang beregne laserens bølgelængde ved hjælp af formeln fra teori delen.
$$\lambda=d\cdot\sin\left(\tan^{-1}\left(\frac{h}{g}\right)\right)$$
$$\lambda=\frac{1}{300}\cdot10^{-3}m\cdot\sin\left(\tan^{-1}\left(\frac{1,24}{8,26}\right)\right)=497,8\cdot10^{-9}m$$
pga. vi regner med første orden er $n=1$ og er reduceret fra formeln 

---
der kontroleres overstående bølgelængde med en anden gitter.
$$\lambda=\frac{1}{600}\cdot10^{-3}m\cdot\sin\left(\tan^{-1}\left(\frac{3,33}{8,26}\right)\right)=623,2\cdot10^{-9}m$$
og beregning med samme gitter i anden orden:
$$\lambda=\frac{\frac{1}{600}\cdot10^{-3}m\cdot\sin\left(\tan^{-1}\left(\frac{6,66}{8,26}\right)\right)}{2}=1046,1\cdot10^{-9}m$$

de tre bølgelængder er meget forskelligt, der bruges $623,2nm$ i det følgende fordi 500nm ligger i det blå/grønne område og 1050nm er ude for det synlige lys, og lasern var rødt

---
Der beregnes nu gitterkonstanten til de ukende gitter.
gitter 3:
$$d=\frac{623,2\cdot10^{-9}m}{\sin\left(\tan^{-1}\left(\frac{10,5m\cdot10^{-2}}{8,26}\right)\right)}=4,903\cdot10^{-5}$$
det er afstanden mellem spalterne som betyder vis der regnes $\frac{1}{d}$ har vi spalter per mm
$$\frac{1}{4,903\cdot10^{-5}}=20395\space spalter/mm$$
i anden orden:
$$d=\frac{623,2\cdot10^{-9}m\cdot 2}{\sin\left(\tan^{-1}\left(\frac{21m\cdot10^{-2}}{8,26}\right)\right)}=4,904\cdot10^{-5}$$
som giver $20391$ spalter/mm


---
gitter 4:
$$d=\frac{623,2\cdot10^{-9}m}{\sin\left(\tan^{-1}\left(\frac{5,5m\cdot10^{-2}}{8,26}\right)\right)}=1,872\cdot10^{-4}$$
$$5342\space spalter/mm$$


$$d=\frac{623,2\cdot10^{-9}m\cdot 2}{\sin\left(\tan^{-1}\left(\frac{6m\cdot10^{-2}}{8,26}\right)\right)}=1,716\cdot10^{-4}$$
$$5827\space spalter/mm$$


# Diskusion

Alderede ved første 2 beregninger kan der ses at der er meget høje afvejninger.
Konkret kan der ses med øjet at laseren er rødt, men den første beregning resulterer i at det ville har været blå laser, den anden passer nogennunde og den tredje er langt ude i det infrarøde lys.

Disse afvejninger skyldes nok primært målefejl især i forhold til afstanden til vægen som blev målt med målebpånd som hang igennem. Det sørger for større forskelle især vis der arbejdes med noget så præcise som lys.

En anden fejlkilde som sandsynligvis også har haft indflydse er at det er svært at sikkre sig at lasern og gitter står ortogonale på vægen. Denne fejl vokser også meget hurtig ret stort gennem den afstand vi har til vægen. Eller bedre sagt den større afstand vi har mellem prikkerne gennem at afstanden til vægen er større.

I fremtiden kunne man fx. bruge en laser afstandsmåler eller en massiv målestok til at måle afstanden.

eller lægge målebånden på gulvet hvor det ikke hænger ned.

I forhold til vinklen kunne man i fremtiden orientere sig ved en væg eller lignende



# Konklusion

Forsøget lykkes ikke, formålet med at finde gitterkonstanten/spalteafstanden blev ikke opfyld.

Det er primært skyllet i det store afvejninger som opstod under dokumentationen af forsøget. Det resulterer i at der ikke kan bestemmes hvad de ukende gitter har for nogle spalteafstande.