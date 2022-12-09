---
Title: Colors
Description: This is the color analyse page.
Template: analysis
---

Färgval och känslan en webbplats signalerar
=======================

* * *

Tre webbplatser har valts ut till att analysera färgvalet samt känslan de framhäver.

Urval
-----------------------

* * *

Urvalet för denna analys är baserat på de mest besökta webbsajterna i Sverige under 2022. Tillvägagångssättet har utförts genom en sökning på Google för att få fram Sveriges mest besökta webbsajter under 2022. Därefter valdes den första artikeln ur sökresultatet, vilket är en undersökning som SEO Bloggen gjort vid Expandtalk [1]. De webbplatser som låg i toppen var Wikipedia.org, Facebook.com, Instagram.com Ica.se samt Youtube.com. Då Facebook och Instagram kräver inloggning för att få ta del av hela sajten har ett val gjorts om att inte ta med dem i denna analys. De tre webbplatserna som slutligen valts ut till denna analys är Wikipedia.org, Ica.se samt Youtube.com.

Metod
-----------------------

* * *

Jag har använt mig av <em>verktyget för webbutvecklare</em> när jag letat efter specifika färger och fonter som webbplatserna använder sig av. 

För webbplatserna Wikipedia och Ica fanns det tydliga hex-koder för färgerna som används, direkt i css-koden innanför inspektören. Youtubes webbplats använder sig av variabler som var satta i rgb-koder. För att då få fram hex-koden lade jag in rgb-koden i Googles sökfält som sedan genererade en hex-kod. Jag ville få fram hex-koderna på färgerna för att kunna använda Adobe Color:s webbplats [2] till att få fram ett färghjul av de insamlade färgerna för webbplatsen. Detta gör det mer intressant vid analys och diskussion av webbplatserna då regeln för färgharmonin enklare kan visualiseras och diskuteras.

Samtliga webbplatsers valda typsnitt är även där inhämtade genom <em>verktyget för webbutvecklare</em>. Jag har då markerat rubriker, titlar, brödtext eller andra fonter som sticker ut för att undersöka i css-koden vilka fonter som används.

Resultat
-----------------------

* * *

### 1. Wikipedia.org

<div class="imgdiv">
    <img src="%base_url%/image/wikipedia.png?save-as=jpg&w=100%" alt="Screenshot Wikipedia">
</div>

Wikipedias webbplats är till största delen designad med färgerna vitt och blått. Den grundläggande färgpoletten består av färgerna blått, svart och vitt, vilket utger ett monokromt färgschema.

Jag anser att Wikipedias färgval stämmer ganska bra överens med den känslan de vill uppnå från användaren, vilket jag tror är enkelhet och förtroende.

<div class="colordiv">
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #a7d7f9">
            <td style="height: 50px; width: 50px; background-color: #202122">
            <td style="height: 50px; width: 50px; background-color: #f8f9fa">
            <td style="height: 50px; width: 50px; background-color: #0645ad">
        </tr>
    </table>
    <div class="imgdiv-smaller">
        <img src="%base_url%/image/wikipedia-colorwheel.png?w=100%" alt="Färghjul Wikipedia">
    </div>
</div>

Accentfärgerna som uppmärksammats på Wikipedias webbplats är i ett ljusare analogt färgschema. 

<div class="imgdiv">
    <img src="%base_url%/image/wikipedia-accent.png?save-as=jpg&w=100%" alt="Screenshot Wikipedia Accentfärg">
</div>

<div class="colordiv">
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #f8eaba">
            <td style="height: 50px; width: 50px; background-color: #cef2e0">
            <td style="height: 50px; width: 50px; background-color: #cedff2">
            <td style="height: 50px; width: 50px; background-color: #ddcef2">
            <td style="height: 50px; width: 50px; background-color: #ffdbdb">
        </tr>
    </table>
    <div class="imgdiv-smaller">
        <img src="%base_url%/image/wikipedia-colorwheel-accent.png?w=100%" alt="Färghjul Wikipedia Accentfärg">
    </div>
</div>

#### Typografi

Det verkar som om Wikipedia använder sig av en default font-family satt i sans-serif nästan överallt på webbplatsen. Det finns inget namn på just den fonten utifrån informationen hämtad från <em>verktyget för webbutvecklare</em>. Den font som sticker ut på Wikipedias webbplats är titlarna där font-familjen "Linux Libertine, Georgi, Times, serif" används.

### 2. Ica.se

<div class="imgdiv">
    <img src="%base_url%/image/ica.png?save-as=jpg&w=100%" alt="Screenshot Ica">
</div>

Icas webbplats består till största delen av färgerna vit och ljusbeige samt en svart-liknande färg för typografin. Accentfärgen som uppmärksammats är den gröna färgen #2f6147 som bland annat används till att förstärka rutan under recept-sidorna där tid, ingredienser och svårighetsgrad visualiseras.

Utifrån färgschemat skapat med Adobe Color visas tydligt hur en komplement-färg-polett valts ut där den gröna accentfärgen har valts i motsatt riktning till resterade färger.

