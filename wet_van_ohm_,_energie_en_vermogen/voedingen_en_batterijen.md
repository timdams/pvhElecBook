## Voedingen en batterijen {#voedingen-en-batterijen}

In hoofdstuk 2 (sectie 2-3) hebben we in het kort voedingen en batterijen besproken. Een voeding of power supply is gedefinieerd als een toestel dat AC-spanning afkomstig van het net converteert tot een bepaalde DC-spanning die de meeste elektronische schakelingen en sommige transducers nodig hebben. Batterijen zijn eveneens in staat om een bepaalde DC-spanning te leveren. Veel systemen zoals bijvoorbeeld een laptop werken zowel met een voeding als met een interne batterij. In deze sectie worden een aantal typen van spanningsbronnen beschreven.

Wat is belangrijk?

*   **De kenmerken bespreken van voedingen en batterijen.**

*   **De controle op de typische laboratoriumvoedingen beschrijven.**

*   **De efficiëntie van een voeding bepalen aan de hand van het ingangs- en uitgangsvermogen.**

*   **Definiëren van begrip ampère-uur bij batterijen**

Algemeen wordt de netspanning (wisselspanning) gebruikt als leveringsbron van elektriciteit vanuit de elektriciteitscentrale naar de gebruiker toe. Wisselspanning wordt gebruikt omdat het gemakkelijk kan worden omgevormd tot zowel hoge spanningen als lage spanningen die geschikt zijn voor de eindgebruiker. Hoge spanningen zijn veel efficiënter en kosteneffectief te verzenden over lange afstanden. In Europa en andere landen is de netspanning gelijk aan _240 V__eff_ met een netfrequentie gelijk aan _50 Hz_. In de USA bedraagt de netspanning standaard _120 V__eff_ met een netfrequentie van _60 Hz_.

Vrijwel alle elektronische systemen vereisen een stabiele gelijkspanning om de geïntegreerde schakelingen en andere apparaten goed te laten functioneren. Voedingen vervullen deze functie door het omzetten van de wisselspanning naar een bepaalde gelijkspanning. Het stabiel houden van deze tot gelijkspanning omgevormde wisselspanning zit meestal ingebouwd in het product. Veel elektronische systemen hebben een verzonken en beschermde schakelaar die het mogelijk maakt de interne voeding in te stellen voor zowel _240 V__eff_als voor _120 V__eff_. Let echter wel op dat de schakelaar correct ingesteld staat vermits anders ernstige schade kan ontstaan aan de apparatuur.

In een labo worden schakelingen ontwikkeld en getest. Het doel van een labovoeding is de vereiste stabiele gelijkspanning voorzien die de te testen schakeling nodig heeft. Een testschakeling kan variëren van een eenvoudig resistief netwerk tot een complexe versterker, zender of logische schakeling.

Om aan de eis te voldoen dat er een constante spanning geleverd moet worden mag de gelijkspanning bijna geen rimpel meer bevatten. Men gebruikt de term rimpel om de mate van variatie in de gelijkspanning aan te duiden. Hoe groter de rimpel, hoe meer variatie in de gelijkspanning. Tevens moet een voeding ook voldoen aan de eis om de juiste constante spanning te behouden bij wisselende belasting of variaties in de netspanning. Labovoedingen moeten in staat zijn om verschillende spanningen te kunnen leveren. Vele elektronische schakelingen vereisen immers meer dan één spanning. Ook moet via een labovoeding het mogelijk zijn om de spanning op een exacte waarde te kunnen instellen alsmede de mogelijkheid om kleine wijzigingen aan te brengen om karakteristieken van elektronische componenten te kunnen bepalen of bepaalde schakelingen te kunnen uittesten.

In het elektronicalabo maken we gebruik van de labovoeding zoals in figuur 3-18 is te zien.

![](/assets/afbeelding_302.png) Deze heeft volgende kenmerken :

*   dubbele LCD display voor spanning en stroom

*   bestaat uit twee delen, kan parallel of in serie worden geschakeld

*   beveiligingsmode: stroombegrenzing

*   uitgangsconnectoren: IEC1010

*   beveiligd door zekering

De specificaties zijn :

*   uitgangsspanning: 5V/3A vast en 2 x 0-30V regelbaar

*   uitgangsstroom: 2 x 0-3A regelbaar

*   rimpelspanning: 1mV

*   afmetingen: 360 x 265 x 165mm

*   gewicht: 11.6kg

Indien je met dit toestel werkt in het labo kan je meer informatie bekomen aangaande de bediening via volgende link : [https://www.velleman.eu/downloads/2/ps23023gbnlfresd.pdf](https://www.velleman.eu/downloads/2/ps23023gbnlfresd.pdf)

$$ \mathit{P}=\mathit{U}\mathit{ }\times \mathit{I}=30\mathit{ }\mathit{V}\mathit{ }\times 3\mathit{ }\mathit{A}=90\mathit{ }\mathit{W}$$ Het vermogen dat een voeding kan leveren is gelijk aan het product van de absolute spanning met de stroom. Stel dat een voeding is _30 V_ kan leveren met een stroom van _3 A_ dan is het geleverde vermogen gelik aan _15 V_ vermenigvuldigt met _3 A_ gelijk aan _90_ W. Voor een tripple output voeding, zoals de vermelde labovoeding, is het totaal geleverde vermogen gelijk aan de som van de drie aanwezige voedingen in het toestel.

### Het rendement van een spanningsbron {#het-rendement-van-een-spanningsbron}

Het rendement  of efficiëntie is de verhouding van het uitgangsvermogen van de spanningsbron op het ingangsvermogen. In formulevorm :

$$ \mathit{ }=\frac{ {\mathit{P}}_{\mathit{O}\mathit{U}\mathit{T}}}{ {\mathit{P}}_{\mathit{I}\mathit{N}}}\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }(3-8)$$

