## De brug van Wheatstone {#de-brug-van-wheatstone}

Een brug van Wheatstone bestaat uit vier weerstanden en kan gebruikt worden om weerstanden heel nauwkeurig te meten. Daarnaast kan deze ook gebruikt worden om fysische grootheden zoals temperatuur, druk, .. te meten. De verandering van de fysische grootheid wordt gemeten met een transducer die deze verandering omzet in weerstandsverandering.

Wat is belangrijk?

*   Je bepaalt wanneer een brug gebalanceerd is.

*   Je bepaalt wanneer een brug ongebalanceerd is.

*   Je bepaalt de weerstandswaarde van een onbekende weerstand met de brug van Wheatstone.

*   Je verklaart hoe je een meting kan verrichten met een ongebalanceerde brug.

Figuur 6-22 toont een brug van Wheatstone. Deze bestaat uit vier weerstanden en een spanningsbron die verbonden is tussen de boven- en onderzijde van de brug. De uitgangsspanning wordt afgenomen tussen de punten $$ A$$ en $$ B $$ van de schakeling. De brug bestaat in feite uit twee spanningsdelers die parallel geschakeld staan met elkaar.

### De gebalanceerde Wheatstonebrug {#de-gebalanceerde-wheatstonebrug}

Een Wheatstonebrug is gebalanceerd of in evenwicht als de uitgangsspanning $$ {U}_{out} $$ tussen de uitgangspunten $$ A$$ en $$ B$$ gelijk is aan $$ 0 V$$ . Als $$ {U}_{out}$$ gelijk is aan $$ 0 V$$ betekent dit dat de spanningen over $$ {R}_{1}$$ en $$ {R}_{3}$$ aan elkaar gelijk zijn en ook dat de spanningen over $$ {R}_{2}$$ en $$ {R}_{4}$$ aan elkaar gelijk zijn. In formulevorm: $$ {U}_{ {R}_{1}}={U}_{R3}$$ en $$ {U}_{R2}={U}_{R4}.$$ Dit betekent eveneens dat:

$$ \frac{ {U}_{R1}}{ {U}_{R2}}=\frac{ {U}_{R3}}{ {U}_{R4}}$$

![](/assets/afbeelding_466.png)

Figuur 6-22 : Brug van Wheatstone

Vervangen we de spanningsvallen door hun wet van Ohm equivalenten:

$$ \frac{ {I}_{1}\times {R}_{1}}{ {I}_{3}\times {R}_{2}}=\frac{ {I}_{2} \times {R}_{3}}{ {I}_{4}\times {R}_{4}}$$

Vermits $$ {I}_{1}={I}_{2}$$ en $$ {I}_{3}={I}_{4}$$ kunnen de stromen in bovenstaande vergelijking weggedeeld worden en kan deze vereenvoudigd worden tot :

$$ \frac{ {R}_{1}}{ {R}_{2}}=\frac{ {R}_{3}}{ {R}_{4}}$$

Of :

$$ {R}_{1}\times {R}_{4}= {R}_{2}\times {R}_{3}$$

Dit houdt in dat de brug in evenwicht is als het product van de schuin tegenover elkaar staande weerstanden aan elkaar gelijk is. De vergelijking is gemakkelijk om te vormen naar een vergelijking waarin je een onbekende weerstand in de brug te vinden in functie van de andere weerstandswaarden. Stel dat $$ {R}_{1}$$ deze onbekende weerstand is dan kan je deze vinden via volgende formule:

$$ {R}_{1}=\frac{ {R}_{2}\times {R}_{3}}{ {R}_{4}}= {R}_{2}\times \frac{ {R}_{3}}{ {R}_{4}} \left(6-2\right)$$

Hoe ga je nu praktisch te werk om deze onbekende weerstand te bepalen? Beschouw hiervoor de schakeling van figuur 6-23\. $$ {R}_{x}$$ is de onbekende weerstand die gemeten wordt. $$ {R}_{regel}$$ is de weer standswaarde van de regelbare weerstand om de brug in balans te brengen. Tussen de punten $$ A$$ en $$ B$$ aan de uitgang van de brug in figuur 6-22 plaats je een galvanometer. Dit is een ouder type meetinstrument waarmee gemakkelijk zeer kleine stromen gemeten kunnen worden. Wanneer er geen stroom meer vloeit tussen de punten $$ A$$ en $$ B$$ betekent dit dat de spanning op beide punten dezelfde is. Door de weerstand $$ {R}_{2}$$ regelbaar te maken kan je de brug afregelen zodat de meter $$ 0 \mu A $$ aangeeft waardoor $$ {U}_{out}$$ gelijk is aan $$ 0 V$$ . De verhouding van de weerstanden $$ {R}_{3}$$ op $$ {R}_{4}$$ vormt een schaalfactor. Wanneer je via schakelaars telkens andere weerstandswaarden kan schakelen voor $$ {R}_{3}$$ en/of $$ {R}_{4}$$ vergroot je het meetbereik van de brugschakeling. Hoe nauwkeuriger de weerstanden, hoe nauwkeuriger de onbekende weerstand in waarde kan gemeten worden. De onbekende weerstand kan dan gevonden worden met volgende formule:

