## Vervangingsweerstand van een parallelschakeling {#vervangingsweerstand-van-een-parallelschakeling}

Als twee weerstanden in parallel staan daalt de totale weerstand in weerstandswaarde. De vervangingsweerstand $$ {R}_{T}$$ van een parallelschakeling is daarom steeds kleiner dan de kleinste parallelweerstand van een tak in de parallelschakeling.

Wat is belangrijk?

*   Je verklaart met eigen woorden waarom de totale weerstand verkleind als er steeds meer weerstanden in parallel komen te staan.

*   Je beschrijft minstens twee toepassingen waarin gebruik wordt gemaakt van een parallelschakeling.

### Formule voor de totale weerstand _R__T_van een parallelschakeling {#formule-voor-de-totale-weerstand-rtvan-een-parallelschakeling}

![](/assets/afbeelding_11386.png)

Figuur 5-7 : (a) vervangingsschema van de parallelschakeling in (b)

Figuur 5-7 (a) toont het vervangingsschema van de parallelschakeling van figuur 5-7 (b). Dit betekent dat door beide schema’s dezelfde stroom $$ {I}_{T}$$ vloeit. Vermits in de schakeling van figuur 5- 7 (b) geldt dat $$ {I}_{T}$$ gelijk is aan de som van de stromen $$ {I}_{1}$$ en $$ {I}_{2}$$ kunnen we schrijven :

$$ {I}_{T}={I}_{1}+{I}_{2}$$

Via de wet van Ohm kan je de stromen omvormen naar verhoudingen van spanning op stroom. Dit levert volgend resultaat op:

$$ \frac{ {U}_{bron}}{ {R}_{T}}=\frac{ {U}_{R1}}{ {R}_{1}}+\frac{ {U}_{R2}}{ {R}_{2}}$$

De spanning over $$ {R}_{1}$$ is gelijk aan de bronspanning $$ {U}_{bron}$$ . Dit geldt eveneens voor de spanning over $$ {R}_{2}$$ . Aldus wordt bekomen :

$$ \frac{ {U}_{bron}}{ {R}_{T}}=\frac{ {U}_{bron}}{ {R}_{1}}+\frac{ {U}_{bron}}{ {R}_{2}}$$

Wegdelen van $$ {U}_{bron}$$ levert het volgende op:

$$ \frac{1}{ {R}_{T}}=\frac{1}{ {R}_{1}}+\frac{1}{ {R}_{2}}$$

Of na herwerking naar $$ {R}_{T}$$ :

$$ {R}_{T}=\frac{1}{\frac{1}{ {R}_{1}}+\frac{1}{ {R}_{2}}}$$

Meer algemeen voor $$ n$$ weerstanden in parallel geldt dat de vervangingsweerstand $$ {R}_{T}$$ als volgt kan worden gevonden :

$$ {\mathit{R}}_{\mathit{T}}=\frac{1}{\frac{1}{ {\mathit{R}}_{1}}+\frac{1}{ {\mathit{R}}_{2}}+\frac{1}{ {\mathit{R}}_{3}}+\dots +\frac{1}{ {\mathit{R}}_{\mathit{n}}}}$$ **_(5-1)_**

Het bepalen van de vervangingsweerstand van twee weerstanden in parallel kan ook op volgende manier:

$$ {R}_{T}=\frac{1}{\frac{1}{ {R}_{1}}+\frac{1}{ {R}_{2}}}$$

$$ {R}_{T}=\frac{1}{\frac{ {R}_{2}}{ {R}_{1}{R}_{2}}+ \frac{ {R}_{1}}{ {R}_{1}{R}_{2}}}$$ = $$ \frac{1}{\frac{ {R}_{2}+{R}_{1}}{ {R}_{1}{R}_{2}}}$$

$$ {\mathit{R}}_{\mathit{T}}=\frac{ {\mathit{R}}_{1}\times {\mathit{R}}_{2}}{ {\mathit{R}}_{1}+{\mathit{R}}_{2}}$$ (5-2)

Deze formule wordt ook wel eens de product over som formule genoemd.

