# Labo 4 - reflecties

Naam: Rabab El Labbari

## 1. Drie kolommen

- Op welk element staat `display: flex`, en op welke elementen staat `flex`?
- Waarom staan die twee niet op hetzelfde element? Display: flex staat op main en flex staat op de drie div-elementen.

## 2. Navigatiebalk

- Welke property verdeelt de ruimte langs de hoofdas, en welke lijnt uit op de kruisas? display: flex maakt de flexcontainer. flex bepaalt hoeveel ruimte de kinderen krijgen.
- Wat gebeurt er met de links als je `gap` vervangt door `margin-right` op elke `li`? justify-content: space-between verdeelt de ruimte langs de hoodas. align-items:center lijnt uit op de kruisas.

## 3. Mondriaan

- Welke twee vlakken moest je expliciet plaatsen, en waarom volstond de impliciete vulling voor de andere vier? De twee brede vakken, lila en olijf, moest ik expliciteit plaatsen. De andere vier werden automatisch geplaats.
- Waarom is `gap` hier beter dan een border op elk vlak? gap maakt ruimte tussen de vakken zonder dat elk een eigen border nodig heeft.

## 4. Trap

- Wat zie je als je de `grid-row`-declaraties weghaalt, en waarom? Zonder grid-row komen de vakken automatisch naast elkaar op een eerste rij.
- Wat betekent `grid-column: 4 / -1` voor de laatste trede, en waarom werkt het hier ook? grid-column: 4 /-1 betekent dat het vierde vak begint bij kolomlijn 4 en eindigt bij de laatste kolomlijn. Dit werkt omdat het raster vier kolommen heeft.

## 5. Dierenasiel Zonnehoek

- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk? 4 layoutcontainers: de header gebruikt flexbox, de kaartcontainer gebruikt grid en de de kaarten gebruiken Flexbox.
- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost? De navigatie en de kaarten worden te smal en passen niet meer goed. Dit wordt opgelost met responsive design en media queries.

## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
