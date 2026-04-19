# Festival-Roadmap 2026 — Mai bis August

*Stand: 19. April 2026*

Im Juli und Anfang August 2026 findet eine dichte Festival-Saison statt, bei der Real Life Stack und Web of Trust öffentlich sichtbar werden. Dieses Dokument definiert was bis dahin stehen muss und plant die Arbeit in Mai und Juni.

## Die Festival-Pipeline

| Zeitraum | Event | Ort | Unsere Rolle | Anforderung |
|----------|-------|-----|--------------|-------------|
| 8.–12. Juli | **DWeb Camp** | Brandenburg | Demo, Networking, Talk/Workshop | Tech-Demo für Expert:innen |
| 12.–14. Juli | **Local First Conf** | Berlin | **Talk eingereicht, halbe Zusage für kostenloses Opportunity Ticket** | Vortrag, technische Tiefe |
| ~15.–20. Juli | Global Ecovillage Network Gathering | — | optional (Anton entscheidet) | — |
| ~20. Juli | Pause | — | Erholung | — |
| ab ~25. Juli | **Pax Friedensfestival** | — | Stand im Vernetzungszelt | Produktiver App-Einsatz mit echten User:innen |

## Anforderungen pro Event

Die drei zentralen Events haben unterschiedliche Charakteristika und stellen unterschiedliche Anforderungen. Alles muss parallel vorbereitet werden.

### DWeb Camp (8.–12. Juli, Brandenburg)

**Publikum:** Tech-Community, P2P-Expert:innen, Aktivist:innen aus dem dezentralen Web. Kleines, fachkundiges Publikum.

**Unsere Rolle:** Präsenz im Ökosystem, Networking mit den Kontakten aus unserer Outreach-Liste (Julio Linares, Joachim Lohkamp, DWeb Berlin Node, Rabble, Paul Frazee, etc.), potenziell eigener Workshop oder Session.

**Was muss sein:**

- Demo-fähige App die wir fachkundigen Zuhörern zeigen können
- Klare, zeigbare technische Erzählung (DIDComm-Kompatibilität, deterministische Nonce, Sybil-Resistenz durch Begegnung)
- Gedruckte oder digitale One-Pager zur Spec
- Kapazität für Hands-on-Gespräche über Architektur-Fragen
- QR-Code-Verifikation-Demo, die zuverlässig in 30 Sekunden funktioniert (darauf werden sie schauen)

**Was unwichtig ist:** Massenhaftes Onboarding. Dieses Publikum braucht keine Hilfe beim Verstehen — es will technische Tiefe.

### Local First Conf (12.–14. Juli, Berlin)

**Publikum:** Local-First-Community, SSI-Entwickler:innen, akademisch-nahe Tech-Szene. Mittelgroßes, sehr gut informiertes Publikum.

**Unsere Rolle:** Talk (bereits eingereicht), halbe Zusage für kostenloses Opportunity Ticket. Sichtbare Positionierung im Local-First-Ökosystem.

**Was muss sein:**

- Ausgearbeiteter Talk mit klarer These, Demo, Einbettung in den größeren Kontext (eIDAS, Plurality, DIDComm)
- Vorzeigbare Implementation die das Gesagte stützt
- Folien auf Englisch, professionell
- Ein One-Pager zum Verteilen
- Vernünftige Antworten auf kritische Fragen (das Local-First-Publikum wird technisch nachbohren)

**Was unwichtig ist:** Onboarding-UX für Laien. Das sind Entwickler:innen die die App als Beispiel für die Architektur verstehen, nicht als Produkt nutzen.

### Pax Friedensfestival (ab ~25. Juli)

**Publikum:** Festival-Besucher:innen ohne technischen Hintergrund. Breiter Querschnitt, emotional geöffnet durch den Festival-Kontext, interessiert an Vernetzung und Gemeinschaft.

**Unsere Rolle:** Stand im Vernetzungszelt, aktives Onboarding der Festivalteilnehmer:innen in die Infrastruktur. Dies ist der erste öffentliche Einsatz der App mit echten End-Usern.

**Was muss sein:**

