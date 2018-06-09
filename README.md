#Introductie

## context/situering
### Inleiding
Samen met Axel Van Uffelen maak ik de website voor het bedrijf ABC-Groep. Onze opdracht bestaat er uit een nieuwe website voor het bedrijf te ontwikkelen aangezien de huidige website niet meer up-to-date is. Omdat alles dynamisch moet zijn hebben ze ons gevraagd een content management systeem te voorzien op de backend, meer bepaald Umbraco. Toen bleek dat onze opdracht sneller dan voorzien klaar zou zijn hebben ze ons nog een tweede opdracht gegeven. Deze odpracht bestond eruit het ontwikkelen van een kleine webshop op het intranet. Het intranet is een webapplicatie enkel toegankelijk voor de werknemers binnen het bedrijf.


## beschrijving stagebedrijf
ABC-Groep levert ICT consultancy diensten op het vlak van outsourcing, software development, IT services en Best Practice solutions voor Microsoft SharePoint en Odoo.
ABC-Groep is een overkoepelend bedrijf van meerdere dochterbedrijven. Als eerste dochterbedrijf heb je ACE. Dit bedrijf houd zich bezig met het op maat maken van applicaties, ontwikkeld in .NET. Dit is ook het dochterbedrijf waarbij we stage gelopen hebben. Beyond-IT is een dochterbedrijf dat zich bezig houdt met het op maat maken van sharepoint oplossingen. 
DynApps is een bedrijf binnen ABC-Groep dat zich bezig houdt met het aanbieden van Odoo oplossingen. Cereus houdt zich bezig met het ontwikkelen en op maat maken van Java en Oracle applicaties. Het is niet zo dat al deze bedrijven onderverdeeld zijn in aparte gebouwen. ABC-Groep heeft 2 locaties. 1 locatie in Geel en 1 locatie in Kalmthout. Vaak is de grens tussen deze dochterbedrijven een beetje vaag. Gericht naar klanten maakt het expliciet uitdragen van welk dochterbedrijf de oplossing afkomstig is niet zoveel uit. Voor de klant draait het erom dat zij een werkende oplossing krijgen voor hut probleem.
##probleemstelling/opgave

### Waarom een nieuwe website?

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

 





## Beschrijving E-commerce oplossing voor het intranet

### Waarom een E-commerce oplossing voor het intranet?


Omdat het regelmatig voorvalt binnen het bedrijf dat er mensen tweedehands spullen verkopen of speelgoed van hun kinderen willen verkopen. Patrick Calleweart had graag een nice-to have uitbreiding voor het bestaande intranet. Omdat het hiervoor een beetje lastig was om dit op een effectieve manier uit te voeren. Daarom hebben wij de opdracht op ons genomen voor het ontwikkelen van een uitbreiding voor het intranet. De bedoeling is dat dat de werknemer die een item verkopen een mail stuurt naar de website bouwer. Dit zal iemand met een HR functie zijn. De mail dient dan een omschrijving te bevatten van het product. In deze omschrijving zal de status van het product omschreven worden. Eventueel ook de rede van de verkoop kan hierin toegelicht worden. Een afbeelding dient ook best meegestuurd te worden. Deze manier van werken zal de flow voor het verkopen van items veel makkelijker maken. Het enigste wat de website bouwer dan nog moet doen is inloggen in de umbraco backend en een pagina aanmaken voor het te verkopen product.

### Verloop

On het begin zijn we vooral bezig geweest met het opzoeken van documentatie van de verschillende umbraco E-commerce oplossingen die beschikbaar zijn. Zo hebben we Merchello, Ucommerce en Tea commerce getest. We hebben deze packages geinstalleerd en werkend gekregen. Na uitvoerig testen en de voor-en nadelen vergeleken te hebben zijn we verdergegaan met het ontwikkelen in Merchello.

### Problemen

Het ontwikkelen van dit project is niet bepaald vlot verlopen. Het intranet is een bestaande applicatie. Dit wil dus zeggen dat de umbraco versie die draait op het intranet een oude versie van umbraco is. Merchello word niet ondersteund op deze versie. De oplossing voor dit probleem was het upgraden van de umbraco versie van het intranet. Echter zijn er aanpassingen gebeurd aan bepaalds dll files van umbraco in dit project. Deze aanpassingen zijn ergens gedocumenteerd geweest maar zijn niet echt makkelijk terug te vinden. Hierdoor is het upgraden van het intranet niet echt een makkelijke en voor de hand liggende oplossing. Aangezien het in het begin ook niet echt duidelijk was wat de juiste requirements waren voor deze opdracht, zijn we nog een keer gaan samenzitten met Patrick Calleweart. Uit dit gesprek werd ons duidelijk dat het niet echt een webshop was maar eerder een reservatie systeem dat vereist was. Het uitvoeren van betalingen en shipment methodes kunnen selecteren was dan ook niet echt van toepassing. Aangezien dit 1 van de belangrijkste redenen zijn op een e-commerce package te gebruiken heeft Sander (onze projectmanager) beslist om niet verder te gaan met Merchello maar ons het te laten programmeren in de bestaande umbraco versie van het intranet. 
