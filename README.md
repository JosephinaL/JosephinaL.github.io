# Open Data Atelier

Van open data naar een bruikbaar instrument, voor elke gemeente. Door Josephine Linders.

**Site:** https://josephinal.github.io

Instrumenten voor gemeentelijke vraagstukken, gebouwd op openbare registraties. Geen rapporten en geen dashboards: met een instrument kies je zelf waar je kijkt. Elk instrument werkt voor alle 342 Nederlandse gemeenten: kies een gemeente en de pagina rekent ter plekke. Geen installatie, geen account.

## Instrumenten

| Instrument | Pagina | Vraag | Bronnen |
|---|---|---|---|
| **Fysieke leefomgeving** | | | |
| Label C-kantoren | [labelc.html](https://josephinal.github.io/labelc.html) | Welke kantoren voldoen aan de energielabel C-plicht, pand voor pand? | BAG, RIVM (energielabels), RCE (rijksmonumenten), CBS |
| **Financiën** | | | |
| Iv3-spiegel | [iv3spiegel.html](https://josephinal.github.io/iv3spiegel.html) | Waar gaat het geld van een gemeente heen, en deed ze wat ze van plan was? | Iv3 (CBS) |
| Iv3-panorama | [iv3panorama.html](https://josephinal.github.io/iv3panorama.html) | Waar wijkt een gemeente af in de verdeling van haar uitgaven? | Iv3 (CBS) |
| **Economie en ondernemen** | | | |
| Bedrijvigheid per buurt *(in ontwikkeling)* | [bedrijvigheid.html](https://josephinal.github.io/bedrijvigheid.html) | Hoe gemengd zijn wonen en werken per buurt? | CBS, BAG, Iv3 |
| **Onderwijs** | | | |
| Basisonderwijs per buurt | [onderwijs.html](https://josephinal.github.io/onderwijs.html) | Waar krimpen en groeien basisscholen tot 2035? | DUO, BAG/PDOK, CBS |
| **Bevolking en wonen** | | | |
| Huishoudens en vergrijzing | [huishoudens.html](https://josephinal.github.io/huishoudens.html) | Hoe zijn de huishoudens samengesteld, hoe snel vergrijst de gemeente sinds 1995, en in welke buurten? | CBS (Regionale kerncijfers, Kerncijfers wijken en buurten), PDOK |
| Woningvoorraad en leegstand | [woningen.html](https://josephinal.github.io/woningen.html) | Hoeveel woningen zijn er, wie bezit ze, wat komt er elk jaar bij en hoeveel staan er leeg? | CBS (Woningvoorraad, Levensloop van woningen, Kerncijfers wijken en buurten), PDOK |
| Bouwstroom | [bouwstroom.html](https://josephinal.github.io/bouwstroom.html) | Welke woningen zijn vergund, in aanbouw of net klaar, en waar is het verwachte bouwjaar al voorbij? | BAG, Officiële bekendmakingen (gemeenteblad), CBS |
| **Sociaal domein · ondersteuning en meedoen** | | | |
| Wmo per wijk | [wmo.html](https://josephinal.github.io/wmo.html) | Hoeveel inwoners krijgen Wmo-ondersteuning, wie zijn dat, wat kost het en hoe verhoudt het zich per wijk tot de vergrijzing? | CBS (Wmo-cliënten, Regionale kerncijfers, Kerncijfers wijken en buurten), Iv3 (CBS), PDOK |
| Schulden per wijk | [schulden.html](https://josephinal.github.io/schulden.html) | Hoeveel huishoudens hebben problematische schulden, bij welke schuldeisers, wie zijn het en in welke wijken? | CBS (Schuldenproblematiek in beeld), PDOK |
| Inburgering per gemeente | [inburgering.html](https://josephinal.github.io/inburgering.html) | Wie werd inburgeringsplichtig onder de Wet inburgering 2021, hoe ver is elke jaargroep en in welke leerroute? | DUO (WI 2021 Instroom, Uitstroom en Leerroute), CBS (Regionale kerncijfers) |
| **Sociaal domein · jeugd en veilig thuis** | | | |
| Jeugdzorg per wijk | [jeugdzorg.html](https://josephinal.github.io/jeugdzorg.html) | Hoeveel jongeren krijgen jeugdzorg, wat kost het en wie verwijst, door de jaren heen en per wijk? | CBS (Beleidsinformatie Jeugd, Kerncijfers wijken en buurten), PDOK |
| Veilig Thuis per gemeente | [veiligthuis.html](https://josephinal.github.io/veiligthuis.html) | Hoe vaak vragen inwoners en professionals Veilig Thuis om advies of doen ze een melding, over welk geweld, wie meldt en wat gebeurt er daarna? | CBS (Beleidsinformatie Veilig Thuis) |
| **Werkbank** | | | |
| Eigen lijst op de kaart | [eigenlijst.html](https://josephinal.github.io/eigenlijst.html) | Hoe ziet een eigen lijst van de gemeente, zoals het vastgoed in eigen beheer, eruit naast de BAG en open data? | BAG, RIVM (energielabels), RCE (rijksmonumenten), CBS; voorbeeld: Gemeentelijk Vastgoed Amsterdam |

## Indicatorenkompas

[indicatoren.html](https://josephinal.github.io/indicatoren.html) staat naast de instrumenten en is zelf geen instrument: het rekent niet en toont geen cijfers. Per thema staat welke indicatoren ertoe doen, wat ze zeggen en wat niet, op welk niveau ze bestaan en waar ze staan: in open data (met tabelnummer), bij een ketenpartner of alleen in de eigen registratie van de gemeente. Interne indicatoren verwijzen naar het Gemeentelijk Gegevensmodel (GGM) v2.5.1; een knop zet ze in één uitvraag voor de informatie-afdeling. Ingedeeld naar de Iv3-hoofdtaakvelden, net als de instrumenten; nu uitgewerkt: Wmo en huiselijk geweld en kindermishandeling. Bronnen van de indicatoren: CBS (StatLine), RIVM, waarstaatjegemeente.nl, Iv3-informatievoorschrift 2025, Regeling beleidsindicatoren (BBV), Impactmonitor huiselijk geweld en kindermishandeling.

## Werkwijze

Vier lagen:

1. **Skelet:** BAG en CBS-buurten en -wijken als verbindende sleutel.
2. **Open domeindata:** energie (RIVM), erfgoed (RCE), onderwijs (DUO), financiën (Iv3), jeugd, Veilig Thuis, Wmo, schulden, bevolking en wonen (CBS), inburgering (DUO), vergunningen (gemeenteblad).
3. **Verrijking:** wat alleen de gemeente weet, toegevoegd in de eigen omgeving. Eigen lijst op de kaart is daar het gereedschap voor.
4. **Antwoord:** navolgbaar per object.

Drie principes:

- **Navolgbaar:** elke uitkomst laat zien welke bron, drempel en uitzondering is gebruikt.
- **Onzekerheid zichtbaar:** waar open data tekortschiet, staat dat er.
- **De code gaat naar de data:** lokale gegevens blijven in de browser of de eigen omgeving van de gemeente.

## Techniek

- Elk instrument is één zelfstandig HTML-bestand, zonder buildstap.
- De data komt live uit openbare API's (PDOK, RIVM, RCE, CBS, Officiële bekendmakingen) of staat inline, zoals bij DUO (onderwijs en inburgering), waar de API geen verzoeken van andere sites toestaat, en bij Schuldenproblematiek in beeld, dat alleen als download bij een CBS-dashboard bestaat.
- Bron en peildatum staan op elke pagina.
- Gehost via GitHub Pages.

### Eigen gegevens

Label C-kantoren en Eigen lijst op de kaart nemen eigen gegevens van de gemeente op. Daarvoor geldt:

- De lijst wordt in de browser gelezen en nergens bewaard. Er is geen eigen server; sluit je de pagina, dan is de lijst weg.
- Eigen lijst op de kaart stuurt alleen de adressen als zoekvraag naar PDOK, om ze in de BAG te vinden. Dat staat op de pagina.
- In Eigen lijst op de kaart staat een beveiligingsregel (Content-Security-Policy) die alleen verbindingen toestaat met `api.pdok.nl` en `data.rivm.nl`. Zo is na te gaan dat de lijst nergens anders heen kan.
- Een controle vooraf stopt lijsten met persoonsgegevens (namen, BSN, contactgegevens, cliënten of bewoners) voordat er iets wordt opgezocht. De pagina is bedoeld voor lijsten zonder persoonsgegevens, zoals het eigen vastgoed.

## Gebruik

© Josephine Linders. Linken, citeren en screenshots gebruiken mag, met vermelding van de pagina en de bron van de cijfers. De pagina's kopiëren, aanpassen of elders publiceren alleen na overleg, via [Samenwerken](https://josephinal.github.io/#samenwerken).

Een directe link naar je eigen gemeente werkt met `#gm=` en de gemeentecode, bijvoorbeeld `schulden.html#gm=0518` voor 's-Gravenhage.

Fout gezien of een cijfer dat je niet herkent? Meld het via de knop onder de cijfers op de pagina, via [Samenwerken](https://josephinal.github.io/#samenwerken) of via [Issues](https://github.com/josephinal/josephinal.github.io/issues).

## Bronnen en licenties

Deze gebruiksregel geldt voor de pagina's zelf: opbouw, code, teksten en rekenwijze. De gebruikte data valt onder de licenties van de bronhouders, met naamsvermelding op de pagina:

- Kadaster/BZK (BAG, PDOK): CC0
- KOOP (Officiële bekendmakingen): CC0
- CBS (Statline, Kerncijfers wijken en buurten, Iv3): CC-BY 4.0; CBS Schuldenproblematiek in beeld (aanvullend statistisch onderzoek): overnemen met het CBS als bron
- RIVM (energielabels, afgeleid uit EP-Online van RVO) en Rijksdienst voor het Cultureel Erfgoed
- DUO: CC-BY; WI 2021-inburgeringsdata: door DUO vrij van auteursrechten verklaard, met DUO als bron vermeld
- Gemeente Amsterdam (Gemeentelijk Vastgoed, alleen als voorbeeldlijst): openbaar

## Auteur

**Josephine Linders**, domeinoverstijgende informatieanalyse. De instrumenten zijn op eigen titel gemaakt.
