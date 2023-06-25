# Meesterproef - Duurzaam, groen en sociaal Strandeiland

- Team Repo: https://github.com/RainbowJM/strandeiland

---
## Inhoudsopgave
- [Meesterproef - Duurzaam, groen en sociaal Strandeiland](#meesterproef---duurzaam-groen-en-sociaal-strandeiland)
  - [Inhoudsopgave](#inhoudsopgave)
  - [Week 1: Debriefing en de eerste iteratie](#week-1-debriefing-en-de-eerste-iteratie)
  - [Opdrachtomschrijving](#opdrachtomschrijving)
  - [User stories](#user-stories)
  - [Voor de briefing](#voor-de-briefing)
    - [Mindmap](#mindmap)
  - [De briefing](#de-briefing)
- [Ideegeneratie](#ideegeneratie)
  - [Requirements lijst en brainstorm sessie](#requirements-lijst-en-brainstorm-sessie)
  - [Visuele analyse](#visuele-analyse)
  - [Schetsen overzichtpagina's](#schetsen-overzichtpaginas)
  - [Iteratie 1 - Overzichtpagina eerste versie op Figma](#iteratie-1---overzichtpagina-eerste-versie-op-figma)
    - [Versie 1:](#versie-1)
    - [Versie 2:](#versie-2)
  - [Iteratie 2: Overzichtpagina op code](#iteratie-2-overzichtpagina-op-code)
    - [Versie 1:](#versie-1-1)
    - [Versie 2:](#versie-2-1)
- [Feedback week 1](#feedback-week-1)
  - [31 mei 2023: Feedback design review](#31-mei-2023-feedback-design-review)
  - [1 juni 2023: Feedback debriefing](#1-juni-2023-feedback-debriefing)
  - [2 juni 2023:  Testen met opdrachtgever iteratie 1 -](#2-juni-2023--testen-met-opdrachtgever-iteratie-1--)
  - [Reflectie](#reflectie)
  - [Wat gaan we volgende week doen?](#wat-gaan-we-volgende-week-doen)
  - [Week 2: Filter functionaliteit, Code review en feedback](#week-2-filter-functionaliteit-code-review-en-feedback)
    - [Wat ik heb gedaan deze week](#wat-ik-heb-gedaan-deze-week)
  - [Filter schetsen variaties](#filter-schetsen-variaties)
  - [Themas](#themas)
  - [Filter design op Figma](#filter-design-op-figma)
  - [Filter component op code](#filter-component-op-code)
  - [Code Opsplitsen in modules](#code-opsplitsen-in-modules)
  - [Code review - 7 Juni 2023](#code-review---7-juni-2023)
  - [Opdrachtegver feedback - 9 juni 2023](#opdrachtegver-feedback---9-juni-2023)
  - [Coding Agreements](#coding-agreements)
- [Week 3: Nieuwe detailpagina design, chat, filter en feedback](#week-3-nieuwe-detailpagina-design-chat-filter-en-feedback)
  - [Wat heb ik gedaan:](#wat-heb-ik-gedaan)
    - [Uitegbereide filter functionaliteit](#uitegbereide-filter-functionaliteit)
  - [Nieuwe wens detailpagina design](#nieuwe-wens-detailpagina-design)
  - [Nieuwe chat design](#nieuwe-chat-design)
    - [Data fetchen op de overzichtpagina](#data-fetchen-op-de-overzichtpagina)
    - [Code snippets](#code-snippets)
    - [Toegankelijkheid testjes](#toegankelijkheid-testjes)
    - [Kleur contrast voor de kleurpallette](#kleur-contrast-voor-de-kleurpallette)
    - [Blauw en wit](#blauw-en-wit)
    - [Pastel Blauw en zwart](#pastel-blauw-en-zwart)
    - [Geel en Zwart](#geel-en-zwart)
    - [Pastel geel en zwart](#pastel-geel-en-zwart)
      - [Responsive](#responsive)
    - [Code review - 14 Juni 2023 met Joost](#code-review---14-juni-2023-met-joost)
    - [Opdrachtgever feedback - 15 Juni 2023](#opdrachtgever-feedback---15-juni-2023)
    - [Design review - 15 Juni 2023 met Sanne](#design-review---15-juni-2023-met-sanne)
  - [Nieuwe kleurpallette](#nieuwe-kleurpallette)
  - [Iteratie 3 - Nieuwe overzichtpagina Design op Figma](#iteratie-3---nieuwe-overzichtpagina-design-op-figma)
    - [Nieuwe thumbnails design](#nieuwe-thumbnails-design)
    - [Wat ga ik voor volgende week doen?](#wat-ga-ik-voor-volgende-week-doen)
  - [Reflectie van week 3](#reflectie-van-week-3)
- [Week 4:](#week-4)
    - [Wat heb ik deze week gedaan?](#wat-heb-ik-deze-week-gedaan)
  - [Iteratie 4 - Nieuwe herontwerp voor de overzichtpagina](#iteratie-4---nieuwe-herontwerp-voor-de-overzichtpagina)
  - [Slogan](#slogan)
    - [Versie 1 - van de slogan](#versie-1---van-de-slogan)
    - [Versie 2 - van de slogan](#versie-2---van-de-slogan)
  - [Thumbnails in code herontwerp](#thumbnails-in-code-herontwerp)
    - [Ronde hoeken](#ronde-hoeken)
    - [Thumbnail hover state](#thumbnail-hover-state)
    - [Iconen van trekkers, delers en helpers in plaats van tekst](#iconen-van-trekkers-delers-en-helpers-in-plaats-van-tekst)
  - [Data ophalen vanuit de database en eromheen stijlen](#data-ophalen-vanuit-de-database-en-eromheen-stijlen)
  - [Thema per wens](#thema-per-wens)
  - [Aantal resultaten zien](#aantal-resultaten-zien)
  - [Laast gemaakte wensen met de data daarbij](#laast-gemaakte-wensen-met-de-data-daarbij)
  - [Responsive design](#responsive-design)
    - [Op mobiel](#op-mobiel)
    - [Op tablet](#op-tablet)
    - [Op desktop](#op-desktop)
  - [Microinteracties](#microinteracties)
    - [Hover state animaties](#hover-state-animaties)
    - [Wens aan maken button](#wens-aan-maken-button)
    - [Wens aan maken button](#wens-aan-maken-button-1)
  - [Filter met selectmenu](#filter-met-selectmenu)
    - [Hoe heb ik de selectmenu gebruikt?](#hoe-heb-ik-de-selectmenu-gebruikt)
  - [Loading met CSS](#loading-met-css)
    - [Kleine styling fixen bij de user pagina](#kleine-styling-fixen-bij-de-user-pagina)
    - [Code review - 21 Juni 2023 met Joost](#code-review---21-juni-2023-met-joost)
    - [Design review - 22 Juni 2023 met Vasilis](#design-review---22-juni-2023-met-vasilis)
    - [Opdrachtgever feedback - 23 Juni 2023](#opdrachtgever-feedback---23-juni-2023)
    - [Kleine css fix](#kleine-css-fix)
- [Week 5: De laaste loodjes](#week-5-de-laaste-loodjes)
  - [Performance test](#performance-test)
  - [Lazy loading bij afbeeldingen](#lazy-loading-bij-afbeeldingen)
    - [Visualistatie van de thema's](#visualistatie-van-de-themas)
    - [Gesorteerde thema's](#gesorteerde-themas)
- [Reflectie](#reflectie-1)
  - [Wat heb ik geleerd?](#wat-heb-ik-geleerd)
  - [Wat ging er goed?](#wat-ging-er-goed)
  - [Wat ging er minder goed?](#wat-ging-er-minder-goed)
  - [Wat ben ik trots op?](#wat-ben-ik-trots-op)
- [Toepassing van de meesterproef Vakken](#toepassing-van-de-meesterproef-vakken)
  - [Web app from scratch](#web-app-from-scratch)
  - [Wishlist](#wishlist)
- [Bronnen](#bronnen)
---

## Week 1: Debriefing en de eerste iteratie
Deze week begonnen we met een kick-off presentatie van het eindproject voor deze Minor. We kregen gedetailleerde informatie over het geplande schema voor de komende vijf weken. Verder hebben we een eerste iteratie aangewerkt van ons prototype. Voor deze week wilde we een eerste versie van de overzichtpagina, detailpagina maak een wens formulier. Ik ben aan de slag geweest met het uitwerken van de overzichtpagina. 

## Opdrachtomschrijving
Het bedrijf CrossmarX wil een nieuwe functionaliteit toevoegen voor de hallostrandeiland.nl website waar IJburg bewoners nieuwe voorstellen kunnen insturen voor de nieuwe wijk van Strandeiland. Hiermee wordt de communicatie tussen toekomstige bewoners van Strandeiland en de projectleiders van de gemeente Amsterdam bevorderd. Het doel is om via Hallo Strandeiland goede ideeën en voorstellen te verzamelen, te verbeteren en de mooie en haalbare ideeën/voorstellen gerealiseerd te krijgen. 

## User stories
> Als toekomstig bewoner, wil ik mijn voorstel voor een duurzamer, groener en socialer strandeiland kunnen delen, zodat dit onderzocht en hopelijk gerealiseerd kan worden.

> Als toekomstig bewoner, wil ik een reactie kunnen geven op voorstellen van andere toekomstige bewoners, zodat we kunnen samenwerken aan het vormgeven van de voorstellen.

> Als projectmanager van de gemeente, wil ik voorstellen van toekomstige bewoners kunnen filteren op thema's, zodat ik per thema kan bekijken of er ideeën bijzitten die kunnen bijdragen aan een lagere ecologische footprint, of betere sociale cohesie van de wijk.

## Voor de briefing
Verder hadden we een eerste ontmoeting met Michel Vogler van CrossmarX. Voordat we de briefing kregen hebben we een mindmap gemaakt met alle informatie die we al hadden over het project. Deze mindmap vind je hieronder.

### Mindmap
![mindmap](images/Meesterproef-3.jpg)

Hieronder vind je de vragen die we hebben gesteld aan Michel Vogler:
1. Wat wil de opdrachtgever met deze opdracht?
1. Eigen repo op github of repo van het bedrijf zelf? (vanuit school moet github)
1. Prototype start from scratch? 
1. Wat is de doelstelling?
1. Wat zijn de randvoorwaarden?
1. Heeft het project relatie met een andere project?
1. Voor desktop alleen? of desktop en mobile?
1. Hosten jullie het zelf?
1. Is er al een design? Is er een huisstijl? Is de huisstijl van de hello strandeiland?
1. Moet het een progressive web app worden? (zodat de app downloadbaar is)
1. Hoe moeten de voorstellen eruit komen te zien? Moet het een soort document worden of tekst met eventueel een afbeelding?
1. Hoe ziet u het onderdeel van de projectmanager voor zich? Bewoners en projectmanager een account of alleen projectmanager een account.
1. Zijn er specifieke thema’s, zoals lagere ecologische footprint en betere sociale cohesie van de wijk of moeten gebruikers deze zelf aan kunnen maken bij het voorstel?
1. Wanneer er meerdere voorstellen zijn geüpload, wilt u deze dan op een pagina zien waar u kunt filteren of onder verschillende tabbladen wilt met de verschillende thema’s?
1. In hoeverre verschilt dit project met hallostrandeiland.nl, aangezien je daar ook berichten hebt waar je een reactie bij kan plaatsen?
1. Hebben jullie het logo en beeldmateriaal, zodat wij dit kunnen gebruiken?

## De briefing
Na de briefing met de opdrachtgever hebben we een debriefing geschreven met ze allen en weer naar de opdrachtgever gestuurd. Hieronder is de link van ons debriefing.

- [https://github.com/RainbowJM/strandeiland/wiki/Debriefing](https://github.com/RainbowJM/strandeiland/wiki/Debriefing)

---
# Ideegeneratie
## Requirements lijst en brainstorm sessie
![Brainstorming](./images/brainstorming.png)

Hieronder zijn een aantal eisen die het product hebben:
- Er is een overzichtpagina waar gebruiker een overzicht van all wensen kan zien.
- Gebruikers kan filtreren op basis van populariteit, oudheid en thema.
- Gebruikers moeten zelf een voorstel kunnen aanmaken met behulp van wens maken formulier.
-  Het voorstel formulier opstellen op loclstorage
-  Een real time chat waar gebruikers met elkaar kunnen praten.


## Visuele analyse
Verder heb ik gewerkt aan de visuele analyse van de brand boek die we hadden gekregen van de opdrachtever. De reden waarom ik een visuel analyse heb gemaakt is omdat wij als groep een beeld kan krijgen welke beeldelementen moet we gebruiken op het protptype. Op de visuele analyse staan de volgende onderdelen:

- Typografie
- Kleurpalette en kleurcodes
- site componenten
- navigatiemenu
- call to action button

## Schetsen overzichtpagina's
Voor deze week zijn we begonnen met de idee generatie van het concept. Ik heb als taak gekregen om aan de slag te gaan met de overzichtpagina. Ik heb op mijn tekentablet, een paar schetsen gemaakt van de overzichtpagina. Hieronder staat een aantal schetsen die ik heb gemaakt van de overzichtpagina.

![Schets van de overzichtpagina](images/overviewpage_sketc_page_1.jpg)


## Iteratie 1 - Overzichtpagina eerste versie op Figma
Daarna ben ik meteen begonnen  met de eerste uitwerking van de overzichtpagina op prototype

### Versie 1:
Dit is mijn eerste versie die ik op figma heb gemaakt. Ik heb eerste de navigatiemnu nagemaakt van de strandeiland website. Want de opdrachtgever zei dat we alleen een nieuwe pagina moet toevoegen. En niet from scratch beginnen. Verder hebben we een slogan bedacht voor de wensen pagina, om het wat aantrekkelijker te maken. De layout hier is een grid van twee kolommen. En helemaal aan de rechterkan staat een onderdeel met de recente gemaakte wensen. Dus het wordt ook real time bijgehouden. 

![Figma versie 1](images/overzichtpagina-figma-1.png)

### Versie 2:
In de tweede figma versie, heb ik andere layou stijl gemaakt. Bovenaan heb je een slideshow met populaire wensen. Maar de opdrachtgever gaf als feedback dat als je de populairste wensen bovenop zet worden ze populairder altijd on top en andere wensen worden in de achtergrond gebleven. Hij wil dat alle wensen gelijke kansen krijgen. 

![Figma versie 2](images/overzichtpagina-figma-2.png)

## Iteratie 2: Overzichtpagina op code
Na het ontwerpen op Figma, ben aan de slag gegaan met de code. Ik heb mijn eerste versie op een aparte branch gemaakt. Hieronder kun je de verschillende iteraties zien die ik heb gemaakt op de overzichtpagina. 

### Versie 1:
![overzicht pagina versie 1](images/overzicht-pagina-1.png)
![overzicht pagina versie 1](images/overzicht-pagina-2.png)

### Versie 2:
![overzichtpagina versie 2 op code](/images/slogan-onderdeel.png)
![overzichtpagina versie 2 op code](images/overzicht-pagina-iteratie-2.png)



---
# Feedback week 1

## 31 mei 2023: Feedback design review
- Meer interactie geven
- Meer afwijken van de huisstijl
- Overleg of de chat echt nuttig is
- Elk thema een kleur geven
- De detailpagina met bepaalde thema een kleur geven
- Animatie bij de slogan

## 1 juni 2023: Feedback debriefing 
We hebben ons eerste versie van de debrief gestuurd aan ons coach en de opdrachtgever. We hebben feedback gekegen die we hebben samen aangepast. Hier is de nieuwe versie van de debriefing:

Hier is een lijst met de feedback:
- Hebben we toegang tot het platform CrossMarX? Is dat nodig? 
- Is er content/data beschikbaar?
- Hoe gaan IJburg bewoners op het platform? Voornamelijk Mobiel? Responsive?
- Hoe krijgt de gemeente en projectleiders de ideeen en voorstellen te zien/horen?
- Hebben we een huisstijldocument? Of moeten we dat samenstellen aan de hand van de bestaande website
- Is de huisstijlgids grafisch of zijn er al web elementen en componenten gedefinieerd (living styleguide)?
- Kunnen we inlog testen? Hebben we test user accounts? Is dat nodig?
- Hebben we toegang tot de gebruikers? Testdagen plannen? (liefst door de opdrachtgever)
- Projectleiders ontbreken in de lijst gebruikers?
- Welke data kunnen/willen de bewoners posten? titel, text, categorie, platje, filmpje? 
- Wat betekent API (vanuit school)? Wie gaat dat doen?
- Ik zie niet goed wat de relatie is tussen het project wat jullie gaan ontwerpen en maken en de CrossmarX software


## 2 juni 2023:  Testen met opdrachtgever iteratie 1 -
- We kunnen de thema bepalen met sustainability development goals of Donut economics
- Andere woorden voor trekkers en delers kunnen zijn; ambassadeur, steunen
- Overzicht van de mensen die de voorstel delen
- Kan wel met de huisstijl afwjken, moet wel strandeland gevoel uiten
- Kan je zien wie online is in de chat
- beetje ingewikkeld over chat, het kan misschien te veel worden, hij wilt echt de belangrijke berichten terug zien.
- meerdere thema's kunnen selecteren in het formulier
- hij wilt de chat zien en ook berichten zien (belangrijke berichten)
- aparte pagina maken waar je de chat apart op een pagina zet
- thema's moeten geod bekeken worden, strandeiland bestaat nog niet, dus speeltuin etc gaat niet handig zijn
- alle dingen die fout gaan op dit moment, die kun je vooraf voorkomen, zulke wensen wilt hij zien


## Reflectie
Deze week is voorbij, we hebben een debrief geschreven en al aan de opdrachtgever gestuurd. Verder heb wel op senlle manier iets samengesteld zodat wij aan de opdrachtgever kon presenteren. Ik moet wel zeggen dat ik mischien meer tijd moet besteden aan het schetsen van bepaalde functionaliteiten, om wat variaties toe te brengen. Verder denk ik wel dat we een beetje uniform moet werken qua code, want iedereen heeft een andere stijl. Dus volgende week ga ik een voorstel geven om linters te gebruiken. 

Verder denk ik wel dat wij als groep goed samenwerken, en er is duidelijke communicatie en taakverdeleling. oor volgende week moeten we bespreken welke nieuwe dingen willen we leren. Want tot nu toe doen we allemaal wat we al goed in bent. 


---

## Wat gaan we volgende week doen?
- filter menu afmaken
- wens maken button aanmaken
- schetsen maken van de filter
- schetsen maken van ui stack
- reflectie schrijven

---
## Week 2: Filter functionaliteit, Code review en feedback 
In deze week hadden we een ons eerste standup met de coach. Hier besproken we wat we allemaal de vorige week hebben gedaan. We hebben aan hem verteld wat voor week 2 gaat doen en hoe we moeten het aanpakkken. Verder hadden we deze week onze eerste individueel code review en uiteindelijk onze tweede iteratie presenteren aan de opdrachtgever.

### Wat ik heb gedaan deze week
- Design gemaakt voor de filter functieop Figma
- Fouten fixen op wens aanmaken formulier
- Filter bouwen met HTML, CSS en JavaScript
- Code refactoren en schoonmaken
  
## Filter schetsen variaties 
Ten eerste heb ik opgezocht naar verschillende manieren waar het filter componenet gemaakt kan worden. Daarna heb ik de beste  ideeën op papier geschets. Ik probeerde veel variaties in te brengen om meer ideeen te generen. Voor de prototype willen een filter functionaliteit kan toevoegen zodat de gebruikers de wensen kan filteren op basis van de thema's en ook sorteren op meest recent, meest gedeeld, meeste trekkers en meeste helpers. WDe gekozen filter criterias worder onderaan terug te zien.

![schetsen variaties van filteren](images/filters-schetsen.jpg)

## Themas
Voordat ik het filter functionaliteit kon implementeren in het prototype hebben we de thema's samen vastgesteld. Hironder kunnen jullie de thema's terugzien.

![Themas](images/themas.png)

## Filter design op Figma
![filter designs op Figma](images/flter-figma.png)
Wanneer ik een concrete idee, ben ik naar figma gegaan om een design te maken aan de filter functionaliteit. Ik maakte een design op Figma want dan is de overstap  van idee naar code makkelijker. 

Op Figma heb ik een component gemaakt voor het filteren op thema's. Ik heb de component gemaakt voor mobiel en op grotere schermen. Voor kleiner schermen heeft filteren twee kolommen. Voor grote schermen heeft de filter drie kolommen. 

Daarma hen ik twee variaties gemaakt. De eerste variatie hebben de filter items ook een checkbox die je kan aanvinken. De andere variatie heeft geen checkbox, hier moet je gewoon klikken. 
Als je op een van de checkboxes klikt verandert de achtergrond van de filter items. Ik heb twee variaties, eentje is met een zwarte achtergrond en de andere is met een blauwe achtergrond. 

## Filter component op code
![filteren op basis thema](/images/filter-iteratie-1.png)
![filteren op basis thema](/images/sort-filter.png)

<details>
<summary><h2>Filter code</h2></summary>

```html
    <form>
      <fieldset>
        <button class="close-filter">Close filter</button>
        <ul>
          <li class="theme-btn" data-filter-target="#theme">
            <span> <b>Filtreren op:</b></span>
            <span>Thema <i class="fa-solid fa-angle-down"></i></span>
          </li>
          <li class="sort-btn" data-filter-target="#sorting">
            <span>Sorteren op:</span>
            <span>Meest recente <i class="fa-solid fa-angle-down"></i></span>
          </li>
          <li>
            <span>Zoek op trefwoord</span>
          <label for="search">
            <i class="fa-solid fa-magnifying-glass" style="color: #000000;"></i>
            <input type="text" name="search" id="search" placeholder="Zoek op treftwoord">
          </label>
          
          </li>
        </ul>

        <section class="filter-content">
          <article id="theme" data-filter-content>
            <ul class="theme-filter-items"> 
              <li><label><input type="checkbox" name="theme" value="sport"><span>Sport</span></label></li>
              <li><label><input type="checkbox" name="theme" value="recreatie"><span>Recreatie</span></label></li>
              <li><label><input type="checkbox" name="theme" value="verkeer"><span>Verkeer</span></label></li>
              <li><label><input type="checkbox" name="theme" value="Winkels"><span>Winkels</span></label></li>
              <li><label><input type="checkbox" name="theme" value="natuur"><span>Natuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="milieu"><span>Milieu</span></label></li>
              <li><label><input type="checkbox" name="theme" value="jeugd"><span>Jeugd</span></label></li>
              <li><label><input type="checkbox" name="theme" value="veiligheid"><span>Veiligheid</span></label></li>
              <li><label><input type="checkbox" name="theme" value="cultuur"><span>Cultuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="huisvesting"><span>Huisvesting</span></label></li>
              <li><label><input type="checkbox" name="theme" value="infrastructuur"><span>Infrastructuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="strand"><span>Strand</span></label></li>
              <li><label><input type="checkbox" name="theme" value="onderwijs"><span>Onderwijs</span></label></li>
              <li><label><input type="checkbox" name="theme" value="overig"><span>Overig</span></label></li>
            </ul>
            <button class="filter-theme-results-btn" type="submit">Toon resultaten</button>
          </article>

          <article id="sorting" data-filter-content>
            <ul class="sorting-filter-items">
              <li><label><input type="radio" name="sort" value="recent"><span>Meest Recente</span></label></li>
              <li><label><input type="radio" name="sort" value="delers"><span>Meest gedeeld</span></label></li>
              <li><label><input type="radio" name="sort" value="trekkers"><span>Meeste trekkers</span></label></li>
              <li><label><input type="radio" name="sort" value="helpers"><span>Meeste helpers</span></label></li>
            </ul>

            <button class="filter-sort-results-btn" type="submit">Toon resultaten</button>
          </article>
        </section>
        <p class="selected-filter-items">Hello</p>
      </fieldset>
      <a href="/form">Maak een wens!</a>
    </form>

```

</details>

## Code Opsplitsen in modules
Een van de feedbak van de code review die ik heb verwerkt is het refatoren van de code in Module. Ik was aan de gang gegaan met het refactoren. Wat ik heb gedaan heb ik bij de script tag de `type="module` gegeven. Met deze aanpassing activeer ik de mogelijkheid om mijn javascript code in modules te schrijven. Ten eerste heb ik een modules bestandmap gemaakt. In de module map heb ik per functie/componenten in een aparte javascript bestand geplaatst. Daarna exporteer ik z naar de hoofd javascript bestand met `export {...}` en in de `script.js` imorteer ze met `import`.

![code opsplitsen in modules](images/code-refactoring.png)

## Code review - 7 Juni 2023
Op  7 juni hebben we een individuele code review met docenten. Ik had code review gedaan bij robert. Ik heb geen nuttige feedback gekregen over mij code. Maar een ander Teamlid heeft heel veel nuttige feedback gekregen. Hier is een lijst van de feedback:
- Branch per functionaliteiten maken
- Issues aanmaken en linken in de projectboard
- Github gebruiken om een to do lijst bij te houden 
- Javascript en ejs templating opspliten en in modules herschrijving.




## Opdrachtegver feedback - 9 juni 2023
- Duidelijker maken dat de filter kun je uitklappen.
- Treftwoord opzoeken. 
- Nieuwe design voor detailpagina
- Niuewe design voor de chat- meer functonaliteiten en de naam veranderen
- Verschillende manieren om afbeeling in wens aan formulier te uploaden
- Voorstel veranderen in wens
- Trekkers menu anders doen en niet aan de zijkant
- De wens aanmaken buton moet een activerend call to action hebben
 

## Coding Agreements
Na een onze code review hebben we ons code overeenkomsten vastgesteld. Om de consistentie van de code te behouden.
Onze overeenkomsten zijn:
- Schrijf zo min mogelijk code.
- Gebruik de juiste namen voor alles.
- Zet je code in blokken/alinea's.
- Gebruik inspringing om het begin en einde van besturingsstructuren te markeren.
- Gebruik het DRY (Don't Repeat Yourself) principe. Automatiseer repetitieve taken wanneer nodig. Hetzelfde stuk code mag niet worden herhaald in het script.
- Gebruik een hoofdletter voor speciale SQL-woorden en functienamen om ze te onderscheiden van tabel- en kolomnamen.
- Vermijd lange rijen. Het is voor mensen gemakkelijker om regelblokken te lezen die horizontaal kort en verticaal lang zijn.
- Alles comments en id's classes (benoemingen) in het Engels.
- Gebruik van camelCase.
- Structuur javaScript is eerst variabelen, daarna logica, daarna functies.
- Alleen gebruik van const en lets
- Javascript, css en html in modules opdelen.

---
# Week 3: Nieuwe detailpagina design, chat, filter en feedback
Ik ben halverwege de meesterproef er zijn nog twee weken te gaan voor de expo. DEze week heb ik veel feedback gekregen van de opdrachtgever en tijdens de code en design review met Sanne en Joost. Verder heb ik verder gewerkt aan de filter functionaliteit, de nieuwe detailpagina en chat figma prototype. 

## Wat heb ik gedaan:
- De filter dropdown menu duidelijker maken dat het een dropdown menu is
- Duidelijker maken wat of het filteren of sorteren is
- De aanmaak wens button een activerende call to action geven
- Een nieuwe chatdesign gemaakt op Figma
- Geholpen met het ontwerpen van de detailpagina  
- Data vanuit supabase opgehaald en op de overzichtpagina weergeven
- Nieuwe design voor de detailpagina

### Uitegbereide filter functionaliteit
![filter iteratie 2](/images/filter-iteratie-2.png)

Ik heb verder gewerkt aan de filter functionaliteit. Tijdens het gesprek van de opdrachtgever, heeft hij aangegeven dat interactie van de dropdownmenu duidelijker moet zijn.  Om de interactie wat duidelijker te maken heb ik een pijl icoon gebruikt van fontawesome. Ik heb fontawesome gebruikt omdat je kan makkelijk implementeren in code met een `<i>` element. 

Verder heb ik meer context gegeven wat voor soort filter het is. Ik heb een label toegevoegd met de tekst "Filter op" en "Sorteren op".

<details>
<summary><h2>Filter code</h2></summary>

```html
    <form>
      <fieldset>
        <button class="close-filter">Close filter</button>
        <ul>
          <li class="theme-btn" data-filter-target="#theme">
            <span> <b>Filtreren op:</b></span>
            <span>Thema <i class="fa-solid fa-angle-down"></i></span>
          </li>
          <li class="sort-btn" data-filter-target="#sorting">
            <span>Sorteren op:</span>
            <span>Meest recente <i class="fa-solid fa-angle-down"></i></span>
          </li>
          <li>
            <span>Zoek op trefwoord</span>
          <label for="search">
            <i class="fa-solid fa-magnifying-glass" style="color: #000000;"></i>
            <input type="text" name="search" id="search" placeholder="Zoek op treftwoord">
          </label>
          
          </li>
        </ul>

        <section class="filter-content">
          <article id="theme" data-filter-content>
            <ul class="theme-filter-items"> 
              <li><label><input type="checkbox" name="theme" value="sport"><span>Sport</span></label></li>
              <li><label><input type="checkbox" name="theme" value="recreatie"><span>Recreatie</span></label></li>
              <li><label><input type="checkbox" name="theme" value="verkeer"><span>Verkeer</span></label></li>
              <li><label><input type="checkbox" name="theme" value="Winkels"><span>Winkels</span></label></li>
              <li><label><input type="checkbox" name="theme" value="natuur"><span>Natuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="milieu"><span>Milieu</span></label></li>
              <li><label><input type="checkbox" name="theme" value="jeugd"><span>Jeugd</span></label></li>
              <li><label><input type="checkbox" name="theme" value="veiligheid"><span>Veiligheid</span></label></li>
              <li><label><input type="checkbox" name="theme" value="cultuur"><span>Cultuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="huisvesting"><span>Huisvesting</span></label></li>
              <li><label><input type="checkbox" name="theme" value="infrastructuur"><span>Infrastructuur</span></label></li>
              <li><label><input type="checkbox" name="theme" value="strand"><span>Strand</span></label></li>
              <li><label><input type="checkbox" name="theme" value="onderwijs"><span>Onderwijs</span></label></li>
              <li><label><input type="checkbox" name="theme" value="overig"><span>Overig</span></label></li>
            </ul>
            <button class="filter-theme-results-btn" type="submit">Toon resultaten</button>
          </article>

          <article id="sorting" data-filter-content>
            <ul class="sorting-filter-items">
              <li><label><input type="radio" name="sort" value="recent"><span>Meest Recente</span></label></li>
              <li><label><input type="radio" name="sort" value="delers"><span>Meest gedeeld</span></label></li>
              <li><label><input type="radio" name="sort" value="trekkers"><span>Meeste trekkers</span></label></li>
              <li><label><input type="radio" name="sort" value="helpers"><span>Meeste helpers</span></label></li>
            </ul>

            <button class="filter-sort-results-btn" type="submit">Toon resultaten</button>
          </article>
        </section>
        <p class="selected-filter-items">Hello</p>
      </fieldset>
      <a href="/form">Maak een wens!</a>
    </form>

```
</details>



## Nieuwe wens detailpagina design
Verder gingen we als groep aan de slag met herontwerpen van de detailpagina van een wens. We hebben een aantal iteraties gemaakt op Figma en uiteindelijk hebben we een design gekozen. Hilal ging het pagina uitwerken in code We hebben de hoogtepunten van een reacties verwijdert en in plaats daarvan de trekkers, helpers en delers wat meer ruimtes gegeven. Omdat de delers misschien te groot kan zijn hebben we besloten om de om alleen de profielfoto te laten zien, dan wordt het makkelijker om meer delers naast elkaar te laten zien. Als je de naam van de deler wilt zien kan je op de profielfoto klikken. Dan komt een kleine popup met de naam van de deler.

We hebben hier ook een beetje gespeeld met de kleur. Aan de rechterkant hebben we  een achtergrondkleur toegevoegd om een beetje wat kleurrijk te maken tussean al de witte vlakken.

Als laaste kreeg de Chat een herontwerp, want de opdrachtgever zag geen toegevoegde waarde in een chat dus we hebben de interface verandert die meer lijkt reactie functionaliteit. In het volgende onderdeel ga ik meer vertellen over de chat. 

![detailpagina design](images/detailpagina-design-1.png)



## Nieuwe chat design
Zoals ik al zei, we wilden een chat implementeren in de detailpagina zodat mensen op wensen reageren. Maar de opdrachtgever zag geen toegevoegde waarde in een chat. Hij chat als whatsapp dus iets informeel. Daardoor hebben we de naam verandert naar reacties. Ook hebben we besloten om meer functionaliteit te implementeren:
- Bekijken hoeveel reacties er zijn:
- Reageren op een reactie
- Reactie kunnen lijken
- Bekijken wie online is
- Kijken wie aan het typen is.
- Datum wanneer het geplaatst is


![chat design](images/chat-nieuwe-design-variaties.png)
![chat design](images/nieuwe-chat-design.png)

Met de nieuwe functionalieiten klinkt het meer formeel dan alleen een simpel chat.

### Data fetchen op de overzichtpagina
Het volegnde stap was de dynamische content in de website te implementeren. In de laaste drie weken hebben we een alleen gewerkt met hardcoded en startische data om zich te focussen op de over de opmaak van de pagina.  

Om de data te halen gebruiken we supabase. Jevona heeft dan een API gemaakt met behulp van supabase. We hebben een paar endpoints gemaakt om de data te fetchen. 

Hier is een datamodel die Jevona heeft gemaakt, hoe de structuur van de data eruit ziet.

![datamodel](images/datamodel-database.png)

Voor de wens overzichtpagina had ik de suggestion endpoint nodig om informatie van de wensen te weergeven. In de endpoint staat informatie zoals:
- titel van de wens 
- beschrijving van de wens
- Aantal reageerders en trekkers
- Datum wanneer het gemaakt is  
- afbeelding van de wens

![data fetchen](/images/thumbnail-met-data.png)

In deze foto kun je zien, hoe de data wordt weergeven op de overzichtpagina. Ik moet het nog een beetje stylen, maar het is een begin. 

### Code snippets
Om de data te fetchen was het niet te moeilijk te doen. De data word server-side opgehaald. Wat ik heb gedaan is een tabel vanuit de supabase database halen en de data loopen in de template engine. 

Dus de wens kaarten heb ik eenmalig gemaakt in een partial bestand. De data wordt gestuurd naar de partial bestand en daarin worden de data weergeven. 

```js
// app.js

const { createClient } = require('@supabase/supabase-js');
const supabase = createClient(
    'https://yyufywjwwwmgfjmenluv.supabase.co',
    `${process.env.SUPABASE_KEY}`);


    
app.get("/",  async (req, res) => {
  const { data: themeData, themeError } = await supabase
    .from('theme')
    .select()

  const { data: suggestionsData, error: suggestionsError } = await supabase
    .from('suggestion')
    .select()
  console.log(suggestionsData)

  res.render("index", {
    title: "Wensen",
    themes: themeData,
    suggestions: suggestionsData
  });
});
```
Wat ik deed was de tabel selecteren met de supabase client met `.from`. Daarna  heb ik de data gestuurd naar de template engine als een object. 


```html
<!-- index.ejs -->

<div class="grid-container">
  <% suggestions.forEach(suggestion => { %>
    <%-include('./partials/thumbnail.ejs',{suggestionData: suggestion})%>
  <% }) %>

</div>
```

```html
<!-- /partials/thumbnail.ejs -->
<section class="thumbnail-container">
    <figure>
        <h2>hey</h2>
        <div class="image-container">

            <img src="<%= suggestionData.image%> " alt="Vanuit het natuur">
        </div>
        <figcaption>
            <%= suggestionData.thema%>
        </figcaption>
    </figure>



    <a href="/detailpage-1">

        <article>

            <ul class="user-info">
                <li>Pieter van der baas</li>
                <li>
                    <%= suggestionData.created_at %>
                </li>
            </ul>

            <h2>
                <%= suggestionData.title %>
            </h2>
            <p>
                <%= suggestionData.description %>
            </p>

            <ul class="statistics">
                <li><span>Reaction:</span>
                    <%= suggestionData.reaction %>
                </li>
                <li> <span> Delers:</span>
                    <%= suggestionData.amount_vote%>
                </li>
            </ul>
        </article>
    </a>

</section>

```

### Toegankelijkheid testjes
Ik heb af en toe een paar toegankelijkheid testen gedaan om het prototype toegankelijker te maken. Omdat het doelgroep voor dit website heel groot is moeten we ervoor zorgen dat de website toegankelijk zijn voor iedereen. 

Ik heb daardoor een aantal testen gedaan om te kijken of de kleurcontrasten tussen de tekt en de achtergrond goed zijn. Ook heb ik gekeken  hoe de website te bedienen is op mobiel.

###  Kleur contrast voor de kleurpallette

### Blauw en wit
Ik heb hier de blauwe kleur van de kleurpallette met de wit getest. De contrast ratio is 3.1:1. Dit is niet genoeg voor kleine teksten maar wel voor grote teksten zoals titels en subtitels.
![kleurcontrast](images/kluercontrast-blauw-wit.png)


### Pastel Blauw en zwart
Hier heb ik de pastel blauwe kleur van de kleurpallette met de zwarte kleur getest. De contrast ratio is 14.3:1. Dit is genoeg voor kleine teksten en grote teksten.

![kleurcontrast](images/kluercontrast-licht-blauw-zwart.png)

### Geel en Zwart
Hier heb ik de felle gele kleur van de kleurpallette met de zwarte kleur getest. De contrast ratio is 16.7:1. Dit is genoeg voor kleine teksten en grote teksten.
![kleurcontrast](images/kleurcontrast-geel-zwart.png)

### Pastel geel en zwart
Hier heb ik de pastel gele kleur van de kleurpallette met de zwarte kleur getest. De contrast ratio is 16.3:1. Dit is genoeg voor kleine teksten en grote teksten.

![Kleurcontrast](images/contrast-checker.png)

#### Responsive 

### Code review - 14 Juni 2023 met Joost
- De code is goed gestructureerd en overzichtelijk.
- De app.js beter gaan opschonen en splitsen in meerdere bestanden


### Opdrachtgever feedback - 15 Juni 2023
Een paar feedback punten vanuit de opdrachtgever zijn:
- Het sorteren functie moet  onderscheid worden van de filter functie. 
- Online weergaven op het bericht, is het iedereen die online is op de community pagina of zijn alleen gebruikers die op dit moment op de pagina bevinden. 
- Groene cirkel (wanneer de gebruiker online is) is niet duidelijk genoeg
- Een paar feedback punten die we van de docenten hebben gekregen
Bij het formulier pagina moet er op hierachie gelet worden welke componenten horen bij elkaar
-  Ook bij het formulier pagina kan de sectie van afbeelding naar een pop up verandert worden.
- De hierarchie van de overzichtspagina letten
- Een pakkende afbeelding voor de banner op de overzichtspagina veranderen 


### Design review - 15 Juni 2023 met Sanne 
- Een pakkende banner afbeelding die meer context geeft.
- Meer spelen met het layout van de overzichtpagina's
- Meer kleur tintne toevoegen aan de kleurpalette


## Nieuwe kleurpallette 
Na de design review hebben we veel opmerkingen gekregen dat website heel saai is en lijkt als een standaard nieuwswebsite. We hebben daardoor als tip gekregen om de kleurpalette uit breiden met meer kleurtinten zoals we meer ruimte krijgen om de te spelen met de kleuren.  
![Kleurpallette](images/nieuwe-kleurpalette.png)


## Iteratie 3 - Nieuwe overzichtpagina Design op Figma

![Nieuwe overzichtpagina](images/nieuwe-overzichtpagina-design.png)

![Nieuwe overzichtpagina](images/overzicht-pagina-iteratie-4.png)


### Nieuwe thumbnails design
![Nieuwe thumbnails](images/thumbnail-iteraties-1.png)

![Nieuwe thumbnails](images/thumbnail-iteraties-2.png)



### Wat ga ik voor volgende week doen?
- De nieuwe kleurpallette implementeren in de  wens overzichtpagina 
- De nieuwe layout van de overzichtpagina  in code verwerken.
- De themas toevoegen per wens
- Data filtreren op de overzichtpagina
- Meer microinteracties toevoegen in de wens overzichtpagina

## Reflectie van week 3
Deze week hebben we veel feedback gekregen, dat ik een gevoel krijgt dat we weer naar 0 zijn gegaan. Deze week heb ik mijn tijd besteed aan de filter en de overzichtspagina. Verder heb ik de data vanuit de database opgehaald en op de overzichtspagina geplaatst. We hebben veel feedback gekregen vanuit het design en code review. In de code review krijgen we als feedback om dynamische data toe te voegen, want het was een van ons core functionaliteiten. Bij de designview kreeg ik als feedback om de overzichtspagina wat creatieve onderdelen inzetten, want het zag er saai uit.  Na de designreview heb ik een nieuw design gemaakt voor de overzichtspagina op Figma. En aantal iteraties gemaakt en samen besproken. Voor de code review heb ik weer data  in de applicatie toegevoegd.

--- 
# Week 4:
Deze week is de vierde week van de meesterproef. Deze week heb ik verschillende dingen qua design met css als de backend zoals data vanuit de database ophalen. Verder had ik weer een code review en design review met docenten. Ik heb de overzichtspagina opnieuw ontworpen en meteen in code verwerkt. Ik heb daarbij nog wat kleine animaties toegevoegd zodat het wat soepeler blijft en als laatste heb ik nog met nieuwe css technieken geëxperimenteerd.

### Wat heb ik deze week gedaan?
- De nieuwe kleurpallette implementeren in de  wens overzichtpagina
- Nieuwe layout van de overzichtpagina  in code verwerken.
- De themas toevoegen per wens
- Dynamische data toevoegen
- Microinteracties toevoegen in de wens overzichtpagina
- Design review
- Skeleton screen toevoegen



## Iteratie 4 - Nieuwe herontwerp voor de overzichtpagina
Na de design review heb ik feedback gekregen om de pagina wat aantrekkelijker te maken. Ten eerste wanneer je op de pagina komt, zie je een afbeelding en de slogan. Maar het geef geen context wat de webpagina is. Het moet duidelijk zijn dat de gebruiker op de wensen pagina is gekomen.  In de eerste versie heb ik alleen de slogan `Draag bij aan Strandeiland,  Jouw ideen ons toekomst` toegevoegd met een afbeelding die ik vanuit de huidige hallo Strandeiland heb geleend. Maar het was niet duidelijk genoeg. Daarom heb ik een nieuwe versie gemaakt met een korte uitleg wat de webpagina is.

## Slogan
### Versie 1 - van de slogan 
![Figma versie 1](images/overzichtpagina-figma-1.png)
De bovenste onderdeel bestaat een hero afbeelding  een een slogan. De bedoeling was om de gebruiker context te geven op  wat de webpagina is.Dus mensen moet kunnen weten dat hier kan je wensen die andere mensen hebben voor de ontwikkeling van Strandeiland.  In de eerste versie was het niet helemaal duidelijk wat de doel van de pagina was. Daarom heb ik een tweede versie gemaakt.

### Versie 2 - van de slogan
![slogan](images/slogan-onderdeel-v2.png)
In de tweede versie hebben ik een aantal dingen toegevoegd. Tne eerste heb ik een button gemaakt die de gebruiker stuurt waar een wens gemaakt kan worden. Ik heb een kopje toegeveogd die zegt `Wensen voor Strandeiland` om meer duidelijkheid te geven aan de gebruiker. En als laatste heb ik de juiste afmetingen gebruikt om de slogan hetzelfe margin krijgen zoals de algemene inhoud van de pagina. 

## Thumbnails in code herontwerp

![Nieuwe thumbnails](images/overzicht-pagina-3.png)

### Ronde hoeken
Ten eerste heb ik de thumbnails ronde hoeken gegeven met` border-radius: 2em.` WIj wilde zeg maar de wens thumbnails een beetje laten lijken op een kaartje. Dus ik heb een `<article>` element met daarin de wens titel, de thema en kleine beschrijving van de wens. De article element heb ik ook een ronde hoek gegeven en met `transform translateY` heb ik de  element een beetje naar boven verplaatst zodat het op de afbeelding komt te staan.

Voor de afbeelding heb ik omgeringd met een `<figure>` element met een afmeting zodat alle afbeelding dezelfde afmetingen krijgen.  

```css
.grid-container .thumbnail-container figure {
  height: 15.625em;
}

.grid-container .thumbnail-container figure img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

/* Article element */
.grid-container .thumbnail-container article {
  width: 100%;
  transform: translateY(-18%);
  transition: transform .5s ease-in-out;
}

.grid-container .thumbnail-container article:hover {
  transform: translateY(-38%);
}
```

### Thumbnail hover state
![Nieuwe thumbnails](images/overzicht-pagina-3.png)

Wanneer je met je muis over de thumbnail gaat, zie je dat de article element een beetje naar boven gaat. Dit heb ik gedaan met `transform: translateY(-38%);` en `transition: transform .5s ease-in-out;`.

Om het paragraaf een beetje te laten vervagen heb ik een ::before psuedo selector op de paragraaf gebruikt en een transparante gradient toegevoegd. 

```css
.thumbnail-container article p {
  position: relative;
  height: 8em;
  overflow: hidden;
}

.thumbnail-container article p::before {
  content: "";
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  background: linear-gradient(transparent 10px, white);
}

```
### Iconen van trekkers, delers en helpers in plaats van tekst
In de vorige versie van de oberzichtpagina had ik alleen Stemmers en trekkers als tekst toegevoegd. Op de huidige  website van Hallo Strandeiland heb je verschillende rollen zoals trekkers, delers en helpers. Trekkers zijn mensen die ambassadeur zijn van een wens, helpers zijn mensen die graag willen helpen met het realiseren van een wens en delers zijn mensen die de wens willen delen.

In de oude versie van de overzichtpagina had ik alleen stemmers en trekkers met de waarde  toegevoegd. Want voor de gemeente Amsterdam kunnen ze bekijken aan de hand van de aantal trekkers en helpers hoe realiseerbaar de wens is. 
![Oude thumbnails](images/overzicht-pagina-2.png)


In de nieuwe versie heb ik ook de delers gezet. Want we vonden dat het ook belangrijk is om te weten hoeveel mensen de wens willen delen. Dus ik die ook toegevoegd. Maar een nadeel was dat de tekst veel ruimte neemt en niet genoeg waren om drie woorden naast elkaar te zetten. Dus ik heb de tekst vervangen met iconen. De eesrte icoon is gemaakt door Ine, en ik vroeg aan haar of ik de icoon mocht gebruiken. Ze vond het goed en ik heb de icoon gebruikt dus credits naar Ine. De andere iconen zijn van fontawesome.

Hoe ik heb het gedaan?
Ik heb een script toegevoegd bij de head van de html pagina. Dit script zorgt ervoor dat de iconen worden geladen. 

```html
<script src="https://kit.fontawesome.com/87a1015511.js" crossorigin="anonymous"></script>
```
Daarna ze ik de iconen in de html pagina. Ik heb een `<i>` element gebruikt met daarin de iconen. 
```html
    <ul class="statistics">
                <li>  <img src="../../images/trekkers.svg" alt=""> <span>5</span></li>
                <li><i class="fa-regular fa-handshake fa-lg" style="color: #000000;"></i> <span>2</span></li>
                <li><i class="fa-regular fa-thumbs-up fa-lg" style="color: #000000;"></i><span><%= suggestion.amount_vote%></span></li>
            </ul>
```

![Nieuwe thumbnails](images/overzicht-pagina-3.png)


## Data ophalen vanuit de database en eromheen stijlen
Vorige week heb ik al de data vanuit de database opgehaald maar het was nog niet compleet. Er miste nog de thema die bij de wens hoort. Dus ik heb de thema ook toegevoegd. Dus de data dat dynamsich zij:
Iteratie 2:
- De titel van de wens
- De thema van de wens
- De beschrijving van de wens
- De afbeelding van de wens
- De datum die daarbij hoort.

Zoals ik al eerder heb benoemd, we gebruiken de supabase database waar de wensen worden opgeslagen. De wensen worden gemaakt via de wens formulier en de data wordt dan gestuurd naar de database. 
Ik haal de data op via de server side met expres.js. Daarna wordt de data weergegeven op de overzichtspagina.

Hieronder zie je de code, hoe ik de data uit supabase ophaalt. Ten eerste maak ik twee variabele met daarin de data object en de error object. Verder gebruik ik de `.from()` methode om de tabel ye kiezen waar de data in zit. Daarna gebruik ik de `.select()` methode om de kolommen te kiezen die ik wil hebben. In dit geval wil ik de titel, thema, beschrijving en de afbeelding hebben. Omdat ik alles in de tabel wil hebben blijft die leeg. 

  En als laatste stuur ik de data mee naar de template engine ejs , om data te renderen op de pagina.

```js
  const { data: suggestionsData, error: suggestionsError } = await supabase
    .from("suggestion")
    .select();

      res.render("index", {
      title: "Wensen",
      themes: themeData,
      suggestions: shuffledSuggestionsData,
    });
```


## Thema per wens 
Wanneer je een wens aanmaak kun je meerdere thema meegeven. In de vorige iteratie waren de themas hardcoded op de overzichtpagina's. Maar ik en Jevona hebben besloten om de themas dynamisch te maken. Wat ik doe is, ik haal data vanuit de thema en de wensen tabel. Daarna kijk ik of de thema id overeenkomt met de thema id van de wens. Als dat zo is dan voeg ik de thema toe aan de wens object. En de data wordt daarna weergegven op de overzichtspagina.
```js
 const { data: themeData, themeError } = await supabase.from("theme").select();
  const { data: themeSuggestions, themeSuggestionsError } = await supabase
    .from("suggestion_theme")
    .select();
  const { data: suggestionsData, error: suggestionsError } = await supabase
    .from("suggestion")
    .select();

    for (const suggestion of suggestionsData) {
    const relatedTheme = themeSuggestions.find(
      (ts) => ts.suggestionId === suggestion.id
    );
    if (relatedTheme) {
      const theme = themeData.find((t) => t.id === relatedTheme.themaId);
      if (theme) {
        suggestion.theme = theme;
      }
    }
  }

   res.render("index", {
      title: "Wensen",
      themes: themeData,
      suggestions: suggestionsData,
    });


```

##  Aantal resultaten zien
![Nieuwe thumbnails](images/overzicht-pagina-3.png)

Voor de gebruiker is het handig om te weten hoeveel wensen er zijn op de overzichtspagina. Dus ik heb een de `count` functie gebruikt waarbij elke item binnen de suggestion table array wordt geteld. 

```js
 const { count, error } = await supabase
    .from("suggestion")
    .select("*", { count: "exact", head: true });

```
Daarna stuur ik de `totalSuggestions` object mee naar de template engine ejs om het te renderen op de pagina.

```js
  res.render("index", {
      title: "Wensen",
      themes: themeData,
      suggestions: suggestionsData,
      totalSuggestions: count,
    });

``` 
Het ziet er zo uit op de pagina's:
![Nieuwe thumbnails](images/overzicht-pagina-3.png)


## Laast gemaakte wensen met de data daarbij
![Laatst gemaakte wens](images/laatst-gemaakte-wensen.png)

In een van ons gesprek met de opdrachtgever heeft hij aangegeven dat hij wil niet de populaire wensen zien want dan blijven ze populair.En andere wensen hebben geen kans om naar voren te komen.  Dus wij dachten om in plaats daarvan de laatst gemaakte wensen te laten zien. Dan hebben nieuwe wensen ook een kans om naar voren te komen.
Hoe zie je dat de wensen nieuw zijn? Dat zie je aan de datum. De datum wordt ook opgeslagen in de database. Dus ik haal de datum op vanuit de database en ik sorteer de wensen op datum. De laatst gemaakte wensen komen dan bovenaan te staan. 

```js
  const { data: latestSuggestionsData, latestSuggestionsError } = await supabase
    .from("suggestion")
    .select()
    .order("created_at", { ascending: false })
    .limit(3);
```
Ik heb een kopie gemaakt van de wensen thumbnails html en in een nieuwe bestand geplaatst. 
Zodat ik de rest van de wensen niet verpest. Daarna in de server heb ik een nieuwe variabele gemaakt om data van de `suggestion` op te halen. Ik selecteer alles en ik sorteer de wensen op datum `.created_at` van nieuw naar oud. En ik gebruik de `.limit(3)` methode om de alleen drie laatst gemaakte wensen te laten zien. En als laatste stuur ik de data mee naar de template engine ejs om het te renderen op de pagina.

```js
  res.render("index", {
      title: "Wensen",
      themes: themeData,
      suggestions: suggestionsData,
      totalSuggestions: count,
      latestSuggestions: latestSuggestionsData,
    });

```

```html
<!-- index.ejs -->
 <h2>Bekijk de laatst gemaakte wensen</h2>
      <section class="latest-ideas">
        <% latestSuggestions.forEach(suggestion=> { %>
          <%-include('./partials/latest-thumbnail.ejs',{suggestion: suggestion})%>
            <% }) %>
      </section>

<!-- latest-thumbnails -->
      <li>
                    <%= (new Date(suggestion.created_at)).toLocaleString("nl-NL", {
      day: "numeric",
      month: "short",
      year: "numeric",
      hour: "2-digit",
      minute: "2-digit",
     
    })%>
                </li>
```




## Responsive design 
Ik heb ook rekening gehouden dat de website voor alle apparaten zo goed mogelijk moet kunnen werken. Dus ik heb met css gezorgt dat de webpagina responsive wordt voor de verschillende apparaten. Om de website responsive te maken heb ik gebruikt gemaakt van `media queries`. Dus  bij de wensen overzicht begin je met vier kolommen en daarna wordt het twee kolommen en daarna wordt het een kolom. 



### Op mobiel
![Op mobiel](images/een-kolommen-responsive.png)
### Op tablet
![Op tablet](images/twee-kolommen-responsive.png)
### Op desktop
![Op desktop](images/overzicht-pagina-3.png)

Hieronder zie je de code van de media queries.
```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-auto-rows: minmax(24em, auto);
  gap: 1.25em;
  max-width: 75em;
  margin: 20px auto;
}

@media (max-width: 60em) {
  .grid-container {
    grid-template-columns: 1fr 1fr 1fr;
    grid-column: span 3;
  }
}

@media (max-width: 55em) {
  .grid-container {
    grid-template-columns: 1fr 1fr;
    grid-column: span 3;
  }
}


@media (max-width: 40em) {
  .slogan-container {
    grid-template-columns: 1fr;
  }

  .grid-container {
    grid-template-columns: 1fr;
    grid-column: span 3;
  }
}

```


## Microinteracties
Na de design review met Sanne en Vasilis, kregen we als opmerking dat de website meer animaties nodig heeft. Het bleef een beetje statisch. Dus we hebben besloten om microinteracties toe te voegen aan de website.
- Springende slogan animaties
- De wens aanmak button een beetje laten draaien wanneer je de muis  zweeft. 
- Wannneer je de muis zweeft op de wens thumbnails dan gaat de tekst onderdeel een beetje omhoog.
Hieronder zie je de microinteracties die ik heb toegevoegd aan de website.
- Wanneer je de filter dropdown menu opent zie je een soepele transitie met fade-in en fade-out

### Hover state animaties
### Wens aan maken button
![button microinteratie](images/microinteractie-btn.png)
Hier is een voorbeeld  van de microinteraties die je krijgt wannneer je op de knop klikt om de wens te gaan maken. De knop gaat een beetje draaien en de achtergrond kleur verandert naar blauw. 

```css

.slogan-call-to-action a {
  display: inline-block;
  margin-top: 0.5em;
  padding: 0.5em 1em;
  background-color: var(--black);
  color: var(--white);
  transition: all .5s ease-in-out;
}

.slogan-call-to-action a:hover {
  transform: rotate(-5deg);
  background-color: var(--blue);
}

@keyframes slogan-1 {
  0% {
    transform: translateY(0);
  }

  100% {
    transform: translateY(-1rem);
  }
}

@keyframes slogan-2 {
  0% {
    transform: rotate(0);
  }

  100% {
    transform: rotate(-8deg);
  }
}

```

### Wens aan maken button
De volgende microinteractie is wanneer je de muis zweeft op de wens thumbnails. De tekst onderdeel gaat een beetje omhoog.

![thumbnail microinteratie](images/thumbnail-hover.png)


## Filter met selectmenu
![Filter](/images/selectmenu.png)
Voor de filtere heb ik een beetje geëxperimenteerd met de selectmenu. Want wanneer je op bepaalde plek bent op de pagina dan kan je de vakje niet volledig zien.  Dus ik heb experimentele functie aangezet in de chrome zodat ik `<selectmenu>` kan gebruiken.

Selectmenu is een alternatief van de `<select>` tag. Het is een native html element. Het is een soort van dropdown menu. Het enige verschil is dat je met de `<selectmenu>` met css kan stijlen en niet met de `<select>` tag.

Ik heb de selectmenu gebruikt bij het sorteren. Het voordeel van dit is dat de dropdown menu wordt aangepast aan de hand van waar je bent op de pagina.

### Hoe heb ik de selectmenu gebruikt?
Wat ik heb gedaan om selectemenu is experimentele functionele aangezet in de chrome. Dit kan je doen door naar `chrome://flags/` te gaan en dan kan je de experimentele functies aanzetten.


```html
<selectmenu name="sort" id="sort" class="select-menu-sorting">
    <option value="recent">Meest recent</option>
    <option value="delers">Meest gedeeld</option>
    <option value="trekkers">Meeste trekkers</option>
    <option value="helpers">Meeste helpers</option>
</selectmenu>

```

```css
.select-menu-sorting::part(button) {
  padding: .9em;
  appearance: none;
  -webkit-appearance: none;
  border: none;
  cursor: pointer;
}

.select-menu-sorting::part(selected-value) {
  font-size: 1.2em;

}

.select-menu-sorting::part(listbox) {
  box-shadow: none;
  width: 30em;
  height: auto;
  padding: .5em 1em;
  animation: smooth-dropdown 0.3s ease-in-out both alternate;
}

.select-menu-sorting option {
  padding: .9em;
  margin: .5em 0;
  font-size: 1.2em;
  border: none;
  background-color: var(--light-grey);
  color: var(--black);
}

.select-menu-sorting option:hover {
  cursor: pointer;
  background-color: var(--black);
  color: var(--white);
}


```


## Loading met CSS
Ik was bezig met de overzichtpagina toen, wanneer een wens zonder afbeeldingen was geplaatst en de hele layout was verplaatst. Dus ik dacht om de afbeelding container een vaste hoogte gegeven en een achtergrond kleuren. Dus wanneer de foto heel traag laad dan zie je een achtergrond kleur. 

Ik heb verschillende kleuren geprobeerd, maar we hebben besloten om de gele te gebruiken. 
![error state 1](images/error-state-blue-background.png)

![error state 2](/images/error-state-pastel-yellow-background.png)
![error state 3](images/error-state-yellow-background.png)

```css
.thumbnail-container {
  background-color: var(--white);
  border-radius: var(--border-radius-medium);
}

.thumbnail-container img {
  width: 100%;
  border-radius: var(--border-radius-medium);
}

.thumbnail-container figure {
  position: relative;
  height: 15.625em;
  background-color: var(--yellow);
  border-radius: var(--border-radius-medium);
}
```
### Kleine styling fixen bij de user pagina


### Code review - 21 Juni 2023 met Joost 
- De code is goed gestructureerd en overzichtelijk.
- Goede bestand benamingen 
- Console.log weghalen
- App.js opsplitsen in meerdere bestanden
- Performance test doen 
- Toegankelijkheid test doen
- Taken prioriteren

### Design review - 22 Juni 2023 met Vasilis
- De wens aanmaak knop een beetje laten draaien wanneer het gehoverd is.
- Probeer de selectmenu bij de filter.
- Grid auto fit gebruiken voor de thumbnails
- 

### Opdrachtgever feedback - 23 Juni 2023
We hebben nog meer feedback gekregen vanuit de opdrachtgever. Hieronder zie je de feedback die we hebben gekregen.
- Laat zien hoe de pagina eruit ziet wannneer de wens gesorteerd is bij thema's
- De call to action aanpassen naar iets anders zoals bijdragen naar een duurzaam sociaal en strandeiland.
- Laat een datavisualisatie zien welke themas het meest wordt gebruikt. 
- filter sorteren etc een stukje eronder onder de meest recente wensen plaatsen
- meer thema’s bij overzicht pagina op 1 wens
- max 3 thema’s in het formulier afdwingen
- bij overzichtpagina even kijken of we de afbeelding omdraaien of hem wat hoger maken.
- Of gewoon goed verwoorden waarom. -> titel is belangrijk
- filter visualiseren en niet in code
- die icoontjes op overzicht op 1 lijntje  overzichtpagina
- visualisatie hoe je kan zien welke themas het meeste voorkomen
- Wat niet heel erg naar voren komt is duurzaamheid en sociaal in de artikelen
in de oproep daarboven. Helpt mee om strandeiland zo duurzaam mogelijk te maken?
bij form u en uw veranderen naar jij en jouw

### Kleine css fix
- Wanneer er geen afbeelding wordt achtergrond kleur gegeven
- De offline error bericht centreren
- De foto's van de userpagina beter  stijlen
- 
---

# Week 5: De laaste loodjes 

## Performance test

## Lazy loading bij afbeeldingen

### Visualistatie van de thema's


### Gesorteerde thema's

--- 
# Reflectie
Ten slotte is er een einde gekomen van de meesterproef. Het was vijf leerzame weken waar we de vakken kunnen toepassen op de eindopdracht. Ik heb uiteindelijk veel geleerd maar ik denk nog steeds dat ik meer kon doen. 

Voor verfrssing ga ik weer een korte samenvatiting over wat ik de laatste vijf weken heb gedaan. De opdracht die ik eraan heb gewerkt is Strandeiland. 

We moesten een functionaliteit maken waar toekomstige bewoners van Strandeiland een wens kunnen plaatsen. We hebben verschillende functionaliteiten gemaakt zoals een overzichtspagina met alle wensen, een detailpagina van elk wens, een manier om op de wens te reageren. Ik heb de laatste vijf weken aan de overzichtspagina gewerkt. 

## Wat heb ik geleerd?
Het meest belangrijk dat ik heb geleerd was hoe ik aan een frontend project werkt met een team. Werken met Git en version control maakt het wat lastiger, vooral met de merge conflicten. Maar door onze duidelijke communicatie en goede afspraken hebben we een goede workflow kunnen creëren. Hiermee heb ik geleerd hoe je merge conflicten kan oplossen, isssues maken en koppelen aan branches en pull requests.

Verder heb ik gewerkt met supabase om data op te halen. Hiervoor moet je kijken hoe je de data is gestructureerd met insomia en uiteindelijk in de applicatie implementeren. 

Als laatste heb ik geleerd hoe je de voor opdrachtgever een concept moet bouwen op basis van zijn criteria's. Hierbij leer je aan de hand van zijn feedback hoe je het concept kan verbeteren.

## Wat ging er goed?
Ten eerste vind ik ons samenwerking heel goe gegaan. Wij hebben elke zo goed gecommuniceerd en afspraken gemaakt. We houden ook tussen door een dagelijkse standup waar wij vertellen hoe het ging en wat hebben gedaan en hoe we verder gaan. Daarna worden de taken verdeeld  en gaan we aan de slag. Dit hele proces werd bijgehouden in ons daily scrum document. 

Wij hebben goede code agreemenst vastesteld zodat we consistent code schrijven. Dit hebben we gedaan door een code review te doen. Hierbij hebben we elkaars code bekeken en feedback gegeven. Onze coding agreements zijn te vinden in de wiki van onze  groep github repository.


Wat er goed ging bij mij was dat ik ietaratief hebt gewerkt aan de overzichtspagina. Je ziet duidelijk dat ik feedback heb verwerkt en een nieuwe variant hebt gemaakt. Ik ben ook blij dat ik ook een beetje kon experimenteren met css zoals animaties, de selectmenu en Grid. Ik had veel moeite met css grid maar ik heb het nu een beetje onder de knie. Ik had ook de kans om mezelf te verdiepen om code te schrijven in de server side, want ik probeerde in het begin alles te maken in de client side.

## Wat ging er minder goed?
Wat minder goed ging voor mij was dat ik vast zit met het implenteren van een filter functionaliteit om de data van de database te filteren. Ik had de css opmaak en alles maar om het echt te laten werken was een uitdaging. Ik wist precies welke code ik moest schrijven, en ik wilde ook geen hulp en liep wekenlang vast. Toen mij dat niet lukte kreeg het gevoel dat ik veel heb nog om te leren en dat ik niet genoeg heb gedaan.Maar in het algemeen ben ik wel tevreden met wat ik heb gedaan.



## Wat ben ik trots op?
Ik ben trots dat ik de meesterproef had overleeft en een leuke project aan de opdrachtgever geleverd. Ik ben trots op mijn team over hoe we zo goed hebben samengewerkt en hoe we elkaar hebben geholpen. Iedreen wisten hun rol en konden makkelijk onze taken vervullen. 

# Toepassing van de meesterproef Vakken


## Web app from scratch
De eerste vak die ik heb toegepast is web app from scratch. Ik heb supabase gebruikt  data op te halen en die op te pagina te tonen. Op de wensen overzichtspagina zie je allerlei gemaakte wensen op basis van wat er wordt in de database ingevuld.  Vanuit de database haalde ik de titel, de beschrijving, de datum en de afbeelding  van de wensen op.

Op basis van de content heb ik een user interface gemaakt met de bijbehorende states bijvoorbeeld de loadings state. De loading state wordt geactiveerd waneer de pagina heel langzaam laadt en de afbeeldingen heel traag worden geladen. Dan zie je een skeleton loader die de afbeeldingen vervangt.

 Qua code structuur heb ik gewerkt met modules. We hebben onze server bestand opgesplits in een routes.js bestand en ons client side javascript code hadden elke functionaliteit een aparte bestand. Ook ons CSS en HTML werd in componenten gedaan.  Voor de html hebben we ejs template engine gebruikt genaamd ejs. Herhalende HTML code wordt in een partials bestand geplaatst en wordt opgeroepen in de ejs bestand. Voor de css kreeg elke pagina's eem eigen css bestand. 
 
 Er is een css bestand voor de wensen overzichtspagina, een wens detailpagina, wens formulier, de chat, gebruikersdetailpagina en een globale css bestand. Ik heb voornamelijk gewerkt met de globale css bestand en de wensen overzichtspagina css bestand.

 Wat ik meer kon doen was het filteren van de data met javascript. Ik heb geprobeerd om de data te filteren maar dat lukte niet. Ik heb wel een filter functionaliteit gemaakt maar dat was met ejs. Ik wilde wel proberen om de wensen te filteren op basis de thema. Maar ik ga het ooit proberen. 

 
- ccs to the rescue
- Browser tech
- pwa
- hcd

## Wishlist
| Prioriteit | User story | Beschrijving | Status |
| :--- | :--- | :--- | :--- |
| 1 |  |  |  |


---
# Bronnen
- How do I fetch Multiple Specific Rows in Supabase JS? (n.d.). Stack Overflow. https://stackoverflow.com/questions/75717077/how-do-i-fetch-multiple-specific-rows-in-supabase-js
- How to get “COUNT(*)” in Supabase. (n.d.). Stack Overflow. https://stackoverflow.com/questions/65612167/how-to-get-count-in-supabase
- Vanilla JavaScript search - how to show results only when button is clicked? (n.d.). Stack Overflow. https://stackoverflow.com/questions/69117827/vanilla-javascript-search-how-to-show-results-only-when-button-is-clicked
- How to get the selected radio button’s value? (n.d.). Stack Overflow. https://stackoverflow.com/questions/9618504/how-to-get-the-selected-radio-button-s-value
- How do I get Date(); to show the time in JavaScript right? (n.d.). Stack Overflow. https://stackoverflow.com/questions/46754181/how-do-i-get-date-to-show-the-time-in-javascript-right
- How to make “fit-content” work across browsers? (n.d.). Stack Overflow. https://stackoverflow.com/questions/54740433/how-to-make-fit-content-work-across-browsers
- Rotate Parent but not child on hover. (n.d.). Stack Overflow. https://stackoverflow.com/questions/48651589/rotate-parent-but-not-child-on-hover
- EJS - pass data to partial view and use it in every view/page. How can i do that? (n.d.). Stack Overflow. https://stackoverflow.com/questions/60551806/ejs-pass-data-to-partial-view-and-use-it-in-every-view-page-how-can-i-do-that
- iterating over JSON object in ejs partial. (n.d.). Stack Overflow. https://stackoverflow.com/questions/37279927/iterating-over-json-object-in-ejs-partial
- Fading out text on overflow with css if the text is bigger than allowed. (n.d.). Stack Overflow. https://stackoverflow.com/questions/22808040/fading-out-text-on-overflow-with-css-if-the-text-is-bigger-than-allowed
- ::-webkit-scrollbar - CSS: Cascading Style Sheets | MDN. (2023, April 1). https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-scrollbar
- Advanced Form Control Styling With Selectmenu And Anchoring API — Smashing Magazine. (2023, June 1). Smashing Magazine. https://www.smashingmagazine.com/2023/06/advanced-form-control-styling-selectmenu-anchoring-api/
- Lazy loading - Web performance | MDN. (2023, March 30). https://developer.mozilla.org/en-US/docs/Web/Performance/Lazy_loading
- Brosset, P. (2022, October 25). The selectmenu HTML Tag | CSS-Tricks. CSS-Tricks. https://css-tricks.com/the-selectmenu-element/
- Fetch data | Supabase. (n.d.). https://supabase.com/docs/reference/javascript/crawlers/select
- Isheanesu. (2022). How To SELECT, COUNT and JOIN Supabase Data. DEV Community. https://dev.to/thisisisheanesu/how-to-select-count-and-join-supabase-data-3ihk
- House, C. (2023). A Complete Guide to CSS Grid | CSS-Tricks. CSS-Tricks. https://css-tricks.com/snippets/css/complete-guide-grid/
- Onyejiaku, T. K. (2023). What is req.query in Express.js? Educative: Interactive Courses for Software Developers. https://www.educative.io/answers/what-is-reqquery-in-expressjs
- Hallo IJburg - houdt je verbonden. (n.d.). halloijburg.nl. https://halloijburg.nl/
- Hallo Strandeiland. (n.d.). hallostrandeiland.nl. https://hallostrandeiland.nl/
- Supabase Javascript Client - Using filters. (n.d.). https://supabase.com/docs/reference/javascript/using-filters
- How To Create Vertical Tabs. (n.d.). https://www.w3schools.com/howto/howto_js_vertical_tabs.asp
- how to use font awesome icons in HTML. (n.d.). Stack Overflow. https://stackoverflow.com/questions/71146319/how-to-use-font-awesome-icons-in-html
- CSS scroll snap - CSS: Cascading Style Sheets | MDN. (2023, May 29). https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_scroll_snap
- Kohler, M. (2020, June 18). Practical CSS Scroll Snapping | CSS-Tricks. CSS-Tricks. https://css-tricks.com/practical-css-scroll-snapping/
- Using Each Loop in EJS Template and Express JS. (2021, July 8). The freeCodeCamp Forum. https://forum.freecodecamp.org/t/using-each-loop-in-ejs-template-and-express-js/468398/2


