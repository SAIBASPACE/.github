# Kontekst: CIEO-modellen

**Tid at lære:** 10 minutter
**Virker i:** Alle værktøjer

---

## Hvad er det?

CIEO er en tjekliste for komplette prompts:

- **C**ontext (Kontekst): Baggrunden
- **I**nstruction (Instruktion): Hvad skal AI'en gøre
- **E**xamples (Eksempler): Vis hvad du vil have
- **O**utput: Hvilket format skal svaret have

Ikke alle prompts behøver alle fire. Men jo flere du inkluderer, jo bedre resultat.

---

## Hvorfor virker det?

AI'en gætter når den mangler information. Hver del af CIEO fjerner gætværk:

| Del | Uden den... | Med den... |
|-----|-------------|------------|
| Context | AI'en ved ikke hvem modtageren er | Rammer den rigtige tone og detaljegrad |
| Instruction | AI'en ved ikke hvad du vil have | Gør præcis det du beder om |
| Examples | AI'en bruger sin egen stil | Kopierer din stil |
| Output | Du får en wall of text | Du får data du kan bruge direkte |

---

## Eksempel der virker

**Opgave:** Lav et LinkedIn-opslag om vores nye produkt

```
KONTEKST:
Vi er Dansk Pumpeservice, 30 ansatte, sælger varmepumper til parcelhuse.
Vores målgruppe på LinkedIn: Husejere 35-55 år, bekymrede for energipriser.
Vi har lige lanceret en ny varmepumpe der er 20% mere effektiv.

INSTRUKTION:
Skriv et LinkedIn-opslag der præsenterer den nye pumpe.
Fokusér på besparelsen i kroner, ikke tekniske specs.

EKSEMPEL PÅ TONE (fra vores tidligere opslag der virkede):
"Der er ingen grund til at fryse i februar. Eller betale overpris for det. 
Vi har regnet på det: En gennemsnitlig villa bruger 18.000 kr på varme om året..."

OUTPUT:
- Overskrift: Max 10 ord, skal skabe nysgerrighed
- Brødtekst: 50-80 ord
- Afslut med spørgsmål (ikke CTA om at købe)
```

**Resultat:** Opslag i præcis jeres tone, klar til at poste.

---

## Eksempel der fejler

```
Skriv et LinkedIn-opslag om vores nye varmepumpe
```

**Hvad AI'en ikke ved:**
- Hvem er I?
- Hvem er målgruppen?
- Hvad er unikt ved pumpen?
- Hvordan lyder jeres brand?
- Hvor langt skal opslaget være?

**Resultat:** Generisk opslag der lyder som alle andres.

---

## CIEO i praksis: 3 eksempler

### 1. Simpel opgave (kun I + O)

```
INSTRUKTION: Oversæt denne tekst til engelsk.
OUTPUT: Kun oversættelsen, ingen forklaring.

"Vi sender din ordre inden for 2 hverdage."
```

Simpelt = færre dele nødvendige.

---

### 2. Medium opgave (C + I + O)

```
KONTEKST: 
Jeg er controller og skal forklare vores Q3-resultat til bestyrelsen.
Bestyrelsen er ikke økonomer - de vil have konklusioner, ikke detaljer.

INSTRUKTION:
Omskriv dette afsnit så det er forståeligt for ikke-økonomer.

"EBITDA-marginen faldt fra 12,3% til 9,8% grundet øgede COGS 
som følge af supply chain disruptions og FX-headwinds på USD-denominerede inputs."

OUTPUT:
Max 2 sætninger. Ingen forkortelser. Inkludér hvad det betyder i kroner.
```

---

### 3. Kompleks opgave (fuld CIEO)

```
KONTEKST:
Jeg er sælger i en dansk IT-virksomhed med 15 ansatte.
Jeg skriver til IT-chefer i produktionsvirksomheder.
Vores produkt: Software til lagerstyring.
USP: Implementering på under 2 uger (konkurrenter tager 2-3 måneder).

INSTRUKTION:
Skriv en kold email der booker et kvalificerende opkald.

EKSEMPEL PÅ TONE:
"Hej [Navn], jeg skriver fordi I lige har åbnet nyt lager i Horsens 
(tillykke med det). De fleste i jeres situation kæmper med [problem]. 
Gør I det også, eller har I styr på det?"

OUTPUT:
- Emnelinje: Max 5 ord, ingen salgs-klichéer
- Email: Max 80 ord
- CTA: Spørg om 15 min opkald, foreslå konkret tid
```

---

## Øvelse (5 minutter)

Tag denne dårlige prompt:

```
Skriv en kundeklage-besvarelse
```

Omskriv den med CIEO. Brug denne situation:
- Du arbejder i kundeservice hos en webshop
- Kunden har ventet 14 dage på en pakke der blev lovet på 3-5 dage
- I vil tilbyde gratis fragt på næste ordre
- Kunden hedder Mette og er tydeligt frustreret

Test begge prompts. Hvor lang tid tager det at rette output fra den dårlige vs. den gode?

---

## Huskeregel

> "Jo mere du giver, jo mindre skal du rette bagefter."

5 minutter ekstra på prompten = 20 minutter sparet på at redigere output.

---

## Næste lektion

[03 - Eksempler i prompts (Few-shot) →](./03-eksempler-i-prompt.md)
