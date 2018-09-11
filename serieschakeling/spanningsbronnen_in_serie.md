## Spanningsbronnen in serie {#spanningsbronnen-in-serie}

Een spanningsbron is een energiebron die een constante spanning aan een belasting levert. Batterijen en voedingen (power supplys) zijn praktische voorbeelden van een spanningsbron. Wanneer twee of meer spanningsbronnen in serie staan, is de totale spanning gelijk aan de algebraïsche som van deze twee spanningsbronnen.

Wat is belangrijk?

*   Je kan de totale spanning van een aantal spanningsbronnen in serie bepalen met dezelfde polariteit.

*   Je kan de totale spanning van een aantal spanningsbronnen in serie bepalen met tegengestelde polariteit.

Om een hogere spanning te bekomen worden een aantal batterijen in serie geplaatst. Zo worden bijvoorbeeld in een bepaalde zaklamp vier batterijen in serie geplaatst om een lamp van _6 V_ te laten branden. In afstandsbedieningen zie je dikwijls twee batterijen in serie om _3 V_ te bekomen.

![](/assets/afbeelding_11306.png)

Figuur 4-21 : schematisch overzicht van een zaklamp met lamp op 6 V

In figuur 4-21 is het schema van de schakeling weergegeven van een zaklamp met een lamp werkend op $$ 6 V$$ . Bronnen die in serie worden geplaatst met hun polariteit in dezelfde richting leveren een totale spanning op dat gelijk is aan de som van de afzonderlijke spanningen van deze bronnen. Voor figuur 4-21 verkrijgen we aldus:

$$ {U}_{T}={U}_{1}+{U}_{2}+{U}_{3}+{U}_{4}=1,5 V+\mathrm{1,5} V+\mathrm{1,5} V+\mathrm{1,5} V=6 V$$

Er is geen geldige reden om een batterij omgekeerd te plaatsen ten opzichte van de andere batterijen. Dit kan leiden tot grote stromen en reduceert de levensduur van de batterij.

$$ {U}_{T}={U}_{1}+{U}_{2}+{U}_{3}=12 V+6 V+2 V=20 V$$

### Positieve- en negatieve voedingsspanning {#positieve-en-negatieve-voedingsspanning}

Veel schakelingen maken gebruik van positieve en negatieve voedingsspanningen. Een dubbele voeding (power supply) heeft meestal twee uitgangen die onafhankelijk van elkaar zijn. In figuur 4-23 is weergegeven hoe je zo’n positieve en negatieve voedingsspanning kan maken met de voeding van het labo.

![](/assets/afbeelding_11319.png)

Figuur 4-23 : instelling labovoeding om een positief 30 V en negatief 30 V spanning te bekomen

Door de linker trackingknop in te drukken op de labovoeding worden intern de twee onafhankelijke voedingen binnen het toestel in serie geschakeld. De tracking zorgt er ook voor dat de instellingen die gemaakt worden op de rechtervoeding (master) automatisch ook gemaakt worden voor de linkervoeding (slave). Zo kan je bijvoorbeeld de rechtervoeding instellen op $$ + 30 V$$ waardoor automatisch de voedingsspanning van de linkervoeding ook op $$ 30 V$$ komt. Wens je dit niet dan duw je de linker trackingknop niet in. Nu kan je de beide spanningsbronnen onafhankelijk van elkaar regelen om bijvoorbeeld $$ +10 V$$ te bekomen en $$ – 5V$$ . Als je deze knop niet indrukt, moet je wel een verbinding leggen tussen de rode uitgangsstekker van de linkervoeding met de zwarte uitgangsstekker van de rechtervoeding om beide voedingen in serie te schakelen.

Stel dat je een voedingsspanning van $$ + 30 V$$ en $$ – 30 V$$ wenst te bekomen om bijvoorbeeld een audioversterker te voeden. Dit kan je doen zoals aangegeven in figuur 4-23\. Je drukt de linker trackingtoets in en regelt de spanning van de rechtervoeding op $$ 30 V.$$ Zoals reeds vermeld komt dan automatisch de spanning van de linkervoeding ook op $$ 30 V$$ . Het induwen van de trackingknop zorgde ervoor dat intern de beide voedingen in serie zijn geschakeld en met elkaar zijn doorverbonden. De rode uitgang van de linkervoeding wordt hierdoor immers automatisch verbonden met de zwarte uitgang rechtervoeding. Door nu, zoals te zien in figuur 4-23, een zwarte kabel in de zwarte uitgang van de linkervoeding te steken en een blauwe kabel in de rode uitgang van deze voeding bekomen we een spanning van $$ 30 V$$ . Gebruiken we de blauwe kabel als massa, dan heeft de spanning op de zwarte kabel een potentiaal dat $$ 30 V$$ lager ligt dan het potentiaal op de blauwe kabel. Steekt men een rode kabel in de rode uitgang van de rechtervoeding, dan hebben we op deze kabel een potentiaal dat $$ 30 V$$ hoger ligt dan het potentiaal op de blauwe kabel. Wil je de blauwe kabel op aardingspotentiaal, dan verbind je deze kabel eveneens met één van de groene uitgangen die je op de labovoeding ziet. Vermits beide spanningsbronnen in serie staan, is de totale spanning tussen de zwarte en rode kabel gelijk aan $$ 60 V$$ (wat overeenkomt met de som van beide spanningen van de spanningsbronnen).

