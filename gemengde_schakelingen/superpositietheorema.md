## Superpositietheorema {#superpositietheorema}

Bepaalde systemen werken met meer dan één bron. Denk maar aan versterkers waar zowel een AC-bron (bv. audio) als een DC-bron aanwezig zijn. Wanneer er meerdere bronnen gebruikt worden in een schakeling is superpositie een middel om de analyse uit te voeren.

Wat is belangrijk?

*   Je past superpositie toe op schakelingen met meerdere spanningsbronnen.

*   Je verklaart de verschillende stappen om superpositie toe te passen.

Wat is superpositie? Superpositie is een manier om stromen te bepalen in een circuit wanneer er meerdere bronnen aanwezig zijn . Hoe? Door afwisselend één bron in het circuit te laten en de andere te vervangen door hun inwendige weerstanden (deze is $$ 0 \Omega $$ als de bron ideaal kan beschouwd worden) . Het totale resultaat (stromen in de verschillende deelketens) wordt gevonden door de resultaten van iedere bron op te tellen.

De stappen voor analyse met superpositie :

*   **_Stap 1:_ **Laat één spanningsbron (of stroombron) in het circuit en vervang alle andere bronnen door hun inwendige weerstand. Voor bronnen die ideaal beschouwd mogen worden is hun inwendige weerstand 0 ohm (kortsluiting). Indien het om een stroombron gaat die ideaal mag worden verondersteld, dan is deze inwendige weerstand gelijk aan oneindig (open keten)

*   **_Stap 2:_ **Bepaal de specifieke stroom of spanning die je wil weten in het circuit (met één bron in het circuit) Dit is een component van de totale stroom of spanning waarnaar je op zoek bent.

*   **_Stap 3:_ **Neem de volgende bron in het circuit en herhaal de eerste twee stappen. Doe dit voor elke bron die aanwezig is in het circuit.

*   **_Stap 4:_ **Om de werkelijke stroom te weten van de stroom die je zoekt, hoef je nu nog algebraïsch de som maken van alle gevonden resultaten met één bron in de schakeling. Eens je de stroom kent, kan je via de wet van Ohm de spanning bepalen

Merk op dat DC-bronnen doorgaans als ideaal zijn te beschouwen. Echter de meeste AC-bronnen zijn dat niet. Vooral functiegeneratoren hebben een inwendige weerstand van 50 Ω of 600 Ω . Stroombronnen zijn doorgaans ook niet ideaal. In het geval van transistoren moeten ze door hun equivalente inwendige weerstand worden vervangen. In figuur 6-45 (a) is een voorbeeldschakeling weergegeven met twee spanningsbronnen en drie weerstanden. Het is de bedoeling om de stroom door $$ {R}_{2}$$ te bepalen. De eerste stap die genomen wordt is één van de spanningsbronnen kortsluiten en vervolgens de stroom bepalen door $$ {R}_{2}.$$ Dit is weergegeven is figuur 6-45 (b). Figuur 6-45 (c) toont een hertekend schema van de schakeling van figuur 6-45 (b).

![](/assets/afbeelding_524.png)

Figuur 6-45 : Superpositie toepassen door eerst spanningsbron $$ {U}_{2}$$ als kortsluiting te aanzien

De volgende stap die genomen wordt is nu met de spanningsbron $$ {U}_{1}$$ de stroom te bepalen die door de weerstand $$ {R}_{2}$$ vloeit. Hiervoor bepaal je eerst de totale weerstand $$ {R}_{parallel1}$$ van de parallel-schakeling met de weerstanden $$ {R}_{2}$$ en $$ {R}_{3}$$ . Deze is gelijk aan:

$$ {R}_{parallel1}=\frac{ {R}_{2}\times {R}_{3}}{ {R}_{2}+{R}_{3}}$$

Van zodra je $$ {R}_{parallel1}$$ kent, kan je spanning over deze parallelschakeling bepalen via de spanningsdelerformule:

