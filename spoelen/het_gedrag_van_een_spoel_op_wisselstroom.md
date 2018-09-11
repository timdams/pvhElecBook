## Het gedrag van een spoel op wisselstroom {#het-gedrag-van-een-spoel-op-wisselstroom}

Een spoel laat wisselstroom door maar met een bepaalde opposite die afhankelijk is van de frequentie van de wisselstroom.

Wat is belangrijk?

*   Je definieert de inductieve reactantie.

*   Je bepaalt de waarde van de inductieve reactantie in een gegeven schakeling

*   Je verklaart het werkelijk, ogenblikkelijk en reactief vermogen in een spoel

*   Je verklaart de faserelatie tussen spanning en stroom bij een spoel

### De inductieve reactantie $$ {\mathit{X}}_{\mathit{L}}$$ {#de-inductieve-reactantie-mathit-x-mathit-l}

Wanneer de voedingsspanning op een constante amplitudewaarde wordt gehouden en de frequentie ervan wordt verhoogd, dan neemt de amplitude van de stroom af. Ook wanneer de frequentie van de bron afneemt neemt de stroomamplitude toe.

Als de frequentie van de bronspanning wordt verhoogd, dan neemt de frequentie van de stroom ook toe. Volgens de wetten van Faraday en Lenz wordt er meer spanning geïnduceerd over de spoel in een richting om de stroom tegen te werken waardoor deze in amplitude afneemt. Evenzo veroorzaakt een afname van de frequentie een toename van stroom.

De inductieve reactantie $$ {X}_{L} $$ is datgene dat weerstand biedt tegen de wisselstroom in een spoel. Deze reactantie biedt geen weerstand tegen constante stroom. Hoe groter de inductantie $$ L$$ , hoe meer weerstand er geboden wordt aangaande de wisselstroom door de spoel. $$ {X}_{L}$$ is evenredig met de frequentie en de zelfinductie.

Bepalen van de inductieve reactantie

Beschouw hiervoor figuur 9-28\. In de figuur is het eerste vierde periode te zien van de wisselstroom door een spoel. Door de gemiddelde stroom te bepalen over $$ \frac{1}{4}$$ periode kan je via vervangingen in de vergelijking de inductieve reactantie bepalen.

Eerst schrijven we de algemene formule neer die de spanning over een spoel bepaald:

$$ {u}_{L}=L\times \frac{dI}{dt}$$

Door het interval van de stroom te bepalen tussen de tijdstippen $$ 0$$ en $$ \frac{T}{4}$$ en deze in bovenstaande formule in te vullen bekomen we een vergelijking die de spanning weergeeft in functie van de stroom.

![](/assets/afbeelding_515.png)

Figuur 9-28 : $$ \frac{1}{4}$$ periode van de stroom om de inductieve reactantie te bepalen

Na een tijdsverloop van $$ \frac{T}{4}$$ is de stroom gevarieerd van 0 tot $$ {I}_{max}$$ . Dit invullen in de vergelijking:

$$ {u}_{L}=L\times \frac{ {I}_{max}-0}{\frac{T}{4}-0}$$

$$ {u}_{L}=L \times \frac{ {I}_{max}}{\frac{T}{4}}=L \times \frac{4\times {I}_{max}}{T}$$

Vermits de periode het omgekeerde is van de frequentie kan je de periode vervangen door de frequentie. Dit levert volgend resultaat op:

$$ {u}_{L}=L \times 4 \times f \times {I}_{max} $$

De spanning $$ {u}_{L}$$ die op deze wijze gevonden wordt is de gemiddelde spanning gezien over het tijdsinterval tussen $$ 0$$ en $$ \frac{T}{4}$$ . Om de correcte reactantiewaarde te vinden moet $$ {I}_{max} $$ ook omgevormd worden tot de gemiddelde waarde. De gemiddelde stroomwaarde kan op volgende wijze gehaald worden uit de maximale stroomwaarde:

$$ {I}_{gemid}=\frac{2}{\pi }\times {I}_{max}$$

Of:

$$ {I}_{max}=\frac{\pi }{2} \times {I}_{gemid}$$

Vullen we laatstgenoemde formule in de vergelijking van $$ {u}_{L}$$ dan bekomen we:

$$ {u}_{L}=L \times 4 \times f \times \frac{\pi }{2} \times {I}_{gemid} $$

Deze formule vereenvoudigen en herschikken levert op :

$$ {u}_{L}=2 \times \pi \times f \times L \times {I}_{gemid} $$

De inductieve reactantie kan dan als volgt worden bepaald:

$$ {X}_{L}=\frac{ {u}_{L}}{ {I}_{gemid}}= 2 \times \pi \times f \times L$$

Of :

$$ {X}_{L}= 2 \pi f L\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }(9-19)$$

Soms spreekt men van een inductantie wat hetzelfde betekent als een inductieve reactantie. De inductieve reactantie wordt in Ohm uitgedrukt.

Serie- en parallelschakelen van inductieve reactanties

Vermits de inductieve reactanties weerstand bieden aan de wisselstroom gedragen ze zich als weerstanden (maar dan enkel op gebied van wisselstroom). Dit betekent dat de formules voor het vinden van de totale seriereactantie of parallelreactantie op dezelfde manier te vinden zijn als de formule voor de totale weerstand van een serieschakeling of parallelschakeling.

De formules zijn:

Voor de serieschakeling :

$$ {X}_{Lt}={X}_{L1}+{X}_{L2}+\dots . {X}_{Ln} (9-20)$$

Voor de parallelschakeling :

$$ {X}_{ {L}_{t}}=\frac{1}{\frac{1}{ {X}_{L1}}+\frac{1}{ {X}_{L2}}+\dots +\frac{1}{ {X}_{Ln}}} (9-21)$$

![](/assets/afbeelding_11275.png)

Figuur 9-29 :bij een spoel ijlt de spanning 90° voor op de stroom

### De faseverschuiving tussen spanning en stroom bij een spoel {#de-faseverschuiving-tussen-spanning-en-stroom-bij-een-spoel}

Een sinusvormige spanning heeft een maximale veranderingssnelheid bij de nuldoorgang en een nul-snelheid van verandering op de pieken. Via de wet van Faraday weet je dat de hoeveelheid spanning die geïnduceerd wordt over een spoel recht evenredig is met de snelheid waarmee de stroom aan het veranderen is. Daarom is de spoelspanning maximaal bij de nuldoorgangen van de stroomwaar de mate van verandering van de stroom het grootst is. Ook de hoeveelheid spanning bij de amplitude van de stroom is nul. Deze fase relatie is geïllustreerd in figuur 9-29\. Via de figuur zie je duidelijk dat bij een spoel de spanning 90° voor-ijlend is op de stroom.

### Vermogen in een spoel {#vermogen-in-een-spoel}

Een spoel bewaart de energie in zijn magnetisch veld. Een ideale spoel (zonder windingsweerstand) dissipeert geen energie maar bewaart het enkel. Als een wisselspanning wordt aangelegd aan een spoel dan zal gedurende een deel van de cyclus de spoel de energie in zijn magnetisch veld bewaren en gedurende een ander deel van deze cyclus deze energie terug afgeven aan de bron.

Figuur 9-30 toont de vermogencurve gedurende een cyclus van het vermogen. Merk op dat deze curve veel gelijkenis toont met deze van de condensator. Het verschil is dat spanning en stroom omgewisseld zijn.

**_Het ogenblikkelijjk of momenteel vermogen_ **$$ \mathit{p}$$

Het product van ogenblikkelijke spanning $$ u $$ met de ogenblikkelijke stroom $$ i$$ levert het ogenblikkelijk vermogen $$ p$$ op. Op punten waar $$ u$$ of $$ i$$ nul is, is $$ p$$ ook nul. Wanneer zowel $$ u$$ als i $$ $$ p ositief zijn, is $$ p$$ ook positief. Wanneer $$ u$$ of $$ i$$ positief is en het andere negatief, is $$ p$$ is negatief. Als zowel $$ u$$ als $$ i$$ negatief zijn, is $$ p$$ positief. Zoals in figuur 9-30 te zien is volgt het ogenblikkelijk vermogen een sinusvormige curve. Positieve waarden van het vermogen geven aan dat er energie door de spoel wordt opgeslagen. Negatieve waarden van het vermogen duiden aan dat er energie wordt teruggestuurd van de spoel naar de bron. Merk op dat het vermogen fluctueert op een frequentie twee keer die van de spanning of stroom. Dit komt omdat energie afwisselend wordt opgeslagen en teruggestuurdnaar de bron.

