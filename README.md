# Semantisk HTML5

Vi vill använda **HTML5** semantiska markup för att berätta om vad innehållet är inuti taggarna. Element som `<span>` och `<div>` säger inte så mycket om innehållet. Om man istället använder en tagg som t.ex. `<main>` vet man att här kommer huvudinnehållet på sidan. Om man använder en tagg som `<header>` vet man att det elementet ska innehålla någon sorts överskrift eller bild som berättar om vad som finns på sidan.

Dock är ju detta enbart markup och de olika elementen beter sig ungefär likadant som t.ex. en `<div>`. Det handlar mer om att strukturera sitt innehåll läsvänligt. Alla element kan vara _nästlade_. D.v.s. man kan ha mer än en `<footer>` på en sida t.ex. Den ena `<footer>` kan vara själva hemsidans `<footer>` medan en annan `<footer>` kan vara en specifik artikels `<footer>`.

Läs mer om vilka element som finns att tillgå nedan:


* [w3schools.com - HTML5 Semantics](http://www.w3schools.com/html/html5_semantic_elements.asp)
    * Snabb översikt av vilka element som finns
* [html5doctor.com - Archive](http://html5doctor.com/article-archive/)
    * Arkiv för alla artiklar av html5doctor.com. Kolla under rubriken **HTML Semantics** där ligger specifika artiklar som förklarar varje enskilt nytt element: [header](http://html5doctor.com/the-header-element/), [footer](http://html5doctor.com/the-footer-element-update/), [aside](http://html5doctor.com/understanding-aside/), [nav](http://html5doctor.com/nav-element/) och [section](http://html5doctor.com/the-section-element/) t.ex.

## Övning

1. Ladda ner [denna zip](https://github.com/ZoComAB/html-semantics/raw/gh-pages/semantics.zip)
2. Packa upp och öppna `start.html` i din textredigerare
3. Ändra alla `<div>`-element i `start.html` till element som säger mer om vad som finns inuti själva elementet genom att använda HTML5-element som t.ex. `<header>`, `<article>` och `<footer>`. 

För att veta vilken element man ska välja kan man följa denna flowchart:

![HTML5 Semantic Flowchart](semantic-flowchart.png)

För att veta om ens HTML5 stämmer och är valid HTML5 kan man använda en validator. Den utgår ifrån vilken `doctype` man har använt och returnerar om ens sida använder rätt markup. Annars får man warningar eller rentav errors om man har något som inte stämmer i ens HTML5.

* [HTML Validator](https://validator.w3.org/)