- Stabile App die ohne Begleitung genutzt werden kann
- Onboarding-Flow in unter 2 Minuten
- Ehrliche Offline-Toleranz (Festival-WLAN wird schlecht sein)
- Pax-Space vorbereitet, in dem Menschen landen
- Map-Modul mit Profilen, Angeboten, Bedürfnissen, Visionen
- Zuverlässige QR-Code-Identitäts-Austausch für gegenseitige Verifikation
- Stand-Material: Flyer, QR-Code-Poster, Erklär-Video auf Tablet, One-Pager
- Gebriefte Stand-Crew die einheitlich erklären kann
- Ehrliche Kommunikation: "Pilotversion, du bist unter den ersten"

**Was unwichtig ist:** Tiefe Spec-Diskussionen. Die meisten am Stand wollen wissen: was habe ich davon, wie mache ich mit, was passiert mit meinen Daten.

## Ziel-Reifegrad für Pax

Pax ist der kritische Punkt: echte Menschen, echte Nutzung, echte Verantwortung.

Während des Festivals kommen geschätzt 50–200 Menschen an den Stand. Jede dieser Personen soll:

1. Per QR-Code in die App kommen (oder direkt als Web-App)
2. In unter 2 Minuten ein Profil erstellen (Name, Avatar, Angebote, Bedürfnisse, Vision)
3. Im **Pax-Space** landen
4. Andere sehen, sich auf einer Karte verorten
5. QR-Codes anderer Menschen scannen (gegenseitige Verifikation)
6. Nach dem Festival verbunden bleiben

### Feature-Priorisierung

**MUSS für Pax (nicht verhandelbar):**

- Onboarding-Flow in unter 2 Minuten, ohne Begleitung
- Profil erstellen und editieren
- In Space joinen (Pax-Space vorbereitet)
- Map-Modul mit eigenen Einträgen
- QR-Code-Scan zuverlässig (Identitätsaustausch)
- Offline-Toleranz (schlechtes Festival-WLAN)
- Keine kryptischen Fehler
- Funktioniert auf iOS, Android, Web

**SOLL (wichtig, aber verzichtbar):**

- Kalender-Modul mit Festival-Events
- Marktplatz mit Angeboten/Bedürfnissen
- Direktnachrichten zwischen Members
- Mehrere Spaces (andere Projekte können eigene Spaces gründen)

**KANN (Nice-to-have, bewusst verzichten wenn knapp):**

- Push-Notifications
- Erweiterte Verifikations-Flows
- Trust-Score-Visualisierung
- Export/Backup-Features

### Bewusst nicht in Scope

Folgendes verschieben wir bewusst auf nach Pax:

- Vollständige DIDComm-Kompatibilität (JWE-Envelope, Mediator-Protokoll)
- Die größeren Security-Hardenings (Multi-Admin, Forward Secrecy, Capability-Chains)
- Interop mit externen SSI-Systemen
- Komplexe Governance-Features

Das ist für einen Pilot-Einsatz im Community-Kontext vertretbar. Die Kommunikation mit Teilnehmer:innen muss dementsprechend ehrlich sein: "Das ist ein laufendes Projekt, du bist unter den ersten Nutzer:innen."

## Zeit-Budget

Mai und Juni = 8 Wochen. Drei Personen (Anton, Sebastian Stein, Tillmann) mit geteilter Aufmerksamkeit.

Realistische Nettostunden:

- Anton: 50% Entwicklung + 50% Outreach/Strategie/Vereins-Gründung
- Sebastian Stein: 80% Entwicklung
- Tillmann: 60% Entwicklung + 40% Infrastruktur

Das ist ein knappes Budget. Deshalb: **klar priorisieren, keinen Scope Creep zulassen, einen Puffer einbauen**.

## Mai — Stabilisieren und Features vervollständigen

### Woche 1 (1.–4. Mai): Audit und Planung

**Ziel:** Klare Feature-Lücken-Liste.

Aufgaben:

- Inventur der aktuellen Implementation gegen die Spec (was ist drin, was fehlt?)
- Bug-Liste aus Issues und Nutzungserfahrung konsolidieren
- Security Quick Wins identifizieren (welche sind im Code, welche nur in der Spec?)
- Personal Doc Spec (010) gegen Implementation abgleichen
- Pax-Minimal-Funktionsumfang verbindlich festlegen (was genau muss am 25. Juli laufen?)
- Verantwortlichkeiten klären: wer arbeitet woran?

