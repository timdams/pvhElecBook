## Toepassingen met condensatoren {#toepassingen-met-condensatoren}

In elektrische en elektronische systemen wordt veel gebruik gemaakt van condensatoren. In deze sectie wordt een overzicht gegeven van de voornaamste toepassingen van condensatoren.

Wat is belangrijk?

*   Je beschrijft het principe hoe een condensator gebruikt kan worden als afvlakfilter in een spanningsbron.

*   Je verklaart het doel van het koppelen en ontkoppelen met condensatoren.

*   Je beschrijft de principes hoe een condensator kan gebruikt worden in afgestemde kringen, timing circuits en computergeheugen.

### Stockeren van elektrische lading {#stockeren-van-elektrische-lading}

Een van de meest eenvoudige toepassingen van een condensator is deze te gebruiken als back-upspanningsbron voor laagvermogenschakelingen zoals bepaalde typen halfgeleidergeheugens in computers. Deze specifieke toepassing vereist een zeer hoge capaciteitswaarde en verwaarloosbare lekkage.Een opslagcondensator wordt aangesloten tussen de plusklem van een spanningsbron en de massa. Zolang de schakeling werkt met de normale spanningsbron blijft de condensator volledig opgeladen tot deze gelijkstroomvoedingsspanning. Van zodra de normale spanningsbron wordt onderbroken (of verwijderd) zal de opslagcondensator tijdelijk gebruikt worden als voedingsbron voor de schakeling.Zolang de lading in de condensator nog voldoende aanwezig is kan deze spanning en stroom leveren aan een bepaalde schakeling. Wanneer er stroom door de schakeling vloeit, wordt de lading uit de condensator verwijderd en neemt de spanning af. Om deze reden kan een opslagcondensator alleen als tijdelijke spanningsbron worden gebruikt. De lengte van de tijd dat een condensator voldoende stroom kan leveren voor een bepaalde schakeling is afhankelijk van de capaciteitswaarde en de hoeveelheid stroom die door de schakeling wordt getrokken. Hoe kleiner de stroom en hoe hoger de capaciteit, hoe langer de condensator stroom kan leveren.

### Afvlakcondensatoren in spanningsbronnen {#afvlakcondensatoren-in-spanningsbronnen}

Een gelijksspanningsbron bevat een schakeling die gelijkrichter wordt genoemd en daarachter staat een zogenaamde afvlakfilter die uit één of meerdere condensatoren bestaat. De gelijkrichter converteert de sinusvormige spanning vanuit het net naar een pulserende gelijkspanning. Afhankelijk van het gebruikte type gelijkrichterschakeling wordt ofwel elke negatieve halve cyclus verwijderd ofwel de polariteit van het negatieve deel omgekeerd. Zie hiervoor figuur 8-33\. Zoals weergegeven in Figuur 8-33 (a) verwijdert een enkelzijdige gelijkrichter elke negatieve halve cyclus van de sinusvormige spanning. Een dubbelzijdige gelijkrichter 8-33 (b) keert in feite de polariteit van het negatieve deel van iedere cyclus om. In beide situaties wordt de wisselspanning die afkomstig is van het elektriciteitsnet omgevormd tot een unipolaire spanning. Om nuttig te zijn voor het voeden van elektronische schakelingen moet de unipolaire gelijkgerichte spanning worden gewijzigd in een constante gelijkspanning. Om dit te kunnen verwezenlijken wordt een afvlakfilter, bestaande uit een condensator, achter de gelijkrichterschakeling geplaatst.

![](/assets/afbeelding_338.png)

Figuur 8-33 : principes van gelijkrichting

De condensator elimineert de schommelingen in de gelijkgerichte spanning en verstrekt een vlotte constante gelijkstroomspanning aan de belasting. Het principe van deze afvlakking is weergegeven in figuur 8-34.

![](/assets/afbeelding_411.png)

Figuur 8-34 : principe van afvlakking met een condensator

Omwille van hun vermogen om elektrische lading op te slaan worden condensatorenin gelijkstroomvoedingen gebruikt om het unipolair signaal dat uit de gelijkrichterschakeling komt verder af te vlakken tot een gelijkspanning. Figuur 8-34 toont het principe van een voeding met een dubbelzijdige gelijkrichter en een condensatorfilter (afvlakfilter).

