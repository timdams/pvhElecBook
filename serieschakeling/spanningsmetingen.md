## Spanningsmetingen {#spanningsmetingen}

Het concept referentie naar de “ground” of “massa” is reeds in hoofdstuk 2 geïntroduceerd als het _0 V_ referentiepunt van de schakeling. De spanning wordt steeds gemeten ten opzichte van een ander punt in de schakeling. Het begrip “massa” wordt in deze sectie meer in detail besproken.

Wat is belangrijk?

*   Je definieert de term massa (reference ground).

*   Je kan op een correcte manier het gebruik van enkel en dubbele subscripts verklaren en toepassen om spanningen aan te duiden.

De term “ground” heeft zijn oorsprong bij telefonie waarbij de geleiders de aarde zelf was. De term werd ook gebruikt bij de eerste radio-ontvangst antennes (airials genoemd) waarbij een deel van het systeem via een metalen pen in de aarde was geslagen. Vandaag kan “ground” verschillende betekenissen hebben en hoeft het niet noodzakelijk hetzelfde potentiaal als de aarde te hebben.

Bij elektronische systemen spreekt men van een “reference ground” of massa. Met massa wordt verwezen naar een geleider die het referentiepunt is voor de spanningsmetingen. De massa is de geleider die de terugkeerstroom naar de voeding bevat. Veel PCB’s hebben een breed geleidingsoppervlak voor de massa. PCB’s die uit meerdere lagen bestaan, multilayer PCB’s genoemd, hebben meestal een speciale laag (layer) die gebruikt wordt als referentie. Men spreekt in dit geval van de “grondplaat”.

Bij elektrische draden heeft de massa (blauwe draad) meestal hetzelfde potentiaal als de aarde. Ze zijn alleen gegarandeerd hetzelfde (dit wil zeggen $$ 0 V$$ ) als de “signaal massa” aangesloten is op de aarding via een signaalpad met lage impedantie (weerstand). Uitzonderingen op het “ $$ 0 V$$ _”_ potentiaal kunnen bestaan zodat de massa in die situaties een andere potentiaal heeft. Dit kan bijvoorbeeld voorkomen in hospitalen (operatiekamers) en bepaalde gezondheidsfaciliteiten.

In auto’s wordt het chassis van de wagen gebruikt als massa. De banden isoleren deze massa van de aarde waardoor deze op een ander potentiaal kan staan dan het aardpotentiaal. De negatieve pool van de accu wordt in de meeste auto’s verbonden met het chassis via een laagohmige verbinding. Door deze verbinding te maken kan het metalen chassis van het voertuig gebruikt worden als retourpad voor de elektrische verbinding.

### Meten van spanningen ten opzichte van de massa {#meten-van-spanningen-ten-opzichte-van-de-massa}

Spanningen die gemeten worden ten opzichte van de massa worden weergegeven met één letter. De massa stelt een potentiaal van $$ 0 V$$ voor. In figuur 4-39 (a) is de massa aangebracht aan de negatieve klem van de spanningsbron. De spanningen op punt $$ A, B$$ en $$ C$$ zijn positiever te opzichte van de massa. De totale weerstand in figuur 4-39 (a) is gelijk aan $$ 600 \Omega $$ waardoor volgens de wet van Ohm de stroom door de drie weerstanden gelijk is aan $$ 20 mA$$ . (). Hierdoor is er een spanningsval van $$ 2 V$$ over $$ {R}_{1}$$ , $$ 4 V$$ over $$ {R}_{2}$$ en $$ 6 V$$ over $$ {R}_{3}$$ .

![](/assets/afbeelding_277.png)

Figuur 4-39 : De plaats van het massapunt heeft geen effect op de stroom door de schakeling en de spanningsval over de weerstanden.

Zoals in figuur 4-39 (a) te zien is, is het massapunt ingesteld aan de negatieve voedingsklem. Dit betekent dat $$ D$$ het referentiepotentiaal bevat van $$ 0 V$$. Vermits over $$ {R}_{3}$$ een spanningsval van $$ 6 V$$ staat is het potentiaalverschil tussen punt $$ D$$ en $$ C$$ gelijk aan $$ 6 V$$. Vermits over $$ {R}_{2}$$ een spanningsval van $$ 4 V$$ staat betekent dit dat het potentiaal verschil tussen punt $$ B $$en massa ($$ D$$_)_ gelijk is aan de som van de spanningsvallen over $$ {R}_{3}$$ en $$ { R}_{2}$$. Dit levert bijgevolg een spanning van $$ +10 V$$ op. Tussen punt $$ A$$en de massa staat de bronspanning van $$ 12 V$$. Deze spanning is eveneens gelijk aan de som van de spanningsvallen van de drie weerstanden.

In figuur 4-39 (b) is het punt $$ A$$ verbonden met de massa. In dit geval bevat het punt $$ A$$ de referentiespanning van $$ 0 V$$ . Beschouwen we de spanning op punt $$ D$$ dan weten we dat deze $$ 12 V$$ lager is dan de spanning op punt $$ A$$ Vermits punt $$ A $$ hier als referentie is genomen, betekent dit dat punt $$ D$$ een potentiaal heeft van $$ -12V$$ ten opzichte van punt $$ A$$ . Over de weerstand $$ { R}_{1}$$ staat een spanningsval van $$ 2 V$$ waardoor het punt $$ B$$ op een potentiaal van $$ -2 V$$ komt te staan ten opzichte van punt $$ A$$ . Tussen de massa ( $$ A$$ ) en punt $$ C$$ hebben we de som van de spanningsvallen van $$ {R}_{1}$$ en $$ {R}_{2}$$ waardoor punt $$ C$$ op een potentiaal van $$ –6 V$$ komt te staan ten opzichte van de massa ( $$ A$$ ).

