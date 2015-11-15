---
layout: post
title:  "Examination 1"
date:   2015-11-18
categories: examinationer
---

#### Pre-compiling CSS
Det jag gillar med pre-compiling CSS är dess fördelar som till exempel att nästla koden och använda variabler för att
slippa upprepa sig så mycket och på ett enkelt sätt kunna ändra på dem i en fil och att den ändringen sker överallt där
variablen är använd. Andra fördelar är att man kan skapa funktioner och dela upp koden i flera filer. Jag använde mig
av de redan skapade filerna där variabler och layout särskiljdes och skapade helt enkelt nya variabler och gjorde
vissa stiljusteringar i layoutfilerna.  
Nackdelar som finns är att det är svårare att felsöka och arbetsmiljön är komplexare med fler inblandade verktyg. Det
kan även bli lite mer tidskrävande om man gör många ändringar och vill se resultaten av dem eftersom laddningstiden
kan bli något längre.

#### Static site generators
Jag tyckte det var väldigt enkelt och smidigt att använda static site generators. Det är ett bra hjälpmedel som gör det
lätt att arbeta med själva informationen och snabbt göra förändringar och sen låta hmtl-koden genereras enligt en färdig mall.
Att dela upp layouten, html-koden och texten på det här sättet underlättade både skapandet och underhållandet av sidan.
De lämpar sig bäst för statiska informationssidor som till exempelvis bloggar.

#### robots.txt
Robots.txt är en textfil som innehåller instruktioner om vilka sidor en webbrobot får gå in och söka information på.
Jag ställde in min på "Disallow: /" vilket instruerar roboten att inte gå in på någon sida. 
Det finns dock robotar som struntar i detta och söker sin information ändå.

#### humans.txt
Humans.txt i sin tur är en textfil med information om skaparen/skaparna av en sida och om sidan själv. I min humans.txt
inkluderade jag mitt namn, mejl och från var sidan skapades samt sidnamn, URL, vilket IDE som användes, språk och 
datum för sensaste uppdateringstillfället.

#### Disqus
För att folk ska kunna kommentera mina inlägg så la jag till den funktionen med hjälp av Disqus. Allt som behövde göras
var att registrera ett konto hos dem och sen kopiera in ett färdiggenererad kodavsnitt till min sidmall. 

#### Open Graph
Genom att lägga till metataggar i headdelen av en webbsida kan man skapa ett "graph object" som används som representation
av sidan vid delning via sociala medier. På min sida har jag inkluderat title, url, type (blog) och image (samma bild
av latinamerika som jag använt mig av i headern). 
