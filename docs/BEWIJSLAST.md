# Lighthouse Analyse van de NS Website

# Toegankelijkheids- en Responsief Ontwerpanalyse van de NS Website

## Geïdentificeerde Problemen

### 1. Ongeldige Waarden in [aria-*] Attributen
   - **Probleem**: De NS-website maakt gebruik van [aria-*] attributen met ongeldige waarden.
   - **Implicaties**: [aria-*] attributen worden ingezet om de webtoegankelijkheid te bevorderen voor gebruikers met beperkingen. Ongeldige waarden kunnen de toegankelijkheid nadelig beïnvloeden.

### 2. Knoppen Zonder Toegankelijke Naam
   - **Probleem**: Op de NS-website hebben knoppen geen toegankelijke naam.
   - **Implicaties**: Knoppen dienen over een toegankelijke naam te beschikken, zodat gebruikers, inclusief screenreaders, begrijpen wat ze uitvoeren. Het ontbreken van een toegankelijke naam kan de toegankelijkheid schaden.

### 3. Gebruik van [user-scalable="no"] in het <meta name="viewport"> Element of [maximum-scale] Minder Dan 5
   - **Probleem**: De NS-website hanteert [user-scalable="no"] in het <meta name="viewport"> element of stelt [maximum-scale] in op minder dan 5.
   - **Implicaties**: Het beperken van de schaalbaarheid van een website kan de gebruikerservaring op mobiele apparaten verstoren en contrasteert met beste praktijken voor responsief webdesign.

### 4. Heading Elementen Niet in Sequentieel Dalende Volgorde
   - **Probleem**: De heading elementen op de NS-website volgen geen sequentieel dalende volgorde.
   - **Implicaties**: Het gebruik van heading elementen (H1, H2, H3, enz.) in een logische volgorde draagt bij aan de begrijpelijkheid van de paginastructuur voor zowel gebruikers als zoekmachines.

## Samenvatting:

De grondige analyse van de NS-website met behulp van Lighthouse heeft verschillende toegankelijkheids- en responsieve ontwerpgerelateerde problemen aan het licht gebracht. Het oplossen van deze kwesties zal resulteren in een verbeterde totaalervaring voor gebruikers en een website die toegankelijker en gebruiksvriendelijker is.




<img src="https://i.imgur.com/vWrzYks.png" width="800">

## Andere Testen die ik heb gedaan

### De Keyboard Test

Het is opmerkelijk dat bij het gebruik van de "Tab" toets de gehele website nauwkeurig doorlopen kan worden, van het logo tot het inloggen en zelfs tot aan de footer.

### De Screen Reader Test

In de screen reader test is vastgesteld dat de knoppen geen toegankelijke namen hebben, wat resulteert in een verminderde begrijpelijkheid of soms zelfs het volledig ontbreken van knopinformatie.

### Interactive Elements Test

De NS-website heeft een doordacht design, met een goede contrastverhouding en een duidelijke gebruikersstroom. Bij het openen van de website wordt de reisplanner direct gepresenteerd, wat de gebruiker onmiddellijk laat begrijpen wat het doel is en hoe dit te bereiken is.

### Headings and Landmarks Test

De uitgebreide ```<div>``` modules maken de website enigszins complex. De opbouw met ```<header>```, ```<main>```, en ```<footer>``` is duidelijk, maar de rest van de HTML-structuur lijkt verward door complexe benamingen en methodes, waardoor de algehele HTML-structuur minder overzichtelijk wordt. Het kan nuttig zijn om de namen en de methoden te vereenvoudigen voor een betere structuur.
