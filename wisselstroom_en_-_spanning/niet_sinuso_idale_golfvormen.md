## Niet sinusoïdale golfvormen {#niet-sinuso-dale-golfvormen}

Sinusgolven zijn belangrijk in de elektronica maar ze zijn niet het enige type van een wisselspanning of een in de tijd variërend signaal. De andere belangrijke golfvormen zijn de blokgolf en de driehoeksgolf.

Wat is belangrijk?

*   Je geeft de eigenschappen van een blokgolf weer.

*   Je vertelt de definitie van duty cycle.

*   Je geeft de eigenschappen van een zaagtandgolf weer.

*   Je verklaart de opbouw van een niet-sinusvormig signaal.

### Pulsgolven {#pulsgolven}

Een elektrische puls is een kortstondige spanning of stroom. Een puls komt veel voor in de digitale techniek waarbij bij positieve logica een positieve puls een $$ “1”$$ voorstelt en de pauze (of geen puls) een $$ “0”$$ .

In principe kan een puls worden beschreven als een zeer snelle overgang van een bepaald spannings- of stroomniveau naar een ander niveau waarbij na een bepaalde tijdsperiode terug een zeer snelle overgang volgt met als gevolg dat het spannings- of stroomniveau terug naar het oorspronkelijk basisniveau overgaat. Een puls is weergegeven in figuur 7-37.

| ![](/assets/afbeelding_11525.png) | ![](/assets/afbeelding_11526.png) |
| --- | --- |
| Positief gaande puls | Negatief gaande puls |

Figuur 7-37 : ideale pulsen

Voor een positief gaande puls geldt dat de baseline van een puls het laagste niveau van de volledige puls is.. Het is het niveau van spanning of stroom dat aanwezig is zonder dat de “pulsamplitude” aanwezig is. Van zodra de puls verschijnt verhoogt het spannings- of stroomniveau vanaf de baseline met een waarde gelijk aan de amplitude. Bij een ideale puls is de stijgtijd om van het baselineniveau tot het niveau van de amplitude te komen oneindig klein. Dit betekent dat de stijgende flank verticaal omhoog gaat. Hetzelfde geldt voor de flankverandering aan de achterzijde van de puls. Doordat de daaltijd oneindig klein is bij een ideale puls verkrijgen we ook hier een verticale lijn naar beneden.

De overgangen in niveau worden stappen genoemd. Een ideale puls bestaat uit twee tegengesteld lopende stappen van gelijke amplitude. Wanneer de flankverandering aan de voor- of achterkant van de puls positief is, spreekt men van een stijgende flank. Wanneer de flank aan de voor-of achterkant negatief gaande is, spreekt men van een dalende flank. Figuur 7-37 (a) toont een ideale positief gaande puls bestaande uit twee tegengesteld lopende ogenblikkelijke stappen, gescheiden door een interval van tijd dat pulsbreedte wordt genoemd. Figuur 7-37 (b) toont een ideale negatief gaande puls. De hoogte van de puls vanaf de baseline is de spannings- of stroomamplitude. Gewoonlijk wordt de analyse vereenvoudigd door het behandelen van pulsen als ideaal. Dit houdt in dat de pulsen meestal beschouwd worden als samengesteld uit ogenblikkelijke stappen die perfect rechthoekig van vorm zijn.

#### Kenmerken van een puls {#kenmerken-van-een-puls}

In de werkelijkheid zijn pulsen niet ideaal. Ze kunnen niet onmiddellijk veranderen van de ene toestand in de andere. Voor iedere stap is een zekere tijd vereist zoals weergegeven in figuur 7-38 (a). Er is een interval van tijd nodig om de puls van de ene toestand naar de andere te brengen. Dit interval wordt de stijgtijd genoemd.

| ![](/assets/afbeelding_11527.png) | ![](/assets/afbeelding_11528.png) |
| --- | --- |
| Stijg- en daaltijden | Pulsbreedte |

Figuur 7-38