Ergebnis: konkreter Arbeitsplan für Mai/Juni mit Aufgaben pro Person pro Woche.

### Woche 2–3 (5.–18. Mai): Kritische Spec-Umsetzung

**Ziel:** Spec-Stand von April 2026 ist im Code.

Aufgaben:

- JWS `alg`-Strict enforcement
- Nonce-History im Challenge-Response
- Capability `validUntil`
- Deterministische Nonce-Konstruktion für AES-GCM (aus `deviceId` und `seq`)
- `seq`-Konsistenz-Prüfung (Sicherheitsrelevant!)
- DIDComm-Envelope-Format (from/to/body, Type-URIs)
- Authcrypt für Inbox (wenn nicht schon da)
- Personal Doc Struktur stimmig zur Spec 010

Ergebnis: Eine Version die der aktuellen Spec entspricht, ohne neue Features.

### Woche 4 (19.–31. Mai): Feature-Lücken Map/Profile/Space

**Ziel:** Die MUSS-Features für Pax sind funktional.

Aufgaben:

- Profil-Erstellung und -Bearbeitung zuverlässig
- Space-Onboarding-Flow (Einladung → Beitritt → erste Aktion)
- Map-Modul: eigene Einträge hinzufügen, editieren, löschen
- Datenbindung zwischen Profil, Map und Space konsistent
- QR-Code-Austausch inkl. Verifikation stabil

Ergebnis: Die MUSS-Features laufen im Happy Path. Bugs und Edge Cases folgen in Juni.

## Juni — Polish und Festival-Vorbereitung

### Woche 1 (1.–7. Juni): UX-Audit

**Ziel:** Onboarding ist intuitiv für Fremde.

Aufgaben:

- Externe Test-Gruppe (5–10 Menschen) das Onboarding durchlaufen lassen
- Beobachten wo sie hängenbleiben, was sie missverstehen
- Fehlermeldungen menschlich formulieren (keine Stack Traces sichtbar)
- Tooltips, Hilfetexte, leere Zustände bedenken
- Mobile Performance messen und optimieren
- Wenn möglich: Onboarding-Video (2–3 Minuten) aufnehmen

Ergebnis: Unbekannte Menschen kommen ohne Begleitung durch das Onboarding.

### Woche 2 (8.–14. Juni): Stress-Test und Robustheit

**Ziel:** Vorhersagbar robust unter Festival-Bedingungen.

Aufgaben:

- Broker-Lasttests (was passiert bei 100 gleichzeitigen Neuregistrierungen?)
- Offline-Szenarien: App funktioniert ohne WLAN, synct wenn es wiederkommt
- Daten-Recovery nach Verbindungsabbruch
- Edge Cases: leere Felder, Unicode-Namen, große Avatars, langsames Netz
- Test mit mehreren Geräten (iOS alt/neu, Android alt/neu, Web in verschiedenen Browsern)

Ergebnis: Eine App die nicht bei jeder Unannehmlichkeit crasht.

### Woche 3 (15.–21. Juni): Festival-Vorbereitung

**Ziel:** Alles konkret für den Festival-Stand vorbereitet.

Aufgaben:

- **Pax-Space technisch vorbereiten**: Space wird vor Festival-Beginn angelegt, Admin-Rollen geklärt, eventuell vorbefüllt mit Festival-Programm
- **Onboarding-Material**: Flyer, QR-Code-Poster für den Stand, einseitiger Erklärbogen
- **Erklär-Video** finalisieren und auf Landing Page einbinden
- **Fallback-Plan** bei Internet-Ausfall: kann die App lokal ohne Server funktionieren?
- **Stand-Crew-Briefing**: wer erklärt was, wie reagiert man auf typische Fragen
- **Ehrliche Kommunikation vorbereiten**: Wir verkaufen keinen fertigen Service, wir laden Menschen ein Teil eines laufenden Projekts zu werden

Ergebnis: Alles für den Festival-Stand steht bereit.

