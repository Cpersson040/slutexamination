# slutexamination

 Rapport – Slutexamination Webbutveckling 1
Syfte och målgrupp
Syftet med denna webbplats är att presentera mig själv, min utbildning, erfarenheter och kontaktuppgifter i form av en digital CV-webbplats. Den ska fungera som ett professionellt komplement till mitt fysiska CV och vara lätt att dela vid ansökningar till jobb eller utbildningar. Målgruppen är därmed arbetsgivare, rekryterare eller utbildningsanordnare som vill få en snabb och tydlig överblick av mig som person och mina kvalifikationer.

Jag ville samtidigt skapa ett projekt som var realistiskt och användbart även efter kursen, samt ett projekt där jag själv kunde bestämma all text och layout, vilket underlättade arbetet.

UI skisser och ev. mockup
Innan jag började koda webbplatsen gjorde jag en enkel skiss över layouten. Skissen visade en startsida med en presentationstext till vänster och en profilbild till höger. I menyn skulle besökaren kunna klicka sig vidare till tre andra sektioner: CV, Kontakt och GDPR. Layouten var inspirerad av moderna en-sidesportföljer med tydlig uppdelning.

Jag valde att arbeta utan grafiska program eftersom skissen var tillräcklig och projektet inte krävde komplex design. Responsiviteten planerade jag från början, genom att använda CSS Grid och Flexbox för att hantera olika skärmstorlekar smidigt.
Semantisk HTML:
Jag har använt semantiska HTML-taggar som <header>, <nav>, <main>, <section>, <article> och <footer> för att skapa en strukturerad och lättillgänglig kodbas som följer god praxis.

CSS Grid:
För layouten på mina sidor har jag använt CSS Grid, bland annat för att skapa en responsiv struktur som fungerar bra på både stora och små skärmar.

Flexbox:
Jag har använt Flexbox för att justera innehållet i mindre komponenter, till exempel navigation, kortlayouter och centrerad placering av element.

Optimerade bilder:
Alla bilder som används på webbplatsen är optimerade i formatet PNG. Jag har komprimerat dem med hjälp av verktyget TinyPNG för att minska filstorleken och förbättra sidladdningen.

Bildspel:
För att uppfylla kriterierna för betyg C eller högre har jag implementerat ett bildspel med JavaScript. Bildspelet visar flera bilder med automatisk rotation samt möjlighet att navigera manuellt.

Publicering via GitHub Pages: 
Webbplatsen är publicerad via GitHub Pages och är tillgänglig online. Detta gör det enkelt att visa upp.

Så här uppfyller min webbplats GDPRs kriterier
Min webbplats samlar inte in någon form av personuppgifter. Det finns inget kontaktformulär, ingen datalagring och inga cookies. Enda sättet att kontakta mig är via en min e-post, vilket inte bryter mot GDPR så länge jag inte begär in uppgifter aktivt.

Skulle jag i framtiden vilja lägga till ett formulär, kommer jag behöva inkludera en tydlig samtyckesruta, en policytext som förklarar hur data hanteras, samt säkerställa att information inte lagras utan godkännande. Men i det här projektet har jag medvetet valt att hålla webbplatsen så enkel som möjligt för att undvika detta.

Tester och testresultat
Jag har testat webbplatsen i följande webbläsare: Google Chrome, Microsoft Edge och Mozilla Firefox. Alla visade samma resultat. Responsiviteten fungerade bra tack vare användning av Grid och Flexbox.

Jag har använt automatiska verktyg som:
WAVE 
Devtools Device mode

Resultaten:

WAVE visade inga allvarliga kontrastfel eller strukturproblem.
 


Device mode
Jag har använt Device Mode i Chrome DevTools för att kontrollera webbplatsens responsivitet. Genom att aktivera Device Mode kunde jag simulera olika enheter och testa hur webbplatsen ser ut och fungerar på olika skärmstorlekar, både för mobil och tablet. Jag har testat på flera vanliga enheter som iPhone, iPad och Android-enheter för att säkerställa att layouten fungerar korrekt och att alla element är anpassade till olika skärmstorlekar. 
 



Analys av webbprojektet efter färdigställan
Jag upplever att projektet gick bra tack vare tydlig planering och ett tydligt syfte. Det var hjälpsamt att utgå från min egen person och inte behöva leta information. Det som tog mest tid var att få layouten responsiv och välja rätt struktur för HTML-sektionerna. Jag lärde mig mycket om semantisk HTML, framför allt vikten av att använda rätt taggar som <section>, <article> och <main> för att skapa logisk och tillgänglig kod.

Jag är nöjd med att ha inkluderat ett bildspel, då det höjde webbplatsens interaktivitet och gör att CV:t blir lite mer interaktivt.

Slutsats
Sammanfattningsvis är jag nöjd med både processen och resultatet. Jag har lyckats skapa en komplett webbplats som uppfyller kursens tekniska krav: den innehåller semantisk HTML, Grid, Flexbox, ett bildspel, optimerade bilder och är publicerad på GitHub Pages. Jag har även dokumenterat mitt arbete och följt GDPR-krav. Det här projektet gav mig en bättre förståelse för webbutveckling och är något jag faktiskt kan använda i verkliga livet.