Het omgekeerde van weerstand is geleiding. Geleiding wordt voorgesteld door $$ G$$ . Via geleiding kan je ook de vervangingsweerstand van een parallelschakeling bepalen. Door eerst de totale geleiding te bepalen kan je vervolgens de vervangingsweerstand bepalen op volgende manier :

$$ {R}_{T}=\frac{1}{ {G}_{T}}$$

Deze manier van werken is handig als je de vervangingsweerstand uitrekent met een rekenmachine. Stel bijvoorbeeld drie weerstanden $$ {R}_{1}, {R}_{2}$$ en $$ {R}_{3}$$ in parallel. De totale geleiding bereken je als volgt :

$$ {G}_{T}=\frac{1}{ {R}_{1}}+\frac{1}{ {R}_{2}}+\frac{1}{ {R}_{3}}$$

Via het rekenmachine:

![](/assets/afbeelding_11339.png)

Figuur 5-8 : bepalen van de totale geleiding G T met een rekenmachine

De totale geleiding kan je vinden door eerst $$ {R}_{1}$$ in te geven, vervolgens op de _1/x-toets_ te drukken. Hierdoor is de weerstandswaarde omgezet naar de geleidingswaarde $$ {G}_{1}$$ . Daarna druk je op de _+-toets_ en geef je de weerstandswaarde van $$ {R}_{2}$$ in. Dit herhaal je tot alle parallelgeschakelde weerstanden zijn ingegeven. Nadat de laatste weerstandswaarde is ingegeven druk je op de _1/x-toets_ en vervolgens op de _=-toets_ . Het resultaat is nu gelijk aan de totale geleiding $$ {G}_{T}$$ . De relatie tussen de totale geleiding en de totale weerstand van de parallelschakeling is als volgt:

$$ {R}_{T}=\frac{1}{ {G}_{T}}$$

Via het rekenmachine:

![](/assets/afbeelding_11375.png)

Figuur 5-9: omzetten via rekenmachine van $$ {G}_{T}$$ naar $$ {R}_{T}$$

$$ {R}_{T}=\frac{100 k\Omega \times 22 k\Omega }{100 k\Omega + 22 k\Omega }=\mathrm{18,03} k\Omega $$ $$ A$$ Via figuur 5-8 en figuur 5-9 heb je een manier om zeer snel de vervangingsweerstand $$ {R}_{T}$$ van een parallelschakeling bestaande uit $$ n$$ weerstanden te bepalen.

### Bepalen vervangingsweerstand bij n gelijke weerstanden in parallel. {#bepalen-vervangingsweerstand-bij-n-gelijke-weerstanden-in-parallel}

$$ {R}_{T}=\frac{1 k\Omega }{5}=\mathrm{0,2} k\Omega =200 \Omega $$ Indien er $$ n$$ gelijke weerstanden in parallel staan kan je de vervangingsweerstand als volgt vinden:

$$ {\mathit{R}}_{\mathit{T}}=\frac{\mathit{R}}{\mathit{n}}$$ **_(5-3)_**

### Notatie om een parallelschakeling aan te geven {#notatie-om-een-parallelschakeling-aan-te-geven}

Om een vervangingsweerstand van $$ n$$ weerstanden weer te geven kan je gebruik maken van de formule van vergelijking 5-1\. Dit is dikwijls een omslachtige manier waarbij het overzicht soms zoek kan geraken. Daarom maakt men gebruik van het symbool “ $$ \parallel $$ ” om weerstanden in parallel aan te geven. De vervangingsweerstand van de parallelschakeling van figuur 5-11 kan men bijgevolg ook als volgt voorstellen:

$$ {R}_{T}={R}_{1} \parallel {R}_{2} \parallel {R}_{3} \parallel {R}_{4} \parallel {R}_{5}$$

Stel dat een weerstand van $$ 330 \Omega $$ parallel staat met een weerstand van $$ 680 \Omega $$ dan kan je de vervangingsweerstand hiervoor als volgt noteren:

$$ {R}_{T}=330 \Omega \parallel 680 \Omega $$

### Toepassingen van parallelschakelingen {#toepassingen-van-parallelschakelingen}