Het werkingsprincipe kan vanuit het laad- en ontlaad-oogpunt beschreven worden. Stel dat de condensator aanvankelijk niet is opgeladen. Wanneer de spanningsbron wordt ingeschakeld en de eerste cyclus van de gelijkgerichte spanning optreedt, laadt de condensator snel op door de lage weerstand van de gelijkrichter. De spanning volgt de gelijkgerichte spanningskromme tot het maximum van de gelijkgerichte spanning. Als de gelijkgerichte spanning dit maximum (piek) passeert en begint te dalen, begint de condensator zich langzaam te ontladen via de hoge belastingsweerstand. De hoeveelheid van ontlading is typisch zeer klein en ter illustratie overdreven weergegeven in figuur 8-34\. Tijdens de volgende cyclus van de gelijkgerichte spanning laadt de condensator weer op tot de piekwaarde. Hierdoor kan de lading in de condensator terug aangevuld worden zodat de kleine hoeveelheid lading die verloren is gegaan sinds de vorige piek terug wordt opgeladen. Zolang de spanningsbron is ingeschakeld blijft dit patroon van een kleine hoeveelheid opladen en ontladen voortduren.

Een gelijkrichter is zo ontworpen dat deze alleen stroom in de richting van de condensator toelaat om de condensator opnieuw op te laden. De condensator kan zich bijgevolg niet ontladen via de gelijkrichterschakeling. De enige weg waarlangs de condensator zich kan ontladen is via de belastingsweerstand die aan de spanningsbron is aan gesloten.

De kleine fluctuatie in gelijkspanning, ten gevolge van het op- en ontladen van de condensator, wordt de rimpel genoemd. Een goede gelijkstroomvoeding heeft een zeer kleine hoeveelheid rimpeling op zijn gelijkstroomoutput. De ontlaadtijdconstante van een voedingsfiltercondensator is afhankelijk van de capaciteit en weerstandswaarde van de belasting. Hoe hoger de capaciteitswaarde hoe langer de ontlaadtijd duurt en hoe kleiner de rimpelspanning is. In een ideale afvlakfilter is er op de gelijkspanning helemaal geen rimpel meer aanwezig.

### Koppel- en ontkoppelcondensatoren {#koppel-en-ontkoppelcondensatoren}

Condensatoren worden gebruikt om te verhinderen dat een bepaalde gelijkspanning in bepaald deel van de schakeling ongewenst invloed uitoefent op een ander deel van de schakeling. Er wordt gebruik gemaakt van de eigenschap dat de condensator voor gelijkstroom een open keten vormt en voor de wisselspanning een frequentie-afhankelijke weerstand. Bij een goede keuze van de capaciteitswaarde gedraagt de condensator zich voor een bepaald frequentiegebied als een kortsluiting.

Gelijkspanning wordt gebruikt om actieve componenten zoals transistoren in te stellen. Versterkers kunnen opgebouwd worden met transistoren. Om te verhinderen dat de instellingsspanning van een bepaalde transistor een andere transistor beïnvloed kan de wisselspanning via een condensator van de ene transistorschakeling worden overgebracht naar de andere. Men spreekt in dit geval van een koppelcondensator. Dit omwille van het feit dat de condensator de uitgang van de ene schakeling koppelt met de ingang van de volgende schakeling.

In bepaalde schakelingen is het nodig om te vermijden dat er een wisselstroom door een bepaalde component vloeit. Dit kan bekomen worden door een condensator parallel met deze component te plaatsen. Door te zorgen dat $$ {X}_{C}$$ -waarde van de condensator in het beschouwde frequentiegebied minstens tien keer kleiner is dan de weerstandswaarde van de component waardoor geen wisselstroom mag vloeien wordt deze component gevrijwaard van de wisselstroom. Men spreekt in dit geval van een ontkoppelcondensator. Figuur 8-35 toont de functie van koppel- en ontkoppelcondensator.

![](/assets/afbeelding_413.png)

Figuur 8-35: voorbeeld van koppel- en ontkoppelcondensatoren

