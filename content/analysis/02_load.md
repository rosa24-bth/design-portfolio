---
Title: Load analysis
Description: This is my load analysis page.
Template: analysis-page
---

# Load

Jag har valt ut tre webbplatser för att mäta och analyser deras laddningstid och användbarhet.

Urval
-----------------------

Jag har valt de tre sidor som jag tidigare gjort en färg-analys av eftersom jag redan bekantat mig med dem. De har också en bra variation av innehåll och ligger även till synes på lite olika nivåer när det gäller programmeringskvalité, vilken kan vara intressant ur analys- och jämförelsesynpunkt.

Metod
-----------------------

Jag har använt mig av PageSpeed Insights och DevTools i Firefox för att göra mina mätningar, samt Google Sheets för sammanställningar.

Resultat
-----------------------

### Sammanställning av mätningarna

<iframe class="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR1F31izdv2amH8pCC3MtwQLVzg2ks4-WO6RjC4fcmEhExDy7b11MieJDCRJlDTknF76bb-Tlm1EGe6/pubhtml?widget=true&amp;headers=false"></iframe>
<p><a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vR1F31izdv2amH8pCC3MtwQLVzg2ks4-WO6RjC4fcmEhExDy7b11MieJDCRJlDTknF76bb-Tlm1EGe6/pubhtml?widget=true&amp;headers=false" target="_blank">Visa spreadsheet i full storlek</a></p>
<br><br>
<br><br>


### Jessica Hische

https://www.jessicahische.is/anoversharer
<br><br>
![En bild på about-sidan för Jessica Hische](../assets/img/jessica_hische.png)
<br><br>
<br><br>
<br><br>

### Martina Paukova

https://martinapaukova.com/about
<br><br>
![En bild på about-sidan för Martina Paukova](../assets/img/martina_paukova.png)
<br><br>
<br><br>
<br><br>

### Wes Bos

https://wesbos.com/about
<br><br>
![En bild på about-sidan för Wes Bos](../assets/img/wes_bos.png)
<br><br>

Analys & diskussion
-----------------------