Het voordeel van een parallelschakeling ten opzichte van een serieschakeling is dat als een bepaalde tak in een parallelschakeling geopend wordt (bijvoorbeeld door een defect), de andere takken niet beïnvloed worden en nog steeds onder stroom staan.

Exterieur lichten van een auto

Door de lichten van een auto in parallel te schakelen in plaats van in serie blijft bij een defecte lamp, de andere lamp nog branden. Figuur 5-12 geeft een voorbeeld weer hoe een elektrisch schema van de exterieurverlichting van een auto kan opgebouwd zijn.

![](/assets/afbeelding_11392.png)

Figuur 5-12: elektrisch schema van een aantal exterieur lichten bij een auto

Met de schakelaar _lichten aan/uit_ worden de koplampen en de achterlichten respectievelijk aan- of uitgeschakeld. Via een aan/uit schakelaar ( _parkeerlichten aan/_ uit) kan gekozen worden tussen de parkeerlichten en de koplichten. Wanneer het rempedaal ingedrukt wordt, wordt de drukschakelaar gesloten en branden de remlichten. Deze blijven net zolang branden tot het rempedaal terug wordt losgelaten. Als de auto in achteruit wordt geschakeld, worden de lichten ter indicatie van het achteruitrijden geactiveerd. De lampen worden in parallel geschakeld opdat bij het doorbranden van één van de lampen de andere lampen nog steeds kunnen branden.

Achterruitverwarming in de auto

Het werkingsprincipe van een autorruitverwarming bestaat er in om dunne weerstandsdraad op het glas aan te brengen en hierdoor stroom te sturen. De stroom in de weerstandsdraad ontwikkelt warmte in de draad. Hierdoor begint de autoruit te ontdooien.

![](/assets/afbeelding_11393.png)

Figuur 5-13 : principe van een achterruitverwarming

Het ontdooisysteem bestaat uit een aantal parallelle weerstandsdraden die het glas opwarmen zodra de schakelaar wordt ingedrukt. Een typische achterruitverwarming dissipeert zo’n $$ 100 W$$ in de ruit. Een eventueel “breukje” in de draad kan bijvoorbeeld opgelost worden met wat zilververf.

Controle circuits

Veel controlesystemen maken gebruik van parallelcircuits voor controle en monitoring in een industrieel proces. De programmeerbare logic controller (PLC) is hiervan een voorbeeld. Een PLC maakt gebruik van een ladderdiagram. Een ladderdiagram geeft het equivalent parallelcircuit van een PLC weer op een computerscherm. In figuur 5-14 is een voorbeeld weergegeven van een motor start/stop circuit.

![](/assets/afbeelding_11394.png)

Figuur 5-14 : voorbeeld van een eenvoudig ladderdiagram

Parallel regelkringen gebruiken ladderdiagrammen maar voegen extra bedieningselementen zoals schakelaars, relais, timers, … toe. Het resultaat is een logisch diagram dat wordt aangeduid als ladderdiagram. Ladderlogica is eenvoudig te begrijpen en wordt gebruikt in industriële controleproblemen. Herstellingshandleidingen maken ook dikwijls gebruik van ladderdiagrammen voor het tonen van schakelingen en voor het oplossen van problemen in deze schakelingen. Aan de hand van een ladderdiagram kan de technicus testprocedures organiseren.

In het voorbeeld van figuur 5-14 is een motor start/stop schakeling weergegeven. Het CR1-contact zorgt er samen met de start-drukknop ervoor dat de motor start. CR1 is een overneemcontact en sluit zodra de startknop wordt ingedrukt. Als de startknop wordt losgelaten blijft CR1 gesloten zodat de motor kan blijven draaien. Als CR1 is bekrachtigt gaat een verklikkerlampje aan zodat visueel zichtbaar is dat de motor aanstaat.

### Test jezelf : vervangingsweerstand van een parallelschakeling {#test-jezelf-vervangingsweerstand-van-een-parallelschakeling}

1.  **Als een weerstand parallel wordt geplaatst met een gekende weerstand, stijgt dan de totale weerstandswaarde of daalt deze?**

2.  **De totale weerstandswaarde is steeds kleiner dan welke waarde?**