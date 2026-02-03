# FDND Agency – Sprint Planning

**Context**  
Deze workshop volgt op de *Projectvoorbereiding* (handover lezen, project board opschonen, conventies en RAPPE testen).  
In deze sessie maak je van het project een **concreet sprintplan** voor Sprint 19: epics, user stories, prioriteiten en een realistische planning.

<!--
Doel van de workshop:
- Het project opdelen in behapbare epics en user stories
- Prioriteiten bepalen vanuit gebruiker en opdrachtgever
- Samen effort inschatten (planning poker)
- Een haalbare sprint backlog maken in het project board
-->

Aan het einde van deze workshop heb je:

- een duidelijk **sprintdoel** voor Sprint 19  
- een set **epics** met bijbehorende **user stories**  
- **story points** (inschattingen) voor de belangrijkste stories  
- een **geprioriteerde** backlog  
- een **sprint backlog** met uitgewerkte taken in je project board  

---

## 1. Sprintdoel bepalen

Begin met het scherp formuleren van het doel van Sprint 19.

### Aanpak

1. Kijk terug naar:
   - `Handover.md`  
   - de epics op het project board  
   - de belangrijkste problemen / kansen uit de RAPPE‑check  

2. Beantwoord samen:
   - **Wie** willen we in Sprint 19 vooral helpen (welke gebruiker / stakeholder)?  
   - **Welk probleem** lossen we deze sprint op?  
   - **Welke uitkomst** willen we aan het einde kunnen laten zien/demonstreren?

3. Formuleer een kort **sprintdoel**

Noteer dit sprintdoel duidelijk de `Handover.md`.

---

## 2. Project breakdown: epics aanscherpen

Gebruik de bestaande epics uit het project board als startpunt en vul aan waar nodig.

### Aanpak

1. **Epics checken**
   - Bekijk de huidige epics in het project board.
   - Beantwoord per epic:
     - Waar gaat deze epic precies over?  
     - Welke gebruiker/helpvraag hoort hierbij?  
     - Past deze epic bij het sprintdoel, of is het meer voor latere sprints?

2. **Epics aanscherpen**
   - Hernoem vage epics naar concrete uitkomsten, bijv.:
     - “Navigatie & informatiearchitectuur”  
     - “Registratie & onboarding”  
     - “Dashboard / overzicht”  
     - “Toegankelijkheid & performance”
   - Hang bestaande issues aan de juiste epic.

3. **Scope voor Sprint 19 kiezen**
   - Markeer welke epics **in deze sprint** de focus hebben.
   - Andere epics blijven op de roadmap voor latere sprints.

---

## 3. User stories schrijven

Zet de belangrijkste wensen en functionaliteiten om naar **user stories**.

### User story formaat

Werk bij voorkeur met dit patroon:

> Als **[type gebruiker]** wil ik **[doel / actie]**, zodat **[waarde / resultaat]**.

Voorbeelden:

- Als *nieuwe bezoeker* wil ik *in één oogopslag zien wat het product doet*, zodat *ik kan beslissen of het voor mij relevant is*.  
- Als *terugkerende gebruiker* wil ik *snel bij mijn opgeslagen projecten kunnen*, zodat *ik zonder zoeken verder kan waar ik was*.

### Aanpak

1. Kies 1–2 focus‑epics die het meest bijdragen aan het sprintdoel.
2. Brainstorm per epic user stories:
   - Schrijf ze op sticky notes op het whiteboard.
   - Focus op **gedrag** en **waarde**, niet op technische oplossingen.
3. Voeg aan de belangrijkste stories **acceptatiecriteria** toe, bijv.:
   - De user kan X binnen Y stappen doen.  
   - Werkt op mobiel en desktop.  
   - Is volledig met toetsenbord te bedienen.

4. Maak voor elke definitieve user story een issue in GitHub:
   - Titel = korte samenvatting  
   - Beschrijving = user story + acceptatiecriteria  
   - Koppel aan de juiste epic

---

## 4. User stories ordenen & prioriteren

Niet alle stories kunnen in één sprint. Bepaal wat nu het belangrijkst is.

### Aanpak

1. Orden stories per epic in een grove volgorde volgens de **MoSCoW** methode:
   - **M**ust have  
   - **S**hould have  
   - **C**ould have  
   - **W**on’t have (in deze sprint)

3. Geef issues in het project board labels voor de prioriteit.

---

## 5. Planning Poker (inschatten met story points)

Gebruik **Planning Poker** om samen de grootte/complexiteit van user stories in te schatten.

### Voorbereiding

1. Spreek een **story point schaal** af, bijvoorbeeld Fibonacci:
   - 1, 2, 3, 5, 8, 13  
2. Kies een **referentie‑story**:
   - Neem een kleine, duidelijke story en geef die bijvoorbeeld **2 punten**.
   - Vergelijk andere stories hiermee.

### Planning Poker stappen

1. Neem één user story tegelijk (beginnend bij de belangrijkste *Must have*).
2. De **Product/Client rol** of degene die de story goed kent, licht de story kort toe.
3. Iedereen kiest **in stilte** een kaart / nummer (1, 2, 3, 5, 8, 13) die past bij de inschatting.
   - Fysiek: echte kaarten of vingers.  
   - Online: Planning Poker tool of typ het punt in de chat.
