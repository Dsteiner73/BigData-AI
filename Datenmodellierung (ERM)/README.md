# Datenmodellierung (ERM)

Zwei ergänzende KI-Skills für die Arbeit mit Entity-Relationship-Modellen: vom fachlichen Chen-Modell bis zum relationalen Schema.

## Welcher Skill passt?

| Merkmal | ER-Modelle nach Chen | Relationale ERD |
| --- | --- | --- |
| Schwerpunkt | Fachliche Struktur und Geschäftsregeln | Relationale Tabellenstruktur und Integrität |
| Symbole | Entitäten als Rechtecke, Beziehungen als Rauten, Attribute als Ellipsen | Tabellenkästen mit Attributzeilen und Crow's-Foot-Verbindungen |
| Schlüssel | Unterstrichene Identifikatoren | PK, FK und weitere Constraints |
| Beteiligungen | Min-Max-Angaben an der teilnehmenden Entität | Kardinalität am jeweiligen Beziehungsende |
| Standardausgabe | PNG-Vorschau und editierbares SVG | PNG-Vorschau, editierbares SVG und strukturierte Modellquelle |
| Arbeitsanweisung | [erstelle-chen-erm/SKILL.md](erstelle-chen-erm/SKILL.md) | [modelliere-relationale-erd/SKILL.md](modelliere-relationale-erd/SKILL.md) |

**Die Leseregeln unterscheiden sich:** Bei Chen-Min-Max bezeichnet der Wert die Beziehungsteilnahmen der unmittelbar zugehörigen Entität. Bei Crow's-Foot bezeichnet das Endsymbol die mögliche Zahl von Instanzen an diesem Ende für eine Instanz am anderen Ende.

## Beispiel: Chen-Modell erstellen

Bei eingerichtetem Skill:

> Nutze $erstelle-chen-erm. Erstelle ein Chen-Modell mit Min-Max-Beteiligungen: Jedes Exemplar gehört genau einem Buchtitel. Ein Buchtitel darf ohne Exemplar bestehen. Jede Ausleihe verbindet genau ein Mitglied und ein Exemplar. Mitglieder und Exemplare dürfen ohne Ausleihen bestehen. Historische Ausleihen bleiben erhalten. Kennzeichne ergänzte Attribute als Vorschläge und liefere PNG, SVG sowie die Geschäftsregeln in beiden Leserichtungen.

Zeitliche Überschneidungen von Ausleihen sind als zusätzliche Geschäftsregel zu behandeln. Sie werden durch die Kardinalität allein nicht ausgeschlossen.

## Beispiel: Relationales ERD erstellen

Bei eingerichtetem Skill:

> Nutze $modelliere-relationale-erd. Erzeuge aus denselben Geschäftsregeln ein relationales ERD mit Tabellen, PK/FK, Nullbarkeit und Crow's-Foot-Verbindungen. Wähle technische Identifikatoren ausdrücklich als Entwurfsvorschlag. Liefere PNG, SVG und JSON-Modellquelle. Benenne zusätzliche Integritätsregeln, die nicht allein durch die gezeichneten Fremdschlüssel gesichert sind.

## Bestehendes Modell prüfen

> Prüfe das beigefügte Modell. Bestimme zuerst Modellierungsebene und Notation. Trenne sichtbare Eigenschaften, fachliche Annahmen und nicht nachgewiesene Regeln. Erkläre die wichtigste Korrektur anhand eines konkreten Gegenbeispiels.

Bei Bildern sollen unlesbare oder nicht dargestellte Eigenschaften offenbleiben. Ein fehlender Bildnachweis ist kein Beweis für einen Fehler in der Datenbank.

## Enthaltene Referenzen

### Chen

- [Fachliche Prüffälle](erstelle-chen-erm/references/prueffaelle.md): Werkstatt, Bestellung, Kursbuchung und Ausleihe.

### Relationale ERD

- [Darstellungsstandard](modelliere-relationale-erd/references/darstellungsstandard.md): Tabellenstil, Verbindungslinien und Endsymbole.
- [Integritätsmuster](modelliere-relationale-erd/references/integritaetsmuster.md): Zuordnungstabellen, optionale Erweiterungen, Eigentum und Auswahl, rekursive Beziehungen sowie Grenzen von Constraints.
- [Prüffälle](modelliere-relationale-erd/references/prueffaelle.md): Gegenbeispiele zur fachlichen und technischen Prüfung.

## Praktische Hinweise

Jeder Skill enthält eine `SKILL.md`, Metadaten unter `agents/`, ein Symbol unter `assets/` und fachliche Referenzen unter `references/`. Stelle bei einer Übernahme den vollständigen Skill-Ordner bereit, damit relative Verweise erhalten bleiben.

Die Diagrammerstellung erfordert eine KI-Umgebung mit geeigneten Zeichen- und Renderingwerkzeugen. Die Skills selbst enthalten keinen ausführbaren Renderer.

[Zur Repository-Übersicht](../README.md) · [Weitere KI-Skills](https://github.com/Dsteiner73/KI-Tipps)