Jag anser att Ica lyckats bra med att framhäva den profil de vill åt med hjälp av färg och typografival, vilket jag tror är lyx, nytt och fräscht men samtidigt en profil av förmånliga priser.

<div class="colordiv">
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #e13205">
            <td style="height: 50px; width: 50px; background-color: #3a3a3a">
            <td style="height: 50px; width: 50px; background-color: #f9f5f5">
            <td style="height: 50px; width: 50px; background-color: #9b0600">
            <td style="height: 50px; width: 50px; background-color: #2f6147">
        </tr>
    </table>
    <div class="imgdiv-smaller">
        <img src="%base_url%/image/ica-colorwheel.png?w=100%" alt="Färghjul Ica">
    </div>
</div>

#### Typografi

Typsnittet som används på Icas webbplats för brödtext, rubriker och titlar är ett samspel av flera font-familjer i samma font-familj-regel. Dessa samspelade font-familjer är "Arial, Helvetica Neue, Helvetica" som alla är applicerade på samtliga fonter på webbplatsen. Det som skiljer fonterna åt är Icas egna typsnitt. För brödtext används "Ica text", för rubriker används "Ica rubrik" och för handstilsliknande-skriva texter används "Ica hand". Samtliga fonter på webbplatsen är satta i en sans-serif.

### 3. Youtube.com

<div class="imgdiv">
    <img src="%base_url%/image/youtube.png?save-as=jpg&w=100%" alt="Screenshot Youtube">
</div>

Youtube:s webbplats är överlägset designad av färgerna vitt och ljusgrått samt svart till typografin. Accentfärgerna som uppmärksammats är en stark röd färg samt en stark blå färg. Den röda färgen används bland annat i samtliga av Youtube:s olika logotyper samt för att visa om någonting är livesänt. Den blå färgen används exempelvis till att framhäva länkar eller hashtags.

Färgschemat som Youtube använder sig är en triad färgpolett där grundfärgerna hämtas upp i mitten av färghjulet samt att de båda accentfärgerna är hämtade längst ut på sidorna.

Jag anser att Youtube har lyckats helt okej med färger och typografin för att motsvara den profil de vill åt, vilket jag tror är enkelhet och en känsla av struktur.

<div class="colordiv">
   <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #f2f2f2">
            <td style="height: 50px; width: 50px; background-color: #065fd4">
            <td style="height: 50px; width: 50px; background-color: #ff0000">
            <td style="height: 50px; width: 50px; background-color: #0f0f0f">
            <td style="height: 50px; width: 50px; background-color: #f0f0f0">
        </tr>
    </table>
    <div class="imgdiv-smaller">
        <img src="%base_url%/image/youtube-colorwheel.png?w=100%" alt="Färghjul Youtube">
    </div>
</div>

#### Typografi

Youtube:s webbplats använder sig av Roboto tillsammans med Arial för brödtexten samt rubriker. Titlarna på webbplatsen använder Youtube:s egna font, Youtube Sans, tillsammans med Roboto. Samtliga fonter är satta i en sans-serif.

Analys
-----------------------

* * *

Vid analys av dessa tre webbplatser: Wikipedia.org, Youtube.com samt Ica.se uppkom en rad intressant information. Samtliga webbplatser använde sig av tydliga färgscheman, vilket som användare kan vara svårt att uppmärksamma vid besök av webbplatsen utan djupare undersökning. 

Den webbplats som använder sig av det mest tydliga och genomtänkta färgschemat är Ica utifrån färghjulet skapat med Adobe Color. Samt att bilderna som finns på Ica:s webbplats är väl anpassade för färgschemat då de valt att öka kontrasten i bilderna för att få fram starkare färger som matchar färgpoletten för webbplatsen. 

Wikipedia har valt att använda sig av en stark blå färg för att framhäva länkar eller ord på sin webbplats. Dock blir texterna på Wikipedia relativt svårlästa eftersom det är så pass många ord som är framhävda, vilket gör att det försvårar läsflödet. Svårt att veta vad som är en bra lösning ifall länkarna bör sättas som en lista i slutet av brödtexten eller att framhäva länkarna på annat vis i brödtexten, som till exempel med hjälp av ett understäck. Wikipedia:s val av typsnitt på sin webbplats känns lite trist och ogenomtänkt. 

Youtube använder sina accentfärger något för lite då webbplatsen nästan ser lite platt ut. Den blå accentfärgen hade kunnat framhävas lite mer. I övrigt ser webbplatsen ren och fräsch ut.

Sammanfattningsvis har samtliga tre webbplatser lyckats relativt bra med att framhäva färger som fungerar tillsammans samt att typografin är väl genomtänkt.

Referenser
-----------------------

* * *

[1] SEO Bloggen. (9 jan 2022). Sveriges största webbsajter 2022. https://expandtalk.se/sveriges-storsta-webbsajter-2022/

[2] Adobe Color. https://color.adobe.com/sv/create/color-wheel#

Övrigt
-----------------------

* * *

Av: Karoline Lindroos 26/11/2022