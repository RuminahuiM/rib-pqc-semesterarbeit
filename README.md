# Implementing Post-Quantum Cryptography in a Python Authentication Service

| | |
| :--- | :--- |
| Titel der Semesterarbeit | Implementing Post-Quantum Cryptography in a Python Authentication Service |
| Name | Dodoe Rumiñahui Mannale |
| Studiengang | Dipl. Informatiker/in HF, ITCNE25, TBZ |
| Semester / Abgabe | Semester 3 / 08.07.2026 |

Dieses Repository enthält die Dokumentation meiner 3. Semesterarbeit als Website: Schlussbericht, Projekt-Artefakte, ADRs, Sprint Journal und Besprechungen. Der Code (Server, App, Infrastruktur) liegt im Produkt-Repository [RuminahuiM/rib-pqc](https://github.com/RuminahuiM/rib-pqc).

**Lesen:** <https://ruminahuim.github.io/rib-pqc-semesterarbeit/>

Teil meines Portfolios: <https://ruminahuim.github.io/>

## Herkunft der Inhalte

Die Inhalte sind eine Kopie der Doku-Teile aus `rib-pqc` zum Stand der Abgabe:

| Quelle in rib-pqc | Hier |
| --- | --- |
| `README.md` (Schlussbericht) | `docs/projektdokumentation.md` |
| `docs/` | `docs/projekt/` |
| `sprint_journal/` (ohne Vorlagen) | `docs/sprints/` |

Relative Links auf Code wurden auf GitHub-Links ins Produkt-Repository umgeschrieben. Die Tenant-ID des Test-Tenants ist im Text durch `<tenant-id>` ersetzt. Sonst sind die Texte unverändert. Die Anker folgen dem GitHub-Schema, damit die bestehenden Inhaltsverzeichnisse funktionieren.

## Lokal ansehen (PowerShell)

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve
```

Die Seite wird bei jedem Push auf `main` automatisch mit GitHub Actions gebaut (`mkdocs build --strict`) und auf GitHub Pages veröffentlicht.
