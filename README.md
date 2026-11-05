# Kochbuch

Rezeptesammlung als GitHub-Pages-Seite.

**➜ Zum Kochbuch: [familien-kochbuch.github.io/Kochbuch](https://familien-kochbuch.github.io/Kochbuch/)**

## Rezept hinzufügen

Alle Rezepte stehen in `rezepte.json`. Ein Rezept sieht so aus:

```json
{
  "id": "omas-rouladen",
  "titel": "Omas Rinderrouladen",
  "kategorie": "haupt-fleisch",
  "von": "Oma",
  "portionen": 4,
  "zeit": 120,
  "tags": ["Familienklassiker", "Für Gäste"],
  "zutaten": ["4 Rinderrouladen", "2 EL Senf", "4 Scheiben Speck"],
  "schritte": ["Rouladen flach klopfen.", "Mit Senf bestreichen und belegen."],
  "notizen": "Schmeckt am nächsten Tag noch besser."
}
```

- `id`: kurz, nur Kleinbuchstaben und Bindestriche, einmalig (wird Teil des Links)
- `kategorie`: fruehstueck, suppen, haupt-fleisch, haupt-fisch, haupt-veggie, beilagen, auflaeufe, desserts, kuchen, brot, weihnachten, getraenke, saucen
- `tags`: Schnell (unter 30 Min.), Vegetarisch, Vegan, Kinderliebling, Für Gäste, Familienklassiker, Gut vorzubereiten
- `zutaten`: eine Zutat pro Eintrag, Menge zuerst, damit der Portionsrechner funktioniert
