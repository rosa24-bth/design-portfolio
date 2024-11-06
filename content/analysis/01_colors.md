---
Title: Colors analysis
Description: This is my colors analysis page.
Template: analysis-page
---

# Colors

I den här rapporten har jag valt ut tre olika webbplatser för att analysera färgpalett och typografi. Jag diskuterar valen kopplat till den känsla webbplatsen troligtvis vill signalera.


Urval
-----------------------

Jag har valt att analysera tre olika webbplatser som sånär kan anses besläktade, om än avlägset; en om en bokstavsillustratör, en annan om en illustratör och en tredje om en webbutvecklare. Det de har gemensamt är att de alla vill förmedla en känsla till besökaren om vem de är och vad som kan förväntas av deras arbeten. Jag använde gammalt hederligt googlande för att hitta olika kreatörers om-sidor, och landade i de här tre eftersom de har samma syften men relativt olika utseenden.
<br><br>
Här är sidorna:
<br><br>
<br><br>
Jessica Hische - https://www.jessicahische.is/anoversharer
<br><br>
![En bild på about-sidan för Jessica Hische](../assets/img/jessica_hische.png)
<br><br>
<br><br>
<br><br>
Martina Paukova - https://martinapaukova.com/about
<br><br>
![En bild på about-sidan för Martina Paukova](../assets/img/martina_paukova.png)
<br><br>
<br><br>
<br><br>
Wes Bos - https://wesbos.com/about
<br><br>
![En bild på about-sidan för Wes Bos](../assets/img/wes_bos.png)
<br><br>

Metod
-----------------------

