## Toepassen van de wet van Ohm {#toepassen-van-de-wet-van-ohm}

In deze paragraaf worden voorbeelden weergegeven van de toepassing van de wet van Ohm. De voorbeelden gaan over het berekenen van de spanning, stroom en weerstand in elektrische schakelingen. Je zal ook zien hoe je hoeveelheden, uitgedrukt met metrische voorvoegsels, kan toepassen in de berekeningen.

Wat onthoud je best?

*   Hoe je via de wet van Ohm spanning, stroom of weerstand bepaalt.

*   Via de wet van Ohm de stroom bepalen als je de spanning en de weerstand kent.

*   Via de wet van Ohm de spanning bepalen als je de stroom en weerstand kent.

*   Via de wet van Ohm de weerstand bepalen als je de spanning en stroom kent.

*   Hoe je gebruik kan maken van hoeveelheden met metrische voorvoegsels.

### Stroomberekeningen {#stroomberekeningen}

$$ I= \frac{U}{R}= \frac{3 V}{220 \Omega }=\mathrm{13,64} mA$$ In volgende voorbeelden leer je de stroomwaarden te bepalen vanuit de waarden van spanning en weerstand. Om de stroom te vinden is de formule _I = U/ R_ gebruikt. Om de stroom in ampère te krijgen, moet u de waarde van V in volt en de waarde van R in ohm geschreven zijn.

![](/assets/afbeelding_11564.png)

Figuur 3-5

Voorbeeld 3-6

Bereken de stroom in milliampères voor de schakeling in de figuur 3-5 en maak gebruik van prefixes.

Oplossing

$$ I= \frac{20 V}{1 k\mathrm{\Omega }}= \frac{20 V}{1 \times {10}^{3}\mathrm{\Omega }}=20 \times {10}^{-3}A=20 mA$$ Met prefixes ….

$$ I=\frac{50 V}{\mathrm{6,8} M\Omega }= \frac{50 V}{\mathrm{6,8} \times {10}^{6}\Omega }=\mathrm{7,35} \times {10}^{-6} A=\mathrm{7,35} \mu A$$ $$ I=\frac{200m V}{\mathrm{2,7} M\Omega }= \frac{200 \times {10}^{-3 } V}{\mathrm{2,7} \times {10}^{6}\Omega }=\mathrm{74,07} \times {10}^{-9} A=\mathrm{74,07} nA$$

### Spanningsberekeningen {#spanningsberekeningen}

In volgende voorbeelden leer je de spanning bepalen als de weerstandswaarde en de stroomsterkte erdoor gekend. Ook zijn er voorbeelden bij die gebruik maken van de prefixen.

![](/assets/afbeelding_11566.png)

Figuur 3-7

$$ U=I \times R= 3 A \times 200 \Omega =600 V$$

$$ U=I \times R= 10 mA \times \mathrm{2,7} k\Omega =10 \times {10}^{-3 }A \times \mathrm{2,7} \times {10}^{3} \Omega = 27 V$$

$$ {V}_{R}=I \times R=180 \mu A \times \mathrm{5,6} k\Omega =\mathrm{1,008} V$$

### Weerstandsberekeningen {#weerstandsberekeningen}

$$ R=\frac{U}{I}=\frac{6 V}{500 mA}=12 \Omega $$Onderstaande voorbeelden geven je meer inzicht hoe je met de wet van Ohm de weerstandswaarde kan bepalen.

$$ R=\frac{U}{I}=\frac{5 V}{\mathrm{1,20} mA}=4167 \Omega of \mathrm{4,17} k\Omega $$

### Toepassingsvoorbeeld : Stroomdetectieweerstand in een batterijlader {#toepassingsvoorbeeld-stroomdetectieweerstand-in-een-batterijlader}

Stroomdetectieweerstanden zijn precisie laagwaardige weerstanden die dikwijls gebruikt worden in diverse schakelingen. Een voorbeeld van zo’n schakeling is een batterijlaadschakeling. Ook in onder andere motorcontrolesystemen, de automobielnijverheid, telecommunicatiesystemen en computers worden ze toegepast.

Zoals de wet van Ohm zegt, staat er een spanningsval over de weerstand wanneer er een stroom doorvloeit. De stoomdetectieweerstand converteert de stroom die doorheen gaat om in een spanning die gemakkelijk kan worden gemeten en bewaakt. De meeste toepassingen met stroomdetectieweerstanden gebruiken precisie SMD-weerstanden. Dit zijn minuscule weerstandjes die weinig plaats vragen op een PCB. Ze hebben een lage weerstandswaarde om het vermogensverlies door zelfopwarmingseffecten te minimaliseren. Weerstandswaarden van _20_ tot _25 m_ _Ω_ komen veel voor.

Figuur 3-12 toont een principeschema van een bepaald type batterijlader waarbij de hoeveelheid stroom kan geregeld worden in functie van de hoeveelheid lading in de op te laden batterij. De stroomdetectieweerstand is weergegeven in het rood. Stroomdetectieweerstanden worden ook wel eens **_current sensing resistor_** genoemd.

![](/assets/afbeelding_295.png)

Figuur 3-12: Principeschakeling van een batterijlader met een stroomdetectieweerstand.

De stroom die de lader levert richting batterij wordt door de stroomdetectieweerstand omgezet in een kleine spanning. De controller kan deze kleine spanningsval bewaken doordat deze via de stroomdetectielijnen naar de controller wordt toegevoerd. De controller is in staat om de hoeveelheid stroom, op basis van een optimaal oplaadprofiel, aan te passen. Op die wijze zorgt de controller ervoor dat de laadschakeling heel efficiënt en betrouwbaar de batterij kan opladen. Immers de spanningsdetectielijn in de schakeling van figuur 3-12 zorgt ervoor dat de controller de actuele spanning van de op te laden batterij kent. Aan de hand van die spanning wordt via de schakeltransistor en de spoel de stroom door de stroomdetectieweerstand geregeld. De controller zorgt er voor dat hoe meer de batterij is opgeladen, hoe lager de laadstroom wordt. Op die wijze kan beschadiging van de batterij voorkomen worden.

### Test jezelf aangaande het toepassen van de wet van Ohm. {#test-jezelf-aangaande-het-toepassen-van-de-wet-van-ohm}

1.  Als _U = 10 V_ en _R = 4,7_ _Ω__,_ hoeveel is dan _I_?

2.  Als over een _4,7 M_ _Ω_ _20kV_ staat, hoeveel bedraagt dan _I_?

3.  Hoeveel stroom zal een spanning van _10 kV_ produceren over een weerstand van _2k__Ω_?

4.  _I = 1 A_ en _R = 10_ _Ω_; hoeveel bedraagt de spanning _U_?

5.  Welke spanning heb je nodig om 3mA te produceren door een weerstand van 3k Ω?

6.  Een batterij produceert 2A stroom door een 6 Ω weerstand. Wat is de batterijspanning?

7.  _U = 10 V_ _en I = 2A_ , bepaal _R_.

8.  In een stereoversterker vind je een weerstand waarover je _25 V_ meet en waardoor _50 mA_ stroom vloeit volgens de aangesloten stroommeter. Hoeveel bedraagt de weerstandswaarde in _k__Ω_ en in _Ω_?