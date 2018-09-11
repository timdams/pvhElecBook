## Serieschakeling van condensatoren {#serieschakeling-van-condensatoren}

De totale capaciteit van een aantal in serie geschakelde condensatoren is steeds kleiner dan de kleinste individuele capaciteit van de in serie geschakelde condensatoren. In serie geschakelde condensatoren verdelen de spanning over hun platen omgekeerd evenredig met hun capaciteitswaarde. De grootste condensator in serie zal bijgevolg minder spanning bevatten dan de condensatoren in serie met een kleinere capaciteit dan deze grootste condensator.

Wat is belangrijk?

*   Je berekent de totale vervangingscapaciteit van een aantal in serie geschakelde condensatoren.

*   Je bepaalt de spanning per condensator van een aantal in serie geschakelde condensatoren.

Stel twee condensatoren in serie geschakeld tezamen met een weerstand over een gelijkspanningsbron zoals in figuur 8-7 is weergegeven. In eerste instantie staat de schakelaar open en zijn de condensatoren volledig ontladen. Van zodra de schakelaar wordt gesloten (zie figuur 8-7 (a)) begint er stroom door de schakeling te vloeien.

| ![](/assets/afbeelding_376.png) | ![](/assets/afbeelding_377.png) |
| --- | --- |
| Tijdens het opladen is de stroom $$ I=\frac{Q}{t}$$ overal hetzelfde. De condensatoren zijn aan het opladen | Eenmaal opgeladen hebben beide condensatoren dezelfde hoeveelheid lading ($$ {Q}_{T}={Q}_{1}={Q}_{2}$$). Er vloeit geen stroom meer waardoor $$ {U}_{R}=0V$$. |

Figuur 8-7 : ladingsverloop bij condensatoren in serie

Vermits het een serieschakeling is vloeit de stroom door alle componenten met dezelfde stroomwaarde $$ \frac{Q}{t}$$ . Dit betekent dat dezelfde hoeveelheid negatieve lading op plaat $$ A$$ van beide condensatoren terecht komt. De hoeveelheid negatieve lading die op plaat $$ A$$ terecht komt van condensator $$ {C}_{1}$$ zorgt ervoor dat eenzelfde hoeveelheid negatieve lading zich verplaats van plaat $$ B$$ van $$ {C}_{1}$$ naar plaat $$ A$$ van $$ {C}_{2}.$$ Dit zorgt ervoor dat eenzelfde hoeveelheid negatieve lading van plaat $$ B$$ van $$ {C}_{2}$$ verplaatst wordt door de weerstand $$ R$$ naar de positieve klem van de spanningsbron. Het resultaat van dit alles is dat over een bepaalde tijdsperiode gezien de hoeveelheid lading opgeslagen door $$ {C}_{1}$$ gelijk is aan de hoeveelheid lading opgeslagen door $$ {C}_{2}$$ en gelijk is aan de totale hoeveelheid lading $$ {Q}_{T}$$ die gedurende deze tijdsperiode verplaatst is geweest. In formulevorm:

$$ {Q}_{T}={Q}_{1}={Q}_{2}$$

Terwijl de condensatoren opladen stijgt de spanningsval tussen hun platen. De grootte van de spanningsval over elk van de condensatoren is afhankelijk van hun capaciteitswaarde en de hoeveelheid lading zij opgenomen hebben. De spanningsval kan bepaald worden via volgende formule :

$$ U=\frac{Q}{C}$$

Figuur 8-7 (b) geeft de toestand weer wanneer beide condensatoren opgeladen zijn. De som van de spanningsvallen over beide condensatoren is dan gelijk aan bronspanning. Er geen spannings-verschil meer ten opzichte van de bronspanning waardoor er ook geen stroom meer vloeit. Vermits de stroom herleid is naar nul, staat er ook geen spanningsval meer over de weerstand.

Via de spanningswet van Kirchhoff kan je de spanningsvallen neerschrijven nadat de condensatoren samen opgeladen zijn tot de aangelegde bronspanning. Men bekomt het volgende:

$$ {U}_{bron}={U}_{C1}+{U}_{C2}$$

Herinner dat door het feit er geen stroom meer vloeit, de spanning over de weerstand gelijk is aan $$ 0 V$$ .

Vervangen we in bovenstaande formule de spanning door zijn equivalent inzake de verhouding van lading op capaciteit. Herinner eveneens dat de hoeveelheid lading in beide condensatoren gelijk is. De bronspanning kan je vervangen door de verhouding van de lading over de totale capaciteit $$ {C}_{T} $$ van de serieschakeling. Aanpassen van bovenstaande formule levert het volgende op:

$$ \frac{Q}{ {C}_{T}}= \frac{Q}{ {C}_{1}}+\frac{Q}{ {C}_{2}}$$

Vermits de lading overal gelijk is:

$$ \frac{1}{ {C}_{T}}=\frac{1}{ {C}_{1}}+\frac{1}{ {C}_{2}}$$

Uitwerken naar $$ {C}_{T}:$$

$$ {C}_{T}=\frac{1}{\frac{1}{ {C}_{1}}+\frac{1}{ {C}_{2}}}$$

Meer algemeen is de uiteindelijke formule voor de serieschakeling van condensatoren gelijk aan:

$$ {C}_{T}=\frac{1}{\frac{1}{ {C}_{1}}+\frac{1}{ {C}_{2}}+\frac{1}{ {C}_{3}}+\dots +\frac{1}{ {C}_{n}}} \left(8-5\right)$$

Hoewel meer dan twee condensatoren in serie eerder zeldzaam is in elektronische schakelingen, moet je wel bewust zijn van de algemene formule indien de situatie zich toch zou voordoen. Merk op dat de formule voor het bepalen van de vervangingscapaciteit van een serieschakeling van condensatoren analoog is als de formule voor het bepalen van de vervangingsweerstand van een aantal weerstanden in parallel. Dit betekent dan ook dat de totale seriecapaciteit $$ {C}_{T}$$ steeds kleiner zal zijn dan de kleinste capaciteit in de serieschakeling.

### De spanning over in serie geschakelde condensatoren {#de-spanning-over-in-serie-geschakelde-condensatoren}

De spanning over elke in serie geschakelde condensator is afhankelijk van de capaciteitswaarde volgens de formule $$ U=\frac{Q}{C}$$ .

Vermits de opgeslagen lading in iedere condensator van de serieschakeling van condensatoren dezelfde is betekent dit dat ook de totale capaciteit van de serieschakeling deze dezelfde lading heeft. Stel drie condensatoren in serie dan kan je schrijven:

$$ {Q}_{T}={Q}_{1}={Q}_{2}={Q}_{3}$$

De opgeslagen lading kan je schrijven in functie van de capaciteit en de spanning die er over staat:

$$ {U}_{bron}\times {C}_{T}={U}_{C1}\times {C}_{1}={U}_{C2}\times {C}_{2}={U}_{C3} \times {C}_{3}$$

Hieruit kan je de spanning per condensator afleiden in functie van eigen capaciteit, totale capaciteit en bronspanning. Immers :

$$ {U}_{bron}\times {C}_{T}={U}_{C1}\times {C}_{1}$$

Waardoor :

$$ {U}_{C1}=\frac{ {C}_{t}}{ {C}_{1}}\times {U}_{bron}$$

Naar analogie kan je voor $$ {U}_{C2}$$ en $$ {U}_{C3}$$ schrijven:

$$ {U}_{C2}=\frac{ {C}_{t}}{ {C}_{2}}\times {U}_{bron}$$ en $$ {U}_{C3}=\frac{ {C}_{t}}{ {C}_{3}}\times {U}_{bron}$$

Meer algemeen kan je dan de spanning vinden over $$ {C}_{x}$$ in een serieschakeling van $$ n $$ condensatoren:

$$ {U}_{Cx}=\frac{ {C}_{T}}{ {C}_{x}}\times {U}_{bron} \left(8-6\right)$$

### Test jezelf : serieschakeling van condensatoren {#test-jezelf-serieschakeling-van-condensatoren}

1.  Is de totale capaciteit van in serie geschakelde condensatoren groter of kleiner dan de kleinste condensator in de serieschakeling?

2.  **Een condensator van** $$ 100\mathit{ }\mathit{p}\mathit{F}$$ **,** $$ 220\mathit{ }\mathit{p}\mathit{F}$$ **en** $$ 560\mathit{ }\mathit{p}\mathit{F}$$ **staan in serie.** Bereken de totale capaciteit van de serieschakeling.

3.  **Een condensator van** $$ 10\mathit{ }\mathit{n}\mathit{F}$$ **en** $$ 15\mathit{ }\mathit{n}\mathit{F}$$ **staan in serie.** Bereken de totale capaciteit van de serieschakeling.

4.  **Bepaal de spanning over de** $$ 10\mathit{ }\mathit{n}\mathit{F}$$ **condensator in vraag 3 als er** $$ 10\mathit{ }\mathit{V}$$ **is aangesloten over beide condensatoren.**