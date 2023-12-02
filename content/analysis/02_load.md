---
Title: kmom05 - Utvärdera webbplatsers laddningstid och användbarhet
Description: kmom05
---

# kmom05

Syftet med den här uppgiften är att utvärdera och analysera tre webbplatsers laddningstid och användbarhet.

## Urval

Jag har använt samma sidor från föregående kmom. Läs mer detaljerat om [urvalsprocessen här](01_colors#urval).

Webbplatserna som valts ut för undersökningen är dessa:
1. Designer & Art Director, Sverige [Sara Svensson](https://sarajuliasvensson.com/)
2. Creative developer, Frankrike [François-Xavier Manceau](https://francoisxaviermanceau.com)
3. Independent Interactive & Graphic Designer, Tyskland [Lu Yu](https://luyu.co/)

Förutom första sidan på varje webbplats kommer även dess "About"-sida samt en projektsida att undersökas. Dessa finns länkade i kalkylarket.

Föregående kmom fokuserade inte på laddningstider, men jag upplevde skillnader i sidornas snabbhet och vill undersöka följande:

Är Francois sida så seg som den upplevdes, eller känns den segare på grund av laddningsskärmen?

Har Sara och Lu liknande laddningstider eftersom de båda använder Wordpress, och såvitt jag kan se, samma tema?

## Metod

Jag använder två verktyg för att få mina mätresultat.

### PageSpeed Insights

[PageSpeed Insights](https://pagespeed.web.dev/)

Följande görs för resultat på både mobil och dator:
- Skriver ner betyget för prestanda i Google Sheets för samtliga tre sidor som kontrolleras
- Noterar gula samt röda resultat från möjligheter och diagnostik om sådana finns, endast för första sidan

### Chrome DevTools
- laddar sidan en första gång, noterar resultat från Nätverksfliken
- laddar om sidan med SHIFT + CTRL + R för att säkerställa att ingen sparad information ligger kvar
- noterar återigen resultaten
- laddar om sidan med SHIFT + CTRL + R
- noterar tredje omgångens resultat

Laddningstid noteras i sekunder, räknar även ut genomsnitt samt skriver ut resultatet med två decimaler.

Sidans storlek noteras i MB.

Utöver detta används Google Kalkylark för att skriva ner resultaten.

## Resultat

### PageSpeed

Prestanda (sämsta värdet fetmarkerat):

|                    | PageSpeed (mobil) | PageSpeed (dator) |
|--------------------|-----------------------------|-----------------------------|
| Sara               | 83                          | 95                          |
| Francois           | 83                          | 99                          |
| Lu                 | **57**                      | **69**                      |
| Sara (about)       | 76                          | 97                          |
| Francois (about)   | **51**                      | 83                          |
| Lu (about)         | 53                          | **60**                      |
| Sara (projekt)     | 78                          | 94                          |
| Francois (projekt) | 54                          | **80**                      |
| Lu (Projekt)       | **37**                      | 84                          |

### Chrome DevTools

Enbart genomsnitt, sorterat efter typ av sida (sämsta värdet fetmarkerat):

|                    | Laddningstid (s) | Antal resurser | Sidans storlek (MB) |
|--------------------|------------------|----------------|---------------------|
| Sara               | 1.53             | 30             | 2.4                 |
| Francois           | 1.52             | 37             | 1.6                 |
| Lu                 | **13.49**            | **67**             | **14.4** |
| Sara (about)       | 0.92             | 27             | 1.6          |
| Francois (about)   | 1.69             | 38             | 1.6          |
| Lu (about)         | **5.83**             | **43**             | **5.4**  |
| Sara (projekt)     | 1.64             | 31             | 2.3          |
| Francois (projekt) | **78.41**        | 49             | **74.53**        |
| Lu (Projekt)       | 6.19             | **56.33**          | 6.87     |

Hela resultatsetet:

<div class="embed-container">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQONY1xVUboVm2XQFvXj67vGMWwJasBtJalCZ1RIb__DPNO4VuNGcUi7tN2TBOt4HJQnK1wwxDEDPwp/pubhtml?gid=1873021622&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

### Sida 1 - Sara Svensson

<div class="col-flex-container">
    <div class="row">
    <div class="col-flex-content">
        <a href="%assets_url%/img/reports/sarajuliasvensson.com_01.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/sarajuliasvensson.com_01.png?h=250&w=250&crop-to-fit&area=0,0,80,0" alt="startsidan sarajuliasvensson.com">
        </picture>
        </a>
        <p class="italic">Första sidan</p>
    </div>
    <div class="col-flex-content">
        <a href="%assets_url%/img/reports/sarajuliasvensson.com_project_inside-the-head-duplicate.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/sarajuliasvensson.com_project_inside-the-head-duplicate.png?h=250&w=250&crop-to-fit&area=0,0,80,0" alt="projektsida sarajuliasvensson.com">
        </picture>
        </a>
        <p class="italic">Projektsida</p>
    </div>
    </div>
</div>


Saras sida laddar snabbt jämfört med de andra två, även om startsidan är precis bakom Francois (1.53s vs 1.52s).
Möjliga förbättringar på den här sidan är i stort sett samma både på mobil och dator. De främsta är att använda bilder i rätt storlek, att använda modernare bildformat samt ta bort resurser som blockerar renderingen, som exempelvis att skjuta upp inläsningen av JavaScript-kod som inte är nödvändig för sidans funktionalitet. På mobil föreslås det även att reducera JavaScript som inte används.


---

### Sida 2 - François-Xavier Manceau

<div class="col-flex-container">
    <div class="row">
        <div class="col-flex-content">
        <a href="%assets_url%/img/reports/francoisxaviermanceau.com_.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/francoisxaviermanceau.com_.png?h=250&w=250&crop-to-fit" alt="startsidan francoisxaviermanceau.com">
        </picture>
        </a>
        <p class="italic">Första sidan</p>
    </div>
    <div class="col-flex-content">
        <a href="%assets_url%/img/reports/francoisxaviermanceau.com_projects_digital-work_keepgrading.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/francoisxaviermanceau.com_projects_digital-work_keepgrading.png?h=250&w=250&crop-to-fit&area=0,0,80,0" alt="projektsida francoisxaviermanceau.com">
        </picture>
        </a>
        <p class="italic">Projektsida</p>
    </div>
    </div>

</div>

Första sidan är den snabbaste av samtliga testade att laddas, medan projektsidan är den absolut långsammaste. Det ser ut att vara bildernas format och hur JavaScript används som kan förbättras (minska belastningen på modertråden - minska tiden det tar att tolka, kompilera och köra JavaScript-kod). På projektsidan som är mer problematisk är det förutom JavaScript flertalet stora mp4-filer som laddas in (den största filen är på 35.2MB och tog enligt DevTools 1,8 minuter att ladda in helt).

---

### Sida 3 - Lu Yu

<div class="col-flex-container">
    <div class="row">
        <div class="col-flex-content">
        <a href="%assets_url%/img/reports/luyu.co_01.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/luyu.co_01.png?h=250&w=250&crop-to-fit&area=0,0,80,0" alt="startsidan luyu.co">
        </picture>
        </a>
        <p class="italic">Första sidan</p>
    </div>
    <div class="col-flex-content">
        <a href="%assets_url%/img/reports/luyu.co_project.png" target="_blank">
        <picture>
            <img src="%base_url%/image/reports/luyu.co_project.png?h=250&w=250&crop-to-fit&area=0,0,80,0" alt="projektsida luyu.co">
        </picture>
        </a>
        <p class="italic">Projektsida</p>
    </div>
    </div>
</div>

Lu's sida är den som presterar sämst. Bildstorlekarna och dess format kan ses över, och hon bör även överväga att använda videor i passande format istället för animerade giffar (exempelvis logotypen). Det kan även gå att förbättra laddningstiden genom att de viktiga komponenterna av sidan prioriteras så att den går att använda innan det innehåll som inte syns på sidan laddas in. 

## Analys

De vanligaste förbättringsåtgärderna är:
- Bildstorlekar och bildformat
- Sådant som stoppar rendering av sidan, exempelvis JavaScript

### Bildstorlekar och bildformat
Samtliga ser ut att främst använda JPEG. 
JPEG resulterar i mindre filstorlekar och har fördelen att komprimeringsgraden går att justera vilket inte är möjligt med PNG-bilder [2, ss. 184-185].

Sara och Lu använder Wordpress, och som nämndes i inledningen är det samma tema (Semplice). Wordpress har inbyggd hantering av responsiva bilder då de skapar olika storlekar av bilden som laddats upp av användaren [1]. Teoretiskt sett ska alltså bilderna vara anpassade till den enhet som används. Om sidan besöks via dator är det dock originalbilden som visas för användaren och möjligen kan viss optimering göas här genom att se till att originalbilden är något mindre eller har en bättre anpassad kvalitet. Om de exempelvis använder Photoshop är det väldigt enkelt att laborera med filstorlekar och kvalitet i "Save Image for Web" - kanske behöver de inte sparas i 100% kvalitet och på så sätt minskas filstorleken till originalbilden som visas.

Francois har kodat sin sida själv och använder alltså inte ett Content Management System som Wordpress. Han använder <code>srcset</code> till sina bilder, men det ser ut som att detta kan anpassas bättre. Tittar jag på sidan med en bredd av 950 pixlar är det bilder med 1440 pixlars bredd som läses in.

Samtliga kan även använda sig av de modernare bildformaten WebP eller AVIF, som har betydligt bättre förmåga att komprimera och hantera bilders kvalitet för att kunna optimera laddningstiden [3].

Lu använder några filer i GIF-format, vilket inte är att rekommendera.
GIF stöder visserligen både animering och transparens, men idag finns det bättre format att använda om animerade element önskas på en sida. Det går att använda MPEG4- eller WebM-format istället för att kunna använda animationer som inte belastar användarens nätverk i onödan [4]. Den begränsade färgpaletten (256 färger) [2, s. 185] är också en anledning att som designer inte välja GIF i första hand, då projekten med all sannolikhet hanterar betydligt fler färger än så. 

### Sådant som stoppar rendering av sidan

Samtliga sidor kan också förbättra hur de hanterar användande av skript.
Innan webbläsaren kan rendera en webbsida behöver den bygga upp DOM-trädet, vilket görs från HTML-koden. 
Om webbläsaren stöter på ett skript (som JavaScript eller CSS) i den här processen behöver den avbryta för att hantera detta och är skriptet externt behöver det även hämtas först. Det kan alltså resultera i att sidan laddas långsammare än önskat.

På grund av detta är det rekommendarat att skjuta upp inläsning av skript som inte är nödvändiga för sidans funktion, och det kan även vara bra att se till att avlägsna all kod som inte används [5].

Att inte läsa in saker direkt utan istället laddda innehållet allt eftersom sidan syns (så kallad lat inläsning) [6] verkar användas på samtliga sidor, dock verkar de ladda in en hel del resurser som inte syns vilket resulterar i att sidan är betydligt långsammare.
Det blir skillnader i fullstora skärmbilder på sidorna, Sara och Lu renderar bakgrunderna så det blir långa men tomma bilder - Francois resulterar enbart i en bild med  innehållet "above the fold", alltså enbart det som syns just då i webbläsaren [2, s. 9] - trots att allt innehåll verkar ha laddats. 

CMS som Wordpress underlättar arbetet för designers då det inte krävs några kunskaper i kodning, dessvärre väljer man ofta bort de möjligheter som finns att skräddarsy en sida på bästa sätt. Francois har fördelen att han kan styra över sina bilder exempelvis, och vilket innehåll som laddas när. Om han utnyttjar detta bättre skulle sidan bli betydligt trevligare att besöka. Jag upplever att mätresultaten stämmer väl överens med hur snabb sidan uppfattas.

Det är intressant att se att den snabbaste och långsammaste sidan båda använder Wordpress - och samma tema. Även om skaparen inte har någon kunskap kring kodning eller optimering så har Wordpress plugins till det mesta, som att konvertera uppladdade bilder till WebP [7] och optimera sidan och prioritera nödvändiga skript [8]. Sedan är det en helt annan diskussion om hur säkert och effektivt det är att använda för många plugins, men om de väljs med omsorg kan de hjälpa personen bakom webbsidan att skapa en trevligare och snabbare upplevelse.

### Testvinnare

Sara står som solklar vinnare eftersom hon inte fått sämst värde i någon av mätningarna. Sidan upplevs också som den snabbaste av de tre. 
Francois och Lu får dela på sistaplatsen, även om Lu har knep de flesta av de sämsta värdena *upplevs* Francois sida som betydligt långsammare.

### Snabb eller långsam webbplats?

Vad gör då att en webbplats upplevs som snabb eller långsam?
Jag har använt internet så pass länge att jag fortfarande kan höra ljudet av ett modem som kopplar upp sig mot nätet. Sidor laddade långsamt hur de än var kodade. Långt efter intåget av fast internetuppkppling hade jag ganska stort tålamod med laddningstider, men detta har minskats avsevärt. Efter 2-3 sekunder börjar jag fundera på vad som är fel och tappa tålamodet, så där någonstans går min gräns. 

De flesta sidorna jag testat klarar sig teoretiskt, men i praktiken är de sidorna långsammare på grund av hur enkelt det är att interagera med sidan direkt. Långsamma animationer och effekter som hos både Lu och Francois gör att sidan inte känns "färdigladdad" och skapar frustration. 

## Referenser

[1] “Responsive images: Common apis handbook,” WordPress Developer Resources, https://developer.wordpress.org/apis/responsive-images/ (hämtad Nov. 29, 2023). 

[2] J. Beaird och J. George, _The principles of beautiful web design_, Third edition. Collingwood, Australia: SitePoint, 2014.

[3] “Serve images in modern formats,” Chrome for Developers, https://developer.chrome.com/docs/lighthouse/performance/uses-webp-images/?utm_source=lighthouse&amp;utm_medium=lr (hämtad Nov. 29, 2023).

[4] “Use video formats for animated content,” Chrome for Developers, https://developer.chrome.com/docs/lighthouse/performance/efficient-animated-content/?utm_source=lighthouse&amp;utm_medium=lr (hämtad Nov. 29, 2023).

[5] “Eliminate render-blocking resources,” Chrome for Developers, https://developer.chrome.com/docs/lighthouse/performance/render-blocking-resources/?utm_source=lighthouse&amp;utm_medium=lr (hämtad Nov. 29, 2023). 

[6] P. LePage, “Responsive images,” web.dev, https://web.dev/articles/responsive-images#optimize_images_for_performance (hämtad Nov. 29, 2023). 

[7] “Showing results for: Convert webp,” Search Results for “convert webp” | WordPress.org, https://wordpress.org/plugins/search/convert+webp/ (hämtad Dec. 1, 2023). 

[8] “Showing results for: Defer CSS javascript,” Search Results for “defer css javascript” | WordPress.org, https://wordpress.org/plugins/search/defer+css+javascript/?utm_source=lighthouse&amp;utm_medium=lr (hämtad Dec. 1, 2023). 


## Övrigt

Rapporten är skriven av Kamilla Persson.