De stijgtijd (rise time $$ {t}_{r}$$ ) is de tijd die nodig is voor een puls om van $$ 10\%$$ van zijn amplitude naar $$ 90\%$$ van zijn amplitude te gaan. De daaltijd (fall time $$ {t}_{f}$$ ) is de tijd nodig voor een puls om van $$ 90\%$$ van zijn amplitude naar $$ 10\%$$ van zijn amplitude te gaan. De pulsbreedte (puls width $$ {t}_{W}$$ ) is de tijd tussen het punt waarbij de voorste flank $$ 50\%$$ van zijn amplitude heeft bereikt tot het punt in de achterste flank waarbij de waarde eveneens gelijk is aan $$ 50\%$$ van de amplitude. De pulsbreedte wordt weergegeven in figuur 7-38.

#### Blokgolftrein (herhalende pulsen) {#blokgolftrein-herhalende-pulsen}

Elke golfvorm die zich op vaste tijdstippen herhaalt is periodiek. Figuur 7-39 toont enkele voorbeelden van periodieke pulsgolfvormen. Merk op dat de pulsen met regelmatige intervallen worden herhaald.

![](/assets/afbeelding_11529.png)

Figuur 7-39 : Zichzelf herhalende pulsvormen

De snelheid waarmee pulsvormen worden herhaaldis de pulsherhalingsfrequentie. Deze is de fundamentele frequentie van de golfvorm. De frequentie kan worden uitgedrukt in Hertz of in pulsen per seconde. De tijd vanaf een bepaalde positie van één puls tot het overeenkomstige punt op de volgende puls wordt periode $$ T$$ genoemd. De relatie tussen de frequentie en de periode is dezelfde als bij de sinusgolf ( $$ f$$ = 1/ $$ T$$ ).

De duty cycle is de verhouding van de pulsbreedte ( $$ {t}_{W}$$ ) tot de periode $$ T$$ en wordt meestal uitgedrukt als een percentage. In formulevorm:

$$ Percentage duty cycle=\frac{ {t}_{W}}{T} \times 100 \% \left(7-20\right)$$

#### Blokgolven {#blokgolven}

Een blokgolf is een pulsgolfvorm waarbij de duty cycle gelijk is aan $$ 50 \%$$ . Dit houdt in dat de pulsbreedte gelijk is aan een halve periode. In figuur 7-41 is een blokgolf weergegeven. Blokgolven worden dikwijls gebruikt als klok in digitale systemen.

![](/assets/afbeelding_324.png)

Figuur 7-41: blokgolf

#### De gemiddelde waarde van een pulsgolfvorm {#de-gemiddelde-waarde-van-een-pulsgolfvorm}

De gemiddelde waarde van een pulsgolfvorm is gelijk aan de baselinewaarde plus het product van duty cycle met zijn amplitude. Hierbij is de baselinewaarde het lage niveau van een positief gaande puls of het hoogste niveau van een negatief gaande puls. De formule om deze gemiddelde waarde te bepalen is gelijk aan :

$$ {U}_{gem}=basesline+\left(duty cycle \times amplitude\right) \left(7-21\right)$$

### Driehoeksgolfvorm en zaagtandvorm {#driehoeksgolfvorm-en-zaagtandvorm}

Driehoekige en zaagtandvormige golfvormen worden gevormd door lineaire spannings- of stroom- hellingen. Een helling stelt een lineaire toename of afname van de spanning of stroom voor. Figuur 7-43 toont zowel een positief als negatief lopende helling voor.

![](/assets/afbeelding_11530.png)

Figuur 7-43 : spanningshellingen

In figuur 7-43 (a) is de helling een positieve helling terwijl in figuur 7-43 (b) een negatieve helling te zien is. De hellingshoek is afhankelijk van de hoeveelheid spanning per tijdseenheid waarmee het signaal wordt vergroot of verkleind. Deze mate van stijging of daling wordt weergegeven met het begrip “slope”. In formulevorm:

$$ slope= \pm \frac{U}{t}$$

of in het geval bij een stroom:

$$ slope= \pm \frac{I}{t}$$

#### Driehoeksgolfvorm {#driehoeksgolfvorm}

De figuur 7-45 (a) toont een driehoekige golfvorm die is samengesteld uit een lineaire stijgende lijn en een lineair dalende lijn met gelijke hellingen. De periode van de golfvorm kan worden gemeten tussen bijvoorbeeld het positief maximum in de eerste periode en het positief maximum in de volgende periode. Dit is in de figuur 7-45 (a) weergegeven. De driehoeksgolf in deze figuur is alternerend en heeft een gemiddelde waarde gelijk aan nul.

