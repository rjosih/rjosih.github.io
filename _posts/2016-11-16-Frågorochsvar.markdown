---
layout: post
comments: true
title:  "Frågor och svar"
date:   2016-11-16 14:13:20
categories: jekyll update
---

<b> Vad tycker du om att förkompilera din CSS? Jämfört med vanlig CSS? </b>
Det innebär att man har CSS i olika filer och det gör ju så att man delar upp allt och min åsikt är det om man kan
verktygen och hur det fungerar korrekt är det ett bättre sätt att jobba på jämfört med ”vanlig” CSS då man lägger all
CSS-kod i en enda CSS-fil. Med hjälp av flera CSS-filer kan man på ett enklare sätt göra mer detaljerade sidor med
underlättning av fördelningen. Då vi inte jobbat med den här typen av CSS tidigare var det lite svårt att komma igång,
men det blev enklare när man väl kommit in i det.

<b> Vilka tekniker har du använt? </b>
I den här examinationen har vi använt variabler i CSS

<b> För och nackdelar? </b>
Fördelar: Mindre CSS-kod, ingen upprepning, organiserad CSS med separata filer (som tidigare nämnt).
Nackdelar: svårare att debugga koden då linjenumren i browsen inte stämmer med källan, mer komplext med mer verktyg etc.

<b> Vad tycker du om static site generators? </b>
Beror på sammanhanget, men i det här fallet när man gör en "blogg" funkar det utmärkt medan Facebook som har ett gående flöde
där man slipper uppdatera själv utan det görs av sig själv med bakgrundsaktivitet osv. Statiska hemsidor är mindre komplexa och
därför enklare att programmera för. Eftersom det enda jag kan i dagsläget är statiska hemsidor tycker jag det är jättebra.
En nackdel kan vara är om man vill ändra något litet då man måste ändra i alla filer och då kan man lätt missa detaljer.

<b> Vilka projekt är det bra att använda till? </b>
Hemsidor som ska ha samma design med en global navigering, då undviker man som tidigare sagt att man slipper upprepa sig.
Då många av dagens webbsidor har global navigering samt gemensam headerbild och liknande skulle jag vilja påstå
majoriteten av webbsidor är static site generators bra.

<b> Vad är robots.txt och hur har du konfigurerat det för din webbplats? </b>
I grund och botten är robots.txt en textfil som är placerad i ens webbserver.
I filen talar man om vilka sökmotorer som är välkomna på sajten eller inte.
Jag konfigurerade robots.txt genom att lägga den i en fri textfil i src med vilka sökmotorer jag ville skulle komma igenom.
I detta fall är det bara Google.

<b> Vad är humans.txt och hur har du konfigurerat det för din webbplats? </b>
Ett sätt att få reda/”känna” människorna bakom en webbplats. Samma som robots.txt är det en textfil som läggs direkt i
src som innehåller information om de olika personerna alternativt personen som bidragit till att bygga och konstruera webbplatsen.

<b> Hur har du lagt till kommentarer på dina blogginlägg? </b>
Med hjälp av hemsidan Disqus som man blev hänvisad via examinationssidan. Jag la in ett kopierat stycke från Disqus
in i src/_layouts/post.html. Samt i alla ”bloggpostinlägg” (alla inlägg som finns i "_posts" skriver jag comments: true om jag vill att kommentarsfunktionen
ska fungera på just det inlägget. Alternativt skriver man comments: false om man inte vill att besökarna ska kunna kommentera.

<b> Vad är Open Graph och hur använder du det? </b>
Open Graph är en teknik som infördes av Facebook 2010 som tillåter samt möjliggör en intergration mellan Facebook,
dess användardata och en webbplats. (Delning av url, type, image etc på sociala medier, i det här fallet Facebook).
Genom att integrera webbsidans metataggar kan man även bestämma vilka delar av sidan som ska visas.
