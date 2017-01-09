# Programmeerproject
## Jelle Mul
### 11402148

Het bedrijf Peerby Go is een bedrijf dat mensen de mogelijkheid biedt om spullen te huur aan te bieden en om spullen te huren. Hierbij fungeren zij als tussenpersoon en mogelijk als bezorgdienst. Voor hen is het gunstig als er veel transacties zijn aangezien zij hier aan verdienen. Het is dus van belang dat veel mensen gebruiken van de dienst. Daarnaast is het voor hen interessant om een beeld te krijgen van het aantal en het type transacties dat plaatsvindt. 

Dit kan op de volgende wijze worden gedaan. In de data wordt van een te bezorgen product de vertrektijd gegeven met daarbij de lengte en breedtegraad, en de lengte en breedtegraad van het aankomstpunt. Op basis van de afstand kan met een combinatie van D3 en de google maps API een lijn worden getrokken tussen het vertrek en aankomstpunt. Hier mee kan dus "realtime" van verschillende transactie de voorspelde route van de bezorger worden weergegeven. Deze kaart is voornamelijk interresant als reclame methode om mensen inzicht te geven in het aantal transacties in de buurt wat hun door de visuele aantrekkelijkheid aanspoort om ook de dienst te gebruiken

Naast de kaart is het interessant om te zien welk type producten worden gehuurd. In de data worden de verschillende voorwerpen al in categorieën onderverdeeld. In een piechart kan worden weergegeven in welke mate de categorieën worden gehuurd. Tot slot is het interessant om te zien hoeveel transacties er per uur plaatsvinden dit kan worden weergegeven in een barchart. Deze 3 visualisaties samen geven de zowel de gebruiker als het bedrijf zelf een goed beeld van welke transacties plaatsvinden. Wat kan worden gebruikt voor verdere data analyse of voor reclamedoeleinden.

### Data
De Data word bij het laden van de pagina opgehaald van de API van het bedrijf Peerby. Deze data heeft een json format.

### Verschillende onderdelen en interacties
De 3 eerder genoemde visualisaties zijn de verschillende onderdelen van de data. Bij de piechart kan het nog mogelijk zijn om de verschillende categorieën aan en uit te vinken om zo deze met elkaar te kunnen vergelijken. Daarnaast zal de data in de kaart gebasseerd zijn op dezelfde data als in de piechart. In het geval dat het gaat om het aantal transacties per uur zou dit kunnen over de transacties van de dag ervoor, of van de komende dag (ofwel de transacties die ook in de kaart worden weergegeven).

### Technische problemen en beperkingen
Ik zal veel kennis moet opdoen over het laten verschijnen van data op basis van een tijdstip, en het leren gebruiken van D3 in combinatie met de google maps API. 2 nuttige bronnen hierbij staan hieronder:
- https://bl.ocks.org/mbostock/899711
- http://bl.ocks.org/marufbd/7191903 




