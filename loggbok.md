# Individuell loggbok – Agil Webbshop

## Sprint 1 – vecka 39

### Vad jag arbetade med
- Jag arbetade med **FE-04 – Alla kan köra frontend lokalt**, som var en gemensam uppgift för hela gruppen.
- Jag klonade frontend-projektet från GitHub, installerade beroenden och fick React-applikationen att fungera lokalt på min dator.
- Min del av uppgiften blev klar, så att jag kunde fortsätta arbeta med frontend under kommande sprintar.

### Eventuella problem och hur jag löste dem
- Jag behövde lära mig hur jag skulle starta projektet lokalt och arbeta med Git och GitHub.
- Jag testade kommandon och felsökte tills utvecklingsmiljön fungerade.

### Samarbete och agilt arbete
- På måndagen hade vi sprintplanering där vi gick igenom backloggen och fördelade uppgifterna.
- Vi hade dagliga möten runt kl. 11.00 där vi diskuterade vad vi arbetade med och om någon behövde hjälp.
- På fredagen hade vi sprint review med läraren och visade vad vi hade gjort under veckan.

## Sprint 2 – vecka 40
### Vad jag arbetade med
- Jag arbetade med **FE-08 – Returnera inloggningsdata som DTO** i auth-service. Uppgiften handlade om att returnera mer information vid inloggning, bland annat token, användarnamn och roller.
- Jag arbetade också med **FE-10 – Visa välkomstsida efter inloggning**. Jag skapade en välkomstsida i frontend där användaren får ett välkomstmeddelande efter att ha loggat in.
- Jag arbetade med kopplingen mellan inloggningsinformationen från backend och det som skulle visas i frontend.

### Eventuella problem och hur jag löste dem
- En utmaning var att förstå hur informationen från auth-service skulle användas i frontend.
- Jag undersökte hur inloggningssvaret var uppbyggt och arbetade med att visa rätt användarinformation på välkomstsidan.

### Samarbete och agilt arbete
- På måndagen gick vi igenom veckans backlog och fördelade uppgifterna mellan oss.
- Under våra dagliga möten runt kl. 11.00 diskuterade vi hur arbetet gick och om någon behövde hjälp.
- Vi använde Trello för att hålla koll på uppgifterna och på fredagens sprint review visade vi läraren vad vi hade arbetat med.
- 
Sprint 3 – vecka 41

Vad jag arbetade med

Jag arbetade med FE-13 – Gemensam header och footer. Jag skapade en gemensam header och footer för webbshoppen så att sidorna fick en mer enhetlig layout.

Jag arbetade också med FE-16 – Utöka kundvagnen med quantity och prisberäkning. Jag utvecklade kundvagnen så att den kunde visa antal produkter, pris per produkt och totalpris.

Jag arbetade med FE-21 – Kundvagn del 3, där kundvagnens innehåll skulle sparas i sessionStorage och skickas till order-service när kunden genomförde ett köp.

Jag arbetade med dessa tre uppgifter under sprinten och utvecklade webbshoppens funktioner och användargränssnitt.

Eventuella problem och hur jag löste dem

En utmaning var att hantera antal produkter och få prisberäkningen att fungera korrekt i kundvagnen.

Jag behövde också förstå hur sessionStorage fungerade och hur kundvagnen skulle kommunicera med order-service.

Jag arbetade stegvis med funktionerna och testade dem för att kontrollera resultatet.
### Samarbete och agilt arbete
- Under sprinten hade vi gemensamma möten där vi diskuterade våra uppgifter, hur arbetet gick och vilka problem vi behövde lösa.
- Eftersom jag arbetade med både layouten och kundvagnen behövde jag ta hänsyn till hur mina ändringar passade ihop med resten av webbshoppen.
- Vi använde Trello för att följa upp arbetet och se vilka uppgifter som var färdiga eller behövde mer tid.
- Under sprint review visade vi vårt arbete för läraren och diskuterade resultatet.
Sprint	Scrum Master
Sprint 1 – vecka 39	Axel
Sprint 2 – vecka 40	Fabian
Sprint 3 – vecka 41	Sara
## Sprint 4 – vecka 42

