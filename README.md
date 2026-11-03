# Roans Hanze Document Skill

Een AI-skill met alles wat je nodig hebt om een document voor de Hanzehogeschool Groningen te maken: de opbouw, de opmaak, de inleverregels, de stijl en de valkuilen. Bedoeld voor het ICT-rapport in de NSE-lijn, maar bruikbaar voor elk verslag, plan of advies.

## Wat erin zit

- De vaste opbouw van een rapport, van omslag tot bijlagen.
- Opmaakeisen: lettertype, marges, paginanummering vanaf de inleiding, figuren en tabellen.
- Inleverregels: PDF via het inleverpunt, per mail naar de begeleider, en het rapport is individueel.
- De stijlregels voor zakelijk en neutraal schrijven.
- Valkuilen die in de praktijk misgaan, zoals kop-stijlen in het voorwerk en velden die met F9 bijgewerkt moeten worden.

## Reference

In `references/` staat het bronmateriaal:

- `25-26 Schrijfwijzer Rapportage ICT_SCMI_def.md`, de schrijfwijzer van de opleiding: de basis voor de vorm van elk document.
- Zes uitgewerkte colleges van Schriftelijke Vaardigheden: introductie, inleiding, brongebruik, kernhoofdstukken, conclusie en aanbevelingen, en herschrijven.

De SKILL.md heeft een index die per bestand zegt waar het over gaat, zodat alleen de reference laadt die bij de taak hoort.

## Gebruik

Zet de map in je skills-directory of voeg hem toe als externe skill-map:

```
skills:
  external_dirs:
    - /pad/naar/Roans-Hanze-Document-Skill
```

## Aanbevolen

Wist je dat je AI onzichtbare watermerken achterlaat en dat docenten daardoor kunnen zien dat je AI gebruikt? Je kan dit gemakkelijk fixen door aan je AI te vragen om github.com/guillaumemeyer/watermarks-remover te installeren.

## Herkomst

De inhoud komt uit de colleges van Schriftelijke Vaardigheden van project thema 2.1 NSE, studiejaar 2026-2027, aangevuld met de Schrijfwijzer van de opleiding. De bestandsnamen van de originele sleeppresentaties staan in de kop van elke reference.
