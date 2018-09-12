## Gemeten waarden
Wanneer een bepaalde hoeveelheid van een grootheid wordt gemeten, is er onzekerheid in het resultaat als gevolg van de beperkingen van de meetinstrumenten. Dikwijls bevat een meting een hoeveelheid geschatte waarden. Denk aan het laatste cijfer van een display dat meestal een afronding van de werkelijke waarde geeft. De cijfers waarvan zeker is dat ze correct zijn worden de beduidende cijfers (significant digits) genoemd. Bij het rapporteren van gemeten hoeveelheden moet de weergegeven meetwaarde bestaan uit de beduidende cijfers en maximaal één cijfer dat onzeker is (afgerond).

Wat onthoud je best na deze sectie?

De manier om een gemeten waarde correct weer te geven met het juiste aantal beduidende cijfers

*   De definitie van nauwkeurigheid (accuracy), fout (error) en precisie (precision)

*   De manier om getallen correct af te ronden

### Fout, nauwkeurigheid en precisie {#fout-nauwkeurigheid-en-precisie}

Metingen die je uitvoert aan een elektronisch circuit zijn niet perfect omdat de nauwkeurigheid van de meetresultaten afhankelijk zijn van de nauwkeurigheid van de meetapparatuur en de omstandigheden waaronder de meting is uitgevoerd. Als je de meetresultaten gaat rapporteren dien je rekening te houden met de fout die geassocieerd is met de meting. De gemeten fout mag niet gezien worden als een echte fout; eerder als een benadering van de werkelijke waarde.

Het verschil tussen de werkelijke of best geaccepteerder waarde van een bepaalde hoeveelheid en de gemeten waarde van die hoeveelheid wordt de fout (error) genoemd. Van een meting wordt gezegd dat ze nauwkeurig (accuracy) is als de fout klein is. Nauwkeurigheid is een indicatie van de foutenmarge in een meting. Stel bijvoorbeeld dat je de dikte van een 10 mm Gauge-meter wil meten met een micrometer en je meet 10,8 mm. Het meetverschil met de 10 mm standaard is hier 0,8 mm waaruit kan worden beschouwd dat de aflezing niet nauwkeurig is omdat een eindmaat (10 mm) wordt beschouwd als een werkende standaard. Als je 10.02 mm meet, is de meting nauwkeuriger omdat het redelijk overeenstemt met de norm.

![](/assets/afbeelding_3.png)  Een andere term geassocieerd met de kwaliteit van een meting is    precisie (precision).   Precisie is een maat voor de herhaalbaarheid (of consistentie) van een meting van een hoeveelheid. Het is mogelijk om een nauwkeurige meting te hebben waarbij een serie metingen niet verspreid liggen, maar elke meting onnauwkeurig is vanwege een fout in het meetinstrument. Bijvoorbeeld een meetinstrument kan uit kalibratie zijn en moet geherkalibreerd worden. Het toestel kan nog steeds precies meten maar door het verlopen van de kalibratie zijn de metingen onnauwkeurig geworden. Het is echter niet mogelijk om een ​​nauwkeurig instrument te hebben tenzij het ook nauwkeurig beduidende cijfers heeft. 

_Figuur 1-11 : visueel onderscheid tussen nauwkeurigheid en precisie_

Als je een meettoestel moet kalibreren zijn precisie en nauwkeurigheid belangrijke begrippen om te begrijpen. Kalibratie is het proces waarmee de meetwaarde van een bepaald instrument wordt vergeleken met een gegeven standaard . De standaard moet over het algemeen met een factor 4 nauwkeuriger zijn dan het te kalibreren instrument. Maar dit alleen is niet voldoende. Om de nauwkeurigheid te verzekeren, moet de kalibratie certificeerbaar zijn en moet het herleidbaar zijn naar de nationale normen die te vinden zijn (in de VS, is dit National Institute of Standards and Technology). De standaard vereist periodiek hernieuwen van de certificatie om de _nauwkeurigheid_ te verzekeren.

Figuur 1-12 toont het onderscheid aan tussen wat met nauwkeurigheid wordt bedoeld en wat met precisie aan de hand van een voorbeeld. Stel een schutter schiet met zijn jachtgeweer op een doel. Wanneer hij heel precies richt maar niet nauwkeurig schiet hij zijn kogels dicht bij elkaar maar niet in het midden van het doel. Er is een zekere afwijking tussen het midden van het doel en de kogelinslagen in het doel. Dit is weergegeven in figuur 1-12 (a).

![](/assets/afbeelding_8.png) 

Figuur 1-12 : onderscheid tussen precisie en nauwkeurigheid

In de situatie waarbij de schutter heel precies en heel nauwkeurig is (fig. 1-12 (b)), zijn alle kogelinslagen in het midden van het doel. Als de schutter wel nauwkeurig mikt maar niet precies is (Fig. 1-12 (c)), zijn de kogelinslagen dicht bij het midden van het doel, maar liggen ze niet samen. Als hij zowel niet precies als nauwkeurig schiet (Figuur 1-12 (d)), liggen de kogelinslagen her en der verspreid op het doel.

### Beduidende cijfers {#beduidende-cijfers}

De cijfers in een gemeten getal waarvan bekend is dat ze correct zijn worden beduidende cijfers of significante cijfers (digits) genoemd. De meeste meetinstrumenten tonen het juiste aantal significante cijfers. Sommige meetinstrumenten kunnen cijfers die niet significant zijn weergeven en laten het aan de gebruiker over om te bepalen wat moet worden gerapporteerd. Dit kan optreden als gevolg van een effect genaamd belastingseffect (zie hoofdstuk 6 sectie 4). Een meter kan de actuele meting in een circuit beïnvloeden door zijn aanwezigheid. Denk hierbij aan de inwendige weerstand van de meter. Het is belangrijk om te herkennen wanneer een meting onnauwkeurig kan zijn. Bij onnauwkeurigheden moet je niet de cijfers vermelden waarvan bekend is dat ze onjuist zijn.

Een ander probleem met beduidende cijfers doet zich voor wanneer je wiskundige bewerkingen uitvoert met getallen. Het aantal beduidende cijfers mag nooit hoger zijn dan het aantal cijfers in de oorspronkelijke meting. Stel bijvoorbeeld dat je 1,0 V moet delen door 3,0 Ω . Als je deze deling uitvoert met een rekenmachine geeft deze de waarde 0,33333333 weer. Aangezien de originele getallen elk twee beduidende cijfers bevatten moet het antwoord 0,33 A zijn. Het aantal beduidende cijfers van het resultaat moet dus hetzelfde zijn als het aantal beduidende cijfers dat aanwezig is in de getallen die met elkaar gedeeld worden.

De regels voor het bepalen of een gerapporteerd cijfer beduidend (significant) is zijn de volgende:

1.  De cijfers die verschillend zin van nul (nonzero) worden altijd als beduidend beschouwd.

2.  Nullen aan de linkerzijde van het eerste “niet-nul” cijfer zijn nooit beduidend.

3.  Nullen tussen “niet-nul” cijfers zijn steeds beduidend.

4.  Nullen rechts van de komma zijn beduidend.

5.  Nullen links van de komma die samen met beduidende cijfers een bepaald getal vormen kunnen al dan niet beduidend zijn afhankelijk van de meting. Zo heeft bijvoorbeeld het getal 35200 Ω drie, vier of vijf beduidende cijfers. Hoeveel beduidende cijfers er gebruikt worden hangt af van het feit wat de beduidende cijfers voorstellen. Indien ze een wetenschappelijke notatie voorstellen (of een metrisch systeem) zoals bijvoorbeeld 35,2 kΩ, dan bevat het getal vier beduidende cijfers.

Wanneer een gemeten waarde wordt gerapporteerd mag er maar één onzeker cijfer worden bewaard. Al de andere moeten verwijderd worden. Om het aantal beduidende cijfers te vinden in een getal kan men het volgende toepassen:

*   Negeer de komma, en tel het aantal cijfers van links naar rechts te beginnen met het eerste “niet-nul” cijfer en eindigend met het laatste cijfer aan de rechterkant.

*   Alle getelde cijfers zijn beduidende cijfers behalve de nullen aan het rechtereinde, welke al dan niet beduidende kunnen zijn.

*   Bij gebrek aan verdere informatie is de beduidendheid (significantie) van de rechter nullen onzeker.

*   Algemeen: nullen die plaatshouders zijn en geen deel uitmaken van de meting worden geacht niet beduidend te zijn.

*   Om verwarring te voorkomen moeten getallen voorgesteld worden met behulp van de wetenschappelijke- of engineering notatie om te zien welke nullen beduidend zijn.

