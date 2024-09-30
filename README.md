# Boiler-room-v39
-------------------------------------------
DOKUMENTATION Vecka 39: Introduktion till Frontend vs. Backend, Fördjupning i Responsiv design med Flexbox, Grid och Clamp, Introduktion till Agila metoder och gruppdynamik. 
På fredagsmötet så kunde alla 4 komma till Scandic för att jobba, varav 3 kom tidigt till och med för att preppa. Efter Mandus genomgång så bestämde vi snabbt hur vi skulle dela upp arbetet för att effektivt bli färdiga samma dag. Vi jobbade på bra, tog paus vid behov och blev nästan helt färdiga med uppgiften samma dag. Resten jobbade vi individuellt med kontakt online under helgen på våra respektive delar och blev färdiga till söndagen.
-------------------------------------------

Textbeskrivning på flödesschema
1. Användaren fyller i inloggningsformuläret. På frontend-sidan HTML/css, skriver man in sitt användarnamn och lösenord
2. Användaren klickar på 'Logga in'. När man klickar skickas en POST-förfrågan från frontend till backend. Denna begäran innehåller inloggningsinfo (användarnamn och lösenord.)
3. Backend validerar inloggningsuppgifterna: Backend (en server) tar emot förfrågan och kontrollerar om de inmatade uppgifterna stämmer överens med databasen.
- Om uppg matchar, generas en session eller en JWT (JSON Web Token) för att autentisera användaren.
- Om uppg inte matchar, skickas felmeddelande tillbaka till frontend
4. Backend skickar svar: Om valideringen lyckas skickar backend tillbaka en bekräftelse om att inloggningen är framgångsrik och eventuellt en sessions-cookie eller token. Vid fel skickas ett svar som informerar om felaktig inloggning.
5. Frontend visar användaren ett meddelande: beroende på svaret från backend.
- Vid framgång omdirigeras användaren till sin startsida eller profil
- Vid fel får användaren ett felmeddelande på inloggningssidan, tex "felaktigt användarnamn eller lösenord".

1. Användaren fyller i sina inloggningsuppgifter (användarnamn och lösenord) på frontend.
2. En POST-förfrågan skickas till backend med användarens uppgifter.
3. Backend validerar uppgifterna mot databasen.
4. Backend skickar tillbaka ett svar (antingen framgång eller fel).
5. Frontend uppdateras baserat på svaret och visar om inloggningen lyckades eller misslyckades.

![alt text](./flödesschemaFB.png)

-------------------------------------------
Vecka 39: Introduktion till Frontend vs. Backend, Fördjupning i Responsiv design med Flexbox, Grid och Clamp, Introduktion till Agila metoder och gruppdynamik

Tema:
Den här veckan fokuserar på att förstå skillnaderna mellan frontend och backend, fördjupa kunskaperna i responsiv design med moderna CSS-tekniker, och introducera agila metoder och gruppdynamik i projektarbete.

Projekt:
Utveckla en responsiv webbapplikation med moderna CSS-tekniker och tillämpa agila metoder

Beskrivning:
I grupper om 4-6 studenter ska ni planera och utveckla en responsiv webbapplikation som utnyttjar moderna CSS-tekniker såsom clamp() och avancerad användning av Flexbox och Grid. Ni ska tillämpa agila metoder (t.ex. Scrum) under projektets gång och dokumentera er process.

Krav för projektet:

Moderna CSS-tekniker:
Använd clamp() för att skapa responsiv typografi och skalbara element.

Avancerad Responsiv Design:
Skapa en avancerad, responsiv layout som anpassar sig smidigt över olika enheter och skärmstorlekar.
Använd både Flexbox och Grid på ett effektivt sätt för att lösa komplexa designutmaningar.

Introduktion till Frontend vs. Backend:
Gör ett flödesschema över ett formulär på valfri hemsida ni inte skapat själva:
I text och..
I diagram
Lägg detta i en readme fil i ert repo.

Tillämpa Agila Metoder:
Använd en agil metodik (t.ex. Scrum) för att planera och genomföra projektet.
Håll sprintplanering, stand-ups och en sprint retrospektiv.
Dokumentera er agila process, inklusive roller, möten och beslutsfattande.

Gruppdynamik:
Arbeta aktivt med att förbättra gruppdynamiken.
Reflektera över samarbetet och kommunikationssätt inom gruppen.

Veckans ämnen ni ska visa att ni har kunskap om:

Frontend vs. Backend:
Förstå skillnaderna mellan frontend och backend.
Visa hur frontend och backend samverkar i en webbapplikation.

Moderna CSS-tekniker:
Använda clamp(), flexbox och grid (alla behövs inte men minst clamp och en till) för att skapa responsiva och dynamiska designlösningar.

Agila Metoder och Gruppdynamik:
Tillämpa agila metoder under projektets gång.
Förstå och förbättra gruppdynamiken inom teamet.

Gruppresentation, alla ska delta i presentationen:
Varje grupp ska presentera sin webbapplikation och reflektera över sin agila process och gruppdynamik.

Presentationen bör inkludera:
Demonstration av applikationen med fokus på responsiv design och moderna CSS-tekniker.
Beskrivning av den agila processen, inklusive hur ni planerade och genomförde projektet.
Reflektion över gruppdynamik, vad som fungerade bra och vad som kan förbättras.
Presentationslängd: Varje grupp har max 15 minuter för sin presentation.

Deadline:
Presentationerna sker på måndag vecka 40 under lektionstid.
Dokumentation av den agila processen och gruppreflektion ska lämnas in före presentationen (Lägg detta i en readme fil i ert repo. och skicka repot till mig i slack).

Allmänna Anvisningar för Grupparbetena:
Kommunikation och Samarbete:
Använd samarbetsverktyg som Slack, Microsoft Teams eller liknande för att underlätta kommunikationen.
Planera regelbundna möten och stand-ups för att hålla alla uppdaterade.

Projektledning:
Använd projektledningstjänster som Trello, Jira eller Asana för att organisera uppgifter och hålla koll på framsteg.

Dokumentation:
Dokumentera er arbetsprocess, beslut och reflektioner löpande.
Inkludera kodkommentarer och använd tydliga commit-meddelanden i Git.

Presentation:
Förbered er presentation noggrant och fördela ansvaret inom gruppen.
Öva på att presentera för att hålla er inom den angivna tidsramen.

Feedback:
Var öppna för feedback från utbildare och klasskamrater.
Använd feedbacken för att förbättra både ert projekt och ert samarbete.

