Undersökning av webbplatsers färgpaletter
=========================================
Den här rapporten undersöker och utvärderar färgpaletterna och typografin
på tre olika webbsidor.


Urval
-----------------------
Jag valde att undersöka kategorin personliga webbplatser, alltså
webbplatser som är byggda av, för och om en enskild person.

Urvalet
gjordes genom en sökning på "blog" i min webbläsarhistorik,
där de tre webbplatserna med högst antal besök (i min historik) valdes
ut, efter att webbplatser som inte lämpar sig för undersökningen
exkluderats. Webbplatserna som exkluderades var företagsbloggar,
bloggar byggda med allmänna bloggplattformar (som alltså inte har
personlig design) och bloggar där ingen design alls har gjorts.

Urvalet gav dessa artiklar och bloggar att undersöka:

1. *PHP: a fractal of bad design* av Evelyn Woods:
   https://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/

2. *Angular is Rotten to the Core* av Max Battcher:
   https://blog.worldmaker.net/2021/06/26/angular/

3. Blogg tillhörande Charles Petzold:
   https://www.charlespetzold.com/blog/


Metod
-----------------------
En skärmdump på varje webbsida togs i Firefox version 102.4.0esr på Debian 11.
Färgvärden extraherades med inspector-panelen i Firefox utvecklarverktyg
för texten och med color picker-verktyget i GIMP version 20.10.22 för
bilderna. För bakgrundsbilderna användes alternativet *sample average* med
radius 20.

Standardinställningarna för relevanta färger kontrollerades förutom i Firefox
också i Chromium version 107.0.5304.87.

För att lokalisera färgerna på färghjulet användes
[Adobe Color][adobe] genom att ange färgerna
att undersöka i custom-läget.

Vilka typsnitt som angivits för brödtext och de första tre nivåerna
av rubriker kontrollerades med hjälp av inspector-panelen i Firefox
och vilket som faktiskt tillämpats (som kan ses på skärmdumpen)
kontrollerades med hjälp av fonts-panelen.

Kontrast och läsbarhet kontrollerades genom okulärbesiktning.


Resultat
-----------------------

### Webbsida 1 (Evelyn Woods)
![Skärmdump på webbsida 1](%assets_url%/img/screenshot-woods-640.png)

Tabellen nedan visar de huvudsakliga färgerna som används på webbsidan.

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 25px; width: 50px; background-color: #1e2530">
<td>Sidans bakgrund (runt kanterna)</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #f3ead7">
<td>Menyns bakgrund</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #f7f6f2">
<td>Artikeltextens bakgrund</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #cfddf3">
<td>Logotyp</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #4078cf">
<td>Länktext</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #9740cf">
<td>Besökta länkar</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #202020">
<td>Rubriker</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #d6aa6d">
<td>Tecknad kanin</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #f5c1eb">
<td>Kaninens rosett</td>
</tr>
</table>

Webbsidan använder i huvudsak ett komplementärt färgschema bestående
av blå och beige nyanser. Som bilden nedan visar ligger de tre
bakgrundsfärgerna, länkfärgen och logotypens färg i rak linje på färghjulet.

![Färghjul för webbsida 1](%assets_url%/img/colors-woods.png)

Besökta länkar använder en färg med samma lightness och saturation
som färgen för icke besökta länkar men med ett annat färgvärde (hue).

Eftersom beige används för själva innehållet skulle de blå färgerna
kunna betraktas som accentfärger.

Typsnitten som används är serifftypsnitten *Merriweather* för brödtexten och
*Lusitana* för rubrikerna, i båda fallen med fallback till *serif*. Båda
typsnitten laddas från Google Fonts och är därför också de faktiska
typsnitt som syns på skärmdumpen.

Enligt [tabellen över förmodade färgassociationer][color-meanings]
skulle orange och brun kunna betyda "warm" medan blå skulle kunna
betyda "peaceful".
Detta verkar lämpligt för en blogg som vill ge möjlighet till avslappnad
läsning.

Typografin ger god läsbarhet och ett harmoniskt intryck.


### Webbsida 2 (Max Battcher)
![Skärmdump på webbsida 2](%assets_url%/img/screenshot-battcher-640.png)

Tabellen nedan visar de huvudsakliga färgerna som används på webbsidan.

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 25px; width: 50px; background-color: #fff">
<td>Brödtext</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #000">
<td>Bakgrund</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #ff4400">
<td>Rubriker i brödtext och meny</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #ff7700">
<td>Bakgrund i menyn</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #ffcc99">
<td>Sekundär bakgrund i menyn (lcars-accent1)</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #ffeecc">
<td>Bakgrund i footer (lcars-accent2)</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #729fcf">
<td>Länkar i menyn</td>
</tr>
</table>

Som kan ses på färghjulet nedan är färgschemat inte så tydligt
komplementärt som för webbsida 1, men det ligger någorlunda nära
att vara komplementärt.

![Färghjul för webbsida 2](%assets_url%/img/colors-battcher.png)

