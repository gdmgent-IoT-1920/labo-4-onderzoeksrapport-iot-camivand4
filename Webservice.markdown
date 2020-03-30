# ****Webservice**:**

## **Betekenis**

webservice heeft 2 betekenissen, ofwel:

 1. een **dienst** die door een elektronisch apparaat wordt aangeboden aan
 een ander elektronisch apparaat, met elkaar communiceert via het World
 Wide Web
 
 2. een **server** die draait op een computerapparaat, luistert naar
 verzoeken op een bepaalde poort via een netwerk, webdocumenten bedient
 en webapplicatieservices maakt, die dienen bij het oplossen van
 specifieke domeinproblemen op het web.

## **Praktijk**
In de praktijk biedt een webservice gewoonlijk een objectgeoriënteerde webgebaseerde interface aan een databaseserver, bijvoorbeeld gebruikt door een andere webserver of door een mobiele app, die een gebruikersinterface biedt aan de eindgebruiker. Veel organisaties die gegevens leveren in opgemaakte HTML-pagina's, zullen die gegevens ook op hun server leveren als XML of JSON, vaak via een webservice om syndicatie mogelijk te maken, bijvoorbeeld Wikipedia's Export. Een andere applicatie die aan de eindgebruiker wordt aangeboden, kan een mashup zijn, waarbij een webserver meerdere webservices op verschillende machines gebruikt en de inhoud in één gebruikersinterface compileert.

## **Algemene webservices**
**Asynchrone JavaScript en XML**
Asynchrone JavaScript en XML (AJAX) is een dominante technologie voor webservices. Ontwikkeld vanuit de combinatie van HTTP-servers, JavaScript-clients en gewone oude XML (in tegenstelling tot SOAP en W3C-webservices), wordt het nu vaak gebruikt met JSON en, of in plaats van, XML.

**Rest**
Representational State Transfer (REST) is een architectuur voor goed opgevoede webservices die op internet kunnen functioneren.  
  
In een document uit 2004 stelt de W3C de volgende REST als een belangrijk onderscheidend kenmerk van webservices:  
  
We kunnen twee grote klassen van webservices onderscheiden:  
- REST-compatibele webservices, waarbij het primaire doel van de service is om XML-weergaven van webresources te manipuleren met behulp van een uniforme set staatloze bewerkingen; en  
- willekeurige webservices, waarin de service een willekeurige set bewerkingen kan weergeven.  
-- W3C, Web Services Architecture

 **Webservices die opmaaktalen gebruiken**
 W3C
Web Services Flow Language (WSFL), vervangen door BPEL
Websjabloon
WS-MetadataExchange
XML-interface voor netwerkdiensten (XINS), biedt een POX-achtige webservice-specificatie-indeling

**Web API**
Een web-API is een ontwikkeling in webservices waarbij de nadruk is verschoven naar eenvoudiger communicatie met representatieve toestandsoverdracht (REST). Restful API's hebben geen op XML gebaseerde webserviceprotocollen (SOAP en WSDL) nodig om hun interfaces te ondersteunen.

## **W3C Web serivces**
Met betrekking tot W3C-webservices definieerde de W3C een webservice als:

Een webservice is een softwaresysteem dat is ontworpen om interoperabele machine-naar-machine-interactie via een netwerk te ondersteunen. Het heeft een interface die wordt geschreven in een machinaal verwerkbaar formaat (met name WSDL). Andere systemen hebben interactie met de webservice op een manier die wordt voorgeschreven door de beschrijving ervan met behulp van SOAP-berichten, meestal overgebracht met HTTP met een XML-serienummering in combinatie met andere webgerelateerde standaarden.

W3C Web Services maakt mogelijk gebruik van SOAP over HTTP-protocol, waardoor minder dure (efficiëntere) interacties via internet mogelijk zijn dan via eigen oplossingen zoals EDI / B2B. Naast SOAP over HTTP kunnen webservices ook worden geïmplementeerd op andere betrouwbare transportmechanismen zoals FTP. In een document uit 2002 definieerde de Web Services Architecture Working Group een webservicesarchitectuur, waarvoor een gestandaardiseerde implementatie van een "webservice" nodig was.

**Uitleg**
De term "webservice" beschrijft een gestandaardiseerde manier om webtoepassingen te integreren met behulp van de open standaarden XML, SOAP, WSDL en UDDI via een Internet Protocol-backbone. XML is het gegevensformaat dat wordt gebruikt om de gegevens te bevatten en er metagegevens om te verstrekken, SOAP wordt gebruikt om de gegevens over te dragen, WSDL wordt gebruikt voor het beschrijven van de beschikbare services en UDDI geeft aan welke services beschikbaar zijn.

Een webservice is een communicatiemethode tussen twee elektronische apparaten via een netwerk. Het is een softwarefunctie die wordt aangeboden op een netwerkadres via het web met de service altijd ingeschakeld, zoals in het concept van utility computing.

Veel organisaties gebruiken meerdere softwaresystemen voor beheer. Verschillende softwaresystemen moeten vaak gegevens met elkaar uitwisselen en een webservice is een communicatiemethode waarmee twee softwaresystemen deze gegevens via internet kunnen uitwisselen. Het softwaresysteem dat gegevens opvraagt, wordt een service-aanvrager genoemd, terwijl het softwaresysteem dat het verzoek zou verwerken en de gegevens zou verstrekken, een serviceprovider wordt genoemd.

Verschillende software kan verschillende programmeertalen gebruiken en daarom is er behoefte aan een methode voor gegevensuitwisseling die niet afhankelijk is van een bepaalde programmeertaal. De meeste soorten software kunnen echter XML-tags interpreteren. Webservices kunnen dus XML-bestanden gebruiken voor gegevensuitwisseling.

