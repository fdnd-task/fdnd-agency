# Opdracht: Design System voor een bestaand project (CMD @ FDND Agency)

## Context
Je werkt aan een bestaand FDND Agency‑project: er is al een live website én één of meerdere Figma‑files. Het design is in de loop van tijd gegroeid en niet altijd consistent. Met een Design System ga jij:

1. Het huidige design van de website **analyseren en verbeteren**.  
2. Het project **beter overdraagbaar** maken voor een volgend team (design én development).

---

## Opdracht

Ontwerp en documenteer een **Design System in Figma** voor jouw project, op basis van de bestaande website en Figma‑designs. Dit Design System:

- is gebaseerd op een **interface inventory** en **UI‑audit** van de huidige website;  
- bevat **design tokens** (colors, type, spacing, etc.) die aansluiten op de codebase;  
- definieert **herbruikbare componenten** en states;  
- is **gedocumenteerd** zodat een volgend team ermee verder kan.

---

## Leerdoelen

Na deze opdracht kun je:

- bestaande UI analyseren en patronen/inconsistenties herkennen;  
- een **Design System met tokens** opzetten in Figma;  
- met developers afstemmen hoe tokens en componenten in code worden toegepast;  
- een systeem zó documenteren dat het overdraagbaar is.

---

## Aanpak

### 1. Interface Inventory & UI‑audit
- Inventariseer alle belangrijke schermen en states (website + Figma).  
- Maak een interface inventory in Figma (typografie, kleurgebruik, buttons, forms, cards, navigatie, etc.).  
- Noteer inconsistenties en dubbels (keep / merge / remove).

### 2. Scope Design System bepalen
- Bepaal de **v1‑scope**: welke foundations (color, type, spacing, radius, shadow) en welke basiscomponenten (buttons, inputs, cards, nav, alerts) pak je mee?  
- Leg kort vast wat binnen scope / buiten scope valt.

### 3. Foundations & Design Tokens in Figma
- Definieer design tokens en leg ze vast als Figma styles:
  - Kleuren (brand, text, background, semantic)  
  - Typografie (headings, body, captions)  
  - Spacing‑schaal, radius, shadows  
- Stem naming en structuur af met developers (mapping design → code).

### 4. Componenten bouwen op tokens
- Bouw de afgesproken basiscomponenten in Figma op basis van je tokens.  
- Maak variants voor states (default, hover, active, disabled, focus).  
- Voeg per component een kort blokje **purpose / varianten / do’s & don’ts** toe.

### 5. Afstemmen met developers
- Loop samen door tokens en componenten: hoe landen deze in de code?  
- Zorg dat minimaal 1–2 componenten (bijv. Button, Alert) in code op je Design System zijn gebaseerd.  
- Pas zo nodig tokens/naming aan op basis van dev‑feedback.

### 6. Documenteren & overdraagbaar maken
- Maak in Figma een duidelijke **overzichtspagina** van het Design System (foundations, componenten, links naar code).  
- Schrijf een korte **“How to use this Design System”** voor een volgend team:
  - Hoe een nieuwe pagina te ontwerpen  
  - Hoe nieuwe componenten voor te stellen / toe te voegen  
- Presenteer de belangrijkste keuzes in het **Design Chapter** en leg eventuele voorgestelde conventies vast.

---

## Deliverables

- Figma‑file met:
  - **Interface Inventory + UI‑audit**
  - **Foundations & design tokens** (styles + naming)  
  - **Component library** (met states en beknopte guidelines)  
  - **Overzichtspagina + “How to use”**   
- Korte **presentatie/demo** aan Design Chapter / Agency (5–10 minuten).

---

## Bronnen

### Design systems & voorbeelden
- 12 Design System Examples (Figma)  
  https://www.figma.com/resource-library/design-system-examples/  
- Design Systems & UI Kits directory  
  https://designsystems.intodesignsystems.com/  

### Design tokens & Figma variables
- Atlassian – Overview Tokens  
  https://atlassian.design/foundations/tokens/  
- Figma Design Tokens: How to Build a Scalable Design System  
  https://sergeichyrkov.com/blog/how-to-build-a-figma-design-system-with-variables-and-design-tokens  
- Design Tokens Workflow in Figma — A practical guide  
  https://intodesignsystems.medium.com/design-tokens-workflow-in-figma-a-practical-guide-1efd508250ad  

### Structuur, audit & documentatie
- The Design System Guide – resources  
  https://thedesignsystem.guide/resources  
- Figma Design Systems in 2026: 26 Scalable Features & Tips  
  https://zeroheight.com/blog/building-scalable-design-systems-with-figma-26-tips-for-2026/
