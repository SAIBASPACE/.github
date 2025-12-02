# Eksempler i prompts (Few-shot)

**Tid at lære:** 5 minutter
**Virker i:** Alle værktøjer

---

## Hvad er det?

Du viser AI'en 1-3 eksempler på hvad du vil have, før du beder den lave noget.

- **Zero-shot:** Ingen eksempler (AI'en gætter på stilen)
- **One-shot:** Ét eksempel (AI'en forstår mønsteret)
- **Few-shot:** 2-3 eksempler (AI'en nagrer stilen præcist)

---

## Hvorfor virker det?

Det er lettere at vise end at forklare.

Prøv at forklare med ord hvordan din virksomheds "tone" lyder. Svært, ikke?

Giv i stedet AI'en 2 eksempler på tekster I har skrevet. Nu kopierer den stilen automatisk.

---

## Eksempel der virker

**Opgave:** Skriv produktbeskrivelser til webshop i vores stil

```
Skriv produktbeskrivelser til vores webshop.

Her er 2 eksempler på vores nuværende stil:

EKSEMPEL 1:
Produkt: Bambus skærebræt
"Dit gamle skærebræt er sikkert fint. Men det her er lavet af bambus 
der gror 30 gange hurtigere end træ. Godt for planeten. Og knivene."

EKSEMPEL 2:
Produkt: Genanvendt håndklæde
"Blødt som et almindeligt håndklæde. Bare lavet af 12 genbrugte 
plastikflasker. Du kan ikke mærke forskel. Havet kan."

---

Skriv nu beskrivelse til:
Produkt: Stålsugerør (sæt med 4)
Specs: Rustfrit stål, inkl. børste, holder 10+ år
```

**Resultat:** Beskrivelse i præcis samme korte, punchline-agtige stil.

---

## Eksempel der fejler

```
Skriv en produktbeskrivelse til stålsugerør. 
Tonen skal være bæredygtig og lidt humoristisk.
```

**Hvorfor det fejler:**
- "Lidt humoristisk" betyder 100 forskellige ting
- AI'en bruger sin default-stil (ofte kedelig eller over-the-top)
- Du skal redigere meget for at ramme jeres tone

---

## Hvornår skal du bruge eksempler?

| Situation | Brug eksempler? |
|-----------|-----------------|
| Tekst skal matche jeres brand | Ja, altid |
| Kategorisering af data | Ja, vis 2-3 korrekte kategoriseringer |
| Oversættelse | Nej, medmindre I har særligt ordvalg |
| Opsummering | Nej, medmindre du vil have specifikt format |
| Kodning | Ja, vis den stil du foretrækker |

---

## Praktisk: Saml dine eksempler

Lav et dokument med "gyldne eksempler" fra din virksomhed:

```
# Vores eksempelbank

## Kundemails (god tone)
[Eksempel 1]
[Eksempel 2]

## Produktbeskrivelser
[Eksempel 1]
[Eksempel 2]

## LinkedIn-opslag der performede
[Eksempel 1]
[Eksempel 2]
```

Kopier relevante eksempler ind i prompts. Det tager 10 sekunder og sparer 10 minutter.

---

## Avanceret: Negative eksempler

Vis også hvad du IKKE vil have:

```
Skriv en LinkedIn-opslag om vores nye kontor.

STIL VI VIL HAVE (eksempel):
"Vi har flyttet. Nye lokaler i Aarhus C. Mere plads, samme mennesker, 
bedre kaffe. Kig forbi."

STIL VI IKKE VIL HAVE:
"Vi er UTROLIGT begejstrede for at kunne annoncere at vi er flyttet 
ind i FANTASTISKE nye lokaler! Dette er en KÆMPE milepæl for os! 🎉🚀"

Skriv opslaget.
```

---

## Øvelse (5 minutter)

1. Find en email du har sendt til en kunde (god tone)
2. Find en email fra en kollega i samme stil
3. Brug denne prompt:

```
Her er 2 eksempler på hvordan vi skriver til kunder:

EKSEMPEL 1:
[Indsæt din email]

EKSEMPEL 2:
[Indsæt kollegas email]

---

Skriv nu en email til en kunde der spørger om leveringstid på ordre #12345.
Svar: Vi sender i morgen, levering onsdag.
```

Sammenlign resultatet med hvad du normalt ville skrive. Hvor tæt er det?

---

## Næste lektion

[04 - Output format →](./04-output-format.md)
