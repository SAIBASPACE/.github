# Kæde tanker (Chain-of-Thought)

**Tid at lære:** 5 minutter
**Virker i:** Alle værktøjer (mest effektivt i GPT-4, Claude, Gemini Pro)

---

## Hvad er det?

Du beder AI'en vise sine mellemregninger før den giver et svar.

Ligesom en matematiklærer siger: "Vis dit arbejde."

---

## Hvorfor virker det?

AI'er laver fejl når de springer direkte til konklusionen. Ved at tvinge dem til at tænke trin-for-trin:
- Færre fakta-fejl
- Bedre logiske slutninger
- Du kan se HVOR den gik galt (og rette)

---

## Eksempel der virker

**Opgave:** Vurdér om vi skal tage denne kunde

```
Vi overvejer at tage en ny kunde. Her er situationen:

Kunde: Mellemstor produktionsvirksomhed, 80 ansatte
Projekt: Nyt lagerstyringssystem
Budget: 400.000 kr
Tidslinje: Go-live om 6 uger
Vores kapacitet: 2 konsulenter ledige, normalt bruger vi 3 på denne type

Analysér trin-for-trin:
1. Hvad er risiciene?
2. Hvad er mulighederne?
3. Hvad ville worst-case scenario koste os?
4. Hvad ville best-case scenario give os?
5. Baseret på ovenstående: Anbefaling (tag/tag ikke/tag med forbehold)
```

**Resultat:** Struktureret analyse du kan præsentere for ledelsen, ikke bare "ja" eller "nej".

---

## Eksempel der fejler

```
Skal vi tage denne kunde? Budget 400k, 6 uger, vi mangler en mand.
```

**Resultat:** AI'en gætter på "ja" eller "nej" uden at veje fordele/ulemper. Du ved ikke hvorfor.

---

## Hvornår skal du bruge Chain-of-Thought?

| Situation | Brug CoT? |
|-----------|-----------|
| Kompleks beslutning | Ja |
| Beregninger | Ja |
| Analyse af data | Ja |
| Simpel omskrivning | Nej |
| Oversættelse | Nej |
| Kort faktaspørgsmål | Nej |

**Tommelfingerregel:** Hvis du selv ville bruge mere end 30 sekunder på at tænke over svaret, så brug CoT.

---

## 3 måder at aktivere Chain-of-Thought

### 1. Den simple
```
Tænk trin-for-trin før du svarer.
```

### 2. Den strukturerede
```
Analysér i denne rækkefølge:
1. [Trin 1]
2. [Trin 2]
3. [Trin 3]
4. Konklusion baseret på ovenstående
```

### 3. Den eksplicitte
```
Før du giver dit endelige svar:
- List hvad der taler FOR
- List hvad der taler IMOD
- Vurdér sandsynligheder
- Giv derefter din anbefaling
```

---

## Praktiske eksempler

### Økonomisk beslutning
```
Vi overvejer at købe ny CNC-maskine.
Pris: 1,2 mio kr
Forventet produktivitetsøgning: 25%
Nuværende maskinens alder: 12 år

Analysér trin-for-trin:
1. Beregn simpel payback-tid
2. Hvad er risikoen ved at beholde den gamle maskine?
3. Hvad er risikoen ved at købe nu?
4. Anbefaling med begrundelse
```

### Personalebeslutning
```
Medarbejder har søgt om at gå ned i tid (32 timer).
Rolle: Sælger, 3 år i firmaet, performance over gennemsnit.

Tænk igennem:
1. Hvad mister vi? (timer, fleksibilitet)
2. Hvad vinder vi? (fastholdelse, motivation)
3. Alternativer til at sige ja/nej?
4. Anbefaling
```

### Vurdér tilbud fra leverandør
```
Leverandør tilbyder 15% rabat hvis vi binder os 2 år.
Nuværende årligt forbrug: 800.000 kr

Beregn trin-for-trin:
1. Hvor meget sparer vi over 2 år?
2. Hvad er risikoen ved at være låst?
3. Hvad er alternativet? (forhandle uden binding?)
4. Anbefaling
```

---

## Øvelse (5 minutter)

Prøv begge versioner:

**Version A (uden CoT):**
```
Skal vores virksomhed begynde at bruge AI til kundeservice?
```

**Version B (med CoT):**
```
Skal vores virksomhed (dansk webshop, 10 ansatte, 500 kundehenvendelser/måned) 
begynde at bruge AI til kundeservice?

Analysér trin-for-trin:
1. Hvilke opgaver i kundeservice kan AI realistisk håndtere i dag?
2. Hvad er omkostningen ved de løsninger? (gratis til enterprise)
3. Hvad er risikoen for kundetilfredsheden?
4. Hvad er gevinsten i sparede timer?
5. Konklusion: Start nu, vent, eller test først?
```

Sammenlign dybden og anvendeligheden af de to svar.

---

## Næste lektion

[06 - Multi-review (selvkritik) →](./06-multi-review.md)