Op printplaten zie je heel dikwijls condensatoren aangesloten tussen een gelijkstroomvoedings-spanningslijn en de massa. Deze ontkoppelcondensatoren worden gebruikt om ongewenste spanningsovergangen of pieken die optreden op de gelijkstroomvoedingsspanning te ontkoppelen. Deze ongewenste storingen op de voedingsspanning zijn dikwijls afkomstig van snel schakelende digitale schakelingen op de printplaat. Telkens een digitaal $$ 0$$ in een digitaal $$ 1$$ verandert of omgekeerd, ontstaan er stroomveranderingen op de voedingslijn waardoor stoorspanningen kunnen ontstaan. Zulke stooorspanningen bevatten hogere frequenties die de werking van de schakelingen kunnen beïnvloeden. Door de koppelcondensatoren aan te brengen worden deze storingen kortgesloten naar massa toe. Je vindt ze dikwijls in de onmiddellijke buurt van de geïntegreerde circuits (IC’s) die deze stroomveranderingen op de voedingsspanning veroorzaken. Op die wijze kan je de mogelijke storing bij zijn ontstaat meteen elimineren. Een ontkoppelcondensator heeft een zeer lage reactantiewaarde waardoor deze zich gedragen als een kortsluiting voor wisselstroom naar massa toe.

### Signaalfilters {#signaalfilters}

Filters worden gebruikt voor het selecteren van een bepaald wisselstroomsignaal met een bepaalde gespecificeerde frequentie van uit een breed bereik van signalen met veel verschillende frequenties. Ze worden eveneens gebruikt voor het selecteren van een bepaalde groep (band) van frequenties en het elimineren van alle andere. Een bekend voorbeeld van deze toepassing is in radio- en televisieontvangers waar het nodig is om het signaal te selecteren dat wordt uitgezonden door een gegeven station en de signalen van de andere stations die in dat gebied worden uitgezonden te elimineren.Wanneer je de radio of tv afstemt, verander je eigenlijk de capaciteit in de tunerschakeling (wat een type filter is), zodat alleen het signaal van het station of kanaal dat je wilt doorlaten naar het ont vangstgedeelte van de schakeling wordt doorgelaten. Condensatoren worden gebruikt in combinatie met weerstanden en spoelen (zie hoofdstuk 9) en andere (actieve) componenten in dit soort filters.Het belangrijkste kenmerk van een filter is de frequentieselectiviteit, die is gebaseerd op dehet feit dat de reactantie van een condensator afhankelijk is van de frequentie $$ {X}_{C}=\frac{1}{2\pi fC}$$ .

### **Timingcircuits** {#timingcircuits}

Een ander belangrijk gebied waar condensatoren worden gebruikt zijn de timingcircuits die zorgen voor gespecificeerde tijdsvertragingen of golfvormen produceren met specifieke kenmerken. Bedenk dat de tijdsconstante van een schakeling via het selecteren van een weerstand en een capaciteit kan worden ingesteld. De oplaadtijd van een condensator kan als basis worden gebruikt voor de tijdsvertraging in verschillende soorten schakelingen. Een voorbeeld hiervan is de schakeling die de e richtingaanwijzers van een auto bestuurt waarmee het licht met regelmatige tussenpozen aan en uit gaat.

### Computergeheugen {#computergeheugen}

Dynamische computergeheugens gebruiken condensatoren als het basisopslag-element voor binaire informatie op te slaan. Een geladen condensator kan een opgeslagen $$ 1$$ voorstellen en een ontladen condensator kan een opgeslagen $$ 0$$ vertegenwoordigen. Patronen van enen en nullen die de binaire data vormen worden opgeslagen in een geheugen dat bestaat uit een reeks condensatoren met bijbehorende MOSFET-schakelingen.

### Test jezelf aangaande toepassingen met condensatoren {#test-jezelf-aangaande-toepassingen-met-condensatoren}

1.  Verklaar hoe de unipolaire spanningsvorm die uit een enkelzijdige- of dubbelzijdige gelijkrichter komt wordt afgevlakt tot een gelijkspanning door een afvlakcondensator.

2.  Verklaar het doel van een koppelcondensator.

3.  Hoe groot moet een de capaciteit zijn om goed te functioneren als koppelcondensator?

4.  Verklaar het doel van een ontkoppelcondensator.

5.  Leg uit waarom het verband tussen frequentie en capacitieve reactantie belangrijk is bij frequentieselectieve schakelingen zoals signaalfilters.