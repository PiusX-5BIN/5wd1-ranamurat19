# 💻 PROJECT: WD1 - Superhero Website

## 🥅 Overzicht en Leerdoelen

Met dit project leer je wat Markup Languages zijn, waar ze voor dienen en gebruik je 2 verschillende Markup Languages (Markdown en HTML) om een website op te bouwen.

## 🔍 Superhero Website

Samen met je leraar Informatica speel je het spel Superfight, waarin je zelf een superheld opbouwt en tegen de supervillains van andere spelers laat vechten. Tijdens deze opdracht ga je één van jouw Superheroes een eigen website geven.

Dit project bestaat uit verschillende opdrachten. Je maakt de opdrachten in de juiste volgorde. Lees elke opdracht goed voor je er aan begint. 

**Het is belangrijk dat je hier _regelmatig_ aan werkt**. Je toont dit door regelmatig een nieuwe update te pushen naar github.\
**TIP**: Commit en Push elke keer je je laptop sluit. Zo voorkom je dat je je werk kwijt geraakt.



## 🛠️ Opdrachten
<details>
  <summary>Opdracht 1: markup met Markdown</summary>

> ### opdracht 2
> 
> Tijdens deze opdracht ga je allerlei inhoud verzamelen die je zal gebruiken tijdens het ontwikkelen van je website. 
>
> Voor jouw personage ga je de pagina een eerste keer uitwerken met behulp van **Markdown**. 
> 
> - Geef het document `superhero.md` de naam van je superheld.
> - werk nu de volgende onderdelen uit in het document:
>   - banner
>     - foto
>     - naam van het personage
>     - een slogan of korte tekst
>   - profiel van het personage
>     - foto/tekening
>     - naam
>     - een tekst die uitlegt wat voor superheld zij/hij/het is.
>   - getuigenissen
>     - personen die hun ervaring met het personage vertellen (minstens 4)
>     - elke persoon bestaat uit een foto, naam en getuigenis-tekstje
>   - Comics
>     - de comics waar het personage de hoofdrol speelt (minstens 3)
>     - elke comic bestaat uit een titel, verschijningsdatum, foto/tekening.
>   - footer
>     - links naar de websites van je klasgenoten

</details>

---

<details>
  <summary>Opdracht 2: van Markdown naar HTML</summary>

> ### opdracht 2
> 
> Vul de html pagina in met de inhoud die je hebt verzameld uit de vorige opdracht. Gebruik de juiste HTML elementen om de inhoud van markup te voorzien.
>
> Voeg ook bij elk onderdeel commentaar toe dat duidelijk maakt waar het onderdeel voor dient. Commentaar kan je toevoegen met behulp van volgende code:  
> `<!-- deze commentaar wordt niet zichtbaar -->`

</details>

---

<details>
  <summary>Opdracht 3: HTML structuur en semantiek</summary>



