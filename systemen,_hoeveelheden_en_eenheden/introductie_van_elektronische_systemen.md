## Introductie van elektronische systemen {#introductie-van-elektronische-systemen}

Een elektronisch systeem is een samenstelling van componenten en schakelingen die speciaal ontworpen zijn voor het bereiken van een specifieke functie. Voorbeelden van elektronische systemen variëren van een eenvoudige garagedeuropener tot een complex systeem zoals een radarsysteem.

Wat onthoud je best na deze sectie?

*   De beschrijving van de attributen van een systeem.

*   De definitie van het woord systeem zoals dit geldt voor de elektrische en elektronische systemen.

*   Het nut van een blokschema en hoe je zo’n blokschema (basisschema) moet interpreteren.

*   Een voorbeeld van een transfertfunctie toegepast op een blok binnen een elektronisch systeem.

### Systeemconcepten {#systeemconcepten}

Een systeem is een groep van onderling verbonden onderdelen die een specifieke functie voorstellen. Een grens is de scheidslijn tussen wat deel uit maakt van het systeem en wat niet. Figuur 1-2 toont een voorbeeld van een systeem en zijn omgeving.

Een systeem communiceert met de buitenwereld via zijn in- en uitgangen. Deze worden ook wel de inputs en outputs genoemd. Een input wordt verkregen door een bepaalde spanning, stroom of vermogen toe te voeren aan het systeem om een bepaald gewenst resultaat te bekomen. Een bepaalde output van het systeem stelt het resultaat voor dat wordt verkregen uit het systeem na verwerking van één of meer ingangen. Het spreekt vanzelf dat systemen meerdere ingangen en uitgangen kunnen hebben. Merk op dat geen enkel systeem volledig geïsoleerd is van zijn omgeving. Stel bijvoor beeld het Internationaal Space Station (ISS). Dit is een systeem dat lijkt volledig geïsoleerd te zijn van zijn omgeving. Echter dit systeem ontvangt zonne-energie, straalt een zekere hoeveelheid warmte in de ruimte en wordt beïnvloed door de zwaartekracht van de Aarde. Vaak kunnen zulke systemen wel ter vereenvoudiging beschouwd worden alsof het volledig geïsoleerde systemen zijn. Systemen kan men ook onderverdelen in elektrische systemen (installaties) en elektronische systemen.

![](/assets/afbeelding_2.png) 

_Figuur 1-2: Een systeem in zijn omgeving_

**Elektrische systemen**

Elektrische installaties zijn elektrische systemen die werken met een bepaald elektrisch vermogen. Een voorbeeld van zo’n elektrisch systeem is de elektrische installatie van een woning. De buitenmuren en het dak van de woning stellen de grenzen van het systeem voor en de binnenruimte (waaronder kelder en zolder) wordt gedefinieerd als systeem. De aansluiting op het elektriciteitsnet wordt gedaan via de elektriciteitsmeter(s) op een paneel en wordt beschouwd als de invoer (input) naar het systeem. De outputs vertegenwoordigen specifieke punten binnen het huis (of buiten) waar belastingen worden aangesloten. De grens kan worden veranderd om de analyse sluitend te maken (voorbeeld voor stopcontacten die in de tuin aangelegd worden). Voor het huis kan het bedradingssysteem, of een deel van deze bedrading (bijvoorbeeld alleen de bedrading voor de verlichting) beschouwd worden als een systeem of een subsysteem.

**Elektronische systemen**

Elektronische systemen gaan om met signalen in plaats van met vermogen. In de context van een elektronisch systeem is een signaal een veranderende elektrische- of elektromagnetische hoeveelheid die informatie draagt. Als een bepaalde invoer voor een systeem nooit verandert dan is het volledig voorspelbaar. In dit geval wordt de ingang niet als een signaal beschouwd omdat er geen informatie aanwezig is. De meeste elektronische systemen verwerken de informatie in een signaal. Het onderscheid tussen een elektronisch systeem en een elektrisch systeem wordt vertroebeld door het feit dat elektrische systemen vaak gebruik maken van elektronische componenten voor de regeling ervan. Een elektronisch systeem heeft normaliter een elektrisch subsysteem voor het leveren van de noodzakelijke stroom.

### Blokdiagram {#blokdiagram}

Een elektronisch systeem zal in het algemeen leiden tot een logische volgorde van processen. Om ingewikkelde processen vereenvoudigd weer te geven wordt gebruik gemaakt van zogenaamde blokdiagrammen of blokschema’s. Meestal worden deze blokdiagrammen ook gebruikt om de volgorde van verwerking van de signalen duidelijk weer te geven. Een blokdiagram is een model van een systeem dat zijn structuur weergeeft in een grafisch formaat met behulp van blokken (waarin zich functies en verbindingslijnen bevinden) om de signaalflow. Figuur 1-3 stelt als voorbeeld het blokdiagram van een digitale temperatuurmeter voor.

Het blokdiagram toont de belangrijkste onderdelen van het systeem en de signaalstroom zonder in detail te gaan aangaande de opbouw van de schakelingen. Stel een temperatuursensor waarbij de uitgangsspanning verandert op basis van de omgevingstemperatuur. Meestal wordt hiervoor een zogenaamde NTC gebruikt. Dit is een weerstand met een Negatieve TemperatuursCoëfficiënt. Naarmate dat de temperatuur stijgt daalt de weerstandswaarde en als deze weerstand in een spanningsdeler wordt gebruikt, daalt bijgevolg ook de spanning over deze NTC.

![](/assets/afbeelding_10.png) 

Figuur 1-3 : blokdiagram van een digitale temperatuurmeter

Het signaal van de sensor wordt versterkt (vergroot) door de versterker. Het versterkte signaal wordt verder doorgestuurd naar de Analoog Digitaal Convertor (ADC). Deze zet het analoog versterkt signaal, afkomstig van de temperatuursensor, om in een digitale code die aan de ingangspoorten van een processor (bv. een arduinosysteem). Hierin is code vervat die de digitale code omzet in een bepaald getal dat overeenkomt met de temperatuurwaarde gemeten via de temperatuursensor. Via het display wordt vervolgens de temperatuur weergegeven als een verlicht getal. Het blokschema toont bijgevolg de belangrijkste onderdelen van het systeem en de signaalstroom zonder detailgegevens over de desbetreffende deelschakelingen van het systeem.

### Stroomdiagram {#stroomdiagram}

Onder data acquisitie wordt het proces verstaan waarbij analoge signalen (afkomstig uit de werkelijke wereld) omgevormd worden tot digitale numerieke waarden die gemanipuleerd kunnen worden door een computer. In het voorbeeld van de digitale temperatuurmeter zet de ADC de werkelijke analoge spanningswaarde om in een digitale code. Data acquisitie wordt voor verschillende toepassingen gebruikt.

De ADC is een belangrijk onderdeel van een data acquisitiesysteem. Systeemanalisten kunnen aan de hand van een blokschema en een flowchart de werking verklaren van bijvoorbeeld de “successieve approximatieve” ADC. Dit is een bepaalde manier van omvorming om een analoge waarde om te zetten in een digitale code. Stel dat we de successieve approximatiemethode als ADC-systeem beschouwen. Het blokschema van zulk systeem is weergegeven in figuur 1-4\. De figuur toont een blokdiagram van de hardware onderdelen en stelt de signaalflow voor. De figuur toont niet de details van het proces dat de controlelogica moet uitvoeren. Deze controlelogica maakt deel uit van de besturingslogica (control logic) en is een deel van het totale systeem. Het blokdiagram toont de flow van een signaal. De schakeling gebruikt een besturingslogicaschakeling (control unit) om een actie te bepalen die gebaseerd is op basis van het resultaat van het vergelijken van de input (analoog) en de output (digitaal).

![](/assets/afbeelding_4.png) 

Figuur 1-4 : blokschema principe successieve approximatieve ADC

Een stroomschema toont de logica die nodig is om het signaal te verwerken. Figuur 1-5 toont een stroomschema die het werkingsprincipe van de besturingslogica van de successieve approximatieve ADC verduidelijkt.