Er moeten regels voor communicatie tussen verschillende systemen worden gedefinieerd, zoals:
- Hoe een systeem gegevens kan opvragen bij een ander systeem.
- Welke specifieke parameters nodig zijn in het gegevensverzoek.
- Wat zou de structuur zijn van de geproduceerde gegevens. (Normaal gesproken worden gegevens uitgewisseld in XML-bestanden en wordt de structuur van het XML-bestand gevalideerd tegen een .xsd-bestand.)
- Welke foutmeldingen moeten worden weergegeven wanneer een bepaalde communicatieregel niet wordt nageleefd, om probleemoplossing gemakkelijker te maken.

Al deze regels voor communicatie zijn gedefinieerd in een bestand met de naam WSDL (Web Services Description Language), dat de extensie .wsdl heeft. (Voorstellen voor autonome webservices (AWS) zijn gericht op het ontwikkelen van flexibelere webservices die niet afhankelijk zijn van strikte regels. )

Een directory genaamd UDDI (Universal Description, Discovery, and Integration) definieert met welk softwaresysteem contact moet worden opgenomen voor welk type gegevens. Dus wanneer een softwaresysteem een ​​bepaald rapport / gegevens nodig heeft, gaat het naar de UDDI en zoekt uit met welke andere systemen het contact kan opnemen om die gegevens te ontvangen. Zodra het softwaresysteem erachter komt met welke andere systemen het contact moet opnemen, neemt het vervolgens contact op met dat systeem via een speciaal protocol genaamd SOAP (Simple Object Access Protocol). Het serviceprovidersysteem valideert eerst het gegevensverzoek door te verwijzen naar het WSDL-bestand, en verwerkt vervolgens het verzoek en verzendt de gegevens volgens het SOAP-protocol.

**Geautomatiseerde ontwerpmethoden**
Geautomatiseerde tools kunnen helpen bij het creëren van een webservice. Voor services die WSDL gebruiken, is het mogelijk om ofwel automatisch WSDL te genereren voor bestaande klassen (een bottom-up model) of om een ​​klassenskelet te genereren op basis van bestaande WSDL (een top-down model).

Een ontwikkelaar die een bottom-up model gebruikt, schrijft eerst implementatieklassen (in een programmeertaal) en gebruikt vervolgens een WSDL-generatietool om methoden van deze klassen als een webservice bloot te leggen. Dit is eenvoudiger te ontwikkelen, maar kan moeilijker te handhaven zijn als de oorspronkelijke klassen regelmatig worden gewijzigd.
Een ontwikkelaar die een top-down model gebruikt, schrijft eerst het WSDL-document en gebruikt vervolgens een codegeneratie-tool om het klassenskelet te produceren, dat indien nodig moet worden voltooid. Dit model wordt over het algemeen als moeilijker beschouwd, maar kan schonere ontwerpen opleveren en is over het algemeen beter bestand tegen verandering. Zolang de berichtformaten tussen afzender en ontvanger niet veranderen, hebben wijzigingen in de afzender en ontvanger zelf geen invloed op de webservice. De techniek wordt ook eerst contract genoemd omdat de WSDL (of contract tussen afzender en ontvanger) het uitgangspunt is.
Een ontwikkelaar die een subset-WSDL (SWSDL)  gebruikt (d.w.z. een WSDL met de subset-bewerking in de oorspronkelijke WSDL) kan testen van webservices en ontwikkeling van bovenaf uitvoeren.

**Criticism**
Critici van niet-RESTful webservices klagen vaak dat ze te complex zijn en gebaseerd zijn op grote softwareleveranciers of integrators, in plaats van op typische open source-implementaties.

Er zijn ook zorgen over de prestaties als gevolg van het gebruik van XML door de webservices als berichtformaat en SOAP / HTTP bij het omhullen en transporteren.

**Regressietesten van webservices**
Functioneel en niet-functioneel testen van webservices wordt gedaan met behulp van WSDL-parsering. Regressietests worden uitgevoerd door de wijzigingen te identificeren die zijn aangebracht om software te upgraden. De behoeften aan regressietests voor webservices kunnen op drie verschillende manieren worden gecategoriseerd, namelijk wijzigingen in WSDL, wijzigingen in de code en selectief opnieuw testen van bewerkingen. We kunnen de bovenstaande drie behoeften vastleggen in drie tussenliggende vormen van Subset WSDL, namelijk Difference WSDL (DWSDL), Unit WSDL (UWSDL) en Reduced WSDL (RWSDL), respectievelijk. Deze drie subset-WSDL's worden vervolgens gecombineerd tot gecombineerde WSDL (CWSDL) die verder wordt gebruikt voor regressietests van de webservice. Dit zal helpen bij Automated Web Service Change Management (AWSCM) door de selectie van de relevante testcases uit te voeren om een ​​gereduceerde testsuite op te bouwen uit de oude testsuite.

Het testen van webservices kan ook worden geautomatiseerd met behulp van verschillende testautomatiseringstools zoals SOAP UI, Oracle Application Testing Suite (OATS), Unified Functional Testing, Selenium, etc.

**Beheer van webserviceveranderingen**
Werkgerelateerd aan het vastleggen en visualiseren van wijzigingen die zijn aangebracht in een webservice. Visualisatie en berekening van veranderingen kunnen worden gedaan in de vorm van tussenliggende artefacten (Subset WSDL). Het inzicht in de berekening van de impact van veranderingen is nuttig bij testen, top-down ontwikkeling en het verminderen van regressietests. AWSCM is een tool die subsetbewerkingen in een WSDL-bestand kan identificeren om een subset WSDL te construeren.

Wikipedia contributors. (2020, 26 maart). Web service. Geraadpleegd van https://en.wikipedia.org/wiki/Web_service