> ### opdracht 3
> 
> Tijdens deze opdracht ga je inhoud die bij elkaar hoort groeperen.  
> Eerst toon je dit met horizontale lijnen met Markdown, daarna in HTML met block-elementen.
> 
> Markdown:
> - open het Markdown bestand van je superheld
> - voeg een horizontale lijn toe op elke plek waar een nieuwe semantische sectie begint.
>   - Gebruik de code `---` toe om een horizontale lijn te plaatsen
>   - bv.: Tussen de **banner** en het **profiel** plaats je een horizontale lijn, omdat de beide onderdelen semantisch verschillen van elkaar
> 
> HTML:
> - Nu je met Markdown een onderscheid hebt gemaakt tussen alle semantisch verschillende secties ga je elke sectie een eigen block-element geven.
> - Gebruik hiervoor een block element dat **semantisch zo correct mogelijk is**.
>   - bv.: gebruik een `<footer>` element om alle footer-inhoud te verzamelen
>   - Je kan een lijst met semantische elementen [hier terugvinden](https://www.w3schools.com/html/html5_semantic_elements.asp).
>     - De bedoeling is dat je zelf op zoek gaat op het internet wat het semantische doel is van elk element. 
>     - **Tip**: gebruik hiervoor [W3Schools](https://www.w3schools.com), [MDN](https://developer.mozilla.org/), [StackOverflow](https://stackoverflow.com/) of [Google](https://www.google.com).
> - Voeg ook bij elk block-element commentaar toe om je code te verduidelijken. Commentaar kan je toevoegen met behulp van volgende code:  
> `<!-- deze commentaar wordt niet zichtbaar -->`

</details>
  
---

<details>
  <summary>Opdracht 4: meer gedetailleerde semantiek</summary>



> ### opdracht 4
> 
> Tijdens deze opdracht voorzie je elementen van IDs en class-namen.
>
> - Voorzie je HTML code van class-namen, waarbij je de semantiek van herhalende elementen benadrukt.
>   - bv.: elke getuigenis over je superheld is een apart element, maar er zijn er 4 van. Je kan deze elementen de klasse `getuigenis` geven.
> - Voorzie je HTML code van IDs, waarbij je de semantiek van unieke elementen benadrukt.
>   - bv.: er is maar één banner in je website. Deze banner kan je semantisch verder verbeteren door deze een id `superheroBanner` te geven.
>
> Voeg ook bij elk onderdeel commentaar toe om je code te verduidelijken. Commentaar kan je toevoegen met behulp van volgende code:  
> `<!-- deze commentaar wordt niet zichtbaar -->`

</details>




---

## 💡 Belangrijke Termen

| Term                 | Definitie                                                                                                                                  |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| HTML                 | Een taal die gebruikt wordt om de structuur van een website te bepalen.                                                                    |
| CSS                  | Een taal die gebruikt wordt om de opmaak van een website te bepalen.                                                                       |
| commentaar           | Een stuk tekst in de code dat genegeerd wordt door de computer. Dit kan gebruikt worden om extra uitleg bij code te geven.                 |
| server               | Een computer met een eigen, uniek internet-adres waar alle code en bestanden van een website zijn opgeslagen.                              |
| browser              | Het programma waarmee je een website kunt bezoeken.                                                                                        |
| viewport             | De ruimte in de browser waarin een website getoond wordt.                                                                                  |
| client               | De computer van een gebruiker die surft naar een website.                                                                                  |
| *.html               | Met deze bestands-extensie worden pagina's van een website opgeslagen als document.                                                        |
| index.html           | De standaard startpagina van een website. Als je geen pagina meegeeft aan het adres van de website, wordt deze pagina automatisch geladen. |
| tag                  | Een kleiner dan (<) en groter dan (>) teken waartussen een codewoord staat.                                                                |
| tagnaam              | Een codewoord dat inhoud aanduidt voor een bepaald doel.                                                                                   |
| openingstag          | Een kleiner dan (<) en groter dan (>) teken waartussen een codewoord staat, dat aanduidt waar de inhoud begint.                            |
| sluitingstag         | Een kleiner dan (<) en groter dan (>) teken waartussen een forward slash en codewoord staat, dat aanduidt waar de inhoud eindigt.          |
| element              | Een blok code, bestaande uit een openingstag, inhoud en sluitingstag.                                                                      |
| zelfsluitend element | Een element dat de inhoud dat het aanduidt zelf toevoegt. Dit element heeft daarom enkel een openingstag.                                  |
| nesten               | Het insluiten van één element in een ander element.                                                                                        |
| inhoud               | Alles dat tussen de openingstag en sluitingstag van een element staat.                                                                     |
| indentatie           | Het aantal spaties voor elke lijn code, dat aanduidt in welk element die lijn code is genest.                                              |
| attribute            | Een deel van de openingstag dat meer informatie geeft over het element.                                                                    |
| attribute-key        | De naam van het attribute. Dit staat aan de linkerkant van het = teken.                                                                    |
| attribute-value      | De waarde van het attribute. Dit staat aan de rechterkant van het = teken.                                                                 |
| block-level          | Een type element dat steeds op de volgende lijn start en de volledige breedte in beslag neemt.                                             |
| inline               | Een type element dat slechts zoveel breedte inneemt als het nodig heeft en tussen andere inhoud geplaatst kan worden.                      |
| structuur            | De logische manier waarop de ontwikkelaar elementen heeft genest.                                                                          |
| semantiek            | Het doel van een element, duidelijk gemaakt door de naam van het element.                                                                  |
| id attribute         | Geeft een unieke naam aan een element.                                                                                                     |
| class attribute      | Deelt een element in bij een groep elementen met gelijkaardige semantische waarde.                                                         |

## 📚 Bronnen

 - [cursus Toegepaste Informatica - Markup](https://t-informatica.github.io/courses/webontwikkeling/html/)
 - [cursus Toegepaste Informatica - Markup theorie oefenen](https://t-informatica.github.io/lms-exercise.html?subject=Markup)
 - [Markdown oefeningen](https://www.markdowntutorial.com/)
 - [W3 Schools - HTML tutorial](https://www.w3schools.com/html/)
 - [W3 Schools - HTML oefeningen](https://www.w3schools.com/html/exercise.asp)

---

## 🏆 Evaluatie


### Markup

A | B | C | D | E
---|---|---|---|---
Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en hebben een duidelijke, correcte naam. Elementen zijn onderverdeeld in grotere elementen, en er is gekozen voor een optimale oplossing. | Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben soms nog onduidelijke naamgeving. Elementen zijn onderverdeeld in grotere elementen, hoewel er oplossingen bestaan die korter of optimaler zijn. | Elementen worden correct genest. De semantisch juiste elementen werden gebruikt. Elementen zijn niet voldoende onderverdeeld in grotere elementen. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving. | Elementen worden correct genest. Elementen zijn niet voldoende onderverdeeld in grotere elementen. Er wordt geen rekening gehouden met de semantiek van de elementen. De id's en classes van elementen zijn ingevuld waar nodig, maar hebben vaak onduidelijke naamgeving. | Elementen worden niet correct genest. Elementen zijn niet voldoende onderverdeeld in grotere elementen. Er wordt geen rekening gehouden met de semantiek van de elementen. De id's en classes van elementen zijn niet of onduidelijk ingevuld waar nodig.


### Foutopsporing

A | B | C | D | E
---|---|---|---|---
Je hebt de meeste syntax- en runtimefouten gevonden en verklaard, en kan er ook een oplossing voor geven. | Je hebt de meeste runtime-fouten gevonden en verklaard, en kan er ook een oplossing voor geven. Je hebt slechts weinig syntax fouten gevonden. | Je hebt de meeste syntax-fouten gevonden en verklaard, en kan er ook een oplossing voor geven. Je hebt slechts weinig runtime fouten gevonden. | Je hebt weinig fouten gevonden. Je kan de fouten die je vond wel verklaren, maar je biedt weinig oplossingen hiervoor. | Je hebt weinig fouten gevonden. De fouten die je vond kan je niet verklaren of oplossen.