$$ {R}_{x}={R}_{regel} \times \frac{ {R}_{3}}{ {R}_{4}}$$

![](/assets/afbeelding_468.png)

Figuur 6-23 : principeschakeling meten onbekende weerstand met Wheatstonebrug

### De ongebalanceerde Wheatstonebrug {#de-ongebalanceerde-wheatstonebrug}

Een ongebalanceerde brug is een brug waarbij de uitgangsspanning $$ {U}_{out}$$ niet gelijk is aan $$ 0 V$$ . Dit type brug wordt gebruikt om verschillende typen fysische grootheden zoals mechanische sterkte, temperatuur, druk, … te meten. In figuur 6-25 (b) is een voorbeeld van een ongebalanceerde Wheatstonebrug weergegeven. De transducer is een component die een fysische grootheid omzet naar een elektrische grootheid. Bijvoorbeeld een NTC. Dit is een **N** egatieve **T** emperatuurs- **C** oëfficiëntweerstand waarbij de weerstandswaarde daalt bij stijgende temperatuur.

| ![](/assets/afbeelding_474.png) | ![](/assets/afbeelding_480.png) |
| --- | --- |
| Ongebalanceerde brug met NTC | Schema ongebalanceerde brug |

Figuur 6-25 : voorbeeld van een ongebalanceerde brug met NTC als transducer om temperatuur in spanning om te zetten

Figuur 6-26

Figuur 6-25 stelt een ongebalanceerde Wheatstonebrug voor om temperatuur te meten. In dit voorbeeld is een NTC als thermistor (temperatuursafhankelijke weerstand) gebruikt. De weerstandswaarde van de NTC verandert op een voorspelbare manier als de temperatuur verandert. Een verandering in temperatuur veroorzaakt een verandering in thermische weerstand waardoor de uitgangsspanning zal veranderen. Deze uitgangsspanning kan met een voltmeter worden afgelezen. Deze spanning kan ook versterkt worden met een versterker en dan omgevormd worden via een ADC naar een digitale waarde. Een brug om temperatuur te meten is zodanig ontworpen dat ze in balans is bij een referentietemperatuur. Bijvoorbeeld de brug is in evenwicht bij $$ 25°C$$ . Dit betekent dat de NTC een gekende weerstandswaarde heeft bij deze temperatuur.

Een ander type weerstandsbrug is een brug die bestaat uit rekstrookjes. Rekstrookjes worden gebruikt om krachten te meten. Wanneer een rekstrookje een kracht ondervindt, wordt de weerstandsdraad ofwel uitgetrokken ofwel samengeduwd waardoor de weerstandswaarde verandert. Rekstrookjes worden in brug geplaatst. De brug is normaal in evenwicht. Naargelang de sterkte van de kracht op het rekstrookje verandert de weerstandswaarde en komt de brug uit evenwicht. Rekstrookjes zijn zeer delicaat en moeten voorzichtig behandeld worden. Een “load cell” is een transducer die rekstrookjes gebruikt om mechanische kracht om te vormen in een elektrisch signaal. Om gewicht te wegen is een load cell typisch in een S-vorm opgebouwd. Toepassingen van een brug met rekstrookjes vind je terug bij onder andere systemen die een reiskoffer wegen of de weegbrug voor vrachtwagens.

### Test jezelf : de brug van Wheatstone {#test-jezelf-de-brug-van-wheatstone}

1.  Onder welke conditie is een brug in balans?

2.  Hoe wordt de Wheatstonebrug gebruikt in ongebalanceerde mode?

3.  Wat is een “load cell”?

4.  Bereken de onbekende weerstand in de schakeling van figuur 6-27.

![](/assets/afbeelding_483.png)

Figuur 6-27