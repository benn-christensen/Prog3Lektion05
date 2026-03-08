# Opgaver lektion 5

## Opgave 1
Lav en `Bil` klasse med attributterne registreringsnummer, mærke, model og farve (og constructor, `toString` samt get/set metoder).

Lav en `App` klasse med en `main()` metode. Opret et `HashSet` og indsæt nogle `Bil` objekter i denne. Lav flere biler med præcis de samme attributter.

**Spørgsmål:** Hvad sker der, når man indsætter to bil objekter der har præcis de samme attributter i det samme `HashSet`?

To biler skal opfattes som værende det samme objekt, hvis de har samme registreringsnummer og mærke. Lav de ændringer der skal til, for at sådanne to biler opfattes som ens. Det betyder, at der kun skal kunne være en bil med samme registreringsnummer og mærke i det samme `HashSet`. Prøv det af ved at indsætte objekter i `HashSet`.

---

## Opgave 2

I denne opgave skal I implementere `Dictionary` interfacet igen, med denne gange skal I bruge hashing.

**Bemærk:** `null` er ikke tilladt som hverken nøgle eller værdi.

I den udleverede kode er der lavet en delvis implementation `DictionaryHashMap`, der implementerer interfacet som et array af `java.util.HashMap`. Kollision håndteres ved kædereglen. Hashfunktionen er givet ved $h(x) = x \pmod N$.

1. Læs den udleverede kode, så du er sikker på at du forstår den inden du går i gang med at programmere.
2. Programmer de manglende metoder (`// TODO`).
3. Lav en applikation der afprøver implementationen.

---

## Opgave 3
Lav endnu en implementation så `Dictionary` interfacet realiseres ved et array af `List`'s (fra Javas Collection framework). Kollision håndteres ved kædereglen. Hashfunktionen er givet ved $h(x) = x \pmod N$.

Hvad er størrelsesordenen af tidskompleksiteten for de forskellige metoder?

---
