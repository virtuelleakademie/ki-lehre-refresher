# Moderationsleitfaden

Anleitung für Workshop-Leitende

Dieser Leitfaden enthält alle Anweisungen für die Durchführung des Workshops. Die Teilnehmenden-Materialien sind davon getrennt.

## Überblick

| Zeit | Phase | Dauer |
|------|-------|-------|
| 0:00--0:30 | Einstieg | 30 Sek |
| 0:30--8:30 | Teil 1: Das Sprachmodell liegt falsch | 8 Min |
| 8:30--14:30 | Teil 2: Warum Nachfragen nicht hilft | 6 Min |
| 14:30--36:30 | Teil 3: Lateral Reading | 22 Min |
| 36:30--40:00 | Teil 4: Die Entscheidungsregel | 3.5 Min |

**Gesamtdauer:** 40 Minuten

---

## Vorbereitung

### 24 Stunden vorher

**Teil 1 -- Beispiel testen:**

- [ ] Prompt bei ChatGPT, Claude, Gemini testen
- [ ] Antworten notieren -- variieren sie? Sind sie falsch?
- [ ] Offizielle Quelle finden (BFS etc.)
- [ ] Backup-Prompt bereit haben

**Teil 2 -- Nachfragen-Experimente testen:**

- [ ] Selbstprüfungs-Prompt testen ("Bist du sicher?")
- [ ] Führenden Prompt testen (mit eingebauter Annahme)
- [ ] Prüfen ob Effekte sichtbar sind

**Teil 3 -- Szenarien:**

- [ ] 6 Szenarien ausdrucken oder Projektion vorbereiten
- [ ] 2--3 Szenarien selbst durchspielen

**Backup:**

- [ ] 2--3 Screenshots von klaren Fehlern aus früheren Tests

### 10 Minuten vor Workshop

- [ ] Projektor testen
- [ ] Tabs geöffnet: ChatGPT/Claude/Gemini, BFS, admin.ch, Uni-Statistiken
- [ ] Handouts bereit

### Benötigte Materialien

**Technisch:**

- Alle Teilnehmenden haben Laptops/Tablets mit Internet
- Projektor für Demonstrationen
- Zugang zu mindestens einem Sprachmodell (ChatGPT, Claude, oder Gemini)

**Vorbereitet:**

- Teil 1 Beispiel: 24 Stunden vorher testen und final auswählen
- Teil 2 Experimente: Selbstprüfungs-Prompt und führenden Prompt vorher testen
- Teil 3 Szenarien: 6 arbeitsbezogene Szenarien
- Handout: Quick-Reference-Karte
- Backup: Screenshots von 2--3 klaren Fehlern von Sprachmodellen

---

## Einstieg (30 Sek)

### Moderationstext

> Wir starten direkt. Öffne ein Sprachmodell deiner Wahl -- ChatGPT, Claude, oder Gemini.

Keine weitere Einleitung. Direkt zu Teil 1.

### Kurz-Check-in (1 Min)

- Zwei Fragen laut vorlesen; alle notieren nur für sich (Zettel/Notiz-App). Nichts einsammeln.
  - "Antworten von Sprachmodellen kann ich ohne weitere Prüfung verwenden." (Zustimmung?)
  - "Wie sicher fühlst du dich, falsche Angaben von Sprachmodellen zu erkennen?" (0--10)
- Keine Diskussion, keine Mittelwerte. Brücke zu Teil 1.

---

## Teil 1: Das Sprachmodell liegt falsch (8 Min)

**Ziel:** Gemeinsam erleben, dass Sprachmodelle überzeugend falsch sein können.

### Das Experiment (5 Min)

> Alle stellen dieselbe Frage. Kopiere diesen Prompt.

Alle testen den Prompt zur Bachelorabschlussquote (siehe Teilnehmenden-Material).

### Alternative Prompts

Falls du andere Themen bevorzugst (vorher testen, einen auswählen):

- "Wie hoch sind die durchschnittlichen IT-Kosten pro Studierenden an Schweizer Unis?"
- "Wie viele Verwaltungsmitarbeitende hat die Universität Bern?"
- "Welcher Prozentsatz der Uni-Mitarbeitenden arbeitet in Teilzeit?"

> **Wichtig: 24h vorher testen!**
>
> Wähle die Frage, bei der:
> - Die Antworten zwischen Teilnehmenden variieren werden, ODER
> - Die Antwort falsch/ungenau ist, ODER
> - Die Antwort sehr spezifisch klingt aber nicht verifizierbar ist

### Antworten sammeln

> Wer möchte seine Antwort vorlesen?

3--4 Teilnehmende teilen ihre Antworten. Notiere die Zahlen sichtbar (Tafel/Flipchart).

### Auswertung durch Lateral Reading (3 Min)

> Wir haben verschiedene Zahlen. Jetzt prüfen wir. Schau zu.

**Live-Demonstration am Projektor:**