Jag har använt mig av DevTools för att inspektera färgval och typografi på sidorna. Jag väljer att jobba med det via Firefox, då jag tycker DevTools där är mer användarvänlig än andra.
<br><br>
Jag har även använt mig av webbplatsen WebAIM:s "Contrast Checker" (https://webaim.org/resources/contrastchecker/). Det verktyget kontrollerar och jämför färger, och ger en snabb bedömning av om färgkombinationen uppfyller tillräckliga krav på tillgänglighet enligt standarden som sätts genom Web Content Accessibility Guidelines (WCAG).


Resultat
-----------------------

### Jessica Hische

Jessica Hische är en erfaren och etablerad bokstavsillustratör från USA. Hon har samarbetat med många välkända personer och företag, och hon har även gett ut prisade böcker. Jessica använder ett complementary färgschema till sin about-sida.
<br><br>
Färgpaletten är denna:
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #fff">
<td style="height: 50px; width: 50px; background-color: #0B755C">
<td style="height: 50px; width: 50px; background-color: #FFD372">
<td style="height: 50px; width: 50px; background-color: #ee9cb2">
</tr>
</table>
<br>
Den gröna färgen mot den vita bakgrundsfärgen används både för den större och fetare H1-rubriken, men även för brödtext. Den färgkombinationen klarar inte av att leva upp till WCAG:s högsta standard (AAA) när det gäller text med normalutseende, vilket brödtexten får anses klassas som. Därutöver så misslyckas både den gula och den rosa färgen med samtliga delar och nivåer av kontrast-testet, gentemot det vita.
<br><br>
Gällande typografi så har Jessica, för H1, valt ett egengjort typsnitt som har en handskriven och elegant stil. Den påminner om fonten "Great Vibes" från Google Fonts.
<br><br>
För H2 har hon också valt ett typsnitt som hon själv skapat. Det framgår även av CSS-delen av källkoden att besökaren uppmanas att inte stjäla fonten. Det här typsnittet är fetstilat och har en lite lekfull stil. Den är sans-serif, vilket innebär att den inte har några extra linjer i ändarna på bokstäverna. Det ger den ett rent och modernt utseende. Den påminner om fonten "Poppins" från Google Fonts.
<br><br>
För H3 har Jessica använt fonten Whitney som skapades år 1996 av Tobias Frere-Jones. Fonten skapades ursprungligen för Whitney-muséet i New York, men ägs nu av Hoefler & Co. Det kan beskrivas som en lättläst, neutral och proportionerlig font, som ger ett sofistikerat intryck.
<br><br>
Slutligen, för brödtexten används fonten Mercury, som även den ägs av Hoefler & Co. Den är lättläst och klassisk.
<br><br>

### Martina Paukova

Martina Paukova är en framgångsrik illustratör från Slovakien, vars illustrationer förekommit i stora publikationer och använts av erkända företag. Hon använder en färgstark och lekfull stil i sitt arbete, med vilken hon illustrerar vardagssituationer med en komisk touch. Martina använder ett complementary färgschema, med följande färgpalett:
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #FFEDED">
<td style="height: 50px; width: 50px; background-color: #000000">
</tr>
</table>
<br>
Bakgrundsfärgen har en rosa ton, vilket framhävs ytterligare när textens färg är svart. Den färgkombinationen tar sig igenom samtliga delar och nivåer av kontrast-testet, utan anmärkningar.
<br><br>
De fontval Martina gjort har, för H1, landat i fonten FK Screamer, som designats av Květoslav Bartoš och publiceras av Florian Karsten Typefaces. Det är en fet, tight och distinkt font av modern stil.
<br><br>
Eftersom Martina har valt att hålla sin about-sida sparsmakad så finns det inga ytterligare fonter för rubriker. Däremot för brödtexten så har hon valt fonten FK Display, som har samma designer och utgivare som FK Screamer. Men till skillnad från den så är FK Display bredare, mer klassisk och lättläst.
<br><br>

### Wes Bos

Wes Bos är en kanadensisk webbutvecklare som erbjuder olika utbildningar och kurser online inom webbutveckling. Han driver också en podcast som även den handlar om webbutveckling. Till sin about-sida har han använt ett complementary färgschema, med den här färgpaletten:
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #ffffff">
<td style="height: 50px; width: 50px; background-color: #000000">
<td style="height: 50px; width: 50px; background-color: #ffc600">
</tr>
</table>
<br>
Med en helt vit bakgrundsfärg till en helt svart typsnittsfärg så hoppar den färgkombinationen högt över WCAG:s ribba för kontrast. Däremot fallerar den gula färgen kontrast-testerna helt och hållet. 
<br><br>
För sina H1:or har Wes använt italic-varianten av fonten Radnika, som ägs av designföretaget Hanken Design Co. De beskriver det själva som ett typsnitt som "överbryggar klyftan mellan de starkt uttrycksfulla typsnitten från 1800-talet och de mer eleganta, något strikta, typsnitten från 1900-talet". På webbsidan fanns det inga spår av någon H2-rubrik, men däremot för de underrubricerande H3:orna så återanvänds Radnika, om än i något mindre storlek.
<br><br>
Wes har vänt sig till Hoefler & Co för att använda fonten Operator Mono till sin brödtext. Det är ett typsnitt som är starkt inspirerat av skrivmaskiners. Det ger både en personlig och seriös framtoning, som kan föra tankarna till ett redaktörsbrev.


Analys & diskussion
-----------------------

### Jessica Hische

Något Jessica Hische lyckas med på sin about-sida är att klämma in mycket matnyttig information på en och samma sida, utan att det känns alltför plottrigt. Den breda och trevliga bilden på henne som besökaren möts av, tillsammans med att hennes namn skrivits med eget typsnitt, bidrar till en personlig och gemytlig känsla. Valen av pastellfärger i rosa, grönt och gult som står emot en vit bakgrund skapar en inbjudande atmosfär. Om man inte vetat vad Jessica arbetar med så skulle en snabb blick på hennes about-sida lätt kunnat få en att tro att hon likväl sysslade med inredning och design.
<br><br>
Det är klockrent att hon, i egenskap av just bokstavsillustratör, också använder helt egna typsnitt på sin sida. Det är förtroendeingivande och kopplar väl samman sidan med personen, samtidigt som det bidrar till att stärka identiteten för hennes varumärke. Däremot så borde man kunna förvänta sig mer nyanserade val av färgkombinationer av någon så framträdande och erfaren inom ett område som helt handlar om utseende och läsbarhet. De olika färgerna samspelar väl med varandra. Däremot så är framförallt det gröna färgvalet för text mot den vita bakgrunden något som inte är helt bekvämt för ögat, vilket även bekräftas av kontrast-testerna. Både för den längre paragrafen och den utförliga listan med klienter så upplevs den gröna färgen något flyktig. Det utgör ett större tillgänglighets-bekymmer än den rosa färgen, eftersom den enbart används med fet stil i underrubriker.
<br><br>
Sammantaget lyckas Jessica med att lyfta fram flera olika typsnitt på en och samma sida, utan att det blir stökigt, vilket känns lämpligt och helt nödvändigt med tanke på vad hon erbjuder. Hennes val av att låta färg och form vara en mix av det personliga, vänliga och professionella känns väldigt genomtänkt. Det gör även valet av att relativt tidigt på sidan presentera de många giganter till klienter hon haft.
<br><br>
Om jag skulle lämna några potentiella förbättringsförslag till Jessica gällande hennes presentativa sida så skulle det vara två stycken. Den ena gäller det gröna färgvalet, alternativt typsnittet som används för den färgen. Där går det absolut att göra det mer läsvänligt och snällt mot ögonen. Det har också sin del i det enda avsnittet av sidan som känns intetsägande och opersonligt, nämligen navbaren. Den upplevs inte ha fått samma omsorg som andra delar av sidan, vilket kan skada helhetsintrycket. Det andra förbättringsområdet jag ser visas när jag skrollar ner till botten av sidan. Tar jag ett steg tillbaka och försöker ta in hur många olika typsnitt, färger och font-storlekar som visas samtidigt så bör det tonas ned, alternativt att vissa delar av sidan där kan struktureras om.
<br><br>

### Martina Paukova

Det finns något befriande med enkelheten Martina Paukova låter regera på sin sida. Här finns inte tid för något överflödigt, utan det är rakt på sak som gäller; besökarens frågor får omedelbara svar. Vem är Martina? Vad jobbar hon med? Vilka klienter har hon haft? Allt identifieras på ett fåtal sekunder. Och färgvalen är inte heller något som saktar ner läsförståelsetempot som bjuds. Martinas är faktiskt den enda av de tre sidorna i det här analysarbetet som klarar sig felfritt igenom den hinderbana som är WCAG:s kontrast-standard. Färgvalen bidrar alltså till att göra texten mer läsarvänlig. Den får mig också osökt att tänka på utseendet av en parfym från Jimmy Choo; det är något med sammansättningen av pudrig rosa, svart och valet av typsnitt för rubriken som för tankarna mer till parfym och modevärlden än illustration. Det är en kombination som lätt blir ihågkommen, men tyvärr kopplar det inte lika väl samman med sidans syfte som det gör för till exempel Jessica Hisches sida.
<br><br>
Valet av brödtextens typsnitt och storleken för densamma är en av sidans svagare delar. Trots att storleken hade behövt vara lite mindre för att vara optimal för en läsare, så lyckas den ändå med konststycket att varken sticka ut eller, när den väl identifieras, vara bekväm att läsa.
<br><br>
Visserligen låg det inte i uppgiftsbeskrivningen att analysera typsnitt utöver de som hittas i H1-H3-rubriker och brödtext. Men jag kan inte låta bli att kommentera den till synes aldrig sinande listan av klienter som Martina lyfter fram. Jag förstår det stilistiska valet av att hoppa mellan två olika typsnitt. Men storleken och själva textmängden är aggressiv och slukar allt fokus. På en sida med annan layout skulle det kunna fungera väl, men här är det en av delarna jag skulle lämna som förslag att se över, åtminstone när det gäller font-storleken.
<br><br>

### Wes Bos

Wes Bos är den av de tre utvalda vars sida ger det mest enhetliga och unika intrycket, och det trots att han främst låter standard-vitt och svart jobba. Med sin minimalistiska färgsättning ligger fokus på tydlighet och kontrast. Han använder en djärv gul för att accentuera vissa delar, såsom rubriker och länkar. Med tanke på hur lite av sidan som faktiskt går i den gula så blir inte kontrast-bristerna som visats alltför stora bekymmer. Den svarta smala ramen som ligger runt den vita bakgrunden är också värd att lyfta. Många sidor jag besökt har precis som denna, en helt vit bakgrund. Men genom att rama in den med svart så blir det enklare för läsaren att fokusera på sidans innehåll; det flyter inte bort i en vit oändlighet. Det gör också att sidan som i övrigt är ganska "street"-aktig och rå också får en känsla av struktur och ordning.
<br><br>
De återhållsamma färgvalen ger Wes möjlighet att istället ta ut svängarna mer när det gäller typsnitt. För rubrikerna så fångas uppmärksamheten av det djärva och blockiga typsnittet, som tillåts ge än mer eftertryck genom att också få gå i kursivt för vissa delar.
<br><br>
En gammal tidningsredaktion kan till synes ha ganska lite gemensamt med skate-kultur. Men ändå gifter sig skrivmaskins-typsnittet för brödtexten väl med övriga fontval. Här kommer jag in på en av få delar som kan anses som något negativa. För skulle jag inte läsa texten utan enbart utgå från färgval, typsnitt och övrig design, så skulle tankarna först röra sig inom just street-, skate- eller annan urban kulturmiljö. Att det är en sida om en webbprogrammerare som erbjuder online-utbildningar är långt ifrån det första som dyker upp i huvudet. Samtidigt är sidan så stilsäker och välstrukturerad att det snabbt blir logiskt att det är just en erfaren webbprogrammerare som ligger bakom den.



Referenser
-----------------------

Beaird, J., Walker, A., & George, J., 2020. *The Principles of Beautiful Web Design*. Fjärde utgåvan.
<br><br>
Tuts+. *An Introduction to Color Theory for Web Designers*. Adress: <https://webdesign.tutsplus.com/an-introduction-to-color-theory-for-web-designers--webdesign-1437a> [Hämtat 6 november 2024].
<br><br>
WebAIM. 'Contrast Checker'. Adress: <https://webaim.org/resources/contrastchecker/> [Hämtat 6 november 2024].


Övrigt
-----------------------

Arbetet med analyserna har genomförts enskilt.
<br><br>
