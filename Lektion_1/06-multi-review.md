# Multi-review: Få AI'en til at tjekke sig selv

**Tid at lære:** 5 minutter
**Virker i:** Alle værktøjer

---

## Hvad er det?

Du beder AI'en:
1. Lave et udkast
2. Kritisere sit eget udkast
3. Lave en forbedret version

Det er som at have en kollega der læser korrektur - bare gratis og på 10 sekunder.

---

## Hvorfor virker det?

AI'er laver fejl i første forsøg, men er gode til at finde fejl når de leder.

Ved at splitte opgaven i "skriv" og "kritisér" får du:
- Færre fejl
- Bedre struktur
- Output der er tættere på klar-til-brug

---

## Eksempel der virker

**Opgave:** Skriv kundeservice-svar

```
Trin 1: Skriv et svar til denne kundeklage:
"Jeg har ventet 3 uger på min ordre. Det er fuldstændig uacceptabelt. 
Jeg vil have pengene retur."

Trin 2: Gennemgå dit eget svar kritisk:
- Er tonen for undskyldende eller for defensiv?
- Mangler der konkret handling?
- Er der noget der kan misforstås?

Trin 3: Skriv en forbedret version baseret på din kritik.
```

**Resultat:** Et gennemarbejdet svar, ikke et første udkast.

---

## Eksempel der fejler

```
Skriv et godt svar til en kunde der klager over forsinkelse.
```

**Resultat:** AI'ens første indskydelse. Ofte for langt, for formelt, eller mangler konkret handling.

---

## 4 review-typer du kan bruge

### 1. Generel kvalitetskontrol
```
[Dit output]

Gennemgå nu dit svar:
- Hvad er den største svaghed?
- Hvad ville en kritisk læser påpege?
- Skriv en forbedret version.
```

### 2. Målgruppe-review
```
[Dit output]

Læs dette som om du er [MÅLGRUPPE].
- Hvad ville forvirre dem?
- Hvad ville de mangle?
- Hvad ville de springe over?
Tilpas teksten baseret på dette.
```

### 3. Fakta-tjek
```
[Dit output]

Gennemgå hvert faktuelt udsagn i teksten:
- Marker usikre påstande med [TJEK]
- Marker potentielt forældede tal med [OPDATER]
- Giv mig listen så jeg kan verificere manuelt.
```

### 4. Tone-review
```
[Dit output]

Vurdér tonen:
- For formel / for uformel?
- For sælgende / for defensiv?
- For langt / for kort?
Tilpas til [ØNSKET TONE].
```

---

## Praktisk: One-shot multi-review

Du kan gøre det i én prompt:

```
Skriv en LinkedIn-anbefaling af min kollega Peter, der skifter job.
Vi har arbejdet sammen i 3 år på IT-projekter. Han er god til at holde ro i kaos.

Når du har skrevet udkastet:
1. Kritisér det: Er det for generisk? For overdrevent?
2. Skriv en forbedret version der føles ægte.
```

---

## Avanceret: Devil's Advocate review

Bed AI'en angribe sin egen konklusion:

```
Du har lige anbefalet at vi vælger leverandør A.

Skift nu perspektiv: Du er advokat for leverandør B.
Giv 3 grunde til at vores analyse er forkert.

Baseret på denne kritik: Holder anbefalingen stadig?
```

---

## Hvornår skal du bruge multi-review?

| Situation | Brug multi-review? |
|-----------|-------------------|
| Ekstern kommunikation (kunder, presse) | Ja |
| Vigtige interne dokumenter | Ja |
| Hurtige interne noter | Nej |
| Brainstorm/idégenerering | Nej |
| Analyse med konsekvenser | Ja |

**Tommelfingerregel:** Hvis du normalt ville bede en kollega læse det igennem, så brug multi-review.

---

## Øvelse (5 minutter)

**Del 1:** Brug denne simple prompt:
```
Skriv en kort præsentation af vores virksomhed til en potentiel samarbejdspartner.
Vi er en dansk IT-konsulentvirksomhed med 20 ansatte, speciale i Microsoft-løsninger.
```

**Del 2:** Brug denne multi-review prompt:
```
Skriv en kort præsentation af vores virksomhed til en potentiel samarbejdspartner.
Vi er en dansk IT-konsulentvirksomhed med 20 ansatte, speciale i Microsoft-løsninger.

Når du har skrevet:
1. Kritisér teksten: Hvad lyder generisk? Hvad mangler vi?
2. Hvad ville få os til at skille os ud fra 100 andre IT-konsulenter?
3. Skriv en forbedret version der er mere specifik og interessant.
```

**Sammenlign de to resultater.**

---

## Næste lektion

[07 - Flipped Interaction (lad AI'en spørge) →](./07-flipped-interaction.md)
