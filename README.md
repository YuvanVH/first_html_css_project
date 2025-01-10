# Laboration 2: Individuellt projekt
Kurs: Html & Css
Slutförandvillkor
Senaste inlämningsdatum: söndag, 24 september 2023, 23:59

Kursens andra betygsgrundande moment är ett individuellt projekt.

Objektivet är att bygga en webbplats åt en påhittad (eller riktig) organisation/kund. Tanken är att komma på sin egen projektidé, men här är tre exempel som kan användas för inspiration:

    En webbplats åt en restaurang, ett café, eller liknande
    En webbplats åt någon typ av evanemang, till exempel en musikfestival
    En e-handelsbutik, som till exempel säljer kläder

Krav kring webbplatsen (för G)

Skapa, innan kodandet påbörjas, (minst) en skiss (i form av en bild) på webbplatsens layout/design. Det gör ingenting om skissen slutar vara aktuell, och webbplatsen slutar “uppfylla” skissen, under arbetets gång. (Tips: Skissen kan vara simpel och kan göras med penna och papper eller programvara.)

Webbplatsen ska bygga på en färgpalett. Likt med skissen gör det ingenting om paletten slutar vara aktuell. (Tips: Använd https://coolors.co/ eller https://color.adobe.com/).

Webbplatsen ska vara tillgänglig i det avseende att det alltid är tillräckligt hög kontrast mellan text och bakgrund. AA-kraven måste uppfyllas. (Tips: https://color.review/ kan vara behjälpligt kring att identifiera lämpliga färger att använda.)

Webbplatsen ska ha en layout som nyttjar Flexbox och/eller Grid Layout på ett lämpligt sätt. Lös problem med dessa tekniker som skulle vara svåra att lösa utan Flexbox eller Grid Layout.

Webbplatsen ska vara responsiv och fungera väl på alla bredder mellan 360px (mobiler) och 980px (desktop). Använd media queries för detta. Inget innehåll ska hamna “utanför” webbläsaren så att användaren behöver scrolla i sidled. (Tips: Det kommer sannolikt att vara effektivare att bygga sajten med “mobile-first”-process (för små skärmar först), istället för tvärtom (för datorskärmar först, för att sedan “skala ner” den till att fungera väl på små skärmar).)

Använd title-elementet och description-meta-elementet, samt rubrikelement (alltså h1-h6), på ett lämpligt sätt, enligt Google:s SEO-rekommendationer kring att hjälpa Google och användare att förstå innehållet och tillgänglighetsrekommendationerna Skriv beskrivande sidtitlar och Skapa rubriker med h-element.

Både class selector- och ID selector-väljarna behöver användas (på ett meningsfullt sätt).

Alla img-element ska (som utgångspunkt) ha ett beskrivande alt-attribut i linje med tillgänglighetskravet kring att beskriva med text allt innehåll som inte är text och Google:s SEO-rekommendationer kring optimering av bilder.

All kod ska vara fri från fel i W3C:s valideringstjänster för HTML och CSS. Varningar från valideringstjänsterna accepteras.

Webbplatsen måste bestå av minst två webbsidor (HTML-filer). En av HTML-filerna (startsidan/hemsidan) ska heta index.html så att användaren hamnar på denna webbsida först. Länkar (a-element) ska skapas så att användaren kan navigera mellan webbsidorna.

Ett tillräckligt stort bidrag måste göras. Insatsen kommer att bedömas utifrån att projektet pågår i runt två veckor.

Eftersom vi bara har gått igenom HTML och CSS, och inga andra språk förväntas användas i projektet, så finns det inga krav kring programmering med JavaScript eller liknande. Projektet behöver till exempel inte stödja inloggningar/konton, försäljning av produkter, och så vidare. Det är OK att fejka funktionalitet!

Webbplatsen ska inte laddas upp på ITHS Distans eller Avancera. Filerna ska dock publiceras via FTP (se nedan).
Krav kring publicering (för G)

Webbplatsen ska publiceras på webben via FTP.

Följande FTP-uppgifter ska användas att publicera webbplatsen.
(visar ej för publik publicering)

Om mappnamnet inte är ditt namn, meddela då att det är du som ligger bakom inlämningen så att du kan betygsättas på laborationen.

Se modulen Publicering för mer information om hur FTP-överföringar kan göras.

Glöm inte att infoga skissen som en bild på FTP-servern. Bilden ska vara i PNG-format och ska heta “skiss”.
Extra webbplatskrav för VG

Skriv enhetligt formaterad kod. Indenteringen ska vara konsekvent. Det ska till exempel inte vara två mellanslags indentering i ett CSS-block, och fyra i ett annat. Detta gäller för både HTML och CSS. Se modulen “Några kodkonventioner” för ett exempel kring hur automatisk kodformatering kan konfigureras. Enhetlig formatering bidrar till kod som är enklare att underhålla och vidareutveckla.

Skriv semantisk HTML-kod, det vill säga använda det mest passade HTML-elementet för allt innehåll. Det är till exempel inte acceptabelt att använda ett div-element för att kapsla in ett textstycke, eller att använda h4 för att representera en huvudrubrik. Vidare ska br-element generellt sett inte användas för att skapa avstånd (det är väldigt ovanligt att br är rätt element att använda för detta; använd som utgångspunkt margin- eller padding-egenskaperna istället). Semantisk kod bidrar till sökmotoroptimering, tillgänglighet, samt kod som är enklare att underhålla och vidareutveckla.

Använd HTML5-strukturelement för att hjälpa användare med skärmläsare att bläddra mellan sidornas olika delar. (ARIA behöver inte användas.)

Använd minst en väljare utöver type selector, class selector och ID selector (för att lösa ett problem där väljaren i fråga är lämplig).

Namnge klasser, ID-värden och filer på ett beskrivande sätt. Det är till exempel inte acceptabelt att skapa en klass som heter “my-class”, eller en bild till “my-image”, eftersom detta namn inte kommunicerar tillräckligt mycket om vad objektet i fråga representerar. Beskrivande namn bidrar till kod som är enklare att underhålla och vidareutveckla.

Lägg in en responsiv bild via picture-elementet, img-elementets srcset-attribut, via min-device-pixel-ratio eller liknande. Minst två bildvarianter ska användas. Bildfilerna ska se likadana ut, förutom att de ska skilja sig i upplösning (hur många bildpunkter bilderna består av). Optimerade bilder bidrar till sökmotoroptimering. GIMP kan användas för att skapa olika storleksvarianter av en bild. Det räcker att en bild är responsiv.

Gör gärna, om tid finns, ytterligare tillgänglighets- och sökmotorsoptimeringsförbättringar utöver kraven som nämns ovan. Se https://webbriktlinjer.se/checklistor/ för några checklistor kring tillgänglighet och Googles SEO-rekommendationer för tips kring sökmotoroptimeringar.
# first_html_css_project