### Zonnepanelen in serie {#zonnepanelen-in-serie}

Zonnepanelen (modules) zijn samengesteld uit vele zonnecellen die in een rij in serie staan om in volle zon een bepaalde spanning te produceren. Elke zonnecel levert ongeveer een $$ 0,5 V$$ spanning op in de volle som. Daarom moet bij een $$ 18 V$$ paneel ten minste $$ 36$$ zonnecellen in serie zijn geschakeld. Om een $$ 24 V$$ paneel te bekomen heeft men tenminste $$ 48$$ zonnecellen in serie nodig. Om een batterij te kunnen opladen is dit voor de meeste applicaties voldoende. Volgens de specificaties , gespecificeerd onder standaard testomstandigheden (STC) die vergelijkingen tussen modules maken, variëren de spanningen van $$ \mathrm{16,5} V$$ tot $$ \mathrm{72,3} V$$_._ De werkelijke gebruiksomstandigheden zijn verschillend.

![](/assets/afbeelding_11324.png)

Figuur 4-24 : Voorbeeld van een klein elektrisch systeem met zonnepanelen

De zonnepanelen zetten zonlicht om in DC elektrische energie. Deze energie wordt naar een ladingscontroller verzonden . Deze regelt de laadstroom van de batterijen om overladen te voorkomen. De laadregelaar voorkomt eveneens dat de batterijen zich over zonnepanelen zouden ontladen als er geen zon is. De omvormer zet de gelijkstroom van de batterijen om naar een wisselstroom. Deze wisselstroom kan als voeding gebruikt worden van kleine apparaten. In het voorbeeldsysteem is de omvormer een basistoestel. Niet een speciaal (duurdere) omvormer zoals een netgekoppelde omvormer.

Voor de meeste systemen zijn de een aantal zonnepanelen onderling verbonden om een hoge gelijkspanning te bekomen alvorens deze om te vormen naar wisselstroom (AC). De nominale spanning van een paneel en de spanning van de omvormer bepalen hoeveel modules in serie moeten geplaatst worden. Alle componenten in het systeem (met inbegrip van zonnepanelen, bekabeling en omvormers) moeten geschikt zijn voor de maximale toegestane spanning van $$ 600 V$$ voor de meeste installaties.

In dit voorbeeld wordt uitgegaan van een paneel dat een maximale spanning heeft van $$ 42 V$$ en een vermogen van $$ 250 W$$ . Het aantal van deze panelen dat in serie moet worden geplaatst is afhankelijk van de maximale toegestane spanning. Voor een toelaatbare spanning van $$ 600 V$$ moeten 14 panelen in serie geschakeld worden. In dit geval is de maximale spanning gelijk aan $$ 588 V$$ (Mag niet meer dan $$ 600 V$$ bedragen). Het voordeel van de serieschakeling van deze panelen is dat met de hogere spanning een hoger rendement kan bereikt worden en een dunnere draad kan gebruikt worden vermits de stroom hetzelfde blijft. Het maximaal vermogen is dan te bepalen via de $$ 14$$ panelen die in serie staan en elk een vermogen van $$ 250 W$$ leveren. Dit is gelijk aan : $$ 14 panelen \times 250 W$$ per paneel wat gelijk is aan $$ 3500 W$$ .

### Test jezelf : Spanningsbronnen in serie {#test-jezelf-spanningsbronnen-in-serie}

1.  1.  1.  1.  **Hoeveel** $$ 12\mathit{ }\mathit{V}$$ **batterijen moeten in serie worden geschakeld om** $$ 60\mathit{ }\mathit{V}$$ ******te bekomen?**

            2.  **Als er vier batterijen van** $$ \mathrm{1,5}\mathit{ }\mathit{V}$$ **in serie in een zaklamp worden geplaatst, hoeveel bedraagt dan de spanningsval over de lamp?**

            3.  Bepaal de totale spanning in de schakeling van figuur 4-25.

![](/assets/afbeelding_11325.png)

figuur 4-25