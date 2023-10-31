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
