# BigData & AI

Arbeitsmaterialien und KI-Skills von Dominik Steiner für Big Data, künstliche Intelligenz und den Transfer in die Unterrichtspraxis.

Der aktuelle Bestand konzentriert sich auf **Datenmodellierung**: konzeptionelle Entity-Relationship-Modelle nach Chen sowie relationale ER-Diagramme im Tabellenstil.

## Inhalt

| Bereich | Inhalt | Einstieg |
| --- | --- | --- |
| Datenmodellierung (ERM) | Zwei Skills für Erstellung, Erklärung und Prüfung von Datenmodellen | [Übersicht und Nutzung](Datenmodellierung%20%28ERM%29/README.md) |

## Den passenden Skill wählen

| Aufgabe | Skill | Darstellung |
| --- | --- | --- |
| Fachliche Entitäten, Attribute und Beziehungen aus einer Textaufgabe ableiten | [ER-Modelle nach Chen](Datenmodellierung%20%28ERM%29/erstelle-chen-erm/SKILL.md) | Rechtecke, Rauten, Ellipsen und Min-Max-Beteiligungen |
| Relationales Schema aus Anforderungen, SQL-DDL oder einem Bild erzeugen oder prüfen | [Relationale ERD](Datenmodellierung%20%28ERM%29/modelliere-relationale-erd/SKILL.md) | Tabellen, PK/FK, Constraints und Crow's-Foot-Verbindungen |

Die beiden Notationen haben unterschiedliche Zwecke und Leseregeln. Die [Bereichsübersicht](Datenmodellierung%20%28ERM%29/README.md) erklärt die Auswahl und enthält Beispielaufträge.

## Nutzung

1. Wähle den passenden Skill und öffne dessen `SKILL.md`.
2. Stelle die Arbeitsanweisung mit der Aufgabenstellung in deiner KI-Umgebung bereit. Eine direkte Installation oder ein Aufruf per Skill-Name setzt entsprechende Unterstützung der Umgebung voraus.
3. Nenne Modellierungsebene, Geschäftsregeln und gewünschte Ausgabe. Fehlende Angaben sollen als Annahmen oder offene Fragen sichtbar bleiben.
4. Prüfe das erzeugte Modell fachlich und visuell.

Für Diagrammexporte braucht die ausführende Umgebung geeignete Werkzeuge zum Erstellen und Rendern von SVG und PNG. Dieses Repository enthält Arbeitsanweisungen und Referenzen, keinen eigenständigen Diagrammrenderer.

## Qualitätsprinzipien

- Vorgaben, Annahmen und Verbesserungsvorschläge trennen.
- Beziehungen in beiden Leserichtungen prüfen.
- Schlüssel, Mindestbeteiligungen und Integritätsregeln nachvollziehbar begründen.
- Präzise Fachdiagramme deterministisch als Vektorgrafik erzeugen.
- Gerenderte Diagramme auf Lesbarkeit und korrekte Symbolzuordnung kontrollieren.
- Aus Gruppenarbeiten keinen gesicherten individuellen Lernerfolg ableiten.

Die konkreten Regeln und Ausgabeformate stehen jeweils in der `SKILL.md`.

## Weitere KI-Arbeitsanweisungen

Im Repository **[KI-Tipps](https://github.com/Dsteiner73/KI-Tipps)** findest du den **RedTeam-Dokumentenprüfer** für kritische Dokumentenreviews.

## Weiterentwicklung

Melde Fehler als Issue mit betroffenem Skill, erwarteter Darstellung und einem fiktiven oder anonymisierten Beispiel. Pull Requests sollten den fachlichen Grund der Änderung nennen und betroffene Referenzen berücksichtigen.

Veröffentliche keine personenbezogenen Lernendeninformationen oder vertraulichen Unterlagen.

## Über die Sammlung

Persönliche Arbeits- und Unterrichtsmaterialien von Dominik Steiner. Die Inhalte stellen keine offiziellen Positionen von Arbeitgebern, Bildungsinstitutionen, Behörden oder Organisationen dar.

Stand der Übersicht: 31. Oktober 2026.
