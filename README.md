# Gruppexamination – Fullstack Webbapplikation med TypeScript

## Introduktion

Ni har fått i uppdrag att utveckla en fullstackapplikation åt en nystartad take away-restaurang!

Restaurangen behöver en modern webbapplikation där kunder kan utforska menyn, beställa och betala för sin mat. Personalen behöver samtidigt ett smidigt system för att hantera inkommande beställningar.

Ni ansvarar för hela utvecklingsprocessen, från idé och design till färdig, driftsatt applikation.

Ni bestämmer själva restaurangens namn, koncept, grafiska profil och vilken mat som serveras. Utöver de obligatoriska kraven har ni stor frihet att själva bestämma vilka funktioner ni vill utveckla.

**Tänk på att projektet kan bli en värdefull del av er portfolio när ni söker LIA eller arbete!**

## Länkar

- [Grupper](https://drive.google.com/file/d/1pLYjeNXpE1gZ0ZZ1K-sDQCr7HV_ylfIX/view?usp=sharing)
- [User Stories – GitHub Projects](https://github.com/users/Santosnr6/projects/21)

## Specifikation

Applikationen ska innehålla följande grundläggande funktionalitet:

**Kunder ska kunna:**
- Se restaurangens meny.
- Lägga till och ta bort produkter i en varukorg.
- Genomföra och betala en beställning online.

**Personal ska kunna:**
- Logga in i applikationen.
- Se inkomna beställningar.
- Uppdatera statusen på beställningar.

**AI-funktionalitet:**

Applikationen ska dessutom innehålla minst en funktion som använder generativ AI. Ni bestämmer själva vad funktionen ska göra, men den ska fylla ett tydligt syfte för restaurangens kunder eller personal.

### User Stories

Ni hittar projektets User Stories via länken ovan.

Utöver funktionaliteten som listas under *Specifikation* ovan, så har ni inga direkta krav på funktionalitet. Det kommer därför vara upp till er att själva skapa kraven utifrån de User Stores som ni anser ha högst prioritet, och vara mest värdeskapande.

Ni får även skriva om, dela upp eller lägga till egna User Stories för att anpassa projektet efter ert koncept. De obligatoriska funktionskraven måste dock alltid uppfyllas.

## Tekniska krav

- **Frontend:** React med TypeScript.
- **Backend:** Node.js med Express eller AWS med Serverless Framework. Backend ska skrivas i TypeScript.
- **Databas:** Valfri databas med persistent datalagring.
- **Betalning:** Integration med en extern betallösning, exempelvis Stripe i testläge.
- **Autentisering:** Säker hantering av credentials och behörighetskontroll.
- **Säkerhet:** Implementera CSP och relevant botskydd.
- **TypeScript:** Använd statisk typning, interfaces/types och en genomtänkt `tsconfig.json`.
- **Tillgänglighet:** Responsiv design med hänsyn till WCAG.
- **Driftsättning:** Både frontend och backend ska publiceras online.

## Driftsättning

Både frontend och backend ska driftsättas och vara tillgängliga online inför varje veckas Sprint Review, samt slutpresentationen.

Ni väljer själva vilka hostingtjänster ni vill använda. Det viktiga är att **samtliga obligatoriska funktioner fungerar i den publicerade applikationen**, inklusive betalningslösningen och AI-funktionen.

AI-funktionen får använda en extern AI-tjänst, exempelvis Ollama Cloud, AWS Bedrock eller något annat AI-API. Det finns inget krav på att ni ska driftsätta en egen AI-modell.

Alla känsliga uppgifter, exempelvis API-nycklar och credentials, ska hanteras säkert på serversidan och får inte exponeras i frontend.

## Designprocessen

Under den första projektveckan ska ni utveckla ert restaurangkoncept och påbörja designarbetet i Figma.

**All funktionalitet med ett visuellt gränssnitt ska ha en tillhörande Figma-design innan den börjar utvecklas.**

Ni behöver inte designa hela applikationen direkt. Det räcker att ni inför varje sprint har färdiga skisser för den funktionalitet ni planerar att utveckla.

Designen får självklart förändras under projektets gång.

## Scrum och GitHub

Ni ska arbeta agilt enligt Scrum under hela projektet.

Det innebär att ni genomför:

- **Sprint Planning:** Varje måndag förmiddag eller fredag eftermiddag.
- **Daily Scrum:** Varje arbetsdag.
- **Sprint Review:** Varje fredag tillsammans med mig som produktägare.
- **Sprint Retrospective:** Efter varje Sprint Review.

Ni ska använda GitHub Projects för att hantera er Product Backlog, Sprint Backlog och era pågående uppgifter.

Gruppen ska även komma överens om en Gitstrategi med branches och Pull Requests samt en gemensam Definition of Done.

Dokumentera sprintmål, feedback från Sprint Reviews och förbättringsåtgärder från retrospektiven. Daily Scrum behöver inte dokumenteras.

**Alla gruppmedlemmar förväntas bidra aktivt under hela projektet.**

Bjud in mig (`Santosnr6`) till era repositories och ert GitHub-projekt.

## AI-assisterad utveckling

Samtliga gruppmedlemmar ska använda AI som stöd under utvecklingsarbetet.

Ni väljer själva vilka verktyg och metoder ni vill använda. Det kan exempelvis handla om ChatGPT för problemlösning, GitHub Copilot för kodkomplettering eller AI-agenter för att analysera och implementera avgränsade funktioner.

Ni ansvarar alltid själva för den kod ni levererar och ska kunna förstå, förklara och granska även AI-genererad kod.

I den individuella skriftliga examinationen kommer ni att reflektera över ert AI-användande, ert eget arbete och samarbetet i gruppen.

AI-användningen kan även diskuteras under den avslutande opponeringen.

## Examination och bedömning

Även om projektet genomförs i grupp sker **betygssättningen individuellt**.

### För Godkänt (G)

Du ska:

- Uppfylla kursens lärandemål.
- Aktivt bidra till gruppens utvecklingsarbete och Scrum-process.
- Bidra till en fungerande, driftsatt applikation som uppfyller de obligatoriska kraven.
- Kunna förklara och motivera dina tekniska val och den kod du arbetat med.
- Genomföra den individuella examinationen.

### För Väl Godkänt (VG)

Utöver kraven för G ska du visa:

- Mycket god kodkvalitet med tydlig och välstrukturerad TypeScript-kod.
- Hög grad av självständighet och problemlösningsförmåga.
- Mycket god teknisk förståelse, vilket bedöms vid den muntliga examinationen.
- Förmåga att arbeta med **package-arkitektur** i frontend.

Bedömningen utgår från din individuella prestation, inte enbart från hur många funktioner gruppen har implementerat.

## Slutredovisning och inlämning

Projektet avslutas med en gemensam redovisning där varje grupp:

1. Presenterar sitt projekt och demonstrerar den driftsatta applikationen på **engelska**.
2. Deltar i en opponering på **svenska**.

Utöver gruppredovisningen genomför varje studerande en individuell skriftlig reflektion och en muntlig examination.

Vid inlämningen ska gruppen tillhandahålla:

- Länkar till GitHub-repositories och GitHub Projects.
- Länk till Figma-projektet.
- Länk till den publicerade frontendapplikationen.
- Länk till det driftsatta backend-API:et, exempelvis dess basadress.
- En kortfattad teknisk dokumentation och sammanfattning av utvecklingsprocessen.

Närmare instruktioner för den individuella examinationen, slutredovisningen och inlämningen meddelas separat.

**Lycka till!**