Het stroomschema (flowchart) start met het inlezen van een digitale code waarvan de MSB-bit getest wordt op de waarde 1\. Als deze bit niet op één staat wordt deze op 1 geplaatst. Vervolgens wordt deze digitale code naar een analoog signaal omgezet en aangelegd aan de comparator. Deze vergelijkt de aangelegde analoge waarde met de van digitaal omgevormde waarde. Als de analoge waarde hoger is dan de omgevormde digitale waarde, wordt de MSB-bit geaccepteerd en wordt de volgende bit getest. Deze wordt op 1 geplaatst en opnieuw wordt vergeleken of de digitale waarde groter is dan de analoge. Is dit het geval, dan wordt de betreffende bit gereset en wordt de volgende bit doorlopen enz.… Op die wijze wordt de volledige digitale code verkregen die overeenkomt met de analoge ingangswaarde van de ADC. Het totale systeem kan het beste uitgelegd worden door het tonen van beide soorten schema’s (blokdiagram en stroomschema) om de signaal flow en de logica te verduidelijken.

![](/assets/afbeelding_5.png) 

Figuur 1-5 : flowchart besturingslogica succesieve approximatie ADC

### **T** **ransfertfunctie** **(** **overdrachtscurve** **of responscurve)** {#t-ransfertfunctie-overdrachtscurve-of-responscurve}

Een transfertfunctie is een grafiek die de verhouding van de uitgang op de ingang toont (transfert = uitgangssignaal/ingangssignaal). In elektronische systemen is de transfertcurve nuttig. De curve beschrijft hoe het systeem zich gedraagt voor een bepaalde input. Het kan worden gebruikt om het gedrag van een gegeven blok of groep blokken te illustreren.

Stel als voorbeeld de versterker van de digitale temperatuurmeter van figuur 4\. Deze maakt het kleine signaal van de temperatuursensor voldoende groot om data acquisitie op uit te voeren met de ADC. In het ideaal geval is de overdrachtscurve voor een lineaire versterker een rechte lijn. Immers een rechte lijn duidt op een constante versterking. Dit is weergegeven in figuur 1-6.

In het ideale geval is de overdrachtscurve voor een lineaire versterker een rechte lijn, zoals getoond in figuur 1-6\. De ingang is een kleine spanning, afkomstig van de temperatuursensor van het voorbeeld van figuur 1-3\. Deze ingangsspanning V IN is langs de horizontale as uitgezet. De uitgang is een evenredige grotere spanning V OUT die is uitgezet op de verticale as. Voor een kleine ingangsspanning is de uitgangsspanning groter met een factor die bekend staat als de versterking. In het getoonde voorbeeld is de versterking 50 omdat bij een bepaalde V IN de uitgangsspanning V OUT 50x groter is.

![](/assets/afbeelding_11.png) 

Figuur 1-6 : ideale transfertcurve voor een versterker met versterkingsfactor 50

In sommige gevallen bestaat de invoer en uitvoer uit verschillende eenheden. In dat geval zal de transfertcurve niet dimensieloos zijn. Stel bijvoorbeeld de transfertcurve voor een sensor. Deze toont de weerstandsverandering (mutatie tegenover stroom) als functie van de temperatuur. In figuur 1-7 is de transfertcurve voor de temperatuursensor weergegeven.

![](/assets/afbeelding_12.png)

Figuur 1-7 : transfertfunctie van een typische NTC

Deze transfertfunctie komt overeen met een typische transfert voor een typische NTC (wat beschouwd kan worden als een soort temperatuursensor). Merk op dat de sensor een niet-lineaire respons heeft. Dit is gemakkelijk te herkennen aan de vorm van de transfertfunctie (geen rechte als karakteristiek).

Als deze sensor wordt gebruikt in de digitale temperatuurmeter dan zal de data nog een bepaalde bewerking moeten ondergaan om deze gegevens om te vormen tot een bepaalde temperatuurwaarde vooraleer deze waarde kan worden weergegeven op het display.

### Test jezelf aangaande systemen {#test-jezelf-aangaande-systemen}

1.  Wat is de input en output van een digitaal thermometersysteem?

2.  Beschouw het Internationaal Ruimtestation als een systeem. Wat vormt de omgeving van dit systeem?

3.  Wat is het doel van een blokschema?

4.  Welke naam wordt er gegeven aan een grafiek (of functie) die de verhouding weergeeft van de uitgang op de ingang van een gegeven blok?