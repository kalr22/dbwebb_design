---
Title: Load
Description: This is the load analyse page.
Template: analysis
---

Olika webbplatsers laddningstid och användbarhet
=======================

Tre webbplatser har valts ut till att analysera dess laddningstid samt användbarhet.

Urval
-----------------------

Webbplatserna som valts ut till denna analys är bhphotovideo.com, hm.com samt bestbuy.com. Valet på dessa tre webbplatser landade i en sökning på Google för att få fram vilka webbplatser som klassas som de snabbaste, vilket landade i en artikel publicerad på solwarwings 2016 där de undersöker webbprestandan för väldens 50 bästa e-handelssajter [1]. I denna artikel låg bhphotovideo.com, hm.com samt bestbuy.com i toppen.

Metod
-----------------------

Analysen genomfördes med hjälp av <em>verktyget för webbutvecklare</em> samt Google Pagespeed Insights [2] härdanefter benäms som GPI. Google Sheets har använts till att dokomentera resultaten. En webbplats åt gången har analyserats och dokumenterats för både desktop och mobilversion. Mätningen har gjort på respektive webbplats startsida.

De mätvärden som ansågs intressanta från GPI var 1. Prestanda, 2. Tillgänglighet samt 3. SEO. Prestandan pekar på kapaciteten av webbplatsen. Tillgängligheten pekar på i stora drag om webbplatsens innehåll är tillgängligt och dess funktionalitet kan användas mer eller mindre av vem som helst. SEO står för Search Engine Optimization som i en kort förklaring innebär hur lätt en webbplats är att hitta utifrån sökningar på innehåll i webbsidan med exempelvis Google. Mätvärden från 0-49 klassas som "underkänt", mätvärden mellan 50-89 klassas som "behöver förbättras" och mätvärden från 90-100 klassas som "bra" [2].

Resultat
-----------------------

### Bestbuy.com

Webbplatsen bestbuy.com är en amerikansk återförsäljare av elektronikvaror. Analysen med hjälp av <em>verktyget för webbutvecklare</em> visar att sidans laddningstid är på cirka 15 sekunder. Det tar cirka 912 millisekunder(ms) för HTML-dokumentet att laddas ner fullständigt. Resurserna som används är på cirka 12.3 megabyte(mb). Begäran ligger på cirka 489. Storleken på hela sidan ligger på cirka 4.24mb varav cirka 1.83mb är bilder.

Analysen med hjälp av GPI för desktop visar att prestandan ligger på 56, vilket innebär att den ligger på skalan "behöver förbättras". Tillgängligheten ligger på 96, vilket klassas som "bra" enligt Google Pagespeed. Värdet för SEO landar på 92, vilket också klassas som "bra".

Analysen med hjälp av GPI för mobil visar att prestandan ligger på 26, vilket klassas som "underkänt". Tillgängligheten ligger på 77, vilket innebär "behöver förbättras". SEO-värdet ligger på 85, vilket även där innebär "behöver förbättras".

För att öka prestandan på bestbuy.com föreslår GPI att bestbuy kan spara flera sekunder på att minska serverns första svarstid, vilket idag ligger på cirka 3,2 sekunder. För att öka prestandan i mobilversionen kan bland annat bilderna modifieras till mer moderna bildformat samt att bilderna bör användas i den rätta storleken.

#### Snapshot Bestbuy
![Screenshot Bestbuy.com](%base_url%/image/bestbuy.png?save-as=jpg&q=100&w=500&sharpen)

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTJKGP4L8yg-w9WaPPDdR9KnnRbwRv8kE9JspnXT99QBPBLPpEsCWxMlBV1PS66JPax-wd7ziHueYUI/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

### Hm.com

Hm står för Hennes och Mauritz AB och är ett multinationelt klädesföretag baserat i Sverige. Analysen med hjälp av <em>verktyget för webbutvecklare</em> visar att webbplatsens laddningstid är på cirka 6 sekunder. Begäran ligger på 276. Antalet resurser är på 24.7mb. Webbsidans storlek är på cirka 5.3mb varav 1.1mb är bilder. Den totala tiden för HTML-dokumentet att laddas ner och parsas är på cirka 861ms.

Analysen med hjälp av GPI för desktop visar att prestandan ligger på 60, vilket innebär att den "behöver förbättras". Tillgängligheten ligger på 91, vilket klassas som "bra". SEO-värdet ligger på 83 vilket GPI klassar som "behöver förbättras".

Analysen med hjälp av GPI för mobil visar att prestandan ligger på 21, vilket klassas som "underkänt". Tillgängligheten ligger på 90, vilket klassas som "bra". SEO-värdet ligger på 83, vilket innebär "behöver förbättras".

