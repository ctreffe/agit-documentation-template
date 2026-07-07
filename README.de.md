# AGIT Documentation Template

> [!NOTE]
> **AI Collaboration**
>
> Dieses Repository pflegt das AGIT Documentation Template.
>
> Das AGIT Documentation Template ist die dokumentationsorientierte Spezialisierung der AGIT Template-Familie.
>
> Das Collaboration Model dokumentiert Dokumentationspraktiken, KI-gestuetzte Dokumentationsworkflows, Link- und Visual-QA-Disziplin und Repository-Konventionen fuer Dokumentationsprojekte.
>
> Das Collaboration Model wird in [ChatGPT.md](ChatGPT.md) gepflegt.

Template fuer AI-gestuetzte technische Dokumentation in AGIT-Kontexten, mit repository-basiertem Workflow, Link-Disziplin, Screenshots, visueller Qualitaetspruefung und dokumentierten Entscheidungen.

Dieses Repository ist ein Ausgangspunkt fuer technische Dokumentationsprojekte, die mit aehnlicher Sorgfalt gepflegt werden sollen wie Software- und wissenschaftliche Schreibprojekte: expliziter Kontext, klare Verantwortung, reproduzierbare Zusammenarbeit, dokumentierte Entscheidungen und nachvollziehbare Meilensteine.

Englisches README: [README.md](README.md)

## Grundprinzip

Der Maintainer verantwortet jederzeit Dokumentationsziel, Struktur, technische Korrektheit, Zielgruppenpassung und finale Veroeffentlichungsentscheidung. Der AI Assistant unterstuetzt beim Formulieren, bei Konsistenzpruefungen, Link-Disziplin, Screenshot- und Visual-QA, strukturellem Feedback und Repository-Pflege, ersetzt aber nicht die Maintainer-Entscheidung.

## Wofuer dieses Template gedacht ist

Das Template eignet sich fuer Dokumentationsprojekte wie:

- Benutzerhandbuecher, Admin-Guides und Betriebsanweisungen.
- Technische Konzepte, Architekturhinweise und Implementierungsdokumentation.
- Troubleshooting-, Migrations-, Setup- und Release-Dokumentation.
- Dokumentationssysteme mit Text, Screenshots, Diagrammen, Links und generierten Outputs.

## Workflow

1. Mit [INITIAL_PROMPT.md](INITIAL_PROMPT.md) starten.
2. [PROJECT_SETUP.md](PROJECT_SETUP.md) und [DOCS_SETUP.md](DOCS_SETUP.md) ausfuellen.
3. Projektspezifischen Kontext in [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) festhalten.
4. Dokumentationstyp, Zielgruppe, Zweisprachigkeit, Quarto-Struktur, Links, Screenshots und Visual-QA festlegen.
5. Dokumentation in kleinen, pruefbaren Schritten erarbeiten.
6. Wichtige Dokumentationsentscheidungen als DDRs festhalten.
7. Sinnvolle Meilensteine mit Changelog, Version und Konsistenzpruefung abschliessen.

## Maintainer-Setup

Fuer ein neues Codex-basiertes Dokumentationsprojekt empfiehlt sich diese Reihenfolge:

1. Neues Repository aus diesem Template erzeugen und lokal klonen.
2. Das Repository als aktiven Codex-Workspace oeffnen.
3. Quarto CLI von <https://quarto.org/docs/get-started/> installieren.
4. Neues Terminal oeffnen und Quarto mit `quarto --version` pruefen.
5. Falls PDF-Output benoetigt wird, eine TeX-Toolchain installieren, zum Beispiel mit `quarto install tinytex`.
6. Quarto-Baseline mit `quarto render` pruefen.
7. Projektinitialisierung mit [INITIAL_PROMPT.md](INITIAL_PROMPT.md) starten.
8. [PROJECT_SETUP.md](PROJECT_SETUP.md), [DOCS_SETUP.md](DOCS_SETUP.md) und [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) ausfuellen.

R und RStudio sind sinnvoll, wenn die Dokumentation R-Code, Datenanalysen, Plots oder R-basierte Quarto-Erweiterungen enthaelt. Fuer einfache Markdown-basierte Dokumentation sind sie nicht zwingend erforderlich.

## Zentrale Dateien

- [ChatGPT.md](ChatGPT.md): Versioniertes AI Collaboration Model.
- [CODEX.md](CODEX.md): Lokale Arbeitsregeln fuer den Assistant.
- [DOCUMENTATION.md](DOCUMENTATION.md): Dokumentationsarchitektur und Rollen der Dateien.
- [PROJECT_SETUP.md](PROJECT_SETUP.md): Initialisierung abgeleiteter Projekte.
- [DOCS_SETUP.md](DOCS_SETUP.md): Dokumentationsspezifische Setup-Checkliste.
- [DOCUMENTATION_PROCESS.md](DOCUMENTATION_PROCESS.md): Laufender Dokumentationsprozess.
- [DOCUMENTATION_TYPE_PROFILES.md](DOCUMENTATION_TYPE_PROFILES.md): Dokumentationstyp-Profile, einschliesslich Tutorial-Profil.
- [QUARTO.md](QUARTO.md): Quarto als bevorzugtes internes Dokumentationsformat.
- [AUDIENCE.md](AUDIENCE.md): Vorlage fuer das Zielgruppenmodell.
- [STYLE_GUIDE.md](STYLE_GUIDE.md): Stilprinzipien technischer Dokumentation.
- [SCREENSHOTS.md](SCREENSHOTS.md): Regeln fuer Screenshots und visuelle Belege.
- [LINKS.md](LINKS.md): Link- und Referenzdisziplin.
- [VISUAL_QA.md](VISUAL_QA.md): Checkliste fuer visuelle Qualitaetspruefung.
- [DDR/](DDR/): Documentation Decision Records.

## Lizenz

Dieses Template steht unter der MIT License. Siehe [LICENSE](LICENSE).
