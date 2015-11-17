---
layout: post
title:  "Här besvaras frågor i exuppgift 1"
date:   2015-11-10 11:21:56
categories: jekyll update
---
I det här inlägget ska jag besvara de frågor som upptått i samband med uppgiften och som enligt uppgiften ska besvaras i en bloggpost.

#Vad tycker jag om att pre-kompilera CSS?
* Det är lite krångligare struktur än vad jag hittills är van vid.
Jämfört med vanlig CSS där allt händer på samma ställe så är det lite förvirrande innan man kommer in i det (inte för att jag kommit helt in i det än haha).
* När det kommer till använda tekniker så har jag främst försökt följa instruktionerna och demofilmerna,
jag vet inte riktigt vad som menas med tekniker.
* Fördelarna är dock ganska uppenbara tycker jag.
Det riktigt bra som jag ser det är att man inte behöver hänga upp allt i samma fil, och att man därför kan vara flera som arbetar med samma projekt samtidigt.
Med hjälp av variabeldeklarationer o dyl förenklas underhåll och ändringar och man kan få ganska bra överblick vilket minskar risken för fel.
Vidare inser jag också fördelarna med att arbeta i en sluten utvecklingsmiljö som är kongruent med alla som ansluter till maskinen. För egen del har jag utvecklat sajter mm skarpt men mot
irrelevanta domäner tills det är färdigt, inte helt optimalt förstås när det handlar om större projekt eller stora förändringar i affärskritiska system och mycket folk inblandat.

#Vad tycker jag om sk "Static site generators"?
* Åsikterna så här långt är ungefär motsvarande som för precompiled CSS, det är krångligare än nödvändigt vid första anblicken.
I gengäld har man då enkelheten i skapandet och det öppnar för betydligt enklare underhåll.
* I dagsläget ser jag att de främsta användningsområdena är antingen då man snabbt behöver sätta ihop en väldigt enkel och snabb sida utan alltför komplicerat innehåll,
 eller i ett projekt där många utvecklare behöver arbeta samtidigt.

#Vad är `robots.txt` och hur har jag konfigurerat den i min webbplats?
* Filen robots.txt är en textfil i vilken man talar om för sökmotorer hur man önskar att tillgängligheten ska vara för det publika innehållet.
I mitt fall har jag angett att ingenting ska indexeras, vilket i de flesta fall gör att sökmotorn vänder utan att indexera något. `Malware` och mindre önskvärda program tar dock inte hänsyn till direktiv i `robots.txt`.

#Vad är filen `humans.txt` och hur har jag konfigurerat den i min webbplats?
* Filen `humans.txt` är också den en textfil som man precis som robots.txt placerar i roten. Detta var nytt för mig och idén går ut på att placera information om
sidans skapare och annat som kan vara av intresse för utvecklare eller dyligt tillgängligt för dessa men lite mer svåråtkomligt för den vanliga besökaren.
I min fil har jag nöjt mig med att ange vem jag är, kontaktuppgifter, jag har tackat min katt och en liten notis om i vilket program sidan är byggd.

#Hur har jag implementerat kommentarsfunktionen på mina blogginlägg?
Det var enklare än väntat, hittade en bloggartikel (`http://www.perfectlyrandom.org/2014/06/29/adding-disqus-to-your-jekyll-powered-github-pages/`)
som jag fann lättare att förstå än själva instruktionerna på disqus, så när jag väl bara testade så fungerade det direkt.
Jag har lagt mina kommentarsfält på `post.html och `page.html` i mappen `_layouts`, då kommer de med överallt där jag vill ha dem.

#Vad är `open graph` och hur använder jag det?
Open graph är den info som dyker upp i samband med delningar, i mitt fall har jag angett beskrivningen jag vill visa i config-filen för att den senare ska hämtas från exvis facebook när man delar en länk.
Återstår att se om det fungerar efter uppladdning till github/pages.


