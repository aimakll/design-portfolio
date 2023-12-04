---
Title: kmom04 - färgval
Description: kmom04
---

# kmom04

Syftet med den här uppgiften är att dokumentera samt analysera utvalda webbplatsers val av typografi samt färgpaletter, tillsammans med argumentation kring den känsla webbplatsen vill förmedla med sina val.

## [Urval](#urval)

Urval har skett genom att besöka sidan [Awwards](https://www.awwwards.com) och [listan med jurymedlemmar från 2022](https://www.awwwards.com/jury/2022/).

Awwwards har valts eftersom det är en plattform som har funnits länge med syfte att visa upp och belöna verk från webbdesigners/utvecklare från hela världen. Det är ett intressant ställe att se vad som är populärt och nytt i branschen.

Inga filter applicerade på ordningen. Ursprungsidén var att välja första personen från Sverige, andra personen från Frankrike och tredje personen från Tyskland. Detta för att det kan vara intressant om det finns några uppenbara skillnader mellan designers i olika länder.

Efter att ha kontrollerat att det fanns sidor och innehåll att analysera modifierades urvalet enligt följande:

- Första personen från Sverige hade enbart en svart/vit sida, och således inte så mycket att analysera i mitt tycke.
- Andra personen från Frankrike hade enbart en länk till Instagram och ingen vanlig hemsida.

Webbplatserna som slutligen valts ut för undersökningen är dessa:
1. Designer & Art Director, Sverige [Sara Svensson](https://sarajuliasvensson.com/)
2. Creative developer, Frankrike [François-Xavier Manceau](https://francoisxaviermanceau.com)
3. Independent Interactive & Graphic Designer, Tyskland [Lu Yu](https://luyu.co/)

## Metod

### Insamling av typsnitt

- Identifierar vilka typsnitt som används med DevTools
- Kontrollerar val av typsnitt för H1-H3 samt brödtext
- Noterar skillnader utseendemässigt i övrigt (färg, stil)

### Insamling av färg

- Identifierar vilka färger som används
- Noterar vilken som är primärfärg, sekundär etc.
- Noterar vilken typ av färgschema som används (monokrom, triad etc.)

### Verktyg

- Chrome DevTools
- [Paletton - The Color Scheme Designer](https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)
- [Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/)
- [Color-pair Contrast Testing](https://color.a11y.com/ContrastPair/) (för manuelll test av färgkombinationer)

### Känsla

- Öppnar sidan
    - Gör en notering av första intrycket
    - Tittar på innehållet på första sidan samt sidan om skaparen

Använder även informell diskussion med ett par personer som beskriver sig själva som icke-designkunniga, där jag först bett dem att ge mig sina första intryck av sidan och vad de känner efter att ha sett första sidan samt sidan om skaparen.

## Resultat

### Sida 1 - Sara Svensson

#### Färger

<table style="border-spacing: 4px; border-collapse: separate">
<tr><th>Färg</th><th>Typ</th><th>Färgkod</th></tr>
<tr>
<td style="height: 50px; width: 50px; background-color: #f6efe1"></td>
<td>Primär</td>
<td>#f6efe1</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #ac5422"></td>
<td>Sekundär</td>
<td>#ac5422</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #292a2c"></td>
<td>Body</td>
<td>#292a2c</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #000000"></td>
<td>Text (p)</td>
<td>#000000</td>
</tr>
</table>

Typ av färgschema: Special

Närmast analog, men färgerna (ljusgul och rödbrun) befinner sig inte direkt intill varandra på färghjulet.

Eftersom den ljusgula är färgen som möter besökaren på förstasidan kan den rimligen antas vara primärfärg, och den rödbruna sekundär.

Kontrast

- Både första och "About"-sidan går igenom det automatiska testet.
- Vid manuell kontroll av kombinationen på "About"-sidan blir det ej godkänt på normal text. 
- Större text klarar AA-kraven men inte AAA.
- Ratio 4.04:1

#### Typsnitt

| Användning | Namn | Typ |
|------------|------|-----|
| body       | Open Sans | Sans-Serif |
| p         | acumin-pro-wide | Sans-Serif |
| H1         | acumin-pro-wide | Sans-Serif |
| H2         | orpheuspro | Serif |
| H3         | acumin-pro-wide | Sans-Serif |
| H4         | acumin-pro-wide | Sans-Serif |
| H5         | orpheuspro | Serif |
| H6         | orpheuspro | Serif |

**Noteringar:**

- code/pre: Courier New, monospace
- H2 används ofta som brödtext, exempelvis på projektbeskrivningar eller "About" 

- Sidan har blockerat högerklick/möjlighet att se källkod med `CTRL+U`, detta kringgicks med att manuellt skriva in adressen för att se källkoden enligt 
`view-source:https://sarajuliasvensson.com/`
- För öppna Dev Tools och inspektera koden fungerar F12 som vanligt (Chrome)

#### Bilder

<div class="col-flex-container">
<div class="row">
    <div class="col-flex-content">
    <a href="../assets/img/reports/sarajuliasvensson_full-w1294.jpg" aria-label="länk till bild på förstasidan sarajuliasvensson.com"><img src="../assets/img/reports/sarajuliasvensson_full-w250.jpg" alt="bild på förstasidan sarajuliasvensson.com"></a>
    <p>Första sidan</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/sarajuliasvensson_full-about-w1294.jpg" aria-label="länk till bild på about-sidan sarajuliasvensson.com"><img src="../assets/img/reports/sarajuliasvensson_full-about-w250.jpg" alt="bild på about-sidan sarajuliasvensson.com"></a>
    <p>"About"</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/sarajuliasvensson_full-product-w1294.jpg" aria-label="länk till bild på projektsida sarajuliasvensson.com"><img src="../assets/img/reports/sarajuliasvensson_full-product-w250.jpg"alt="bild på projektsida sarajuliasvensson.com"></a>
    <p>Exempel på projektsida</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/sarajuliasvensson_no-right-click.png" aria-label="länk till detaljbild sarajuliasvensson.com"><img src="../assets/img/reports/sarajuliasvensson_no-right-click.png" alt="detaljbild sarajuliasvensson.com"></a>
    <p>Sara har blockerat möjligheten att högerklicka.</p>
    </div>    
</div>
</div>

#### Skaparens intentioner vs hur sidan uppfattas

Valet av färger samt typografi med både serift och sans-serif typsnitt, i kombination med layout och mängden bilder gör att jag överlag anser att sidan når upp till de intentioner skaparen haft, dock med tveksamheter med färgvalet på "About"-sidan.

---

### Sida 2 - François-Xavier Manceau

#### Färger

<table style="border-spacing: 4px; border-collapse: separate">
<tr><th>Färg</th><th>Typ</th><th>Färgkod</th></tr>
<tr>
<td style="height: 50px; width: 50px; background-color: #f3f2f1"></td>
<td>Primär</td>
<td>#f3f2f1</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #385245"></td>
<td>Sekundär</td>
<td>#385245</td>
</tr>

</table>

Typ av färgschema:

Komplementär, med en basfärg och ett komplement.

Oklart vilken som är primärfärg, möjligen den ljusgråa eftersom den används som bakgrund på föstasidan.

Kontrast

- Inga anmärkningar varken i automatiskt eller manuellt test.
- Ratio 7.63:1

**Noteringar:**

- Färgerna används till allt men inverterat, menyn har grön bakgrund och ljusgrå text

#### Typsnitt

| Användning | Namn | Typ |
|------------|------|-----|
| body       | Founders Grotesk | Sans Serif |
| H1         | PP Mori | Sans-Serif |
| H2         | PP Mori | Sans-Serif |

**Noteringar:** 

- code/pre: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace
- H3-H5 är definierade i CSS men ser inte ut att användas på sidan

#### Bilder

<div class="col-flex-container">
<div class="row">
    <div class="col-flex-content">
    <a href="../assets/img/reports/francoisxaviermanceau_full-w1294.jpg" aria-label="länk till bild på förstasidan francoisxaviermanceau.com"><img src="../assets/img/reports/francoisxaviermanceau_full-w250.jpg" alt="bild på förstasidan francoisxaviermanceau.com"></a>
    <p>Första sidan</p>
    </div>
    <div class="col-flex-content">
    <p></p>
    <a href="../assets/img/reports/francoisxaviermanceau_full-about-w1294.jpg" aria-label="länk till bild på about-sidan francoisxaviermanceau.com"><img src="../assets/img/reports/francoisxaviermanceau_full-about-w250.jpg" alt="bild på about-sidan francoisxaviermanceau.com"></a>
    <p>"About"</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/francoisxaviermanceau_full-product-w1294.jpg" aria-label="länk till bild på projektsida francoisxaviermanceau.com"><img src="../assets/img/reports/francoisxaviermanceau_full-product-w250.jpg" alt="bild på projektsida francoisxaviermanceau.com"></a>
    <p>Exempel på projektsida</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/francoisxaviermanceau_full-menu-w1294.jpg" aria-label="länk till bild på menyn francoisxaviermanceau.com"><img src="../assets/img/reports/francoisxaviermanceau_full-menu-w250.jpg" alt="bild på menyn francoisxaviermanceau.com"></a>
    <p>Menyn</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/francoisxaviermanceau.com-peekaboo.png" aria-label="länk till detaljbild francoisxaviermanceau.com"><img src="../assets/img/reports/francoisxaviermanceau.com-peekaboo.png" alt="detaljbild francoisxaviermanceau.com"></a>
    <p>Francois säger hej till den som vill kontrollera hans källkod.</p>
    </div>
</div>
</div>

#### Skaparens intentioner vs hur sidan uppfattas

Jag upplever att sidan är orimligt seg för mängden av innehåll, och att det bitvis känns som att han fokuserat på effekter istället för funktion, typografin lämnar lite frågetecken, så trots utmärkt färgval anser jag att han inte riktigt når fram med sitt budskap.

---

### Sida 3 - Lu Yu

#### Färger

<table style="border-spacing: 4px; border-collapse: separate">
<tr><th>Färg</th><th>Typ</th><th>Färgkod</th></tr>
<tr>
<td style="height: 50px; width: 50px; background-color: #9a42ff"></td>
<td>Primär</td>
<td>#9a42ff</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #CBA5EA"></td>
<td>Sekundär</td>
<td>#CBA5EA</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #090809"></td>
<td>Bakgrund</td>
<td>#090809</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #2c2c30"></td>
<td>Bakgrund, sekundär</td>
<td>#2c2c30</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #717073"></td>
<td>Text (p)</td>
<td>#717073</td>
</tr>

<tr>
<td style="height: 50px; width: 50px; background-color: #ffd300"></td>
<td>Accent/komplement</td>
<td>#ffd300</td>
</tr>

</table>

Typ av färgschema:

Monokromatiskt alternativt analogt

Använder en lila samt nyanser av den. Använder huvudsakligen väldigt mörka gråa som bakgrundsfärger.
Finns även en gul som används som rubrikfärg på en del projektsidor.

Kontrast

- Både första och "About"-sidan går igenom det automatiska testet.
- Vid manuell kontroll av kombinationen som används på "About"-sidan blir det ej godkänt på allt utom stor text, som endast klarar AA-kraven.
- Ratio 4.06:1

#### Typsnitt

| Användning | Namn | Typ |
|------------|------|-----|
| body       | Open Sans | Sans Serif |
| p, a       | patron | Sans Serif |
| H1         | Cosi Azure | Serif |
| H2         | Cosi Times | Serif |

**Noteringar:** 

- code/pre: Courier New, monospace
- Det finns ingen tydlig H1-H6 struktur, rubriker är placerade i div samt span-element

#### Bilder

<div class="col-flex-container">
<div class="row">
    <div class="col-flex-content">
    <a href="../assets/img/reports/luyu_full-w1294.jpg" aria-label="länk till bild på förstasidan luyu.co"><img src="../assets/img/reports/luyu_full-w250.jpg" alt="bild på förstasidan luyu.co"></a>
    <p>Första sidan</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/luyu_full-about-w1294.jpg "aria-label="länk till bild på about-sidan luyu.co"><img src="../assets/img/reports/luyu_full-about-w250.jpg" alt="bild på about-sidan luyu.co"></a>
    <p>"About"</p>
    </div>
    <div class="col-flex-content">
    <a href="../assets/img/reports/luyu_full-product-w1294.jpg" aria-label="länk till bild på projektsida luyu.co"><img src="../assets/img/reports/luyu_full-product-w250.jpg" alt="bild på projektsida luyu.co"></a>
    <p>Exempel på projektsida</p>
    </div>
</div>
</div>


#### Skaparens intentioner vs hur sidan uppfattas

Sidan anses generellt vara en bra portfoliosida där skaparen på ett tydligt strukturerat sätt visar sina färdigheter, dock med några reservationer kring färgvalet. 

## Analys

**Sara**

En viss kreativ frihet verkar ha tagits med färgvalet, då de två färgerna inte riktigt stämmer in på något färgschema. Färgerna är inte motsatta, och de är inte heller precis intill varandra på färghjulet.

Det är riskabelt att använda färger utanför de "etablerade" scheman som finns, eftersom risken är stor att resultatet ser ut som en 80-tals explosion [1, s. 75]. 
Färgerna är i det här fallet så pass nära varandra och nedtonade så kontrasten blir inte för stor, utan upplevs mer som behaglig.

Den gula nyansen gör att den upplevs som positiv, utan att vara påträngande som en mer traditionellt gul kan vara [1, s. 55].
Den rödbruna upplevs som lite mer sofistikerad, men även varm och mysig. 

Att hon tycks valt att ha ett längre textstycke, brödtexten på sidan, som ett H2-element kan jag tycka är lite märkligt.
Eftersom de även är till för tillgänglighet blir det med all sannolikhet inte någon trevlig upplevelse för någon med exempelvis en skärmläsare.

> Headings communicate the organization of the content on the page. Web browsers, plug-ins, and assistive technologies can use them to provide in-page navigation.
>
> [2]

Typsnitten fungerar bra ihop och är lätta att läsa i flera storlekar. Det serifa typsnittet Orpheus Pro ger en sofistikerad och något retro känsla, möjligen eftersom det är baserat på två typsnitt från 1920-talet [3]. Det sans-serifa typsnittet (Acumin pro wide) är lätt att läsa i alla storlekar och är inte distraherande. På något ställe används även Open Sans, men det ser ut att vara enbart på hennes namn på toppen av sidan, så det är oklart om det är medvetet eller ej.

**Francois** användning av en gråaktig färg upplevs som neutral och lugn. Att det inte är en "riktig grå" (som en av mina tillfrågade döpte den till) gör att den skapar lite mer liv i sidan. Färgen är på den orange skalan och upples därför som varmare än om den varit på exemplevis den blåa.

Den grön-blåa färgen upplevs som naturlig, den blåa nyansen bidrar med känslor av intelligens och lugn [1, s. 56] och den gröna kan symbolisera stabilitet [1, s. 56]. Färgen bidrar även med mer djup än den andra gråaktiga.

Tillsammans kan dessa färger skapa en balans mellan lugnet och enkelheten i den ljusgråa tonen och djupheten i den grönblå.
Det är en kontrast som är visuellt behaglig.
Kombinationen är dessutom lyckad eftersom färgerna kan användas som både förgrundsfärg och bakgrundsfärg.

De lugna färgerna bidrar till att ta uppmärksamhet från uppfattningen om att sidan är något seg och frustrerande att använda.

Det är två ganska lika typsnitt som valts till sidan, två sans serifer (Founders Grotesk och PP Mori), och när de används i så pass stora storlekar är skillnaden mellan dem inte så jättetydlig. 
Det skapar ingen större kontrast, och när jag tittade på sidan första gången kunde jag inte riktigt sätta fingret på vad det var som inte stämde. Den lilla skillnaden som finns mellan dem skapar en ganska obehaglig balans [1, s. 154] - detta var dock inte något de jag konverserade med tänkte på. 

Francois skriver på sin "About"-sida att han inspireras av musik och dess rytm. Rytmen på sidan med blandningen av storlekar och placering känns inte så lugn, men det är ju en *rytm*.
Den kanske stämmer överens med musiken han lyssnar på, tyckte det var lite roligt att se att han hämtar vilken låt som  han lyssnar på för tillfället. Så huruida detta faktiskt fyller en funktion eller bör räknas in som ytterligare dekoration (likt muspekaren) är något otydligt. 

**Lu** använder mestadels mörkgråa toner, så för analysens skull fokuserades det på den lila som kan anses vara huvudfärg.

Huvudfärgen är en färgrik lila som kan väcka känslor av kreativitet och fantasi. Lila har också historiska kopplingar till kungligheter och lyx, vilket kan ge en känsla av överflöd.
[1, ss. 57-58]

Det för mig in på valet av en roterande, skinande logotyp. Det var oväntat och det första jag noterade och jag kan inte riktigt bestämma mig för om det är ett bra val - det sticker verkligen ut. 
För mig krockar det förmodligen för att logotypen är tredimensionell och rörlig, vilket är en stark kontrast till den annars väldigt platta designen på sidan.

Lu skriver dock på sin "About"-sida att hon inte gillar att sätta utseende framför funktion:

> "Everything I make should always look nice and intentional. I don't believe in settling on design because of function or doing something because it looks good."

Med det i åtanke undrar jag över valet att ha så dålig kontrast mellan textfärg och bakgrund - är det ett medvetet val?
Jag är även tveksam till valet av en gul färg som rubrikfärg på exempelvis vissa projektsidor, eftersom bilderna är så färgrika känns det något överväldigande och onödigt med det färgbytet. Möjligen hade det varit klokare att konsekvent använda sig av lila även där. 

Rubrikerna använder två olika men väldigt lika serifa typsnitt (Cosi Azure och Cosi Times), och de är stora och tydliga. Att de är lite "kaotiska" i sin utforming gör inte så mycket eftersom de används konsekent som rubriker, och inte i någon längre text. Detta skapar en intressant och livfull kontrast till det ganska enkla och avskalade sans-serifa (patron) typsnitt som använts.

Generellt använder samtliga sidor ganska få färger, de satsar istället på att ha stora och färgglada bilder. Detta är ganska logiskt eftersom det är de olika projekten som är det egentliga fokuset. Dock upplevs Saras sida som lugnast och enklast att följa, det finns en naturlig rytm i flödet på sidan. Lu och Francois har rytm på sina sidor, men de har element som bryter av något vilket kan uppleva störa helheten i sidans layout. [1, s. 25] 

Jag upplever inga större skillnader i känsla eller val av typsnitt baserat på geografiska skillnader utan det verkar mest vara trender inom branschen som gäller.  

## Referenser

[1] J. Beaird och J. George, _The principles of beautiful web design_, Third edition. Collingwood, Australia: SitePoint, 2014.

[2] W. W. A. I. (WAI), “Headings,” Web Accessibility Initiative (WAI), https://www.w3.org/WAI/tutorials/page-structure/headings/ (hämtad Nov. 21, 2023).

[3] “Orpheus from Canada type,” Orpheus | Adobe Fonts, https://fonts.adobe.com/fonts/orpheus#recommendations-section (hämtad Nov. 24, 2023). 

## Övrigt

Rapporten är skriven av Kamilla Persson.