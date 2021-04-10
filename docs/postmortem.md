# Kampanj "Fix the Facinorous Food"

Filip TE19 2021

## Inledning

Här beskriver du kortfattat arbetets syfte/mål, arbetssätt, genomförande.
Jag har gjort en kampanj och kampanjsida för webben och kollat målgrupp, validerat sidan och använt användartest för att göra den så användbar som möjligt.
Planering i grupp och kodning och skrivande av text enskilt.

## Bakgrund
Vi gjorde en planering för en kampanj om att fixa skolmaten i Sverige där vi kom på vad kampanjen skulle handla om, strukturen, målgrupp, färgerna, typsnitt, etc.

Sen tog vi det och gjorde en skiss i Figma där vi testade hur de olika färgerna passade och gjorde en struktur.

Efter det skrev vi innehållet på engelskan och började att jobba enskilt.

Jag började att strukturera texten i HTML och använde mig av olika listor, rubriker och olika tjocklek på texten för att göra den så lätt att läsa som möjligt.

Sen stoppade jag in rätt typsnitt, färger och bilder med CSS och började att göra det responsivt. (använde media queries, texten i mitten och margins på sidorna minskar. bilderna minskar också. )

Sen gjorde jag en header med flex som jag stoppade in text i. Det gick bra, men jag ville ha en logotyp där också.

Det gjorde så att texten hamnade längst upp på sidan och bilden ville inte passa in i rutan som jag hade.

Då la jag till en responsiv version av logotypen, fixade så att logotypen blev mindre och större som jag ville och gjorde så att allt har rätt spacing.

Sen gjorde jag så att det finns länkar i navbaren så att den funkar.

Gjorde också en kopia av index.html och gjorde en about us sida.

Efter det var jag i stort sätt klar. Jag tog CSS och HTML och validerade det och fixade några mindre problem, sen använde jag också wave för att kolla och ändra kontrast (starka färger på svart bakgrund kan vibrera) och annat.
Sen gjorde jag också ett användartest och ändrade lite saker som var otydliga.

Användartest:

Vad är viktigast att göra på sidan?
1. Få information om kampanjen
2. Navigera runt
3. Få information om vilka som har står bakom kampanjen
4. Läsa vanliga frågor
5. Hitta fakta
6. Hitta information om strejk

1, 3, 4 och 6 ställde jag som frågor till testpersonen. Det gick bra att hitta information om kampanjen, vilka som står bakom den och vanliga frågor. Men jag märkte att det var svårt att hitta någon information om strejken så jag gjorde det lättare att göra det för att användare orkar inte läsa all text från topp till botten för att hitta vad de söker efter. Om användare inte kan hitta vad de letar efter så lämnar de bara istället. Därför gjorde jag information om strejken till en egen rubrik.

Ändringar jag gjorde efter användartestet gjorde så att jag måste validera sidan igen. (borde validera efter användartest nästa gång)

I index HTML var det en /p utan någon p så jag fixade det.

About us HTML hade inga problem.

I CSS hade jag inte ändrat någonting så är redan validerad.

Jag kollade sidan med Wave och såg att några alt texter till bilder inte var så beskrivande, så ändrade det. Dessutom skippade jag h2 och använde h3 efter en h1 som man inte borde göra för tillgänglighetens skull och bytte ut h3 mot h2.

## Positiva erfarenheter
Det gick bra att göra sidan responsiv och det var bra att jag gjorde det eftersom så att jag inte försökte göra all responsivitet på slutet.

Planeringen i grupp hjälpte mycket så att alla fick ett ganska likadant resultat. Då kunde alla också hjälpta till för att få en bra början.

Jag gjorde en bra grundstruktur i HTML först så att jag behövde inte riktigt ändra något där sen. Därför använde jag den mesta tiden till att fixa CSS.

Jag hittade några riktlinjer på internet från Google på hur man gör en dark-mode sida också. 
Det hjälpte mig att se dom för att jag kunde då ändra några saker så att slutresultatet blev mycket bättre. T.ex. så ska element som ligger högre upp i dark-mode vara ljusare än andra och färger borde inte vara så starka mot en svart bakgrund.

Det var en bra idé att göra ett användartest för att då kunde jag se sidan från någon som använder den för första gången.

## Negativa erfarenheter
Jag försökte att stoppa in Google graphs i min sida men jag var först tvungen att ändra färgen och innehållet och det var lite svårt att förstå hur och 
sen när jag var färdig så vägrade mitt diagram att vara responsivt och det la sig ovanför navbaren oavsett vad jag gjorde i CSS 
så jag var tvungen att ta bort det från min sida. Om jag hade undvikt Google graphs och bara använt ett vanligt diagram istället så hade det funkat lika bra.

En annan negativ erfarenhet jag hade var att när jag skulle göra användartestet så visade det sig att jag ville att användaren skulle kunna hitta information om strejken 
enkelt, men det visade sig vara svårare än jag trodde. Därför gjorde jag en egen rubrik för det där jag sammanställde den viktigaste informationen.
Därför borde jag göra en lista med de viktigaste sakerna och se till att det är tydligt hur man kommer åt dom. 

Jag borde också försöka att undvika bilder i navbaren om jag inte har så mycket tid för att det tog mest tid av allt. 
Antingen det eller så återanvänder jag koden som jag nu har för att den funkar ganska bra nu.

Det hade varit bra att ha flera olika sätt att ta sig till samma ställe, t.ex. så kan man nu trycka på logotypen för att ta sig till home, 
men det skulle man kunna göra till en egen knapp i navbaren så att det är extra tydligt.

## Sammanfattning
Vad jag borde göra nästa gång:

* Göra responsivitet eftersom.
* Planering i grupp.
* Bra grundstruktur i HTML.
* Hitta riktlinjer på internet om jag försöker göra något speciellt.
* Användartest.
* Skriva lista på vanliga saker man vill hitta.
* Inte Google graphs.
* Återanvänd kod från det här projektet för bilder i navbar.
* Flera sätt att komma åt samma sak.
* Borde validera efter användartest nästa gång

Hur kan kampanjen utvecklas vidare?

Länkar till sociala media, footer, JavaScript, animationer t.ex. för när man trycker på FAQ att sidan skrollar ner.
