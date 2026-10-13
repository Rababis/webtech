# Labo 2 - reflecties

Naam: ( Rabab El Labbari)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: De drie links in het menu: Adopteren, Onze bewoners en Openingsuren.
- b. `article > p`: De paragrafen over adopteren, onze bewoners en openingsuren.
- c. `.uren li:nth-child(3)`: woensdag 14-18u
- d. `h2 ~ p`: De 4 paragrafen op lijnen 26, 27, 30 en 49.
- e. `.rassen li:first-child`: Honden, Herders en herderkruisingen, Europese korthaar.
## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |herkomst |groen|ja|
| 2 |blauw |volgorde|blauw |ja |
| 3 |rood|specificiteit|rood|ja|
| 4 |rood|volgorde | rood |ja |
| 5 |blauw |specificiteit|blauw |ja |
| 6 |blauw |volgorde|blauw |ja|
| 7 |rood |overerving |rood |ja|
| 8 |rood |rechtstreekse stijl|rood |nee|
| 9 | rood|!important |rood |ja |
| 10 |blauw | volgorde |blauw | ja|

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?) Ik had vraag 8.Ik dacht dat de tekst rood zou zijn, maar in de browser was die blauw. Vraag8 vond ik het moeilijkst omdat ik niet goed wist welke CSS-regel zou winnen.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class? Ik koos nav a, omdat ik allee de links in de navigatie wilde aanpassen en geen class nodig had.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak? De navigatie kostte mij het meeste tijd, omdat ik eerste de CSS op de verkeerde plaats had gezet.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die? ik koos achtergrond, tekst en accent, omdat ik zo de kleuren van mijn website makelijk kan aanpassen.
- Wat verandert er in je site als je één token wijzigt? Als ik één token wijzig, verandert die kleur overal op mijn website waar dat token gebruikt wordt.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:
## 2. Selectors
1. 'header nav ul li a' selecteert alle links in de navigatielijst van de header.
2 'article > p' selecteert paragrafen die rechtstreeks in een article staan.
3. '.uren li:nth-child(3)' selecteert het derde lijstitem in de lijst met openingsuren.
4. 'h2 ~ p' selecteert alle paragrafen die na een h2 staan en dezelfde ouder hebben.
5. '.rassen li:first-child'selecteert elk eerste lijstitem binnen de rassenlijs.
