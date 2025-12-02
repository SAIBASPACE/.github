# Output format: Få data du kan bruge

**Tid at lære:** 5 minutter
**Virker i:** Alle værktøjer

---

## Hvad er det?

Du fortæller AI'en præcis hvordan svaret skal se ud:
- Tabel
- Punktliste
- Nummereret liste
- JSON
- Email-format
- Specifik længde

---

## Hvorfor virker det?

Uden format-instruktion får du en "wall of text" du skal omformatere selv.

Med format-instruktion får du data klar til at:
- Kopiere ind i Excel
- Sende som email
- Bruge i et andet system

---

## Eksempel der virker

**Opgave:** Analysér kundefeedback

```
Her er 10 kommentarer fra kundetilfredshedsundersøgelse:
[KOMMENTARER]

Kategorisér hver kommentar.

OUTPUT FORMAT:
Tabel med kolonnerne:
| # | Kategori | Positiv/Negativ | Citat (max 10 ord) |

Kategorier at bruge: Levering, Produkt, Service, Pris, Andet
```

**Resultat:** 
| # | Kategori | Positiv/Negativ | Citat |
|---|----------|-----------------|-------|
| 1 | Levering | Negativ | "Ventede 2 uger på pakken" |
| 2 | Service | Positiv | "Hurtig hjælp i chatten" |

**Klar til at kopiere direkte i Excel.**

---

## Eksempel der fejler

```
Analysér denne kundefeedback og fortæl mig hvad kunderne synes
```

**Resultat:** 5 afsnit prosa du skal læse og selv lave til handling.

---

## Format-eksempler du kan bruge

### Tabel (til Excel)
```
Output som tabel med kolonnerne: [Kolonne1], [Kolonne2], [Kolonne3]
```

### Punktliste
```
Output som punktliste. Max 5 punkter. Hvert punkt max 15 ord.
```

### Email-klar
```
Output som email med:
- Emnelinje
- Kære [navn]
- Brødtekst
- Venlig hilsen
```

### JSON (til systemer)
```
Output som JSON:
{
  "kunde": "navn",
  "problem": "beskrivelse",
  "prioritet": "høj/mellem/lav"
}
```

### Specifik længde
```
Max 50 ord.
Præcis 3 bullet points.
Max 2 sætninger pr. afsnit.
```

---

## Kombination: Format + begrænsning

```
Giv mig 5 forslag til blogindlæg-emner.

Format:
| # | Overskrift (max 8 ord) | Vinkel (1 sætning) |

Begrænsning: Ingen emner om AI eller digitalisering (det har vi skrevet om).
```

---

## Praktisk: De 5 mest brugte formater i erhvervslivet

### 1. Meeting notes
```
Output:
## Beslutninger
- [liste]

## Handlinger
| Hvad | Hvem | Deadline |

## Parkeret til senere
- [liste]
```

### 2. Email-svar
```
Output som email.
Tone: Professionel men varm.
Max 100 ord.
Inkludér ikke "Jeg håber denne email finder dig vel" eller lignende fyld.
```

### 3. Rapport-afsnit
```
Output som afsnit til intern rapport.
Ingen bullets.
3-4 sætninger.
Afslut med anbefaling.
```

### 4. Social media
```
Output:
- Hook (første linje, max 10 ord)
- Brødtekst (max 60 ord)
- CTA (spørgsmål, ikke salgstale)
```

### 5. Analyse-resultat
```
Output:
1. Konklusion (1 sætning)
2. Top 3 indsigter (bullets)
3. Anbefalet handling (1 sætning)
```

---

## Øvelse (3 minutter)

Test forskellen:

**Prompt 1 (uden format):**
```
Hvad er fordelene ved varmepumper?
```

**Prompt 2 (med format):**
```
Hvad er fordelene ved varmepumper for danske husejere?

Output:
Tabel med 5 rækker.
Kolonnerne: Fordel | Årlig besparelse (ca.) | Forudsætning
```

Hvilken er mest brugbar hvis du skal lave en salgspræsentation?

---

## Næste lektion

[05 - Kæde tanker (Chain-of-Thought) →](./05-kaede-tanker.md)