$$ {U}_{Rparallel1}={U}_{R2}=\frac{ {R}_{parallel1}}{ {R}_{1}+{R}_{parallel1}}\times {U}_{1}$$

De stroom door de weerstand $$ {R}_{2}$$ kan nu bepaald worden. We noemen deze stroom $$ {I}_{R2-1}$$ :

$$ {I}_{R2-1}=\frac{ {U}_{Rparallel1}}{ {R}_{2}}$$

Nu moet je de vorige berekeningen herhalen voor de tweede spanningsbron $$ {U}_{2}$$ . Dit wil zeggen je sluit de spanningbron $$ {U}_{1}$$ kort, hertekend het schema voor de duidelijkheid en maakt de noodzakelijke berekeningen om de stroom $$ {I}_{R2-2}$$ te bepalen. Deze is de stroom die door $$ {R}_{2}$$ vloeit ten gevolge van de spanningsbron $$ {U}_{2}$$ . In figuur 6-46 stelt het schema voor met bron $$ {U}_{1} $$ kortgesloten.

Via figuur 6-46 (c) kan zie je dat de schakeling nu bestaat uit een parallelschakeling van de weerstanden $$ {R}_{1}$$ en $$ {R}_{2}$$ . De totale weerstand van deze parallelschakeling wordt voorgesteld als $$ {R}_{parallel2}$$ . Deze is gelijk aan:

$$ {R}_{parallel2}=\frac{ {R}_{1}\times {R}_{2}}{ {R}_{1}+{R}_{2}}$$

![](/assets/afbeelding_525.png)

Figuur 6-46: Superpositie toepassen door de spanningsbron $$ {U}_{1}$$ als kortsluiting te aanzien

Van zodra je $$ {R}_{parallel2}$$ kent, kan je spanning over deze parallelschakeling bepalen via de spanningsdelerformule:

$$ {U}_{Rparallel2}={U}_{R2}=\frac{ {R}_{parallel2}}{ {R}_{3}+{R}_{parallel1}}\times {U}_{2}$$

De stroom door de weerstand $$ {R}_{2}$$ kan nu bepaald worden :

$$ {I}_{R2-2}=\frac{ {U}_{Rparallel2}}{ {R}_{2}}$$

De laatste stap is de optelling van beide stromen door $$ {R}_{2}$$ . Hiervoor dien je ook de zin van de stromen na te gaan. Passen we de elektronenzin toe dan zie je dat beide stromen door $$ {R}_{2} $$ in dezelfde zin vloeien. Dit is weergegeven in figuur 6-47.

![](/assets/afbeelding_526.png)

Figuur 6-47: De wijze hoe de twee deelstromen, gevonden door toepassing superpositie, door $$ {R}_{2}$$ vloeien

Beide stromen vloeien in dezelfde zin, dus kan je ze optellen. Indien beide stromen tegengesteld vloeien, moet je ze van elkaar aftrekken. Kom je een negatief getal uit dan weet je dat de stroom in de omgekeerde richting vloeit. In dit voorbeeld is de totale stroom $$ {I}_{R2}$$ door $$ {R}_{2}$$ gelijk aan:

$$ {I}_{R2}= {I}_{R2-1}$$ + $$ {I}_{R2-2}$$

$$ {I}_{R2}= \frac{ {U}_{Rparallel1}}{ {R}_{2}}+ \frac{ {U}_{Rparallel2}}{ {R}_{2}}$$

### Test jezelf: Superpositietheorema {#test-jezelf-superpositietheorema}

1.  Leg uit wat het superpositietheorema inhoud.

2.  Waarom is het superpositietheorema zinvol om te gebruiken voor analyse van schakelingen met meerdere bronnen?

3.  Waarom wordt een ideale spanningsbron korgesloten als je superpositie toepast?

4.  Als bij superpositie twee stromen in tegengestelde richting vloeien, in welke richting zal dan de uiteindelijke stroom vloeien (resultaat van superpositiebewerkingen)?