Voorbeeld 1-9

Geef het getal **7500** weer met twee, drie en vier beduidende cijfers.

Oplossing

Nullen die zich rechts van de komma bevinden zijn beduidend. Bijgevolg om het getal te schrijven met twee beduidende cijfers bekomt men :

**7,5 x 10** **3**

Het getal met drie beduidende cijfers :

**7,50 x 10** **3**

Tot slot het getal met vier beduidende cijfers :

**7,500 x 10** **3**

Voorbeeld 1-10

Onderlijn de beduidende cijfers in ieder van volgende metingen :

1.  **20,0** (b) **0,4030**(c) **3,60 x 10****6**(d) **0,00609**

Oplossing

1.  **20,0** heeft drie beduidende cijfers (zie regel 4)

2.  **0,** **4030** heeft vier beduidende cijfers (zie regels 2 en 3)

3.  **3,60** **x 10** **6** heeft drie” beduidende cijfers (zie regel 3)

4.  **0,00** **609** heeft drie beduidende cijfers (zie regels 2 en 3)

### Afronden van getallen {#afronden-van-getallen}

Metingen bevatten steeds benaderende cijfers . Zoals reeds is vermeld worden meetwaarden enkel weergeven met enkel de beduidende cijfers en niet meer dan één onzeker cijfer. Het aantal cijfers dat wordt getoond is indicatief voor de nauwkeurigheid van de meting. Om deze reden moet je de meetwaarde afronden door één of meerdere cijfers (digits), die zich uiterst rechts van het getal van de meetwaarde bevinden, te laten vallen. Gebruik alleen het meest significante weggelaten cijfer om te beslissen hoe af te ronden.

De regels voor het afronden zijn:

1.  Als het meest significante cijfer van de te laten vallen cijfers **groter is dan 5, verhoog dan het laatste behouden cijfer** met 1

2.  Indien het meest significante cijfer van de te laten vallen cijfers **kleiner is dan 5, verander dan niets** aan het laatste behouden cijfer

3.  Indien het meest significante cijfer van de te laten vallen cijfers **gelijk is aan 5, verhoog het laatste behouden cijfer enkel met 1 als het verhogen maakt dat dit cijfer een even getal wordt**. Anders niet. Dit wordt de **“round-to-even” regel** genoemd.

In de meeste elektrische- en elektronische schakelingen hebben de componenten meestal toleranties die meer dan 1% (5% en 10% is gebruikelijk) bedragen. De meeste meetinstrumenten hebben nauwkeurgheidsspecificaties die beter zijn dan dit. Het is echter ongebruikelijk dat metingen worden gedaan met een hogere nauwkeurigheid dan 1: 1000\. Daarom zijn in alle situaties drie beduidende cijfers geschikt om getallen voor te stellen die gemeten hoeveelheden voorstellen behalve diegene die een zeer hoge nauwkeurigheid van de metingen vereisen. Als berekeningen moeten worden uitgevoerd met een aantal tussentijdse resultaten, bewaar alle cijfers in je rekenmachine, maar rond de antwoorden af op drie cijfers bij het rapporteren van een resultaat.

Voorbeeld 1-11

Rond ieder van onderstaande getallen af tot drie beduidende cijfers :

1.  **80,072** (b) **13,941**(c) **3,2947**(d) **682,53**

Oplossing

1.  **80,072** wordt afgerond tot **80,1**

2.  **13,941** wordt afgerond tot **14,0**

3.  **3,2947** wordt afgerond tot **3,29**

4.  **682,53** wordt afgerond tot **682**

### Test jezelf aangaande gemeten waarden {#test-jezelf-aangaande-gemeten-waarden}

1.  Wat is de regel om nullen weer te geven in een getal aan de rechterzijde van de komma?

2.  Wat is de “round-to-even” regel?

3.  **In schema’s zie je dikwijls een 1000** **Ω** **weerstand weergegeven als een 1,0 k** **Ω** **.** Welke invloed heeft dit op de waarde van de weerstand?

4.  Als een voeding (power supply) moet ingesteld worden op 10,00V, wat houdt dit in aangaande de nauwkeurigheid die nodig is voor het meetinstrument?

5.  Hoe kan men de wetenschappelijke- of de engineering notatie gebruiken om het correcte getal te tonen van de beduidende cijfers in een meting?
