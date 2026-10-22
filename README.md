# Van open data naar een bruikbaar informatieproduct, voor elke gemeente

**Site:** https://josephinal.github.io

Informatieproducten voor gemeentelijke vraagstukken, gebouwd op openbare registraties. Elk product werkt voor alle 342 Nederlandse gemeenten: kies een gemeente en de pagina rekent ter plekke. Geen installatie, geen account.

## Producten

| Product | Pagina | Vraag | Bronnen |
|---|---|---|---|
| Label C-kantoren | [labelc.html](https://josephinal.github.io/labelc.html) | Welke kantoren voldoen aan de energielabel C-plicht, pand voor pand? | BAG, RIVM (energielabels), RCE (rijksmonumenten), CBS |
| Iv3-spiegel | [iv3spiegel.html](https://josephinal.github.io/iv3spiegel.html) | Waar gaat het geld van een gemeente heen, en deed ze wat ze van plan was? | Iv3 (CBS) |
| Iv3-panorama | [iv3panorama.html](https://josephinal.github.io/iv3panorama.html) | Waar wijkt een gemeente af in de verdeling van haar uitgaven? | Iv3 (CBS) |
| Bedrijvigheid per buurt *(in ontwikkeling)* | [bedrijvigheid.html](https://josephinal.github.io/bedrijvigheid.html) | Hoe gemengd zijn wonen en werken per buurt? | CBS, BAG, Iv3 |
| Basisonderwijs per buurt | [onderwijs.html](https://josephinal.github.io/onderwijs.html) | Waar krimpen en groeien basisscholen tot 2035? | DUO, BAG/PDOK, CBS |
| Jeugdzorg per wijk | [jeugdzorg.html](https://josephinal.github.io/jeugdzorg.html) | Hoeveel jongeren krijgen jeugdzorg, wat kost het en wie verwijst, door de jaren heen en per wijk? | CBS (Beleidsinformatie Jeugd, Kerncijfers wijken en buurten), PDOK |

## Werkwijze

Vier lagen:

1. **Skelet:** BAG en CBS-buurten en -wijken als verbindende sleutel.
2. **Open domeindata:** energie (RIVM), erfgoed (RCE), onderwijs (DUO), financiën (Iv3), jeugd (CBS).
3. **Verrijking:** wat alleen de gemeente weet, toegevoegd in de eigen omgeving.
4. **Antwoord:** navolgbaar per object.

Drie principes:

- **Navolgbaar:** elke uitkomst laat zien welke bron, drempel en uitzondering is gebruikt.
- **Onzekerheid zichtbaar:** waar open data tekortschiet, staat dat er.
- **De code gaat naar de data:** lokale gegevens blijven in de browser of de eigen omgeving van de gemeente.

## Techniek

- Elk product is één zelfstandig HTML-bestand, zonder buildstap.
- De data komt live uit openbare API's (PDOK, RIVM, RCE, CBS) of staat inline, zoals bij DUO, waar de API geen verzoeken van andere sites toestaat.
- Bron en peildatum staan op elke pagina.
- Gehost via GitHub Pages.

## Bronnen en licenties

De gebruikte data valt onder de licenties van de bronhouders: Kadaster/BZK (BAG, PDOK), CBS, RIVM, Rijksdienst voor het Cultureel Erfgoed en DUO (CC-BY, naamsvermelding op de pagina).

## Auteur

**Josephine Linders**, domeinoverstijgende informatieanalyse. De producten zijn op eigen titel gemaakt.