| ![](/assets/afbeelding_348.png) |
| --- |
| ![](/assets/afbeelding_349.png) |

Figuur 7-45 : driehoeksgolfvormen

Figuur 7-45 (b) toont een driehoekige golfvorm met een gemiddelde waarde verschillend van nul. De frequentie voor driehoekige golven is op dezelfde manier bepaald als voor sinusvormige golven, namelijk: $$ f=\frac{1}{T}$$ .

#### Zaagtandvorm {#zaagtandvorm}

De zaagtandvorm is eigenlijk een speciaal geval van de driehoekige golfvorm. Hij bestaat uit twee hellingen waarvan één helling een veel langere duurtijd heeft als de andere. Zaagtandsgolfvormen worden gebruikt in vele elektronische systemen. Bijvoorbeeld in automatische testapparatuur wordt een zaagtandgolfvorm gebruikt. Ook bij besturingssystemen en bepaalde displays waaronder analoge oscilloscopen worden zaagtandvormen gebruikt. In figuur 7-46 is een voorbeeld van een zaagtandvorm weergegeven. Merk op dat deze bestaat uit een positieve helling van relatief lange duur gevolgd door een negatieve helling die relatief kort duurt.

![](/assets/afbeelding_351.png)

Figuur 7-46 : zaagtandgolfvorm

### Harmonischen {#harmonischen}

Een repetitieve niet sinusoïdale golfvorm bestaat uit sinusvormige golfvormen met een fundamentele frequentie of grondgolf en harmonischen. De grondfrequentie is de herhalingssnelheid van de golfvorm en de harmonischen zijn sinusgolven met een hogere frequentie die een veelvoud is van de fundamentele frequentie. Is de frequentie van de harmonische een even veelvoud van de fundamentele frequentie dan spreekt men van een even harmonische. Bijvoorbeeld als een bepaalde golf een fundamentele frequentie heeft van $$ 100 Hz$$ dan is de tweede harmonische gelijk aan $$ 200 Hz$$ en de vierde harmonische gelijk aan $$ 400 Hz, enz\dots $$ Is de frequentie van de harmonische een oneven veelvoud dan spreekt men van een oneven harmonische. Bijvoorbeeld een $$ 1 kHz$$ blokgolf bestaat uit een fundamentele frequentie (of grondgolf) van $$ 1 kHz$$ en oneven frequenties van $$ 3 kHz, 5 kHz, 7 kHz, enz\dots $$ De $$ 3 kHz$$ frequentie is in dit geval de derde harmonische en de $$ 5 kHz$$ frequentie de vijfde harmonische

| ![](/assets/afbeelding_353.png) | ![](/assets/afbeelding_355.png) |
| --- | --- |
| ![](/assets/afbeelding_356.png) | ![](/assets/afbeelding_358.png) |

Figuur 7-47 : Combinatie van oneven harmonischen vormen een blokpuls. (De amplitude van de omhullende is aangepast voor een betere verduidelijking)

Elke afwijking van een sinusgolf produceert harmonischen. Een niet sinusoïdale golfvorm is een samenstelling van de fundamentele frequentie en harmonischen. Sommige soorten golfvormen bestaan uit enkel oneven harmonische terwijl andere golfvormen dan weer bestaan uit enkel even harmonischen. Andere golfvormen bevatten dan weer zowel even- als oneven harmonischen. De vorm van de golf wordt bepaald door de aanwezige harmonischen.

Algemeen zijn voor het bepalen van de golfvorm alleen de fundamentele frequentie en het eerste paar harmonischen van significant belang. Een blokgolf is een voorbeeld van een golfvorm die bestaat uit een grondfrequentie en enkel oneven harmonischen. Wanneer de momentele waarden van de fundamentele en elke oneven harmonische op elke punt van de golfvorm algebraïsch worden opgeteld zal de resulterende curve de vorm van een blokgolf hebben