För att göra ett axplock av de förbättringsmöjligheter som finns för de olika webbplatserna så kan sägas att Jessicas webbplats skulle kunna förbättras, främst för mobila enheter, när det gäller det som på PageSpeed Insights kallas "Cumulative Layout Shift" (CLS). Det handlar om hur mycket användaren upplever att sidan "hoppar" när den laddas in. För Martinas webbplats fastnar jag på att hennes news-sida ligger i botten gällande Search Engine Optimization (SEO). Av resultatbeskrivningen på PageSpeed Insights så är en bidragande orsak till detta att det saknas en metabeskrivning, vilket vore en relativt enkel sak att lägga till för att förbättra sidan gällande SEO. För Wes Bos och hans startsida så är det tiden det tar att visa innehållet (cirka 6,7 sekunder) som har den största negativa inverkan på prestandabetyget.
<br><br>
Generellt sett så är det tydligt att större sidor med fler saker att ladda också tar ganska mycket längre tid att ladda in än andra sidor. Det här är logiskt så klart, men belyser ändå vikten av att just sidor med till exempel många bilder också mår bra av att byggas på ett effektivt sätt. Det kan handla både om val av filtyp och om att använda funktioner som "lazy loading", som ser till att ladda bilder mer vid behov istället för att jobba lika hårt med alla delar av sidan. Men för att göra så en sida laddas snabbare kan det också vara en god idé att se över om det är möjligt att minska ner på mängden JavaScript som används, alternativt säkerställa att de laddas asynkront vilket innebär att ett skript laddas in parallellt med resten av sidan.
<br><br>
Det är knappast en slump att en webbplats av en webbprogrammerare presterar bäst i den här typen av tester. I nästan samtliga delar av analysen påvisar webbplatsen för Wes Bos höga betyg. Att till exempel startsidan har 100/100 gällande tillgänglighet för besök av datorer är imponerande. Det kanske känns självklart att en webbprogrammerare har en bättre optimerad webbplats än andra. Men det visar också att det går att bygga kod på ett sätt som gör webbplatsen smidigare, snabbare och mer användarvänlig, om man lägger ner programmerings-jobbet på den. När jag ögnar igenom diagnostiken som PageSpeed Insights så snyggt och tydligt bjuder på så är en hel del av de förslag på förbättringar var för sig till synes ganska enkla att ta hand om. Att ändra filformaten för bilder, lägga till width, height och alt-attribut till bildelement och använda bilder med rätt storlek bör inte kräva alltför stort arbete och ingrepp i sidans kod. När det gäller CLS så kan det behöva göras en mer djupgående analys av alla delar som kan orsaka ett sämre betyg. En sak kan vara att se till så olika delar har reserverat utrymme på sidan, så att platsen den kommer ta är "paxad" från början. Det är ett sätt att undvika "hoppandet" på sidan som många användare stör sig på.
<br><br>
Om jag ska våga mig på en rangordning av de olika webbplatserna så är vinnaren enkel att utse; Wes Bos har både högst genomgående snittbetyg och även den minsta variationen. Inte heller i hans dippar faller sidorna helt ur ramen.
<br><br>
Däremot är det något knivigare att landa i plats två och tre. Om jag bara snabbt blickar på resultaten så ser det ut som att Martinas sida är bättre än Jessicas. Men jag väljer att även väga in skillnaderna mellan webbplatsernas högsta toppar och djupaste dalar, samt komplexitet. Därför är det särskilt intressant att jämföra Jessicas "working"- sida med Martinas "news"-sida. Martinas sida laddar in 240 resurser med en storlek på 163 MB. Jessicas sida har hela 369 resurser (i genomsnitt), men ändå knappa 24 MB. Det säger mig att det på Jessicas sida har lagts ner mer optimerings-arbete och eftertanke. Dessutom klockar Jessicas sida in på nästan nio sekunder mindre än Martinas. Sammantaget placerar jag därför Jessicas sida på silverplats och Martinas på brons.
<br><br>
För att en sida ska kunna sägas vara snabb så skulle jag säga att den bör landa in på under fem sekunder. Men för att landa i ett omdöme om en sida är snabb eller långsam så skulle jag också vilja väga in vad det är för typ av sida och vilket innehållet är. Vissa sidor är kanske främst tänkt för användaren att scrolla igenom mycket innehåll, men andra sidor kanske det inte är tanken. Om det då finns delar längst ned på sidan som laddas in "för långsamt", men som i praktiken sällan besöks av användarna, eller åtminstone oftast inte förrän långt efter fem sekunder, ja då skulle jag inte se det som ett stort problem. I slutändan finns webbplatser främst till för människor som besöker en sida för att ta del av innehållet i någon utsträckning. Om den upplevelsen i praktiken upplevs som smärtfri så skulle jag säga att det är viktigare än vilken siffra PageSpeed Insights ger sidan i en viss kategori. Med det sagt så är det väldigt bra att ha sådana verktyg för att göra webbplatser snabbare och för att bidra till att säkerställa tillgänglighet för många olika användare med olika behov och evenutella funktionsvariationer.
<br><br>
När det då gäller de webbplatserna jag gjort mätningar på så har samtliga av dem tider som överstiger fem sekunder. Wes har visserligen laddningstider som samtliga överstiger fem sekunder, men å andra sidan är de väldigt kosekventa och rör sig inom det smala spannet 6,64 - 7,28 sekunder. Det bidrar till att man inte reflekterar så mycket över laddningstiderna, eftersom de aldrig spretar. Däremot för Jessicas och Martinas bildtunga sidor så sticker laddningstiden iväg långt. Det har sina förståeliga förklaringar, men likväl blir det inget bra flyt på de sidorna.


Referenser
-----------------------

Beaird, J., Walker, A., & George, J., 2020. *The Principles of Beautiful Web Design*. Fjärde utgåvan.
<br><br>
Moz. *Page Speed*. Adress: https://moz.com/page-speed [Hämtat 11 november 2024].
<br><br>
Google Developers. *Why Performance Matters*. Adress: https://developers.google.com/web/fundamentals/performance/why-performance-matters [Hämtat 11 november 2024].

Övrigt
-----------------------

Arbetet med analyserna har genomförts enskilt.
<br><br>