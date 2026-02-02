
# FDND Agency – Projectvoorbereiding (remote)

**Context:**  
Deze workshop is voor de **dinsdag na de kickoff**. Op dinsdag werk je **remote vanuit huis**.  
Je werkt dus samen via een **online call** in Teams.

---

## Sprint planning

Project voorbereiden en de handover van het vorige team omzetten naar een concreet plan voor Sprint 19.

Je begint een nieuwe sprint altijd met een goede projectvoorbereiding: je leest de handover van het vorige team, bekijkt de epics en issues op het project board, zet het project lokaal op en maakt afspraken over samenwerking.

Aan het einde van deze (remote) workshop heeft ieder teamlid het project lokaal draaiend, is het board opgeschoond, zijn de RAPPE‑principes getest en zijn er vragen voorbereid voor de volgende stand‑up.

### Aanpak

Deze sprint werk je aan een bestaand FDND Agency project. In deze (remote) workshop:

- start je een **online teamcall** en een gedeeld **Miro board**
- lees je de `Handover.md` van het vorige team  
- bekijk je de epics en issues op het project board  
- installeer je het project lokaal  
- controleer je of het project voldoet aan de FDND Agency‑conventies  
- test je de RAPPE‑principes  
- maak je afspraken over samenwerking, workflow en rollen  
- bereid je vragen voor voor de stand‑up van woensdag  

Voer de workshop uit met het team dat aan hetzelfde Agency‑project werkt, **via een online call**.

---

## 0. Opstarten (online call + Miro)

1. **Plan een online call** met je team
2. **Maak een Miro board** aan met in elk geval deze secties:
   - Handover – “We weten zeker / denken / hebben geen idee”
   - Project board / epics & issues
   - RAPPE bevindingen
   - Teamafspraken & rollen
   - Vragen voor stand‑up woensdag
3. Deel de link naar de call en het Miro board in jullie vaste communicatiekanaal.
4. Vul een Team Canvas in en voeg het toe aan het Miro board

---

## Handover.md lezen

Lees met het hele team de `Handover.md` die door het vorige team is achtergelaten.

### Aanpak

1. **Individueel lezen**

   - Iedereen opent `Handover.md` in de repository.
   - Noteer voor jezelf (bijvoorbeeld in Miro sticky notes of eigen notities):
     - Wat is de opdracht / het doel van het project?  
     - Wat is al gedaan (features, design, technische keuzes)?  
     - Wat is nog niet af of onzeker?  

2. **Samen bespreken (in Miro)**

   - Gebruik een Miro‑frame “Handover” met drie kolommen:
     - “We weten zeker dat…”  
     - “We denken dat…”  
     - “We hebben geen idee van…”
   - Laat iedereen zijn/haar sticky notes in de juiste kolom slepen.
   - Bespreek de belangrijkste punten in de online call.
   - Vertaal onduidelijkheden naar:
     - **vragen** (voor opdrachtgever / docent / stand‑up)  
     - **issues** op het project board

---

## Project board bekijken (epics & issues)

Open tijdens de call samen het GitHub Project board dat bij het FDND Agency project hoort.

### Epics en issues analyseren

- Bekijk samen:
  - Welke **epics** zijn er?
  - Welke issues staan op *Done*, *In Progress* of *To Do*?

Je kunt in Miro een klein overzicht tekenen of een screenshot van het board plakken om epics en prioriteiten te markeren.

---

## Project clonen & installeren

Iedereen zet de code lokaal op zijn eigen machine en controleert of het project draait.

### Repo clonen

- Clone de repo van het project naar je eigen laptop.

### Installeren en starten

- Volg de stappen in `README.md` 
- Controleer:
  - Start het project zonder errors?
  - Zijn de belangrijkste pagina’s lokaal bereikbaar?

### Issues aanmaken waar nodig

Maak één of meerdere issues aan als:

- installatie‑instructies ontbreken of onduidelijk zijn  
- er errors of warnings zijn bij installeren of starten  
- bepaalde scripts niet werken zoals beschreven  