In figuur 7-47(a) produceren de fundamentele en de derde harmonische een golfvorm dat begint op een blokgolf te gelijken. In figuur 7-47 (b) is de vijfde harmonische toegevoegd waardoor de gelijkenis nog beter is. Bij het toevoegen van de zevende harmonische zal de resulterende golfvorm nog beter op een blokgolf gelijken enz. Hoe meer harmonischen er zijn inbegrepen, hoe beter een blokgolf wordt benaderd. Figuur 7-47 (d) zijn heel veel harmonischen toegevoegd waardoor het resultaat op een blokgolf gelijkt. De amplitude van de blokgolfvorm is groter dan normaal gekozen om een duidelijker beeld te bekomen. Per subfiguur is de vergelijking van de blokgolf neergeschreven in functie van het aantal gebruikte harmonischen.

### Analyse signalen in het frequentiedomein {#analyse-signalen-in-het-frequentiedomein}

Alle golfvormen kunnen opgesplitst worden in een groot aantal verschillende sinusgolven. Het frequentiedomein stelt de verschillende frequenties van een bepaalde golfvorm zichtbaar in functie van hun amplitude. Eenzelfde golf kan zowel weergegeven worden in het tijdsdomein als in het frequentiedomein. In het tijdsdomein wordt het signaal weergegeven als de som van alle frequenties in het signaal. Het frequentiedomein laat alle frequenties afzonderlijk zien die in het signaal zijn inbegrepen. Zowel tijds- als frequentiedomein zijn belangrijk voor het beschrijven van elektronische signalen.

![](/assets/afbeelding_360.png)

Figuur 7-48 : Tijd- en frequentiedomeinzichten van een signaal

De relatie tussen tijds- en frequentiedomein is voor het eerst wiskundig beschreven door Joseph Foerier in 1807\. De conversie tussen de domeinen wordt hierdoor genoemd als Fourieranalyse. De relatie is weergegeven in figuur 7-48\. Een spectrumanalyser kan het frequentiedomein weergeven en een oscilloscoop het tijdsdomein. In digitale oscilloscopen kan een voorziening aanwezig zijn waardoor ook het frequentiespectrum zichtbaar kan gemaakt worden. In figuur 7-49 (a) is het beeld weergeven van een blokgolf die samengesteld is uit zijn fundamentele golf (grondgolf) en de derde, vijfde en zevende harmonische. Figuur 7-49 (b) geeft ditzelfde signaal weer maar in het frequentiedomein via een spectrumanalyser. Spectrumanalysers zijn bruikbaar bij testen om na te gaan of er interferentie aanwezig in het WIFI-netwerk, afstandsbedieningen, smartphones? …

| ![](/assets/afbeelding_361.png) | ![](/assets/afbeelding_362.png) |
| --- | --- |
| Signaal gezien met de oscilloscoop | Hetzelfde signaal als in (a) maar nu gezien via een spectrumanalyser |

Figuur 7-49 : blokgolf, bestaande uit fundamentele frequentie en 3de, 5de en 7de harmonische, weergegeven in tijdsdomein (a) en frequentiedomein (b)

### Test jezelf : {#test-jezelf}

1.  Wat is stijgtijd (rise time), daaltijd (fall time) en pulsbreedte?

1.  **Bij een bepaalde positief gaande pulsvorm zijn de pulsjes** $$ 200\mathit{ }\mathit{\mu }\mathit{s}$$ **breed en verschijnen ze om de milliseconde.** Wat is de frequentie van deze pulsvorm?

1.  **Bepaal de amplitude, duty cycle en gemiddelde waarde van onderstaande golfvorm in figuur 7-50.** ![](/assets/afbeelding_363.png)

Figuur 7-50

1.  Wat is de periode van de driehoeksgolf van figuur 7-51?

![](/assets/afbeelding_366.png)

Figuur 7-51

1.  Wat is de frequentie van de zaagtandvorm in figuur 7-52?

![](/assets/afbeelding_367.png)

Figuur 7-52

1.  Definieer fundamentele frequentie.

1.  Wat is de tweede harmonische van een signaal met grondgolf 3 kHz?

1.  **Wat is de fundamentele frequentie van een blokgolf met een periodetijd gelijk aan** $$ 10\mathit{ }\mathit{\mu }\mathit{s}$$ **?**