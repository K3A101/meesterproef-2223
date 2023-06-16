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
  - [Overzichtpagina eerste versie op Figma](#overzichtpagina-eerste-versie-op-figma)
    - [Versie 1:](#versie-1)
    - [Versie 2:](#versie-2)
  - [Overzichtpagina op code](#overzichtpagina-op-code)
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
    - [Code review - 14 Juni 2023](#code-review---14-juni-2023)
    - [Opdrachtgever feedback - 15 Juni 2023](#opdrachtgever-feedback---15-juni-2023)
    - [Design review - 15 Juni 2023](#design-review---15-juni-2023)
  - [Nieuwe kleurpallette](#nieuwe-kleurpallette)
  - [Nieuwe overzichtpagina Design op Figma](#nieuwe-overzichtpagina-design-op-figma)
    - [Nieuwe thumbnails designg](#nieuwe-thumbnails-designg)
    - [Wat ga ik voor volgende week doen?](#wat-ga-ik-voor-volgende-week-doen)
- [Week 4:](#week-4)
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


## Overzichtpagina eerste versie op Figma
Daarna ben ik meteen begonnen  met de eerste uitwerking van de overzichtpagina op prototype

### Versie 1:
Dit is mijn eerste versie die ik op figma heb gemaakt. Ik heb eerste de navigatiemnu nagemaakt van de strandeiland website. Want de opdrachtgever zei dat we alleen een nieuwe pagina moet toevoegen. En niet from scratch beginnen. Verder hebben we een slogan bedacht voor de wensen pagina, om het wat aantrekkelijker te maken. De layout hier is een grid van twee kolommen. En helemaal aan de rechterkan staat een onderdeel met de recente gemaakte wensen. Dus het wordt ook real time bijgehouden. 

![Figma versie 1](images/overzichtpagina-figma-1.png)

### Versie 2:
In de tweede figma versie, heb ik andere layou stijl gemaakt. Bovenaan heb je een slideshow met populaire wensen. Maar de opdrachtgever gaf als feedback dat als je de populairste wensen bovenop zet worden ze populairder altijd on top en andere wensen worden in de achtergrond gebleven. Hij wil dat alle wensen gelijke kansen krijgen. 

![Figma versie 2](images/overzichtpagina-figma-2.png)

## Overzichtpagina op code
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

### Themas
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

### Code review - 14 Juni 2023
- De code is goed gestructureerd en overzichtelijk.
- De app.js beter gaan opschonen en splitsen in meerdere bestanden


### Opdrachtgever feedback - 15 Juni 2023
Een paar feedback punten vanuit de opdrachtgever zijn:
- Op de overzichtspagina de volgorde van sorteren en filtreren aanpassen 
- Online weergaven op het bericht, is het iedereen die online is op de community pagina of zijn alleen gebruikers die op dit moment op de pagina bevinden. 
- Groene cirkel (wanneer de gebruiker online is) is niet duidelijk genoeg
- Een paar feedback punten die we van de docenten hebben gekregen
Bij het formulier pagina moet er op hierachie gelet worden welke componenten horen bij elkaar
-  Ook bij het formulier pagina kan de sectie van afbeelding naar een pop up verandert worden.
- De hierarchie van de overzichtspagina letten
- Een pakkende afbeelding voor de banner op de overzichtspagina veranderen 


### Design review - 15 Juni 2023
- Een pakkende banner afbeelding die meer context geeft.
- Meer spelen met het layout van de overzichtpagina's
- Meer kleur tintne toevoegen aan de kleurpalette


## Nieuwe kleurpallette 

## Nieuwe overzichtpagina Design op Figma

### Nieuwe thumbnails designg



### Wat ga ik voor volgende week doen?
--- 
# Week 4: