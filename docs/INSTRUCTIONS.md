
# Look and Feel - Living Styleguide

Ontwerp en maak een *living styleguide* voor een opdrachtgever.

## Context

Deze deeltaak hoort bij sprint 4 Look and Feel. Dit is een deeltaak die je in een team uitvoert, met alle studenten die dezelfde opdrachtgever hebben.

In de workshop Living Styleguide wordt uitgelegd wat een living styleguide is en hoe je het kan ontwerpen en maken.

Deze deeltaak hoort bij de leertaak:
- [Look and feel - Corporate identity](https://github.com/fdnd-task/look-and-feel-corporate-identity)

## Doel van deze opdracht

> Living style guides are an important tool for web development today, especially in large, complex web applications. They help document styles and patterns, keep designers and developers in sync, and greatly help to organize and distill complex interfaces. (<cite>[Lambert, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/))

Een living styleguide is essentieel voor het begrijpen en overbrengen van de look and feel van een website. Het geeft voorbeelden en uitleg over hoe iets eruit moet zien en hoe markup (HTML) en vormgeving (CSS) moeten worden toegepast. Een living styleguide helpt bij het ontwerpen en bouwen van een website met consistente look and feel in de huisstijl van een opdrachtgever.

## Werkwijze

Deze opdracht gaat over analyseren en ontwerpen/bouwen van de DLC. 

In de [analysefase](#analyseren) breng je in kaart hoe het zit met de huidige uitingen van de opdrachtgever en welke huisstijl elementen in gebruik zijn. Het resultaat is een *interface inventory*. 

In de [ontwerp/bouwfase](#ontwerpen-en-bouwen) maak je keuzes, bepaal je ontwerp standaarden en leg je vast hoe componenten in HTML en CSS opgenomen worden. 

Het resultaat is een levende - dat wil zeggen live, semantisch, toegankelijk - stijlgids welke gebruikt kan worden door alle frontenders en designers in een organisatie. Welke kleuren en typografie worden gebruikt in de huisstijl? Wat zijn overeenkomstige elementen van de verschillende pagina's of componenten? Hoe ziet de layout van verschillende onderdelen eruit? Hoe gedraagt de website zich in verschillende contexten (responsive design). En tenslotte, welke HTML en CSS is nodig om de elementen van de living styleguide op te maken en vorm te geven?

### Analyseren

Je begint met het in kaart brengen van alle gemaakte elementen van de huisstijl en gemaakte website. Het resultaat is een *interface inventory*, een verzameling van alle gemaakte onderdelen van de interface.


#### Interface inventory
 
 1. Maak een Miro board aan. Hier gaan jullie alle gemaakte onderdelen verzamelen
 2. Zet een template met categorieen om de onderdelen te verzamelen 

- Typography
 - Headings: headings, titels, subtitles, ...
 - Text elements: paragraphs, blockquotes, ...
 - Lists: bulleted, numbered, definition, ...
- Images
 - Logo's
 - Icons
 - Content images: different content images with borders, white space, ...
 - Image with captions
- Media
 - Video player
 - Audio player
 - Slideshow players
- Tables 
- Buttons
- Forms
 - Text inputs: text, email, url, password, ...
 - Select menu's
 - Radio/Checkbox Inputs
- Navigation
 - Primary Navigation
 - Tabs
 - Breadcrumbs
- Components
 - Carousels
 - Accordions
- ... 
 
 3. **Begin met screenshotten.** Nu het leuke gedeelte. Neem screenshots van de ingrediënten van jouw interface. Je doel is om unieke versies van componenten te vangen. Hier een mogelijke categorisering (kies wat van toepassing is op jouw project!):
Jullie voeren de interface audit uit op de oorspronkelijke huisstijl en alle gemaakte projecten voor de opdrachtgever.

    
    - Globals: header, footer en andere globale elementen
    - Navigatie: primair, footer, paginering, kruimelpad, …
    - Afbeeldingen: logo’s, hero’s, avatars, thumbnails, …
    - Iconen: vergrootglas, sociale, spinners, favicons, hamburgers, pijlen, …
    - Formulieren: inputs, textareas, select menu’s, checkboxes, radio buttons, …
    - Knoppen: groot, klein, primair, secundair, voortgang, …
    - Interactieve componenten: accordions, tabs, carrousels, alles met bewegende delen
    - Media: video spelers, audio spelers, …
    - Berichtgeving: alerts, success, error, warning, validatie, …
    - Headings: h1, h2, h3, h4, h5, h6 en typografische variaties
    - Lijsten: ongeordend, geordend, definitielijst, bullets, lijnen, …
    - 3de partij: widgets, iframes, beurs-tickets, social links, alles wat niet op hetzelfde domein gehost wordt
    - Reclame: reclame banners en andere reclame elementen
    - Blokken: combinaties van afbeeldingen, koppen en inleidingen, …
    - Animatie: gifjes van interface animatie of echt werkende animaties
    - Kleuren: unieke huisst
    - ijlkleuren
    - …
   
 4. 
5. **Categoriseer jouw screenshots.** Je kunt dit doen terwijl je bezig bent of na afloop van je screenshot sessie. Het doel is dat je alle verschillende voorkomens van een bepaald molecuul naast elkaar kunt zien.
6. **Presenteer.** Laat als groep de interface inventory zien aan je ~~opdrachtgever~~ docent en kijk toe hoe ze in tranen uitbarsten. Na deze exercitie ga je door met [ontwerpen](#ontwerpen).

#### Meer lezen?

- [Brad Frost, Interface Inventory, 2013](https://bradfrost.com/blog/post/interface-inventory/)
- [Mar High, How to create an interface inventory, 2021](https://mainmatter.com/blog/2021/06/02/how-to-create-an-interface-inventory/)
- [Brad Frost, Atomic Design, 2013](https://bradfrost.com/blog/post/atomic-web-design/)

### Ontwerpen en Bouwen

Je hebt inmiddels vast een beeld bij wat een huisstijl is. De meeste opdrachtgevers van FDND-Agency maken gebruik van een of andere styleguide waarin de huisstijl vastgelegd is. Bekijk als voorbeeld de [huisstijl van de Hogeschool van Amsterdam](https://www.hva.nl/praktisch/algemeen/hva-breed/communicatie/hva-huisstijl/hva-huisstijl.html). Een groot nadeel van traditionele huisstijlhandboeken is dat ze meestal in de vorm van een PDF gemaakt worden. De reden daarvoor is dat ontwerpers dit van oudsher zo gewend zijn te doen. Voor een toegankelijk ontwerp in een responsive omgeving is dit echter niet genoeg. Frontenders willen weten hoe een logo zich gedraagt als er weinig ruimte, een beetje meer ruimte én veel of zelfs heel veel ruimte is. Kortom, we hebben behoefte aan een responsive variant op het klassieke huisstijlhandboek.

Een *living styleguide* of levende stijlgids biedt het antwoord op de tragisch statische handboeken van weleer. De *living styleguide* is een modern huisstijlhandboek welke in de browser leeft, het is een website over websites van een organisatie. *Living* heeft hierbij een dubbele betekenis. Enerzijds is het een live, toegankelijke en semantische verzameling huisstijlcomponenten. Anderzijds is het een up-to-date huisstijl welke bijgehouden wordt als ontwerpbeslissingen genomen worden, dus *living* in de zin van groei.

Goede voorbeelden van een levende stijlgids zijn de [Decathlon Design System](https://www.decathlon.design/726f8c765/p/75e137-digital-overview) of de  [Familysearch Styleguide](https://www.familysearch.org/frontier/styleguide/) uit een artikel van Steven Lambert op Smashing Magazine. Het artikel staat onderaan bij ‘Meer lezen?’ mocht je het willen lezen.

#### Maak een living styleguide
Alhoewel bedrijven vaak aandacht besteden aan het uiterlijk van de living styleguide gaat het in dit geval écht om de inhoud. Richt je dus in eerste instantie daar op. In deze repository is een voorbeeldstructuur opgenomen maar deze mag je naar eigen inzicht volledig aanpassen.

1. **Kies een categorie** uit de interface inventory en onderzoek of je overeenkomsten kunt ontdekken.  Als je met een team werkt kan je categorieën verdelen. Het is aan te raden in verschillende bestanden te werken.
2. **Schrijf HTML**. Kies de best passende elementen en neem die met nette, toegankelijke en semantische HTML op in het betreffende bestand.  Blijf zo dicht mogelijk bij het origineel van de opdrachtgever (dus gebruik de originele huisstijl).
3. **Schrijf CSS**. Schrijf CSS voor de zojuist opgenomen elementen. 
4. **Maak een voorbeeld** in HTML en CSS en toon de code van het voorbeeld. Het handigste is om dit tussen `<pre>` en `<code>` tags te doen zoals in het onderstaande voorbeeld:
```
<pre>
<code>
  <h1>Heading Level 1</h1>
</code>
</pre>
```
5. **Schrijf uitleg** over hoe de elementen wel en niet gebruikt mogen worden.
6. **Ga terug naar 1**. Je gaat door tot alle nodige elementen in de *living styleguide* zijn opgenomen.

#### Meer lezen?

- [Steven Lambert, Creating A Living Style Guide, 2016](https://www.smashingmagazine.com/2016/05/creating-a-living-style-guide-case-study/)

## Definition of done

Deze opdracht is done als:

- [ ] een Interface Inventory is opgenomen in de wiki
- [ ] een living styleguide is gemaakt met HTML en CSS
- [ ] de living styleguide te bekijken is via Github pages