**_Werkelijk vermogen_ **$$ {\mathit{P}}_{\mathit{w}\mathit{e}\mathit{r}\mathit{k}\mathit{e}\mathit{l}\mathit{i}\mathit{j}\mathit{k}}$$

Bij een ideale spoel wordt, alle tijdens het positieve deel van de vermogencyclus opgeslagen energie, tijdens het negatieve gedeelte teruggestuurd naar de bron. Er gaat geen netto energie verloren door omzetting in warmte in de ideale spoel, dus het vermogen is nul. In werkelijkheid zal er vanwege de windingsweerstand er altijd wat vermogen gedissipeerd worden. Dit is slechts een zeer klein deel van het vermogen en kan in de meeste situaties worden verwaarloosd. Het werkelijk vermogen is te vinden met onderstaande formule:

$$ {P}_{werkelijk}={I}_{eff}^{2} \times {R}_{W} (9-22)$$

![](/assets/afbeelding_11276.png)

Figuur 9-30 : vermogencurve voor een spoel

**_Reactief vermogen_ **$$ {\mathit{P}}_{\mathit{r}}$$

De snelheid waarmee een spoel energie opslaat of retourneert wordt het reactief of blind vermogen $$ Pr$$ genoemd. De eenheid van het reactief vermogen is $$ VAR$$ (volt-ampère reactief). Het reactievevermogen is een niet-nulhoeveelheid omdat op elk moment in de tijd de spoel eigenlijk ofwel energie uit de bron aan het nemen is ofwel energie terug naar de bron aan het afgeven is. Reactief vermogen vertegenwoordigt geen energieverlies door omzetting in warmte. De volgende formules zijn van toepassing :

$$ {P}_{r}={I}_{eff}\times {U}_{eff} (9-23)$$

$$ {P}_{r}=\frac{ {U}_{eff}^{2}}{ {X}_{L}} (9-24)$$

$$ {P}_{r}={I}_{eff}^{2}\mathrm{ }\times {X}_{L} (9-25)$$

### De kwaliteitsfactor $$ \mathit{Q}$$ {#de-kwaliteitsfactor-mathit-q}

De kwaliteitsfactor ( $$ Q$$ ) is de verhouding van het reactieve vermogen in de spoel tot het werkelijke vermogen in de wikkelweerstand van de spoel. Het is een verhouding van het vermogen in $$ L$$ tot het vermogen in $$ {R}_{W}$$ . De kwaliteitsfactor is belangrijk in resonantieschakelingen. De kwaliteitsfactor kan als volgt worden bepaald:

$$ Q=\frac{reactief vermogen}{werkelijkj vermogen}=\frac{ {P}_{r}}{ {P}_{werkelijk}}=\frac{ {I}^{2}\times {X}_{L}}{ {I}^{2}\times {R}_{W}}$$

$$ Q=\frac{ {X}_{L}}{ {R}_{W}} \left(9-26\right)$$

Merk op dat $$ Q$$ een verhouding van soortgelijke eenheden is en daarom zelf geen eenheid heeft. De kwaliteitsfactor is ook bekend als “ $$ onbelast Q$$ ” omdat het wordt gedefinieerd zonder belasting over de spoel. Tevens is $$ Q $$ afhankelijk van de frequentie omdat $$ {X}_{L}$$ afhankelijk is van de frequentie.

### Test jezelf : Het gedrag van een spoel op wisselstroom {#test-jezelf-het-gedrag-van-een-spoel-op-wisselstroom}

1.  Omschrijf de faserelatie tussen stroom en spanning in een spoel.

2.  Bereken $$ {X}_{L}$$ voor $$ f=500 kHz$$ en $$ L=10 mH$$ .

3.  Voor welke frequentie is de reactantie van een $$ 50 \mu H$$ spoel gelijk aan $$ 800 \Omega ?$$

4.  Over een spoel van $$ 10 \mu H$$ staat een effectieve spanning van $$ 1 V $$ met een frequentie van $$ 1 MHz.$$ Bereken de effectieve stroom door de spoel.

5.  Over een ideale spoel van $$ 50 mH$$ staat een effectieve spanning van $$ 12 V$$ . Wat is het werkelijk vermogen en wat is het reactief vermogen bij een frequentie van $$ 1 kHz?$$