1. Neuen Browser-Tab öffnen (nicht das Sprachmodell fragen)
2. Suchen: `BFS Studiendauer Bachelor Schweiz`
3. Suchergebnisse zeigen:
   > Hier ist bfs.admin.ch -- das Bundesamt für Statistik. Das ist eine Primärquelle.
4. Zur BFS-Seite navigieren, offizielle Statistik zeigen
5. Mit den Antworten der Sprachmodelle vergleichen

### Beobachtungen sammeln

> Was siehst du?

Teilnehmende berichten: Zahlen stimmen nicht überein, das Modell war spezifisch aber falsch, etc.

### Minimaler Frame

*Erst nach den Berichten der Teilnehmenden:*

> Die Antwort klang überzeugend. Spezifische Zahl, selbstsicher formuliert. Aber nicht richtig. Das ist das Muster: **Überzeugend heisst nicht korrekt.**

### Die Spezifitätsfalle

*Optional, wenn Zeit:*

> Achte auf die Spezifitätsfalle: Je präziser eine Antwort klingt -- genaue Prozentzahlen, Jahreszahlen, Namen -- desto vertrauenswürdiger wirkt sie. Aber Spezifität ist kein Beweis. Sprachmodelle erfinden oft sehr präzise klingende Details.

### Troubleshooting

**Alle Antworten sind gleich und korrekt?**

Selten, aber möglich. Optionen:

**Option A:**

> Das Modell hat heute gut geantwortet. Aber schau: Hat es eine Quelle genannt? Woher weisst du, dass die Zahl stimmt -- ausser dass das Sprachmodell es sagt?

**Option B:**

Backup-Screenshot zeigen:

> Letzte Woche sah das so aus...

Dann weiter zu Teil 2 -- der Punkt "Sprachmodelle können sich nicht selbst prüfen" funktioniert unabhängig davon.

---

## Teil 2: Warum Nachfragen nicht hilft (6 Min)

**Ziel:** Entdecken, dass Sprachmodelle sich nicht selbst prüfen können -- und dass sie Annahmen bestätigen.

### Experiment A: Selbstprüfung (2 Min)

> Eine naheliegende Idee: Frag das Sprachmodell, ob es sicher ist. Probiere das jetzt.

Teilnehmende testen den Selbstprüfungs-Prompt.

> Was ist passiert? Ein paar Beispiele.

2--3 Teilnehmende berichten kurz.

### Experiment B: Annahme einbauen (2 Min)

> Jetzt ein zweiter Test. Starte einen neuen Chat und stelle die Frage so:

Teilnehmende testen den führenden Prompt.

> Was sagt das Modell jetzt?

2--3 Teilnehmende berichten kurz.

### Auswertung (2 Min)

> Du hast zwei Dinge ausprobiert. Was hast du beobachtet?

Typische Antworten:

- "Sie hat einfach nochmal dasselbe gesagt"
- "Sie hat meine Zahl bestätigt"
- "Sie hat 'korrigiert' aber ohne echte Quelle"

### Minimaler Frame

*Erst nach den Berichten der Teilnehmenden:*

> Zwei Beobachtungen:
>
> **Erstens:** Das Sprachmodell kann sich nicht selbst prüfen. Es hat keinen Zugang zu seinem eigenen Denkprozess -- es generiert einfach die nächste plausible Antwort. Das ist keine Prüfung, das ist mehr vom Gleichen.
>
> **Zweitens:** Es bestätigt tendenziell das, was du andeutest. Deine Annahmen fliessen in die Antwort ein.
>
> Beide Wege sind blockiert. Bleibt: **Externe Quellen.** Das üben wir jetzt.

### Troubleshooting

**Das Modell sagt "Ich bin nicht sicher" oder verweigert?**

Manchmal gut trainierte Antwort. Nutze es:

> Es hat Unsicherheit signalisiert. Aber: Ist das eine echte Prüfung oder eine trainierte Antwort? Bei anderen Fragen bekommst du diese Warnung nicht. Verlassen kannst du dich darauf nicht.

---

## Teil 3: Lateral Reading (22 Min)

**Ziel:** Die Technik praktisch anwenden -- von geführt bis selbständig.

### Runde 1: Gemeinsam (7 Min)

> Lateral Reading heisst: Raus aus dem Sprachmodell, eigene Suche, Primärquellen finden. Wir machen das jetzt gemeinsam.

**Szenario vorstellen:**

> Das Sprachmodell sagt: "Das durchschnittliche Gehalt für Verwaltungsmitarbeitende an Schweizer Universitäten liegt bei CHF 78'000 brutto pro Jahr." Du willst das für einen Budgetantrag verwenden.

**Schritt 1: Suchbegriffe (1.5 Min)**

> Wie würdest du suchen? Nicht das Sprachmodell fragen. Was tippst du bei Google ein?

Teilnehmende machen Vorschläge.

> Gute Begriffe: "Schweiz Universität Verwaltung Gehalt Statistik" oder "swissuniversities Lohnstruktur". Nicht: "Stimmt 78000?"

