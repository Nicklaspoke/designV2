# Utvärdering av webbplatsers laddningstid och användarbarhet



## Urval

I mitt urval valde jag att jämföra tre olika nyhetswebbplatser.

* Aftonbladet
* SVT
* Metro

Jag valde just dessa tre för det skulle vara intressant att jämföra skillnaden på tider mellan en betaltidning som Aftonbladet, en statlig källa såsom SVT och en
gratistidning såsom Metro. Och då se hur deras kvalitet på laddningstider skiljer sig.

De tre underkategorier som valdes på varje av dessa tre nyhets webbplatser var. Startsidan, sportnyheter samt tekniknyheter.

## Metod

På varje av dessa nyhetssidorna testades följande på samma sätt. [Google pagespeed](https://developers.google.com/speed/pagespeed/insights/) kördes på varje av de 9 utvalda
sidor. Och resultatet för både mobil och desktop antecknades.
Därefter så mättes sidornas laddningstid, inkluderade resurser samt deras storlek med hjälp av devtools i webbläsaren google chrome.
Denna mätning gick till på följande sätt. Först stängdes anonsblockrande tillägg såsom adblock av. Därefter användes valet clear cache and hard reload för att försäkra sig om
att mätningarna blir korrekta, så att webbläsaren inte använder något cachat material när en omladdning annars sker.
Dessa mätningar gjordes tre gånger per sida. Resultaten antecknades och sedan togs ett medelvärde ut för var och en av kategorierna som mättes.

Mätningarna gjordes över ett trådlöst nätverk med en nedladdningshastighet på ca 63 Mbps.

## Resultat

[Fullständig data för alla mätningar kan hittas i detta google spreadsheet](https://docs.google.com/spreadsheets/d/1GNQHy_3bcqo_PNaIZqh9tqwWy5cAFRf-NEgRpiosN8w/edit?usp=sharing)

## Aftonbladet

### [Startsidan](https://www.aftonbladet.se/)

[FIGURE src=image/kmom05-report/Aftonbladet-Startsida.png?width=720 caption="Aftonbladet fig 1"]

Värderna som denna sida fick var

* Google pagespeed:
    * Mobil: 59
    * Desktop: 89

* Devtools Mätresultat:
    * Laddningstid: 7,58s
    * Inkluderade resurser: 182
    * Storlek på sidan: 4,70MB

### [Sportnyheter](https://www.aftonbladet.se/sportbladet)

[FIGURE src=image/kmom05-report/Aftonbladet-Sporten.png?width=720 caption="Aftonbladet fig 2"]

* Google pagespeed:
    * Mobil: 50
    * Desktop: 97

* Devtools Mätresultat:
    * Laddningstid: 8,77s
    * Inkluderade resurser: 218
    * Storlek på sidan: 8,33MB

### [Tekniknyheter](https://www.aftonbladet.se/teknik)

[FIGURE src=image/kmom05-report/Aftonbladet-Teknik.png?width=720 caption="Aftonbladet fig 3"]

* Google pagespeed:
    * Mobil: 65
    * Desktop: 100

* Devtools Mätresultat:
    * Laddningstid: 5,25s
    * Inkluderade resurser: 146
    * Storlek på sidan: 2,95MB

### Överlag för webbplatsen
Man kan se i överlag för de tre mätta sidorna på denna webbplats. Att medans alla tre sidor har ett ganska dåligt resultat på sin pagespeed i mobil version. Så har webbplatsen
ett bra resultat när det gäller sin desktop version av webbplatsen. Då alla tre mätta sidor fick en poäng över på 89 eller högre. Denna webbplats skulle kunna förbättra sig
genom att minska antalet resurser som inkluderas vid nedladdning.

Ett medelvärde på alla tre sidors resultat blev:

* Google pagespeed:
    * Mobil: 58
    * Desktop: 95,33

* Devtools Mätresultat:
    * Laddningstid: 7,20s
    * Inkluderade resurser: 182
    * Storlek på sidan: 5,33MB

## SVT

### [Startsidan](https://www.svt.se/)

[FIGURE src=image/kmom05-report/SVT-Startsida.png?width=720 caption="SVT fig 1"]

* Google pagespeed:
    * Mobil: 46
    * Desktop: 97

* Devtools Mätresultat:
    * Laddningstid: 3,30s
    * Inkluderade resurser: 119
    * Storlek på sidan: 2,40MB

### [Sportnyheter](https://www.svt.se/sport/)


[FIGURE src=image/kmom05-report/SVT-Sporten.png?width=720 caption="SVT fig 2"]

* Google pagespeed:
    * Mobil: 51
    * Desktop: 99

* Devtools Mätresultat:
    * Laddningstid: 2,99s
    * Inkluderade resurser: 81
    * Storlek på sidan: 1,70MB

### [Tekniknyheter](https://www.svt.se/nyheter/vetenskap/)

[FIGURE src=image/kmom05-report/SVT-Teknik.png?width=720 caption="SVT fig 3"]

* Google pagespeed:
    * Mobil: 54
    * Desktop: 86

* Devtools Mätresultat:
    * Laddningstid: 2,49s
    * Inkluderade resurser: 46
    * Storlek på sidan: 1,10MB

### Överlag för webbplatsen

Man kan se i överlag för de tre mätta sidorna på denna webbplats. Att medans denna webbsida fick ett dåligt resultat på sin mobil version i pagespeed med lägsta resultat på 46
och högsta på 66. Så fick denna webbplats ett väldigt bra och högt resultat på sin desktop version med ett lägsta resultat på 97 och ett högsta resultat på 100.

Ett medelvärde på alla tre sidors resultat blev:

* Google pagespeed:
    * Mobil: 53,67
    * Desktop: 98,67

* Devtools Mätresultat:
    * Laddningstid: 2,93s
    * Inkluderade resurser: 82
    * Storlek på sidan: 1,73MB

## Metro

### [Startsidan](https://www.metro.se/)

[FIGURE src=image/kmom05-report/Metro-Startsida.png?width=720 caption="Metro fig 1"]

* Google pagespeed:
    * Mobil: 62
    * Desktop: 94

* Devtools Mätresultat:
    * Laddningstid: 2,01s
    * Inkluderade resurser: 171
    * Storlek på sidan: 1,57MB

### [Sportnyheter](https://www.metro.se/metro-sport)

[FIGURE src=image/kmom05-report/Metro-Sporten.png?width=720 caption="Metro fig 2"]

* Google pagespeed:
    * Mobil: 61
    * Desktop: 96

* Devtools Mätresultat:
    * Laddningstid: 2,14s
    * Inkluderade resurser: 135
    * Storlek på sidan: 1,27MB

### [Tekniknyheter](https://www.metro.se/teknik)

[FIGURE src=image/kmom05-report/Metro-Teknik.png?width=720 caption="Metro fig 3"]

* Google pagespeed:
    * Mobil: 61
    * Desktop: 96

* Devtools Mätresultat:
    * Laddningstid: 1,95s
    * Inkluderade resurser: 120
    * Storlek på sidan: 1,30MB

### Överlag för webbplatsen

Man kan se i överlag för de tre mätta sidorna på denna webbplats. Att medans alla tre sidor har ett ganska dåligt resultat på sin pagespeed i mobil version. Dock Så har
webbplatsen ett väldigt bra resultat när det gäller sin desktop version av webbplatsen. Då alla tre mätta sidor fick en poäng över på 94 eller högre.
Denna webbplats skulle kunna förbättra sig genom att minska antalet resurser som inkluderas vid nedladdning.

Ett medelvärde på alla tre sidors resultat blev:

* Google pagespeed:
    * Mobil: 61,33
    * Desktop: 95,33

* Devtools Mätresultat:
    * Laddningstid: 2,03s
    * Inkluderade resurser: 142
    * Storlek på sidan: 1,38MB

## Analys

Man kan se att gemensamt för alla tre sidorna så har de ett dåligt pagespeed resultat för mobil version. Detta kan bero på att de troligtvis inte lägger mycket kraft på att
utveckla webbplats versionen för sin webbplats. Då alla tre webbplatser har egna mobilappar för att visa sitt innehåll på mobila enheter och då anser de troligtvis att det inte
är så lönt att lägga mycket kraft på att utveckla sin mobil version av webbplatsen.
På två av webbplatserna, Aftonbladet och Metro kan en av deras största förbättringar vara att inkludera mindre antal resurser vid laddning av sidan. Men denna höga andel
resurser beror troligtvis på att båda webbplatserna använder sig av mycket annonser på sin webbplats för att kunna få en inkomst från besökarna på sidan. Dock kan man tro att
detta ska medföra långa laddningstider för sidorna. Men det är endast aftonbladet som har en lång laddningstid med ett genomsnitt på 7,20 sekunder. Medans metro har en
genomsnittlig laddningstid på 2,03. Även då har de båda väldigt många inkluderade resurser. Aftonbladet har i genomsnitt 182 resurser och metro har 142. Detta kan bero på att
Metro använder sig av mer statiska annonser såsom gif och statiska bilder och de är få. . Medans Aftonbladet har större bilder samt har många fler annonser som ska laddas in
externt. Och detta skadar webbplatsens laddningstid grovt. Ta detta i en kontrast till SVT som inte har någon reklam på sin sida. Denna webbplats har i genomsnitt 82 resurser,
och en laddningstid i genomsnitt på 2,93 sekunder.

Om man ska ranka alla dessa webbplatser överlag så baserat på alla mätningar skulle de bli.

1. SVT
2. Metro
3. Aftonbladet

Anledningen till att Aftonbladet tar sista plats är på grund av att webbsidan har dåligast genomsnittliga resultat. De har 7,20 sekunder i laddningstid, 182 inkluderade
resurser samt har en nedladdningsstorlek på 5,33MB. Vilket är väldigt mycket högre resultat än  de andra två mätta webbplatserna. Vilket de andra två får en laddningstid på
cirka 2-3 sekunder har mindre antal inlkuderade resurser samt båda webbplatsernas nedladdningsstorlek är mindre än 2MB i genomsnitt.

I överlag skulle jag säga att ett gränsvärde i dagens teknik så är något som tar längre än 2-3 sekunder att ladda, kan uppfattas som slött. Vilket då genast kommer sparka ut
Aftonbladet från mitt urval då de har mer än dubbelt så lång laddningstid som jag satt som gräns.

Men i överlag så kan man se att alla tre webbplatser har fått bra pagespeed resultat på sina desktop versionen, medans deras mobilversion har fått mindre bra resultat. Men
detta beror troligtvis på som har nämnts tidigare i analysen att de fokuserar mer på sin mobilapp istället för att jobba på mobilversionen i webbläsaren.

## Övrigt

Skriven av Nicklas König (niko14)
