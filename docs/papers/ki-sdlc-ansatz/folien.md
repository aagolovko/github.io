Folie 1: Motivation und mehrwert für Unternehmen

* KI in der Softwareentwicklung: besser, schneller, weiter  mit ...
* Weniger Rework, mehr Qualität
* Geringere technische Schulden
* Höhere Lieferfähigkeit und Planbarkeit
* Es gibt aber auch Risiken und Herausforderungen

Wie und wo können wir KI einsetzen?

Folie 2: Leitfaden und SDLC-zentrierte einsatz

* Prompt "erstelle mir android App für Zeitverwalung" funktioniert heutzutage (noch) nicht
* man entwickelt so was mit SDLC und es hat sich seit 1950ern bewährt
* 7 Phasen: Planung, Analyse, Design, Implementierung, Test, Deployment, Betrieb
* Ziel: alle Phasen sinnvoll mit KI unterstützen – nicht nur das Coding
* Holistische Integration statt isolierter Tools 
* Wir befinden uns in einer Pionierphase – nicht alle Ansätze werden überleben
* Wir wollen nicht: isolierte tools, chaotisches experimentieren, blindes kopieren ohne Reflexion, Konzepte entwickeln ohne Umsetzung

Versprechen ist großartig, mit welche (zur Zeit vorhersehbaren) Risiken müssen wir aber rechnen?


Folie 3: Herausforderungen und Risiken

* Produktivitätsparadoxon: Wer einen schlechten Prozess beschleunigt, beschleunigt seine technischen Schulden
* Kontextverlust zwischen SDLC-Phasen – Phasengedächtnis als Antwort
* Souveräne RAG: interne Daten als Treibstoff – aber wer darf was sehen?
* Datenschutzrisiko: sensible Daten in öffentliche LLMs – verlockend, aber gefährlich
* KI ist keine Wunderwaffe – Halluzinationen und Grenzen müssen erkannt werden.
* Studien sind zwar optimistisch, aber: messen bei isolierten Aufgaben und nicht Business Impact, langzeitstudien fehlen, Entwicklerproduktivität steigt und Software-Lieferperformance aber nicht unbedingt (DORA-Report)

> "Wer gewarnt ist, ist gewappnet." Wie unterstützen wir SDLC mit KI eigentlich? 


Folie 4: Manifest für KI-unterstützte Softwareentwicklung

* Human-in-the-loop: KI schlägt vor, der Mensch entscheidet
* Kennzahlbasierte Entscheidungen: kein Bauchgefühl bei der Bewertung von KI-Ansätzen
* Phasengedächtnis: persistenter Kontext über alle SDLC-Phasen
* Intent Engineering: nicht wer schneller promptet, sondern wer präziser formuliert, gewinnt
* Agentic Engineering statt Vibe Coding: holistisches, strukturiert, kontrolliert
* Wir wollen uns den Weg nicht verbauen: offene Formate, kein Vendor Lock-in
* Mit KI darf man sich mehr gönnen: KI als Exoskelett für Entwickler (eigentlich für alle)

> Was können wir uns gönnen hinsichtlich KI Ansatz?

Folie 5: Zielbild: gönne sich mehr mit "Think big, do small"

* KI-Integration in Vier Reifestufen
* Stufe 1: Lokale Entwicklung – Claude Code, Cursor, Copilot
* **Stufe 2: Orchestrierung im SDLC – Agenten über alle Phasen**
* Stufe 3: Unternehmensweite KI-Workflows – über die Softwareentwicklung hinaus
* Stufe 4: Agent2Agent über Unternehmensgrenzen hinweg. Technologische Basis existiert bereits: MCP, A2A, ACP, AGNTCY

> Fokus auf Stufe 2, ist es wirkungsvoll? machbar? Wie kann es umgesetzt werden?

Folie 6: Zielbild: (2) Orchestrierung im SDLC

* Drei Säulen: KI-Orchestrierungsplattform + Claude Code + CI/CD-Pipeline
* n8n als KI-Orchestrierungsplattform: Multiuser-Workflows, always-on, RAG
* Claude Code als Platform für lokale Entwicklung, Refactoring, Codegenerierung
* CI/CD: Code-Review, Log-Analyse, FinOps, Fraud-Detection, Alerting
* Kein Tool-Zoo, sondern ein hybrides Team aus Menschen und KI-Agenten

> Wie viel KI ist zu viel – und wer trägt die Verantwortung? 

Folie 7: Ethische Aspekte und Verantwortung

* Governance, Datenschutz, Compliance, Ethik. KI kann helfen, Richtlinien und Policies konsequenter durchzusetzen.
* Es ist aber so verlockend und technisch einfach, sensible oder personenbezogene Daten in
  öffentliche LLMs hochzuladen
* und es ist möglicherweise so verlocken so was wie "social scoring" (verboten EU AI Act, 2024) zu verwenden.
* klassische Schutzmaßnahme wie rollenbasierte Rechte, Kryptografie reichen nicht aus um KI Verantwortungsvoll zu nutzen
* Das Problem ist erkannt – die Suche nach Lösungen beginnt ...