### Vad jag arbetade med
- Jag arbetade med **FE-14 – Undersök betalning för webbshoppen**. Jag undersökte olika möjligheter för hur betalning skulle kunna fungera i webbshoppen. Uppgiften blev klar.
- Jag arbetade också med **FE-29 – 404-sida ska visas vid felaktig URL**. Jag skapade en 404-sida i frontend som visas när användaren försöker öppna en sida som inte finns. Den uppgiften blev också klar.
- Jag var även tilldelad den gemensamma uppgiften att säkerställa att email-service kunde skicka mejl lokalt. Eftersom arbetsbelastningen var hög prioriterade jag FE-14 och FE-29 och hann inte färdigställa min del av email-uppgiften under sprinten.

### Eventuella problem och hur jag löste dem
- Jag hade flera uppgifter samtidigt och märkte att tiden inte räckte till för allt.
- Jag behövde därför prioritera arbetet och fokusera på de två uppgifter som jag kunde slutföra under sprinten.
- Jag lärde mig att det är viktigt att planera realistiskt och anpassa arbetsmängden efter den tid som finns.

### Samarbete och agilt arbete
- Under den här sprinten var jag **Scrum Master**, vilket innebar att jag tog ett större ansvar för gruppens agila arbete.
- Jag hjälpte till att hålla struktur i arbetet, följa upp uppgifterna i Trello och diskutera framsteg och hinder tillsammans med gruppen.
- Vi behövde anpassa planeringen efter hur mycket arbete vi faktiskt hann med, vilket gav mig en bättre förståelse för prioritering och flexibilitet inom Scrum.
- Vid sprint review kunde vi visa de uppgifter som blivit färdiga och diskutera det arbete som återstod.

## Sprint 5 – vecka 43

### Vad jag arbetade med
- Jag arbetade med **FE-32 – Gateway-applikation i backend**. Alla i gruppen fick skapa en egen gateway för att öva och förstå hur frontend kommunicerar med olika mikrotjänster.
- Jag skapade min egen version av gatewayn. Efteråt jämförde vi våra lösningar och bestämde tillsammans att använda Fabians gateway (`gateway-agil`) i det gemensamma projektet.
- Jag arbetade tillsammans med Sara med **FE-39 – Konfigurera MSW**. Vi konfigurerade MSW för att kunna simulera API-svar och testa frontend utan att behöva starta backend.
- Jag arbetade självständigt med **FE-40 – Testa produkthämtning**. Jag använde MSW för att testa att produkter kunde hämtas och visas i frontend samt att ett felmeddelande visades om hämtningen misslyckades.

### Eventuella problem och hur jag löste dem
- En utmaning var att förstå hur gatewayn skulle hantera kommunikationen mellan frontend och de olika backend-tjänsterna. Genom att skapa en egen version fick jag bättre förståelse för hur systemet hänger ihop.
- Jag behövde också förstå hur MSW fungerar och hur man kan testa API-anrop utan en riktig backend. Genom samarbetet med Sara och arbetet med mina egna tester fick jag mer erfarenhet av integrationstestning.

### Samarbete och agilt arbete
- Under sprinten arbetade vi både självständigt och tillsammans. Gateway-uppgiften gav oss möjlighet att testa egna lösningar och sedan jämföra dem innan vi valde en gemensam lösning.
- Jag samarbetade med Sara kring MSW-konfigurationen men tog eget ansvar för testerna av produkthämtningen.
- Vi diskuterade våra lösningar i gruppen och använde Trello för att följa upp arbetet.
- Jag lärde mig hur viktigt det är att dela kunskap, kommunicera och samtidigt ta ansvar för sina egna uppgifter i ett agilt projekt.