För att öka prestandan på hm.com för både desktop- och mobilversion menar GPI att hm.com kan spara flera sekunder genom att ändra bildformatet, vilket idag är i png. Även att använda bilder i rätt storlek kan öka prestandan. För att öka SEO-värdet på hm.com bör samtliga länkar ha en beskrivande text, föreslår GPI.

#### Snapshot Hm
![Screenshot hm.com](%base_url%/image/hm.png?save-as=jpg&q=80&w=500&sharpen)

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS5fnCQ2OK90NEoUKWl6q2hQ8FfXI1CBILuzNElXGernPK4umqmChin2Rb_T4TfEGlqS_1xYX6G9lHQ/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

### Bhphotovideo.com

Webbplatsen Bhphotovideo är en amerikansk återförsäljare av foto- och videoutrustning. Analysen av webbplatsens laddningstider med hjälp av <em>verktyget för webbutvecklare</em> visade en laddningstid på cirka 2.8 sekunder. Webbplatsens storlek ligger på cirka 436 kilobyte(kb) varav 86kb är bilder. Resurserna som laddas är på cirka 7.4mb. Det tar cirka 522ms för HTML-dokumentet att laddas och parsas fullständigt. Begäran ligger på 180. 

Vid analys av webbplatsen på GPI i desktopversionen låg prestandan på 52, vilket är väldigt nära "underkänt" men den hamnar precis på skalan "behöver förbättras". Tillgängligheten får en 67 av GPI, vilket också innebär att den hamnar på skalan "behöver förbättras". SEO-värdet ligger på en 75, vilket även där "behöver förbättras". 

Vid analys av webbplatsen på GPI i mobilversionen var det endast SEO-värdet som hamnade över "bra", vilket låg på 91. Prestandan låg på 79, vilket är något högre än desktopversionen men att den fortfarande är på "behöver förbättras". Tillgängligheten fick 77 av GPI.

För att öka prestandan på bhphotovideos.com föreslår GPI att DOM-trädet bör minskas radikalt, idag har DOM-trädet cirka 3812 element vilket leder till att bland annat minnesförbrukningen ökar. För att öka tillgängligheten och SEO bör bland annat samtliga bildelement ha [alt]-attribut. För att öka prestandan på mobilversionen föreslår GPI att reducering av JavaScript-filer som inte används bör åtgärdas, vilket kan göras genom att sätta attributet async på den länkade JavaScript-filen [2].

#### Snapshot Bhphotovideo
![Screenshot bhphotovideo.com](%base_url%/image/bhphotovideo.png?save-as=jpg&q=80&w=500&sharpen)

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQwPrSJlwQ8Vpku0EGepKNRcIbEGOfdnA6zU0POhEVkBtjP-FJZLR1nkn7tv6XgcWrvfYCKB06i5vWP/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

Analys
-----------------------

De vanligaste förbättringsåtgärderna för att förbättra prestandan och tillgängligheten på webbplatsen verkar vara att ändra bildformat till ett mer modernt filformat, som WebP eller AVIF, vilket ger en bättre komprimering än PNG och JPEG. Även att se till att bilderna är i rätt storlek verkar vara en vanlig förbättringsåtgärd.  

Min ungefärliga gräns för absolut laddningstid på snabbhet ligger mellan 2-3 sekunder. Det är endast bhphotovideo.com som ligger inom ramarna för min gräns, däremot känns det som om samtliga sidor laddas snabbare än vad resultatet säger. Det kan bero på att viss HTML-innehåll laddas in även fast resten inte är på plats, vilket kan ge en falsk bild av att hemsidan är fulladdad. Däremot är det bra att någonting visas, snarare än att webbplatsen är helt vit innan webbplatsen är fullt laddad.

Resultatet för analystestet ser ut följande:

1. Bhphotovideo.com = 2.8 sek
2. Hm.com = 6 sek
3. Bestbuy.com = 15 sek

Jag är själv förvånad över att resultatet på både hm.com och bestbuy.com var ganska mycket sämre än bhphotovideo.com med tanke på att de var med i artikeln för världens snabbaste e-handelssajter. Dock var artikeln från 2016, vilket är några år sedan och mycket i webbvärlden har hänt sedan dess. Laddningstiden för webbplatserna kanske också kan bero på min internethastighet och hur snabbt min webbläsare läser in samtliga webbläsare.

Referenser
-----------------------

[1] SolarWinds Pingdom. (8 juni 2016). Web Performance of the World's Top 50 E-Commerce Sites. https://www.pingdom.com/blog/web-performance-top-50-e-commerce-sites/

[2] Pagesspeed Insight. https://pagespeed.web.dev/report?url=https%3A%2F%2Fwww.bestbuy.com%2F%3Fintl%3Dnosplash&form_factor=mobile


Övrigt
-----------------------

Av: Karoline Lindroos 02/12/2022