Het rendement wordt dikwijls uitgedrukt in een percentage. Als bijvoorbeeld het ingangsvermogen gelijk is aan _100_ W en het uitgangsvermogen gelijk is aan _75_ W, dan is het rendement gelijk aan :

$$ \mathit{ }=\frac{ {\mathit{P}}_{\mathit{O}\mathit{U}\mathit{T}}}{ {\mathit{P}}_{\mathit{I}\mathit{N}}}=\frac{75\mathit{ }\mathit{W}}{100 W}=\mathrm{0,75}\mathit{ }\mathbf{o}\mathbf{f}\mathit{ }75\mathit{ }\mathit{\%}$$

Alle elektronische voedingen zijn energieomzetters en vereisen dat er vermogen wordt ingebracht om een bepaald vermogen uit te halen. Zo kan een elektronische gelijkspanningsvoeding via een stopcontact vermogen van het net gebruiken als ingangsvermogen. Het uitgangsvermogen wordt meestal geleverd via een ingestelde gelijkspanning. Het uitgangsvermogen is steeds minder dan het opgenomen vermogen uit de netspanning. Omdat een deel van de totale stroom intern wordt gebruikt voor de stroomvoorziening van de interne schakelingen, ontstaat er een intern energieverlies. Dit intern energieverlies wordt het vermogenverlies genoemd. Het uitgangsvermogen is bijgevolg gelijk aan het ingangsvermogen waarbij dit vermogenverlies wordt afgetrokken. Als het vermogenverlies wordt voorgesteld door $$ {P}_{LOSS}$$ kan het uitgangsvermogen als volgt bepaald worden:

$$ {\mathit{P}}_{\mathit{O}\mathit{U}\mathit{T}}={\mathit{P}}_{\mathit{I}\mathit{N}}-{\mathit{P}}_{\mathit{L}\mathit{O}\mathit{S}\mathit{S}}\mathit{ }\mathit{ }\mathit{ }\mathit{ }\mathit{ }(3-9)$$

$$ =\frac{ {P}_{OUT}}{ {P}_{IN}}=\frac{40 W}{64 W}=\mathrm{0,625} \mathrm{o}\mathrm{f} 62.5 \%$$ Een hoog rendement betekent dat er heel weinig vermogen wordt gedissipeerd in de voeding zelf. Hierdoor wordt er een hoger hoeveelheid uitgangsvermogen geleverd bij een gegeven ingangsvermogen.

### Het begrip ampère-uur (Ah) bij batterijen {#het-begrip-amp-re-uur-ah-bij-batterijen}

$$ 40 Ah=\mathrm{2,5} A \times x uur$$ Batterijen zetten opgeslagen chemische energie om in elektrische energie. Ze worden veel gebruikt voor het leveren van stabiele gelijkstroom aan kleine systemen zoals laptops en smartphones. De batterijen in deze kleine systemen zijn gewoonlijk oplaadbaar. Bij een oplaadbare batterij kan de chemische reactie worden omgekeerd via een externe spanningsbron. De capaciteit van een batterij wordt uitgedrukt in ampère-uur ( _Ah_ ). Op een batterij staat het aantal ampère-uur vermeld. Voor een oplaadbare batterij is het vermelde ampère-uur de maximale capaciteit die kan worden afgegeven alvorens deze opnieuw moet opgeladen worden. De ampère-uur-waarde van een batterij be paald hoelang een batterij een bepaalde hoeveelheid stroom kan leveren gedurende één uur. Bijvoorbeeld een batterij met vermelding _1500 mAh_ kan een stroom leveren van _1500 mA_ of _1,5 A_ gedurende _1_ uur aan een belasting. Dit betekent dat diezelfde batterij een stroom van _3 A_ kan leveren gedurende een half uur. Analoog kan deze batterij een stroom leveren van _750 mA_ gedurende twee uren. Hoe meer stroom de batterij moet leveren, hoe korter de levensduur van de batterij en omgekeerd. In de praktijk is de batterij gewoonlijk geschikt voor een bepaald stroomniveau en uitgangsspanning. Bijvoorbeeld een _12 V_ autobatterij kan worden beoordeeld voor _70 Ah_ bij een stroomsterkte van _3,5 A_ . Dit betekent dat deze batterij een gemiddelde stroom van _3,5 A_ kan leveren gedu rende _20_ uur bij de nominale spanning.

### Test jezelf aangaande voedingen en batterijen {#test-jezelf-aangaande-voedingen-en-batterijen}

1.  Als een laadinrichting een verhoogde hoeveelheid stroom uit een voeding trekt, vertegenwoordigt deze stroomverhoging een grotere of kleinere belasting op de voeding?

2.  Een voeding levert een uitgangsspanning van _10 V_. Indien deze voeding een stroom levert van _0,5 A_ aan een belasting, wat is het vermogen?

3.  Op een batterij staat vermeld _100 Ah_. Hoe lang kan zij een stroom van _5 A_ leveren aan een belasting?

4.  Als de hierboven vermelde batterij (in 3.) een _12 V_ batterij is, hoe groot is dan het vermogen dat aan de belasting wordt geleverd bij _0,5 A_ stroom?

5.  Een voeding in een labo werkt met een ingangsvermogen van _1_ W. Het kan een uitgangsvermogen leveren van _650 m_W. Wat is het rendement van deze voeding?