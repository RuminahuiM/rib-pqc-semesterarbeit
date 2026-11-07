# Implementing Post-Quantum Cryptography in a Python Authentication Service

| | |
| :--- | :--- |
| Titel der Semesterarbeit | Implementing Post-Quantum Cryptography in a Python Authentication Service |
| Name | Dodoe Rumiñahui Mannale |
| Studiengang | Dipl. Informatiker/in HF, ITCNE25, TBZ |
| Semester / Abgabe | Semester 3 / 08.07.2026 |
| Themenfelder | Security, Post-Quantum-Kryptografie, Python, FastAPI, React Native, Docker |

Diese Seite ist die Dokumentation meiner 3. Semesterarbeit.

> **Hinweis zu den Jira-Links:** Die Links auf Jira-Tickets (rumidesigns.atlassian.net) waren für die betreuenden Lehrpersonen gedacht und sind öffentlich nicht zugänglich.

## Worum geht es?

Klassische asymmetrische Kryptografie wie RSA und ECC wird durch ausreichend grosse Quantencomputer brechbar. Seit August 2024 gibt es mit FIPS 203, 204 und 205 die ersten NIST-Standards für Post-Quanten-Kryptografie (PQC). In dieser Arbeit habe ich einen Authentifizierungs-Microservice in Python (FastAPI) gebaut, der diese Standards praktisch einsetzt, demonstriert über eine minimale React-Native-App.

PQC wirkt dabei auf zwei Ebenen: als hybrides PQ-TLS hinter nginx und als PQ-Sitzungsschicht auf Applikationsebene mit ML-KEM-768, AES-256-GCM und ML-DSA-65-signierten Tokens. Logins über Google und Microsoft werden per Identity Broker in eine PQ-sichere Session überführt.

## Links

| Was | Wo |
| --- | --- |
| Produkt-Repository (Code: Server, App, Infrastruktur) | [github.com/RuminahuiM/rib-pqc](https://github.com/RuminahuiM/rib-pqc) |
| Repository dieser Dokumentation | [github.com/RuminahuiM/rib-pqc-semesterarbeit](https://github.com/RuminahuiM/rib-pqc-semesterarbeit) |
| Portfolio mit allen Projekten | [ruminahuim.github.io](https://ruminahuim.github.io/) |

## Aufbau dieser Dokumentation

| Bereich | Inhalt |
| --- | --- |
| [Projektdokumentation](projektdokumentation.md) | Der Schlussbericht mit Teil A Projektmanagement und Teil B fachliche Umsetzung |
| [Projekt](projekt/index.md) | Einreichung, Requirements, Design, Scrum-Setup, Backlog, Risk Register, Traceability, ADRs |
| [Sprints](sprints/index.md) | Planning, Daily Journal, Review und Retrospektive pro Sprint, mit Demos und Evidence |
| [Besprechungen](sprints/mentor_meetings/index.md) | Vorbereitung der Besprechungen mit den Experten |

Die Dokumentation ist eine Kopie der Doku-Teile aus dem Produkt-Repository zum Stand der Abgabe. Links auf Code führen ins Produkt-Repository.