**Schritt 2: Suchergebnisse filtern (1.5 Min)**

Am Projektor suchen und Ergebnisse bewerten:

> Was sehen wir hier? jobs.ch -- das sind Stellenanzeigen, nicht offizielle Statistik. Hier ein Blog -- überspringen. BFS -- das ist eine Primärquelle. swissuniversities -- auch gut.

**Schritt 3: Zur Quelle gehen (2 Min)**

> Wichtig: Nicht die Google-Zusammenfassung lesen. Zur echten Seite gehen.

BFS oder swissuniversities öffnen, navigieren, zeigen was man findet (oder nicht findet).

**Schritt 4: Zwei Prüffragen (1 Min)**

> Wenn du eine Quelle gefunden hast, stell zwei Fragen: Erstens, ist die Quelle zuverlässig -- also eine Primärquelle oder offizielle Stelle? Zweitens, steht da wirklich das, was das Sprachmodell behauptet?

> Sprachmodelle nennen manchmal echte Quellen, interpretieren sie aber falsch oder übertreiben. Immer selbst nachlesen.

**Schritt 5: Ergebnis besprechen (1 Min)**

> Was haben wir gefunden?

Teilnehmende berichten. Typisches Ergebnis: Die exakte Zahl existiert nicht in dieser Form.

> Das ist selbst eine wichtige Information. Die Zahl vom Sprachmodell ist nicht verifizierbar -- also nicht verwendbar für einen Budgetantrag.

### Runde 2: In Kleingruppen (8 Min)

> Wähle ein Szenario. Du hast 5 Minuten.

6 Szenarien projizieren oder austeilen (siehe Teilnehmenden-Material).

**Während Teilnehmende arbeiten:**

- Herumgehen, bei Suchbegriffen helfen falls nötig
- Notieren, wer interessante Funde hat

**Auswertung (3 Min):**

> Wer hat etwas gefunden? Oder etwas Interessantes entdeckt?

3--4 Teilnehmende berichten kurz:

- Welches Szenario?
- Was gefunden?
- War das Modell richtig, falsch, oder nicht prüfbar?

### Runde 3: Eigenes Beispiel (7 Min)

> Jetzt dein eigener Fall. Denk an etwas, das du diese Woche ein Sprachmodell fragen könntest -- oder schon gefragt hast.

Aufgabe auf Projektor zeigen (siehe Teilnehmenden-Material).

**Teilen (3 Min):**

> Wer möchte teilen?

2--3 Freiwillige berichten.

**Bei jedem Beispiel fragen:**

> Würdest du diese Information in einem formellen Dokument verwenden?

Das bereitet Teil 4 vor.

### Troubleshooting

**Teilnehmende finden keine Quelle:**

Das ist selbst lehrreich:

> Du findest keine offizielle Quelle? Das ist wichtige Information. Die Aussage vom Sprachmodell ist nicht verifizierbar -- also nicht verwendbar für wichtige Entscheidungen.

**Zeit wird knapp:**

Kürze Runde 3 (eigenes Beispiel). Der Kern ist Runde 1 (gemeinsam) und Runde 2 (Szenarien).

---

## Teil 4: Die Entscheidungsregel (3.5 Min)

### Die Eine Frage (1 Min)

> Eine einfache Frage hilft dir entscheiden:
>
> Würdest du diese Info in einem Bericht zitieren? In einem Antrag verwenden? Als Grundlage für eine Entscheidung nutzen?

Die Entscheidungsregel zeigen (siehe Teilnehmenden-Material).

### Kurz-Check-out (1 Min)

- Gleiche zwei Fragen wie zu Beginn; alle schauen auf ihre Notiz und vergleichen nur für sich.
- Nur wenn Zeit: Freiwillige dürfen teilen, ob sich ihre Antworten geändert haben. Kein Einsammeln, keine Mittelwerte.

### Abschluss (2.5 Min)

> Du hast heute drei Dinge erlebt:
>
> **Erstens** -- Sprachmodelle können überzeugend falsch liegen.
>
> **Zweitens** -- Nachfragen beim Sprachmodell ist keine echte Prüfung.
>
> **Drittens** -- Lateral Reading funktioniert: Raus aus dem Sprachmodell, eigene Suche, Primärquellen.
>
> Das Handout fasst die wichtigsten Punkte zusammen. Probiere es diese Woche einmal aus.

Handout verteilen (oder auf Link verweisen).

> Danke.

---

## Erfolgskriterien

**Minimal-Erfolg:**
Teilnehmende haben erlebt, dass Sprachmodelle falsch liegen können, und kennen eine vertrauenswürdige Quelle für ihren Bereich.

**Guter Erfolg:**
Teilnehmende haben Lateral Reading selbst angewendet und verstehen, warum Nachfragen beim Sprachmodell keine Lösung ist.

**Optimaler Erfolg:**
Teilnehmende nehmen sich vor, diese Woche mindestens einmal eine Antwort vom Sprachmodell extern zu verifizieren.