4. Iedereen laat tegelijk zijn/haar keuze zien.
5. Als de waarden ver uit elkaar liggen:
   - Laat de **laagste** en **hoogste** inschatting kort uitleggen waarom.
   - Bespreek kort de aannames.
   - Stem opnieuw tot er (ongeveer) consensus is.
6. Schrijf de definitieve story points in het issue (bijv. via label of in de issue‑beschrijving).

Focus op **relatieve** grootte, niet op exacte uren.

---

## 6. Capaciteit & sprint backlog bepalen

Bekijk hoeveel werk jullie realistisch in deze sprint kunnen doen.

### Capaciteit inschatten

1. Tel per teamlid:
   - Beschikbare dagen in Sprint 19 (rekening houdend met andere vakken / verplichtingen).
2. Maak een ruwe afspraak in het team:
   - Bijvoorbeeld: “We mikken op ongeveer **X story points per persoon**”  
   - Of kijk naar eerdere sprints: hoeveel werk was toen haalbaar?

> Je hoeft niet perfect te zijn; het gaat om een **realistische** eerste inschatting.

### Sprint backlog samenstellen

1. Begin bij de **Must have** stories die het sprintdoel ondersteunen.
2. Voeg stories toe aan de sprint backlog (GitHub milestone / project board) totdat:
   - jullie geschatte capaciteit ongeveer bereikt is  
   - óf het sprintdoel goed ingevuld is
3. Laat ruimte voor:
   - onvoorziene issues  
   - bugs / technische problemen

Resultaat: een set user stories met story points die je als **Sprint 19 backlog** markeert.

---

## 7. Stories opdelen in taken

Maak de sprint backlog concreet door stories op te breken in **kleine taken**.

### Aanpak

1. Neem één story uit de sprint backlog.
2. Brainstorm welke taken nodig zijn om deze story “Done” te krijgen, bijvoorbeeld:
   - UX / ontwerp: schets, flow, Figma aanpassingen  
   - Frontend: HTML, CSS, JavaScript, componenten  
   - Toegankelijkheid: toetsenbord, screenreader test, wcag audit
   - Testing: handmatige tests, bugfixes, gebrukkerstesten  
   - Documentatie: README/Handover bijwerken

3. Zorg dat taken:
   - klein genoeg zijn om in (maximaal) 0,5–1 dag te doen  
   - duidelijk geformuleerd zijn (“Maak X”, “Test Y”, “Refactor Z”)

4. Maak van deze taken:
   - losse issues die gelinkt zijn aan de user story  
   - óf checklist‑items in het user story issue

Zet de taken in je project board (bijv. in de kolom *To Do*).

---

## 8. Definition of Ready & Definition of Done

Maak afspraken over wanneer een user story klaar is om te starten en wanneer hij echt af is.

### Definition of Ready (DoR)

Een story is **Ready** als:

- de user story duidelijk is (wie, wat, waarom)  
- er acceptatiecriteria zijn  
- afhankelijkheden bekend zijn  
- het team denkt: “We weten genoeg om te beginnen”

### Definition of Done (DoD)

Een story is **Done** als bijvoorbeeld:

- de functionaliteit werkt volgens de acceptatiecriteria  
- de UI consistent is met de styleguide  
- basis‑toegankelijkheid is gecontroleerd (toetsenbord, contrast, ARIA waar nodig)  
- alle tests slagen (wat voor jullie project relevant is)  
- code is gereviewd en gemerged  
- documentatie / Handover is bijgewerkt  

Leg DoR en DoD kort vast (bijv. in `CONTRIBUTING.md` of `team-agreements.md`).

---

## 9. Alles in het project board zetten

Zorg dat je project board de planning weerspiegelt.

### Aanpak

- Maak (of controleer) kolommen zoals:
  - Backlog  
  - To Do  
  - In Progress  
  - Review  
  - Done  
- Sleep de geselecteerde stories en taken naar de juiste kolom.
- Gebruik de **Roadmap**‑view om een tijdlijn te tonen:
  - zet start‑ en einddatum op de belangrijkste issues  
  - koppel alles aan de Sprint 19 milestone

---

## 10. Check & afsluiting

Sluit de workshop af met een korte check:

- Klopt het sprintdoel nog met de gekozen stories?  
- Is de hoeveelheid werk realistisch voor deze sprint?  
- Weet ieder teamlid:
  - wat de prioriteiten zijn?  
  - welke stories en taken hij/zij als eerste oppakt?  

Maak één laatste “review‑ronde” over het board en pas waar nodig nog small tweaks toe.

---

## Deliverables na deze workshop

Na de Sprint Planning heb je:

- een helder **Sprint 19 doel** (vastgelegd in de repo)  
- aangescherpte **epics** die het project structureren  
- een set **user stories** met acceptatiecriteria  
- **story points** voor de belangrijkste stories via Planning Poker  
- een **geprioriteerde backlog** (Must/Should/Could)  
- een **Sprint 19 roadmap** met geselecteerde stories en taken in het project board  
- een afgesproken **Definition of Ready** en **Definition of Done**