Koppel deze issues aan een epic (bijv. “Developer Experience” of “Tech debt”).

---

## FDND Agency‑conventies controleren

Bekijk in hoeverre het project voldoet aan de [FDND conventies](https://docs.fdnd.nl/conventies.html)

### Repository & documentatie

- Deel weer een scherm met de repo (bijv. in GitHub of de editor).
- Controleer gezamenlijk of er een duidelijke `README.md` is met:
  - korte beschrijving van het project  
  - installatie‑ en start‑instructies  
  - gebruikte scripts (build, test, lint, etc.)  
- Controleer of `Handover.md` matched met wat je in de code ziet.


### Structuur & naamgeving

- Laat iemand de mappenstructuur tonen (scherm delen).
- Bespreek:
  - Zijn de mappen logisch ingedeeld (bijv. `src`, `components`, `styles`, `assets`)?  
  - Is er consistente naming (kebab‑case, PascalCase, etc.)?  
  - Zijn componenten, pagina’s, utils en data gescheiden?

### Code style & tooling

- Controleer of er configuratiebestanden zijn voor bijv. ESLint, Prettier.
- Bespreek kort hoe de huidige commit‑geschiedenis eruitziet (branch‑namen, messages).

### Issues aanmaken

Maak voor afwijkingen en verbeterpunten issues, bijvoorbeeld:

- `Conventies: README updaten`  
- `Conventies: mappenstructuur herorganiseren`  
- `Conventies: ESLint/Prettier configureren`

Noteer in Miro kort de belangrijkste “conventie‑problemen” en de bijbehorende issue‑nummers, zodat het team overzicht houdt.

---

## RAPPE‑principes testen

Toets de huidige staat van de applicatie aan de RAPPE‑principes.

### De applicatie testen (remote)

- Iedereen opent lokaal de applicatie in de browser.
- Spreek in de call af wie welk RAPPE‑onderdeel kort onderzoekt.
- Gebruik waar nodig tools zoals:
  - Lighthouse / browser devtools  
  - toetsenbord‑navigatie  
  - screenreader  
  - responsive design mode  

Laat teamleden kort hun bevindingen delen en noteer ze als sticky notes in een Miro‑frame “RAPPE”.

### Issues aanmaken

- Groepeer sticky notes in Miro per thema (bijv. Accessibility, Performance, Usability).
- Maak op basis daarvan issues aan in GitHub, bijvoorbeeld:
  - “Navigatie is niet volledig met toetsenbord te bedienen”  
  - “Performance is slecht op mobiele devices (Lighthouse score onder X)”  
  - “Contrast van buttons is onvoldoende”
- Label de issues waar mogelijk (bijv. `accessibility`, `performance`, `usability`).
- Koppel de issues aan de juiste epics.

---

## Afspraken over samenwerking & workflow

Maak duidelijke afspraken over hoe jullie als team werken in deze sprint en leg die **remote** vast.

### Workflow afspreken (in de call + Miro)

- Gebruik een Miro‑frame “Teamafspraken” en beantwoord samen:
  - **Branching:**
    - Werken jullie met `main` + feature branches?  
    - Wanneer mag er naar `main` gemerged worden?
  - **Pull Requests:**
    - Altijd review door minimaal 1 teamlid?  
    - Gebruiken jullie een PR‑template (beschrijving, teststappen, screenshots)?
  - **Issues & project board:**
    - Werkt iedereen altijd vanuit een issue?  
    - Wanneer verander je de status (To do → In progress → Done)?  
    - Hoe vaak checken jullie samen het board (bijv. korte remote daily)?

### Communicatie (remote‑specifiek)

- Spreek af:
  - Welke tools gebruik je (Teams, Slack, Discord, GitHub comments) voor **dagelijkse communicatie**?  
  - Hoe snel reageer je op berichten (bijv. binnen 24 uur op studie‑dagen)?  
  - Hoe ga je om met stilte / afwezigheid (bijv. afmelden in kanaal)?
  - Wat doe je bij blokkades:
    - eerst vraag in teamkanaal  
    - daarna eventueel docent / stand‑up

### Vastleggen

- Kies één iemand die de Miro‑afspraken omzet naar een document in de repo:
  - `CONTRIBUTING.md`, of  
  - `team-agreements.md`, of  
  - een sectie in `Handover.md` voor Sprint 19
- Maak een issue **“Workflow & afspraken vastleggen”** en voeg deze toe aan het project board.

---

## Rollen afstemmen

Bepaal wie waar verantwoordelijkheid voor neemt in deze sprint.

### Mogelijke rollen

- **Tech lead** – bewaakt technische keuzes, code‑kwaliteit en reviews  
- **Product / Client contact** – contactpersoon voor opdrachtgever / docenten, bewaakt scope  
- **Design / UX lead** – bewaakt UX, UI, toegankelijkheid en consistentie  
- **Project lead / Scrum master** – bewaakt planning, (remote) stand‑ups en voortgang  
- **Documentation lead** – houdt README, Handover, issues en Miro‑samenvattingen actueel  

### Rollen verdelen (remote)

- Gebruik een Miro‑sectie “Teamrollen”.
- Laat iedereen kort in de call aangeven:
  - Waar wil je meer mee oefenen of in groeien?  
  - Welke rol sluit daar het beste bij aan?
- Zet voor ieder teamlid een sticky note met naam + rol(len).
- Spreek kort af:
  - welke taken bij elke rol horen in **deze sprint**  
  - hoe jullie elkaar remote op de hoogte houden

Leg de rolindeling vast in een bestand zoals `team-roles.md` of in `Handover.md`.

---

## Vragen voorbereiden voor de stand‑up van woensdag

Sluit de workshop af met het voorbereiden van gerichte vragen voor de stand‑up van woensdag.

### Inventariseren (in Miro)

- Maak een Miro‑frame “Vragen voor stand‑up”.
- Kijk naar:
  - `Handover.md`  
  - de epics en issues op het project board  
  - de RAPPE‑bevindingen  
  - onduidelijkheden over scope, prioriteiten of technische keuzes
- Laat iedereen sticky notes plakken met:
  - Waar hebben we *duidelijkheid* over nodig?  
  - Waar willen we *feedback* op?  
  - Waar hebben we *beslissingen* van opdrachtgever / docent voor nodig?

### Vragen formuleren

- Bundel de sticky notes in 5–10 heldere vragen. Bijvoorbeeld:
  - “Welke user group heeft in Sprint 19 de hoogste prioriteit?”  
  - “Mogen we component X herontwerpen als dat nodig is voor betere toegankelijkheid?”  
  - “Wat is belangrijker in deze sprint: performance verbeteren of feature Y opleveren?”
- Bespreek in de call wie welke vraag stelt tijdens de stand‑up.

### Vastleggen

- Maak een issue **“Vragen voor stand‑up woensdag”** met:
  - een lijst van alle vragen  
  - de naam van het teamlid dat de vraag stelt
- Voeg het issue toe aan de juiste epic (bijv. “Afstemming opdrachtgever”).

---

## Deliverables na deze (remote) workshop

Aan het eind van de workshop heeft het team minimaal:

- `Handover.md` gelezen en in eigen woorden samengevat (in Miro + repo)  
- een opgeschoond en aangevuld project board (met nieuwe issues voor conventies & RAPPE)  
- een lokaal draaiend project op elke laptop (of issues als dat niet lukt)  
- vastgelegde teamafspraken over **remote** workflow en communicatie  
- verdeelde teamrollen met bijbehorende verantwoordelijkheden  
- een lijst met concrete vragen voor de stand‑up van woensdag (vastgelegd in een issue)  
- een Miro board met:
  - Handover‑samenvatting  
  - epics/issues‑overzicht  
  - RAPPE‑bevindingen  
  - teamafspraken en rollen  
  - vragen voor de stand‑up