### Woche 4 (22.–30. Juni): Letzte Tests und Puffer

**Ziel:** Fertig. Kein Scope Creep mehr.

Aufgaben:

- Menschen aus unserem Netzwerk die gesamte Flow durchlaufen lassen
- Letzte Bugs fixen (nur das was wirklich blockt — Rest ist Post-Festival)
- Dokumentation für Stand-Besucher:innen finalisieren
- Mental und physisch Bereitsein für Festival-Saison

Ergebnis: 30. Juni ist "Feature Freeze". Danach nur noch Bug-Fixes.

## Abbruch-Kriterien

Wenn Mitte Juni klar wird dass es zu knapp wird, folgende Entscheidungs-Reihenfolge:

1. **Global Ecovillage Network Gathering streichen** — ohnehin optional, Anton nutzt die Tage als Pause
2. **KANN-Features aus dem Pax-Scope entfernen** — keine Push-Notifications, keine erweiterten Features
3. **SOLL-Features reduzieren** — Kalender und Marktplatz nur rudimentär
4. **Talk bei Local First Conf entschärfen** — weniger Live-Demo, mehr konzeptueller Vortrag
5. **Pax-Stand reduzieren** — kleinerer Umfang, vorsichtigeres Onboarding
6. **Pax als "Soft Launch" kommunizieren** — weniger Erwartungen

**Nicht verhandelbar:**

- DWeb Camp Präsenz (Community-Verortung)
- Local First Conf Talk (wir haben zugesagt)
- Pax-Stand mit Vernetzungs-Angebot (Commitment ans Vernetzungszelt)

Alle drei Events sind zugesagt. Die Frage bei Zeitknappheit ist nur *wie tief* wir jeweils gehen — nicht *ob*.

## Rollenverteilung (Vorschlag, im Team-Termin zu bestätigen)

**Anton:**

- Protokoll-Finalisierung und Spec-Entscheidungen
- Team-Koordination
- Outreach für Festival (Pax-Orga, DWeb Camp Anmeldung)
- Vereins-Gründung parallel (nicht in Festival-Stunden)

**Sebastian Stein:**

- Frontend/UX (Real Life Stack)
- Onboarding-Flow
- Map, Profile, Space-Module
- Pax-Space Vorbereitung

**Tillmann:**

- Mobile App (Android, iOS Build)
- Infrastruktur (Broker, Vault, Profile Service)
- Stress-Tests
- Release-Prozess

## Risiken

| Risiko | Auswirkung | Mitigation |
|--------|-----------|------------|
| Scope Creep | Zeitplan platzt | Feature-Freeze am 30. Juni, klare Muss/Soll/Kann-Trennung |
| Kritischer Bug entdeckt spät | Kein Fallback | Externe Tests ab Woche 1 Juni, nicht später |
| Sebastian Galek Kollaboration drängt | Ablenkung | Eigener Track, nicht in Mai/Juni-Roadmap einplanen |
| Festival-Infrastruktur versagt | Blamage | Offline-Fallback, ehrliche Kommunikation als "Pilot" |
| Physische/mentale Erschöpfung | Alle fallen aus | Pause zwischen Events bewusst nutzen, nicht jeden Termin mitnehmen |

## Langfristig (nach August)

Das Festival ist kein Endpunkt, sondern ein Meilenstein. Danach:

- Feedback und Erkenntnisse aus den Festivals auswerten
- Post-Festival-Phase: Konsolidierung, Bug-Fixes, bessere Docs
- Die Kontakte die an den Festivals entstehen systematisch nachverfolgen
- Spec-Weiterentwicklung (die verschobenen Security-Themen) wieder aufgreifen
- NLnet-Rückmeldung spätestens bis dahin vorhanden — je nach Ausgang Planung anpassen

## Offene Fragen für den Team-Termin

- Passt die Wochenstruktur für Sebastian Stein und Tillmann?
- Welche MUSS-Features sind aus eurer Sicht noch unklar?
- Braucht der Pax-Stand zusätzliche Personen außer uns drei?
- Kann einer von euch Pax-Orga-seitig den Kontakt halten?
- Kann Sebastian Galek in Mai/Juni auf eigener Spur laufen ohne uns zu blockieren?
