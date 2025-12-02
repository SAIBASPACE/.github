# Persona: Giv AI'en en rolle

**Tid at lære:** 5 minutter
**Virker i:** Alle værktøjer (ChatGPT, Claude, Copilot, Gemini)

---

## Hvad er det?

Du fortæller AI'en hvem den er, før du giver den en opgave. 

Ligesom du ville bede en revisor om skattehjælp (ikke en bartender), giver en persona AI'en den rigtige "ekspertise" at trække på.

---

## Hvorfor virker det?

- **Rigtig tone:** En "HR-chef" skriver anderledes end en "sælger"
- **Rigtige fagtermer:** En "controller" bruger regnskabssprog automatisk
- **Færre hallucinationer:** AI'en holder sig inden for rollens ekspertise

---

## Eksempel der virker

**Opgave:** Skriv afslagsbrev til jobansøger

```
Du er HR-chef i en dansk mellemstor virksomhed med 50 ansatte. 
Du har 10 års erfaring og lægger vægt på at behandle kandidater respektfuldt.

Skriv et afslagsbrev til en kandidat der søgte en stilling som projektleder.
Vi valgte en anden med mere erfaring inden for byggebranchen.
Kandidatens navn: Thomas Nielsen
Tone: Professionel men varm. Vi vil gerne have han søger igen.
```

**Resultat:** Personligt brev med korrekt HR-sprog, ikke en kold standardskabelon.

---

## Eksempel der fejler

```
Skriv et afslagsbrev til Thomas
```

**Hvorfor det fejler:**
- Ingen kontekst om virksomheden
- Ingen tone-angivelse
- Ingen grund til afslaget
- AI'en gætter på alt → generisk output

---

## Personas du kan bruge i morgen

| Din opgave | Persona |
|------------|---------|
| Kundeklage | "Erfaren kundeservicechef der prioriterer at beholde kunder" |
| Salgsmail | "B2B-sælger med 10 års erfaring i consultative selling" |
| Regnskabsforklaring | "Controller der forklarer tal til ikke-økonomer" |
| Kontrakt-review | "Juridisk assistent med fokus på risici for køber" |
| Teknisk dokumentation | "IT-supporter der skriver til ikke-tekniske brugere" |
| LinkedIn-opslag | "Marketing-ansvarlig i dansk SMV, autentisk tone" |

---

## Avanceret: Kombinér persona med begrænsninger

```
Du er erfaren dansk tekstforfatter med speciale i B2B-kommunikation.

Begrænsninger:
- Du skriver ALDRIG "I en verden hvor..." eller andre klichéer
- Du bruger korte sætninger (max 15 ord)
- Du undgår engelske buzzwords når der findes danske alternativer
```

Dette fjerner det "AI-agtige" sprog mange klager over.

---

## Øvelse (2 minutter)

1. Åbn ChatGPT, Claude eller Copilot
2. Indtast denne prompt uden persona:
   ```
   Skriv en mail om at vi hæver priserne 5%
   ```
3. Indtast nu med persona:
   ```
   Du er salgsdirektør i en dansk produktionsvirksomhed. 
   Du har langvarige kunderelationer og hader bullshit.
   
   Skriv en mail til eksisterende kunder om at vi hæver priserne 5% fra 1. februar.
   Grund: Øgede råvarepriser.
   Tone: Ærlig, direkte, ikke undskyldende.
   Max 100 ord.
   ```

**Sammenlign de to svar.** Hvilket ville du sende til en kunde?

---

## Næste lektion

[02 - Kontekst →](./02-kontekst.md)
