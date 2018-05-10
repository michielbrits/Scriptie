#Introductie

### Inleiding
Samen met Axel Van Uffelen maak ik de website voor het bedrijf ABC-Groep. Onze opdracht bestaat er uit een nieuwe website voor het bedrijf te ontwikkelen aangezien de huidige website niet meer up-to-date is. Omdat alles dynamisch moet zijn hebben ze ons gevraagd een content management systeem te voorzien op de backend, meer bepaald Umbraco. 

### Waarom?

Omdat de oude website niet meer up-to-date is. De website is ontwikkeld met een tegelstructuur. Heel handig op mobiele apparaten, maar veel minder handig op een laptop op desktop.
Deze structuur zorgt er ook voor dat je nooit weet waar ergens op de website men zich bevindt. Er is ook geen sprake van *breadcrumbs wat het ook niet handig maakt om naar een bovenliggende pagina of categorie te navigeren.

### De website
De website wordt ontwikkeld in .NET Model-View-Controller. Voor het front-end gedeelte heeft het bedrijf een template aangekocht. Deze template zullen we aanpassen aan de requirements van het bedrijf. Vervolgens gaan we het Content-Management-Systeem Umbraco integreren. We houden rekening met de feedback van het management en wat zij graag nog willen veranderd zien of wat er volgens hun nog beter kan. In het begin van de stage gaan we ons focussen op het aanpassen van de template aan de requirements van het bedrijf. Later gaan we de Content-Management-Systeem Umbraco in de website integreren. 
### De opbouw
Op de homepagina zijn er verschillende secties. Verschillende stijlen zullen voorzien worden zodat de website-bouwer nog uit verschillende stijlen kan kiezen. Er is onder andere een slider sectie waar het bedrijf aanbiedingen op wil kunnen instellen. Er zal ook een Technologieen sectie zijn die de verschillende technologieen waar het bedrijf mee bezig is uitlicht. Een diensten pagina is aanwezig. Deze geeft de verschillende diensten weer waar het bedrijf mee bezig is. Verder is er ook een "vacature pagina" waarop de verschillende vacatures getoond zullen worden. Deze zal dan doorverwijzen naar een vacature detail pagina die je door middel van een listview in Umbraco kan aanpassen, en waar je dan vacatures kan toevoegen. Er is een "over ons" pagina waarop meer informatie over het bedrijf ABC-Groep getoond zal worden. Ook is er een "Nieuws" pagina waarop nieuws getoond zal worden. Ook hier zal je in Umbraco nieuws items kunnen toevoegen. Ten slotte is er nog een "contact" pagina die onder andere is uitgerust met een map waarop de locatie van het bedrijf aangeduid wordt. De locatie moet aanpasbaar zijn door het adres in te stellen in Umbraco zelf. Verder moet ook het adres regel per regel ingesteld kunnen worden. 

De template die het bedrijf heeft aangekocht heet "Versa - Clean Minimal Business template" van de website wrapbootstrap. Deze template heeft een minimale look en het kleurenpalet is niet overweldigend of overdadig. 


### Dynamische opbouw
Om de website volledig dynamisch opgebouwd te krijgen gaan we alles onderverdelen in secties die we vervolgens verschillende templates gaan geven. Dit zorgt ervoor dat de website volledig modulair kan opgebouwd worden. De opbouw van de website kan ook perfect gebeuren door iemand die geen kennis heeft van C#, het enigste wat vereist is: een beetje kennis van Umbraco. Ook is de Grafische-Unit-Interface straight-forward en makkelijk in gebruik. De code die we gaan schrijven gaan we ook heel netjes en modulair opbouwen, zodat toekomstige programmeurs die op het project gezet worden makkelijk aan de slag kunnen met ons project, en makkelijk wijzigingen of bug fixes kunnen toepassen. Hiervoor heeft Umbraco een ingebouwd systeem dat als je een pagina maakt in Umbraco dan zal deze hier zelf een model voor generen. De properties die je op dit model gezet hebt kan je dan vanuit Model-View-Controller raadplegen. De values van de properties wordt door middel van Razor on the fly in het HTML document geinjecteerd. Op het moment als de pagina geladen wordt door de user. Elke week hebben wij een sprint-earnings point meeting waarop we onze sprint moeten toelichten en ook moeten zeggen wat er goed of minder goed ging. Hier wordt onder andere ook naar de burndown-chart gekeken en ook beslist wat er in de volgende sprint zal gebeuren. Als er problemen zijn of dingen waar je op vast loopt kan je dit beter op de daily scrum meetings mede delen want als je hier op deze meetings mee af komt is het eigenlijk een beetje te laat. "Als je tickets inschat maak je een commitment" : Bart De Meyer ( Senior-Developper / team manager ). Met andere woorden wordt er ook van je verwacht dat je eerlijk bent bij het inschatten van de estimate van de tickets zodat op het einde je klant of opdrachtgever niet voor verassingen komen te staan.

Voor onze bachelorproef tot een goed einde te brengen is het vooral nodig dat we ook goed luisteren naar de feedback. Aangezien Umbraco een heel uitgebreid Content-Management-Systeem is. Zo kan je dezelfde problemen op veel verschillende manier oplossen. Is het zeker in het begin soms moeilijk om te zien wat nu juist de beste oplossing is. Zeker omdat er heel veel verschillende DataTypes beschikbaar zijn, die je vervolgens ook nog zelf kan aanpassen naargelang jouw voorkeuren.

 