Vilka färger som är tänkta som accentfärger indikeras av namnen
på CSS-variablerna: Bakgrundsfärgen för menylänkarna och
sidfoten kallas `lcars-accent1` respektive `lcars-accent2`.
De här namnen ger också en indikation om att designen är tänkt
att efterlikna [LCARS][lcars], användargränssnittet som används
i Star Trek.

Typsnittet som används för brödtexten serifftypsnittet
*Cormorant Garamond* med fallback
till några andra serifftypsnitt och i sista hand *serif*.
Förstahandsvalet är dock inbäddat och laddat från samma server,
så någon fallback behöver normalt inte användas.

För rubrikerna används typsnittet *Exo 2* med fallback till en serie
olika sans-serifftypsnitt och i sista hand *sans-serif*. Dessa typsnitt
bäddas inte in, varför det som syns på skärmdumpen är *Nimbus Sans*.

Enligt [tabellen över förmodade färgassociationer][color-meanings]
skulle de starka röda färgerna kunna betyda "error", "stop" och "warning"
medan den svarta färgen skulle kunna betyda "evil", "death" och "fear".
Möjligen är det vad författaren vill kommunicera i sammanhanget
för att varna för Angular, men eftersom samma färger används på hela
webbplatsen kanske det är mer troligt att rött avses syfta på "daring"
och svart på "night", vilket skulle passa ihop med Star Trek-temat.

Sidans typografi tycks vara mycket medvetet designad, med inbäddade
typsnitt och användning av CSS-regler som t.ex.
`font-variant-ligatures: discretionary-ligatures`,
`font-variant-numeric: oldstyle-nums` och
`text-rendering: optimizeLegibility`, men resultatet är svårläst,
så om `optimizeLegibility` antas indikera att målet var läsbarhet
har det inte uppnåtts.


### Webbsida 3 (Charles Petzold)
![Skärmdump på webbsida 3](%assets_url%/img/screenshot-petzold-640.png)

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 25px; width: 50px; background-color: #fff">
<td>Brödtextens bakgrund* och titeltext</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #000">
<td>Brödtext* och bakgrund för titel</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #0000ee">
<td>Länktext*</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #000040">
<td>Rubriker (h2)</td>
</tr>
<tr>
<td style="height: 25px; width: 50px; background-color: #008000">
<td>Textfärg för valt menyalternativ</td>
</tr>
</table>

\* Färger markerade med asterisk är inte uttryckligen angivna utan
   använder webbläsarens standardvärden. Färgerna i tabellen och
   på skärmdumpen är standardinställningen i både Firefox och Chromium.

Som färghjulet nedan indikerar är det inte tydligt vilken
typ av färgschema
som används, men det skulle kunna betraktas som huvudsakligen blått
(rubrikfärgen är mycket mörkt blå) med en grön accentfärg,
vilket möjligen kan ses som ett analogt färgschema, beroende på
huruvida blå och grön ses som närliggande färger.

![Färghjul för webbsida 3](%assets_url%/img/colors-petzold.png)

Typsnittet som är angivet för brödtexten och för rubrikerna (h2)
är *Segoe UI* med fallback
till *Tahoma*, *Geneva*, *Verdana* och slutligen *sans-serif*. Typsnitten
bäddas inte in och inget av dem finns installerat på Debian-systemet som
användes för undersökningen, varför sans-serifftypsnittet *DejaVu Sans*
är det som syns på skärmdumpen.

För sidtiteln används ett serifftypsnitt. Det som är angivet är
*Cambria* med fallback till *Cochin*, *Georgia*, *Times*, *Times New Roman*
och slutligen *serif*. Inte heller dessa bäddas in, så det som tillämpas
och syns på skärmdumpen är *Nimbus Roman*.

Enligt [tabellen över förmodade färgassociationer][color-meanings]
skulle vitt kunna syfta på "clean", blå på "peaceful" och grön
på "newness". Det verkar i så fall lämpligt för en blogg, där nya
saker ständigt publiceras för att läsas i lugn och ro. Det skulle dock
också kunna vara så att designen sätter funktion
framför form och att avsikten är enkelhet och läsbarhet mer än
att kommunicera någon särskild känsla.

Typografin är ändamålsenlig. Typsnittet är läsbart, texten har lämpliga
marginaler och kontrasten är god. Möjligen skulle den kunna förbättras
av större radavstånd.


Analys
-----------------------
Resultaten indikerar att mer designarbete inte nödvändigtvis är bättre
om målet är en läsbar och användbar webbsida. Woods har uppnått en design
som är behaglig och lättläst medan Battcher skapat något som (även om det
visserligen ganska bra lyckas efterlikna LCARS, vilket man får förmoda var
ett av målen) blir betydligt mer svåranvänt än Petzolds mycket mindre
designade webbsida som till stor del använder sig av standardinställningarna.


Referenser
-----------------------
* [Adobe Color][adobe]

* [Web Design - The Complete Reference, kapitel 13][color-meanings]

* [Wikipedia om LCARS][lcars]


[adobe]: https://color.adobe.com/
[color-meanings]: https://www.webdesignref.com/chapters/13/ch13-17.htm
[lcars]: https://en.wikipedia.org/wiki/LCARS


Övrigt
-----------------------
Undersökningen utförd och rapporten skriven av Henrik Tunedal.