In figuur 4-39 (c) ten slotte is de spanningsbron opgesplitst in twee bronnen in serie van $$ 6 V$$ en wordt de massa tussen deze twee bronnen gelegd. Hierdoor is de spanning op punt $$ A$$ gelijk aan de positieve voedingsspanning van bron $$ {\mathrm{U}}_{1}$$ of $$ +6 V$$ . Dezelfde redenering kunnen we toepassen met spanningsbron $$ {U}_{2}$$ . In dit geval is de positieve klem verbonden met de massa en verkrijgen we op punt $$ D$$ de negatieve klemspanning van deze bron of $$ -6 V.$$ Op punt $$ C$$ verkrijgen we de som van de spanning in punt $$ D$$ met de spanningsval over $$ {R}_{3}$$ . Dit levert een potentiaal op van $$ -6 V$$ plus $$ +6 V$$ op wat gelijk is aan $$ 0 V.$$ In punt $$ B$$ vinden we tenslotte de spanning van $$ +4 V$$ ten opzichte van de massa. Ten gevolge van de spanningsval over $$ {R}_{1}$$ van $$ 2 V$$ ligt het potentiaal op punt $$ B$$ $$ 2 V$$ lager dan het potentiaal op punt $$ A$$ . Door de som van de spanningen te nemen van bron $$ {U}_{2}$$ , $$ {R}_{3}$$ en $$ {R}_{2}$$ bekomen we eveneens dat het potentiaal op punt $$ B$$ gelijk is aan $$ +4 V$$ .

![](/assets/afbeelding_11332.jpg) Merk op dat ongeacht waar we het massapunt plaatsen de totale weerstand in de schakeling constant blijft en bijgevolg de spanningsvallen over de weerstanden en de stromen door de weerstanden hetzelfde blijft. Enkel het referentiepunt om de spanningspotentialen op de punten $$ A, B, C$$ en $$ D$$ wijzigen in functie van het gekozen massapunt.

Niet alle spanningen worden gemeten ten opzichte de massa. Als je bijvoorbeeld een spanningsval over een weerstand wil weergeven die niet verbonden is met de massa kan je de naam van de weerstand opnemen in het subscript of gebruik maken van twee letters. Zo kan je bijvoorbeeld de spanningsval over $$ {R}_{2}$$ in figuur 4-39 (a) schrijven als $$ {U}_{R2}$$ of $$ U{}_{BC}$$. Deze spanningswaarde is dan gelijk aan:

$$ {U}_{BC}={U}_{B}-{U}_{C}=10 V-6 V=4 V$$

Wil je de spanning $$ {U}_{CB}$$ weten in plaats van $$ {U}_{BC}$$ dan kan je die als volgt vinden:

$$ {U}_{CB}={U}_{C}-{U}_{CB}=6 V-10 V=-4 V$$

Met andere woorden de spanning of het potentiaal dat aangeduid wordt met de twee subscripts heeft steeds de volgende betekenis : de spanningsval tussen de twee punten die aangeduid worden met twee subscripts is gelijk aan de spanningswaarde op punt weergegeven door de eerste subscript min de spanningswaarde op het punt weergegeven door de tweede subscript.

Merk op dat bij een digitale multimeter de klem $$ COM$$ of $$ COMMON$$ de ingang is waarmee het zwarte meetsnoer mee verbonden wordt. Deze stelt de massa van de multimeter voor en niet van de schakeling zelf.

Voorbeeld 4-20

Bepaal de spanningswaarde van elk van de gedefinieerde punten in figuur 4- 40.

![](/assets/afbeelding_11595.png)

Figuur 4-40

Voedingsbronnen worden meestal met twee subscripts aangeduid. Bijvoorbeeld een bepaalde spanningsbron wordt aangeduid met $$ +{U}_{CC}.$$ Dit is een positieve spanningsbron ten opzichte van de massa. Voedingsspanningen krijgen meestal de dubbele letter van het geen ze spanning leveren. De $$ C$$ slaat hier op de collector van een transistor (zie electronic devices) en betekent in feite “voedingsspanning van de collector”. Op analoge manier betekent $$ -{U}_{EE}$$ een negatieve voedingsspanning ten opzichte van de massa die de emitter van een transistor van spanning voorziet. Vandaar de benaming “ $$ E$$ _”_ als eerste letter van de emitter.

$$ {R}_{T}= {R}_{1}+{R}_{2}+{R}_{3}+{R}_{4}=100 \Omega +50 \Omega +150 \Omega +300 \Omega =600 \Omega $$

### Test jezelf aangaande spanningsmetingen {#test-jezelf-aangaande-spanningsmetingen}

1.  Hoe wordt het referentiepunt van een schakeling genoemd?

2.  **Als in een schakeling de spanning** $$ {\mathit{U}}_{\mathit{A}\mathit{B}}$$ **gelijk is aan** $$ +10\mathit{ }\mathit{V}$$ **, hoeveel bedraagt dan de spanning** $$ {\mathit{U}}_{\mathit{B}\mathit{A}}$$ **?**

3.  Spanningen in een schakeling worden over het algemeen gerefereerd ten opzichte van de massa. (waar of niet waar ?)

4.  Een metalen behuizing of chassis kan gebruikt worden als referentie massa. (waar of niet waar ?)