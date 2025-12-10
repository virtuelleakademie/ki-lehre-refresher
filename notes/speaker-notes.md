# Speaker Notes: KI in der Hochschulbildung

**Vollversion (~3.25 Stunden)**

::: {.callout-note}
## Meta: Über dieses Dokument
Dieses Dokument enthält detaillierte Sprechernotizen für jeden Abschnitt der Präsentation "KI in der Hochschulbildung". Es dient als Begleitdokument für Vortragende und enthält:

- **Hintergrundinformationen** zu den zitierten Studien und Theorien
- **Rhetorische Hinweise** zur Präsentation der Inhalte
- **Antizipierte Fragen** und mögliche Antworten
- **Vertiefende Erklärungen** für komplexe Konzepte

Die Sprechernotizen sind in grünen Callouts formatiert. Meta-Kommentare zur Struktur des Dokuments erscheinen in blauen Callouts.
:::

---

## Überblick und Kernthese

::: {.callout-tip}
## Sprechernotizen: Vorbereitung
**Kernthese in einem Satz:** KI-Werkzeuge sind für Experten gemacht — sie machen Experten produktiver, aber Lernende profitieren oft nicht, weil Lernen die kognitive Anstrengung erfordert, die KI eliminiert.

**Narrativer Bogen:** Die Präsentation folgt einer Drei-Akt-Struktur:
1. Was KI kann (kurz) — Fähigkeiten etablieren
2. Warum es für Experten funktioniert — kognitionswissenschaftliche Grundlagen
3. Warum es für Lernende oft scheitert — das Produktivitäts-Lern-Paradox

**Wichtig:** Die Präsentation ist bewusst theoretisch gehalten. Konkrete Handlungsempfehlungen werden vermieden, weil (a) die Evidenzbasis für spezifische Interventionen schwach ist und (b) Lösungen kontextabhängig sind.
:::

---

## Teil 1: Was KI heute kann (~30 Min)

### Slide: Die zentrale Frage

::: {.callout-tip}
## Sprechernotizen
**Einstieg:** Beginne mit der linken Spalte — die beeindruckenden Fähigkeiten von KI, die das Publikum wahrscheinlich bereits kennt. Dann der Kontrast: die Bastani-Zahlen.

**Hintergrund zur Bastani-Studie:**
- Randomisierte kontrollierte Studie mit ~1000 türkischen Gymnasiasten
- Erschienen 2024, noch nicht peer-reviewed zum Zeitpunkt der Zitation
- Die 48%/17%-Zahlen sind der "Hook" der gesamten Präsentation
- Sie werden später im Detail erklärt (Teil 4)

**Rhetorischer Hinweis:** Lass die Zahlen wirken. Die Spannung zwischen "48% besser MIT" und "17% schlechter OHNE" ist das zentrale Rätsel, das die Präsentation auflöst.

**Mögliche Frage:** "Ist das nicht nur eine Studie?"
**Antwort:** Ja, und das wird später thematisiert. Die Studie ist gut designt (RCT), aber Replikation fehlt. Die Zahlen illustrieren ein Muster, das theoretisch gut begründet ist.
:::

### Slide: Wie LLMs Text produzieren

::: {.callout-tip}
## Sprechernotizen
**Ziel:** Konzeptionelles Verständnis ohne technische Details. Das Publikum sind Hochschuldozierende, keine Informatiker.

**Kernbotschaft:** LLMs sind "extrem ausgeklügelte Autovervollständigung". Sie generieren, sie rufen nicht ab.

**Wichtige Unterscheidung:**
- **Retrieval** (wie eine Suchmaschine): Information wird gefunden und zurückgegeben
- **Generation** (wie ein LLM): Text wird neu erzeugt basierend auf statistischen Mustern

**Warum das wichtig ist:** Diese Unterscheidung erklärt, warum LLMs "halluzinieren" können — sie optimieren für plausibel klingenden Text, nicht für Wahrheit.

**Analogie:** Ein LLM ist wie ein Autor, der in jedem Genre schreiben kann, weil er Millionen von Büchern gelesen hat — aber er erfindet, statt zu recherchieren.
:::

### Slide: Wie "Denken" in KI funktioniert

::: {.callout-tip}
## Sprechernotizen
**Kontext:** Chain-of-Thought (CoT) Reasoning ist eine Technik, die ab 2022 populär wurde (Wei et al., 2022). Sie verbessert die Leistung bei komplexen Aufgaben dramatisch.

**Das Beispiel:** Die Multiplikation 17 × 24 zeigt den Unterschied zwischen direkter Antwort und schrittweisem Vorgehen. Mit CoT "zeigt die KI ihre Arbeit".

**Kernpunkt:** Auch mit CoT ist es immer noch Mustererkennung — aber über Denkschritte, die in den Trainingsdaten vorkamen. Die KI hat gelernt, wie Menschen Probleme aufteilen.

**Mögliche Frage:** "Denkt die KI dann wirklich?"
**Antwort:** Das ist eine philosophische Frage, die wir hier nicht beantworten müssen. Funktional produziert sie Outputs, die wie Denken aussehen. Ob es "echtes" Denken ist, ist für unsere Zwecke irrelevant.
:::

### Slide: Werkzeug-fähige Agenten

::: {.callout-tip}
## Sprechernotizen
**Aktualität:** Dieser Bereich entwickelt sich rasant. Stand 2024/25 können Agenten:
- Webrecherche durchführen und Quellen zusammenfassen
- Code schreiben, ausführen und debuggen
- Dateien lesen, bearbeiten und erstellen
- APIs aufrufen (Kalender, E-Mail, Datenbanken)

**Beispiele zum Veranschaulichen:**
- Ein Agent, der eine Literaturrecherche durchführt, PDFs herunterlädt, zusammenfasst und eine Bibliographie erstellt
- Ein Coding-Agent, der ein Programm schreibt, testet, Fehler findet und korrigiert
- Ein Analyse-Agent, der Daten importiert, visualisiert und interpretiert

**Kernbotschaft:** Die Fähigkeitsgrenze verschiebt sich ständig. Was heute unmöglich scheint, kann in sechs Monaten Routine sein.

**Rhetorischer Hinweis:** Hier nicht in Details verlieren. Das Ziel ist, die Reichweite zu etablieren, nicht jede Fähigkeit zu erklären.
:::

### Slide: Diskussion (5 Min)

::: {.callout-tip}
## Sprechernotizen
**Ziel der Diskussion:**
1. Erfahrungen des Publikums aktivieren
2. Übergang von "Was KI kann" zu "Was das für Lehre bedeutet"

**Moderationshinweise:**
- Bei grossen Gruppen: Kurze Murmelphase (2 Min), dann 2-3 Wortmeldungen
- Frage 2 ist wichtiger — sie führt zum Rest der Präsentation

**Typische Antworten:**
- "Studierende lassen sich Zusammenfassungen schreiben"
- "Code wird komplett von ChatGPT generiert"
- "Hausarbeiten klingen plötzlich alle gleich"

**Überleitung:** "Viele von euch haben beobachtet, dass Studierende KI nutzen. Die Frage ist: Lernen sie dabei noch? Dafür müssen wir verstehen, wie Lernen überhaupt funktioniert."
:::

::: {.callout-note}
## Meta: Teil 1 im Kontext
Teil 1 ist bewusst kurz gehalten. Das Publikum kennt die KI-Fähigkeiten weitgehend. Der Teil dient primär dazu, alle auf denselben Stand zu bringen und die zentrale Frage zu etablieren. Die eigentliche Argumentation beginnt in Teil 2.
:::

---

## Teil 2: Wie Expertise entsteht (~45 Min)

::: {.callout-note}
## Meta: Funktion von Teil 2
Dieser Teil legt das kognitionswissenschaftliche Fundament. Ohne dieses Verständnis wäre das Produktivitäts-Lern-Paradox (Teil 4) überraschend statt vorhersagbar. Die Reihenfolge ist didaktisch wichtig: Erst die Theorie, dann die Evidenz.
:::

### Slide: Experten und Novizen sind grundlegend verschieden

::: {.callout-tip}
## Sprechernotizen
**Hintergrund:** Die Experten-Novizen-Forschung geht auf de Groot (1946/1965) und Chase & Simon (1973) zurück. Das Schachbeispiel ist klassisch.

**Das Experiment:** Schachmeistern und Anfängern wurden Stellungen für wenige Sekunden gezeigt. Bei echten Spielstellungen erinnerten Meister ~25 Figuren, Anfänger ~4. Bei zufälligen Stellungen: beide gleich schlecht.

**Interpretation:** Meister sehen nicht einzelne Figuren, sondern "Chunks" — bedeutungsvolle Muster wie "Königsangriff" oder "offene Linie". Diese Chunks sind in ihrem Langzeitgedächtnis gespeichert.

**Übertragung auf andere Domänen:**
- Ärzte sehen "Symptomkomplexe", nicht Einzelsymptome
- Programmierer sehen "Design Patterns", nicht Codezeilen
- Historiker sehen "Epochenmerkmale", nicht Einzeldaten

**Kernbotschaft:** Expertise ist nicht einfach "mehr Wissen", sondern eine qualitativ andere Art, Wissen zu organisieren.
:::

### Slide: Von schwachen zu starken Methoden

::: {.callout-tip}
## Sprechernotizen
**Theoretischer Hintergrund:** ACT-R (Adaptive Control of Thought—Rational) ist eine kognitive Architektur, entwickelt von John Anderson seit den 1970ern. Sie modelliert, wie deklaratives Wissen zu prozeduralem Wissen wird.

**Schwache Methoden (Novizen):**
- **Mittel-Ziel-Analyse:** "Wo bin ich? Wo will ich hin? Was bringt mich näher?"
- **Versuch und Irrtum:** Ausprobieren ohne systematische Strategie
- **Analogie:** "Das ist wie etwas, das ich schon kenne"
- **Rückwärtsarbeiten:** Vom Ziel aus rückwärts denken

Diese Methoden sind "schwach", weil sie langsam, fehleranfällig und kognitiv anstrengend sind.

**Starke Methoden (Experten):**
- Direkte Mustererkennung: "Das ist ein Fall von X"
- Automatische Lösungswege: "Bei X macht man Y"
- Intuition: "Das fühlt sich falsch an" (basierend auf tausenden Erfahrungen)

**Kernbotschaft:** Der Übergang von schwachen zu starken Methoden erfordert umfangreiche Übung — es gibt keine Abkürzung.

**Rhetorischer Hinweis:** Hier beginnt das Argument, warum KI problematisch sein könnte: Sie kann die schwachen Methoden ersetzen, aber der Übergang zu starken Methoden erfordert, dass man die schwachen selbst durchläuft.
:::

### Slide: Prozeduralisierung und Kompilation

::: {.callout-tip}
## Sprechernotizen
**Das Autofahren-Beispiel:** Fast jeder im Publikum kann sich erinnern, wie schwierig Autofahren anfangs war. Heute ist es automatisch.

**Die Phasen:**
1. **Deklarativ:** Wissen als Fakten ("Kupplung vor Schalten")
2. **Bewusste Anwendung:** Aktiv an jeden Schritt denken, langsam, fehleranfällig
3. **Prozeduralisierung:** Schritte werden zu Einheiten ("Anfahren" statt "Kupplung-Gas-Kupplung")
4. **Automatisierung:** Keine bewusste Aufmerksamkeit mehr nötig

**Warum das wichtig ist:**
- Automatisierte Prozesse belasten das Arbeitsgedächtnis nicht
- Sie sind schneller und zuverlässiger
- Sie setzen kognitive Ressourcen für Höheres frei

**Kernbotschaft:** "Diese Transformation kann nicht übersprungen werden." Man kann nicht direkt von deklarativem Wissen zu Automatisierung springen. Der Weg führt durch bewusste, anstrengende Übung.

**Mögliche Frage:** "Aber kann KI nicht die langweiligen Übungsphasen übernehmen?"
**Antwort:** Genau das ist das Problem — die "langweiligen" Phasen sind die, in denen Prozeduralisierung stattfindet. Ohne sie keine Expertise.
:::

### Slide: Cognitive Load Theory: Die Grundlagen

::: {.callout-tip}
## Sprechernotizen
**Hintergrund:** Cognitive Load Theory (CLT) wurde von John Sweller in den 1980ern entwickelt. Sie ist eine der einflussreichsten Theorien der Instruktionspsychologie.

**Arbeitsgedächtnis:**
- Miller (1956): "The magical number seven, plus or minus two"
- Neuere Forschung (Cowan, 2001): eher 4±1 Chunks
- Dauer: 15-30 Sekunden ohne Rehearsal
- **Metapher:** Arbeitsgedächtnis ist wie ein kleiner Tisch, auf dem man arbeitet. Nur wenige Dinge passen drauf.

**Langzeitgedächtnis:**
- Praktisch unbegrenzte Kapazität
- Organisiert in Schemata (vernetzte Wissensstrukturen)
- Information hier erfordert kein Arbeitsgedächtnis zur Nutzung

**Das Nadelöhr:** Alles, was ins Langzeitgedächtnis soll, muss durch das Arbeitsgedächtnis. Wenn das Arbeitsgedächtnis überlastet ist, findet kein Lernen statt.

**Rhetorischer Hinweis:** Die Nadelöhr-Metapher ist zentral. Sie erklärt, warum Lernen Zeit und Anstrengung erfordert — es gibt keinen Bypass.
:::

### Slide: Drei Arten kognitiver Belastung

::: {.callout-tip}
## Sprechernotizen
**Die drei Typen:**

1. **Intrinsische Belastung:** Die Komplexität des Materials selbst.
   - Beispiel: Quadratische Gleichungen sind intrinsisch komplexer als Addition
   - Kann reduziert werden durch Vereinfachung (aber dann lernt man weniger)
   - Kann reduziert werden durch Vorwissen (Chunks im Langzeitgedächtnis)

2. **Extrinsische Belastung:** Belastung durch schlechtes Instruktionsdesign
   - Beispiel: Unübersichtliches Layout, irrelevante Information, getrennte Quellen
   - **Ziel:** Minimieren
   - Hier kann gute Didaktik helfen

3. **Lernförderliche (Germane) Belastung:** Produktive Anstrengung
   - Belastung, die zum Aufbau von Schemata führt
   - Beispiel: Selbsterklärungen, Elaboration, Vergleiche
   - **Ziel:** Erhalten oder erhöhen

**Die entscheidende Frage:** "Welche Art der Belastung reduziert KI?"

**Antwort (vorwegnehmen, aber noch nicht ausführen):**
- KI kann extrinsische Belastung reduzieren (gut)
- KI kann lernförderliche Belastung eliminieren (problematisch)
- Das Ergebnis hängt vom Nutzungskontext ab

**Methodologische Anmerkung:** Die Unterscheidung zwischen germane und extrinsic load ist in der Literatur umstritten. Sweller selbst hat in neueren Arbeiten die germane load als Konstrukt hinterfragt. Für unsere Zwecke ist die Kernaussage wichtig: Nicht alle kognitive Anstrengung ist gleich.
:::

### Slide: Der Expertise-Umkehr-Effekt

::: {.callout-tip}
## Sprechernotizen
**Hintergrund:** Der Expertise Reversal Effect wurde von Slava Kalyuga und Kollegen systematisch erforscht. Die Meta-Analyse (Kalyuga, 2007) fasst Dutzende Studien zusammen.

**Die Zahlen:**
- d = 0.505 für Novizen mit hoher Unterstützung: mittlerer positiver Effekt
- d = -0.428 für Experten mit hoher Unterstützung: mittlerer negativer Effekt
- Zur Einordnung: d = 0.4 gilt als "kleiner bis mittlerer" Effekt

**Warum passiert das?**
- Für Novizen: Unterstützung reduziert extrinsische Last, lässt Raum für Lernen
- Für Experten: Unterstützung ist redundant mit vorhandenem Wissen, verursacht zusätzliche Verarbeitung ("Ich weiss das schon, aber muss es trotzdem durcharbeiten")

**Beispiele:**
- Worked examples helfen Anfängern, stören Fortgeschrittene
- Detaillierte Anleitungen helfen Novizen, frustrieren Experten
- Scaffolding muss abgebaut werden, wenn Expertise wächst ("Fading")

**Implikation für KI:**
- Dasselbe KI-Tool kann für Experten produktiv und für Novizen schädlich sein
- Oder umgekehrt, je nach Nutzungsweise
- Es gibt keine "one-size-fits-all" Lösung

**Rhetorischer Hinweis:** Diese Folie ist zentral. Sie etabliert das theoretische Fundament für die Experten-Lernenden-Unterscheidung, die die gesamte Argumentation trägt.
:::

### Slide: Diskussion Think-Pair-Share (10 Min)

::: {.callout-tip}
## Sprechernotizen
**Ziel:** Persönliche Verbindung zum Material herstellen. Die Teilnehmenden sollen ihre eigene Expertise-Entwicklung reflektieren.

**Timing:**
- Think: 2-3 Minuten
- Pair: 3-4 Minuten
- Share: 3-4 Minuten (2-3 Beiträge)

**Typische Antworten:**
- "Am Anfang war alles bewusst und anstrengend, jetzt läuft es automatisch"
- "Ich sehe jetzt Muster, die ich früher nicht gesehen habe"
- "Ich weiss oft nicht mehr, warum ich etwas weiss — es ist einfach da"

**Überleitung:** "Ihr habt alle beschrieben, wie Expertise sich anfühlt: automatisch, musterbasiert, intuitiv. Aber diese Expertise kam nicht von selbst — sie kam durch Jahre der Übung. Die Frage ist: Was passiert, wenn KI diese Übung ersetzt?"
:::

---

## Teil 3: Kritisches Denken ist domänenspezifisch (~30 Min)

::: {.callout-note}
## Meta: Funktion von Teil 3
Dieser Teil adressiert einen verbreiteten Mythos: dass "kritisches Denken" oder "KI-Kompetenz" als generische Fähigkeit gelehrt werden kann. Die Widerlegung dieses Mythos ist wichtig, weil sie zeigt, warum Fachwissen nicht durch generische "Medienkompetenz" ersetzt werden kann.
:::

### Slide: Die traditionelle Annahme

::: {.callout-tip}
## Sprechernotizen
**Kontext:** Die "21st Century Skills"-Bewegung hat kritisches Denken als übertragbare Kernkompetenz propagiert. Viele Curricula versuchen, kritisches Denken fachunabhängig zu lehren.

**Die Annahme:** Es gibt eine allgemeine Fähigkeit "kritisches Denken", die in einem Kontext erworben und in anderen angewendet werden kann.

**Auf KI übertragen:** Die Idee, dass wir Studierenden "KI-Kompetenz" beibringen können — also die Fähigkeit, KI-Outputs kritisch zu bewerten — unabhängig vom Fachgebiet.

**Rhetorischer Hinweis:** Nicht direkt angreifen. Erst die Annahme neutral darstellen, dann hinterfragen. Das Publikum soll selbst skeptisch werden.

**Die rhetorische Frage:** "Aber stimmt diese Annahme?" — Überleitung zu Willingham.
:::

### Slide: Willinghams Herausforderung

::: {.callout-tip}
## Sprechernotizen
**Hintergrund zu Daniel Willingham:**
- Professor für Psychologie an der University of Virginia
- Bekannt für Arbeiten zur Anwendung der Kognitionspsychologie auf Bildung
- Sein Buch "Why Don't Students Like School?" (2009) ist weit verbreitet
- Der Artikel "Critical Thinking: Why Is It So Hard to Teach?" (2008) fasst die Forschung zusammen

**Das Zitat:** "Critical thinking is not a skill. There is not a set of critical thinking skills that can be acquired and deployed regardless of context."

**Willinghams Argument:**
1. Kritisches Denken erfordert Hintergrundwissen
2. Transfer von einer Domäne zur anderen ist extrem schwierig
3. Was wie "kritisches Denken" aussieht, ist meist Domänenwissen in Aktion

**Rhetorischer Hinweis:** Das Zitat ist provokant. Lass es wirken. Dann erkläre, was Willingham meint — nicht dass kritisches Denken unmöglich ist, sondern dass es domänenspezifisch ist.
:::

### Slide: Evidenz für Domänenspezifität

::: {.callout-tip}
## Sprechernotizen
**Die Beispiele:**

1. **Neurologen und Kardiologen:** Studie von Patel & Groen (1986). Neurologen, die kardiale Fälle analysierten, machten systematisch Fehler, die Kardiologen nicht machten — obwohl beide "kritisch denken" können.

2. **Fachredakteure und Zeitungsartikel:** Technische Redakteure konnten ihre Fähigkeiten nicht auf journalistisches Schreiben übertragen (Scardamalia & Bereiter, 1991).

3. **Philosophen und logische Fehler:** Selbst trainierte Philosophen werden von irrelevanten Merkmalen beeinflusst, wenn das Thema ausserhalb ihrer Expertise liegt (mehrere Studien).

**Das Zitat:** "Abstract principles like 'look for hidden assumptions' won't help much in evaluating an argument about a topic you know little about."

**Warum das wichtig ist:**
- "Kritisch denken" als Anweisung ist zu vage
- Man braucht Domänenwissen, um zu wissen, *worauf* man kritisch schauen soll
- Generische Strategien ("Quellen prüfen", "Logik überprüfen") nützen wenig ohne Fachwissen

**Mögliche Frage:** "Aber gibt es nicht transferierbare Strategien?"
**Antwort:** Einige metakognitive Strategien sind etwas übertragbar — das kommt auf der nächsten Folie.
:::

### Slide: Angewendet auf KI-Bewertung

::: {.callout-tip}
## Sprechernotizen
**Das Biomedizin-Beispiel:** Konkret machen. Ein Experte in Biochemie kann erkennen, wenn ChatGPT einen Stoffwechselweg falsch beschreibt. Ein Novize sieht nur flüssigen Text.

**Die zwei Seiten:**

*Experte:*
- Hat mentale Modelle des Fachgebiets
- Kann "Das klingt falsch" erkennen
- Weiss, welche Quellen zur Verifizierung dienen
- Kann Plausibilität einschätzen

*Novize:*
- Hat keine Referenzrahmen
- Kann nicht unterscheiden zwischen plausibel und korrekt
- Weiss nicht, welche Quellen autoritativ sind
- "Kritisches Denken" als Strategie hilft nicht

**Kernbotschaft:** "Was wie 'kritisches Denken' aussieht, ist tatsächlich Domänenwissen."

**Praktische Implikation:** Die Forderung "Studierende müssen lernen, KI kritisch zu nutzen" klingt sinnvoll, ist aber leer, wenn kein Fachwissen vorhanden ist.
:::

### Slide: Die Metakognitions-Lücke

::: {.callout-tip}
## Sprechernotizen
**Konzession:** Einige Strategien sind etwas verallgemeinerbar:
- Planung ("Bevor ich anfange, überlege ich...")
- Monitoring ("Verstehe ich das noch?")
- Evaluation ("War das erfolgreich?")

**Das Problem:** Die *Ausführung* dieser Strategien erfordert Domänenwissen.

**Die Tabelle durchgehen:**

| Strategie | Erfordert |
|-----------|-----------|
| "Prüfe, ob das plausibel ist" | Wissen, was plausibel wäre |
| "Verifiziere mit autoritativen Quellen" | Wissen, welche Quellen existieren |
| "Erkenne Fehler" | Wissen, was korrekt wäre |

**Beispiel:** "Prüfe, ob das plausibel ist" — ein Novize in Quantenphysik kann nicht einschätzen, ob eine Aussage über Quantenverschränkung plausibel ist. Die Strategie ist nutzlos ohne Hintergrundwissen.

**Rhetorischer Hinweis:** Hier wird das Argument geschärft. Selbst wenn metakognitive Strategien helfen können, erfordert ihre Anwendung Fachwissen.
:::

### Slide: Die zentrale Implikation

::: {.callout-tip}
## Sprechernotizen
**Die drei Punkte der Callout-Box:**

1. **Studierende mit "hohem kritischem Denken" haben wahrscheinlich mehr Domänenexpertise**
   - Studien, die zeigen, dass "kritische Denker" von KI profitieren, messen möglicherweise Vorwissen, nicht eine generische Fähigkeit

2. **Die beste Vorbereitung für kritische KI-Nutzung ist tiefes Fachlernen**
   - Kontraintuitiv: Nicht "KI-Training", sondern Fachausbildung
   - Expertise ermöglicht kritische Nutzung; ohne Expertise keine Kritik

3. **Generische "KI-Kompetenz" kann Fachwissen nicht ersetzen**
   - Workshops zu "Prompt Engineering" lösen das fundamentale Problem nicht
   - Die Fähigkeit, einen guten Prompt zu schreiben, ersetzt nicht die Fähigkeit, die Antwort zu bewerten

**Rhetorischer Hinweis:** Diese Folie ist die Brücke zum Produktivitäts-Lern-Paradox. Wenn kritische Evaluation Fachwissen erfordert, und KI das Erwerben von Fachwissen verhindert, dann verhindert KI die Fähigkeit, sie kritisch zu nutzen.
:::

### Slide: Diskussion (5 Min)

::: {.callout-tip}
## Sprechernotizen
**Ziel:** Konkrete Beispiele aus den Fächern der Teilnehmenden sammeln.

**Die Fragen:**
1. "Hast du beobachtet, dass Studierende KI-Outputs in deinem Fach nicht bewerten können?"
2. "Welches Domänenwissen wäre nötig?"

**Typische Antworten:**
- Medizin: "Sie merken nicht, wenn Symptomkombinationen unsinnig sind"
- Recht: "Sie sehen nicht, dass das Zitat aus dem falschen Rechtsgebiet stammt"
- Geschichte: "Sie erkennen keine anachronistischen Fehler"
- Informatik: "Der Code läuft, aber die Architektur ist problematisch"

**Überleitung:** "Ihr habt konkrete Beispiele genannt, wo Domänenwissen fehlt. Jetzt machen wir eine kurze Pause, und dann schauen wir uns an, was die Forschung über das Verhältnis von KI-Nutzung und Lernen sagt."
:::

---

## Pause (15 Min)

::: {.callout-tip}
## Sprechernotizen
**Timing:** 15 Minuten sind Standard für einen Workshop-Break. Pünktlich wieder beginnen.

**Während der Pause:** Eventuelle Materialien bereitlegen, Technik checken, kurz durchatmen.

**Zum Wiedereinstieg:** "Wir haben in den ersten 1.5 Stunden das theoretische Fundament gelegt: Wie Expertise entsteht, warum kritisches Denken domänenspezifisch ist, und warum nicht alle kognitive Anstrengung gleich ist. Jetzt schauen wir uns an, was passiert, wenn KI in dieses Bild kommt."
:::

---

## Teil 4: Das Produktivitäts-Lern-Paradox (~45 Min)

::: {.callout-note}
## Meta: Funktion von Teil 4
Dies ist der empirische Kern der Präsentation. Hier wird die Evidenz präsentiert, dass KI Aufgabenleistung verbessern, aber Lernen beeinträchtigen kann. Das theoretische Fundament aus Teil 2 und 3 macht diese Befunde erklärbar.
:::

### Slide: Das zentrale Paradox

::: {.callout-tip}
## Sprechernotizen
**Das Jose-Zitat:** "Learning and task completion are not synonymous." — aus einem Überblicksartikel von 2025, der das Paradox systematisch diskutiert.

**Die Unterscheidung:**
- **Aufgabenleistung (Performance):** Wie gut man eine Aufgabe *jetzt* löst
- **Lernen (Learning):** Die Fähigkeit, ähnliche Aufgaben *später unabhängig* zu lösen

**Warum das wichtig ist:**
- KI verbessert Aufgabenleistung (eindeutig belegt)
- Aber das sagt nichts über Lernen
- Lernen erfordert möglicherweise genau die Anstrengung, die KI eliminiert

**Rhetorischer Hinweis:** Dieses Konzept ist zentral und kontraintuitiv. Nimm dir Zeit. Mögliche Nachfrage: "Wenn ich eine Aufgabe besser löse, lerne ich doch dabei?" — Nicht unbedingt. Wenn KI die Arbeit macht, findet das Lernen im Kopf der KI statt, nicht im Kopf des Studierenden.
:::

### Slide: Die Bastani-Studie: Mathematik

::: {.callout-tip}
## Sprechernotizen
**Details zur Studie:**
- ~1000 türkische Gymnasiasten
- Randomisierte Zuweisung zu: (1) Kontrolle, (2) GPT-4 direkt, (3) "GPT Tutor"
- Mathe-Übungen über mehrere Wochen
- Test am Ende ohne KI-Zugang

**Die Bedingungen:**
- **Direkter Zugang:** Studierende konnten GPT-4 frei nutzen
- **GPT Tutor:** Strukturierte Nutzung mit pädagogischen Leitplanken

**Die Ergebnisse:**
- Mit direktem GPT-4: 48% mehr Aufgaben gelöst
- Mit GPT Tutor: 127% mehr Aufgaben gelöst
- Ohne KI (später): 17% schlechter als Kontrollgruppe

**Das Zitat:** "Students attempt to use GPT-4 as a 'crutch'..." — zentral für die Interpretation

**Die Nuance (Callout-Box):**
- Die negativen Effekte betrafen den direkten Zugang
- Der "GPT Tutor" zeigte bessere Ergebnisse
- Aber: Selbst mit Tutor war die Leistung ohne KI später reduziert
- Implikation: Die Art der KI-Nutzung macht einen Unterschied

**Methodologische Einschränkungen:**
- Einzelstudie, Replikation ausstehend
- Spezifischer Kontext (türkische Gymnasiasten, Mathematik)
- Kurzfristige Effekte (Wochen, nicht Jahre)

**Rhetorischer Hinweis:** Die Zahlen sind eindrücklich, aber nicht überbewerten. Die Studie zeigt ein Muster, beweist aber nicht, dass dies universell gilt.
:::

### Slide: Desirable Difficulties

::: {.callout-tip}
## Sprechernotizen
**Hintergrund zu Robert Bjork:**
- Professor an der UCLA, einer der einflussreichsten Lernforscher
- "Desirable Difficulties" ist sein bekanntestes Konzept
- Jahrzehnte der Forschung zu effektivem Lernen

**Das Zitat:** "Conditions that slow the rate of apparent learning often optimize long-term retention and transfer."

**Die vier Schwierigkeiten:**

1. **Variation:** Lernen unter wechselnden Bedingungen (nicht immer gleich)
2. **Interleaving:** Aufgabentypen mischen (nicht blocken)
3. **Spacing:** Verteilt lernen (nicht alles auf einmal)
4. **Retrieval Practice:** Aktiv abrufen (nicht passiv wiederholen)

**Alle vier haben gemeinsam:** Sie fühlen sich *schwerer* an, aber sie sind *effektiver*.

**Der Mechanismus (Callout-Box):** KI-Zugang kann Retrieval-Versuche kurzschliessen. Statt selbst nachzudenken ("Was weiss ich darüber?"), fragt man die KI. Die Gedächtnisspur wird nicht gestärkt.

**Rhetorischer Hinweis:** Hier wird der Mechanismus klar: KI eliminiert genau die Schwierigkeiten, die das Lernen fördern.
:::

### Slide: Der Generierungseffekt

::: {.callout-tip}
## Sprechernotizen
**Hintergrund:** Der Generierungseffekt wurde von Slamecka & Graf (1978) systematisch untersucht. Die Meta-Analyse umfasst 86 Studien.

**Das Experiment (typisch):**
- Gruppe A: Liest Wortpaare (Heiss — Kalt)
- Gruppe B: Ergänzt Wortpaare (Heiss — K___)
- Test: Beide Gruppen werden abgefragt
- Ergebnis: Gruppe B erinnert besser

**Effektstärke:** d = 0.40 — ein robuster, mittelgrosser Effekt über Dutzende Studien hinweg.

**Warum funktioniert es?**
- Aktivere Verarbeitung während des Generierens
- Mehr Verbindungen im Gedächtnis
- Tiefere Encodierung

**Die Implikation (Callout-Box):** Wenn KI generiert, was Studierende selbst produzieren sollten, wird der Generierungseffekt eliminiert.

**Konkretes Beispiel:**
- Studierende, die selbst einen Essay-Entwurf schreiben: Generierungseffekt
- Studierende, die einen KI-generierten Entwurf bearbeiten: kein Generierungseffekt
- Auch wenn das Endprodukt ähnlich aussieht, ist der Lernprozess fundamental verschieden

**Rhetorischer Hinweis:** Das ist der Mechanismus hinter "Crutch": Die Arbeit wird ausgelagert, aber damit auch das Lernen.
:::

### Slide: Die Scaffolding-Hypothese

::: {.callout-tip}
## Sprechernotizen
**Neues Konzept:** Diese Folie geht über die bisherige Argumentation hinaus. Sie unterscheidet zwei Arten von Schaden:

1. **Fertigkeitsatrophie:** Eine vorhandene Fähigkeit verkümmert durch Nichtgebrauch
   - Beispiel: GPS-Nutzung und räumliches Gedächtnis
   - Reversibel: Wenn man wieder übt, kommt die Fähigkeit zurück

2. **Entwicklungsbeeinträchtigung:** Eine Fähigkeit entsteht nie, weil der konstruktive Prozess übersprungen wird
   - Beispiel: Schreiben als Werkzeug, um Denken zu entwickeln
   - Möglicherweise irreversibel: Das Entwicklungsfenster wurde verpasst

**Die Hypothese:**
- Schreiben, Rechnen, Lesen sind nicht nur *Fertigkeiten*
- Sie sind *konstruktive Prozesse*, die kognitive Architektur aufbauen
- Schreiben ist ein "epistemisches Werkzeug" — Gedanken entwickeln sich *durch* das Schreiben

**Evidenz:**
- "Writing-to-learn" Forschung (Bangert-Drowns et al., 2004): Schreiben verursacht Lernen, demonstriert es nicht nur
- Flower & Hayes (1981): Schreiben als kognitiver Prozess
- Aber: Vieles ist korrelativ, Kausalität unsicher

**Rhetorischer Hinweis:** Diese Hypothese ist spekulativer als die vorherigen Punkte. Betone die Unsicherheit, aber auch die Tragweite, wenn sie stimmt.
:::

### Slide: Historische Analogien

::: {.callout-tip}
## Sprechernotizen
**GPS-Studie (Dahmani & Bohbot, 2020):**
- Longitudinale Studie über 3 Jahre
- Stärkere GPS-Nutzung korreliert mit steilerem Rückgang des räumlichen Gedächtnisses
- Kausalität bestätigt: GPS-Nutzung → Gedächtnisrückgang (nicht umgekehrt)
- Mechanismus: Hippocampus-Volumen verringert sich bei GPS-Nutzern

**Taschenrechner-Forschung (Siegler et al., 2017):**
- Jahrzehntelange Debatte in der Mathematikdidaktik
- Ergebnis: Kontext-abhängig
- Für Schüler mit Grundkenntnissen: neutral oder leicht positiv
- Für Schüler ohne Grundkenntnisse: schädlich
- Parallele zu KI: Dasselbe Tool, unterschiedliche Effekte je nach Vorwissen

**Google-Effekt (Sparrow et al., 2011):**
- Menschen erinnern Information schlechter, wenn sie erwarten, dass sie verfügbar bleibt
- Sie erinnern stattdessen, *wo* die Information zu finden ist
- "Transaktives Gedächtnis" — Wissen, wer/was weiss

**Das Muster:** Werkzeuge, die Experten helfen, können Novizen schaden. Kognitive Auslagerung hat Kosten.
:::

### Slide: Grenzen historischer Analogien

::: {.callout-tip}
## Sprechernotizen
**Wichtige Einschränkung:** Die historischen Analogien sind suggestiv, aber nicht ausreichend.

**Die Argumente:**
1. GPS, Taschenrechner, Google: jeweils *spezifische*, *enge* kognitive Funktionen
   - GPS: räumliche Navigation
   - Taschenrechner: arithmetische Berechnungen
   - Google: Informationsabruf

2. Generative KI: fast *jede* kognitive Aufgabe
   - Schreiben
   - Argumentieren
   - Analysieren
   - Synthetisieren
   - Bewerten

3. Die Breite ist beispiellos. Wir können nicht einfach extrapolieren.

**Aber:** Die historischen Bedenken hatten oft Berechtigung. Sie waren nicht "falsche Panikmache". GPS *beeinflusst* räumliche Kognition. Taschenrechner *veränderten* Mathematikunterricht.

**Rhetorischer Hinweis:** Diese Folie ist wichtig für die Glaubwürdigkeit. Sie zeigt, dass die Argumentation die Grenzen der Evidenz anerkennt.
:::

### Slide: "Das haben sie über das Schreiben auch gesagt"

::: {.callout-tip}
## Sprechernotizen
**Der Einwand:** Ein häufiges Gegenargument ist: "Sokrates hat vor dem Schreiben gewarnt, und wir haben überlebt. Jede neue Technologie löst Panik aus."

**Sokrates im Phaidros:** Schrift wird das Gedächtnis schwächen und nur "Scheinwissen" erzeugen.

**Die drei Antworten:**

1. **Schrift *hat* Kognition tiefgreifend verändert**
   - Wir denken anders als orale Kulturen
   - Abstraktion, Kategorisierung, lineare Argumentation wurden durch Schrift gefördert
   - Das war nicht nur positiv oder negativ — es war transformativ

2. **Einige Bedenken waren berechtigt**
   - Mündliche Gedächtnistraditionen *sind* zurückgegangen
   - Homers Epen wurden über Generationen mündlich überliefert — das können wir heute nicht mehr
   - Die Fähigkeit zu extensiver Memorierung ging verloren

3. **Schriftkultur entwickelte sich über Jahrhunderte**
   - Zeit für kulturelle Anpassung
   - Bildungssysteme entwickelten sich mit
   - KI-Integration geschieht in Jahren, nicht Jahrhunderten

**Rhetorischer Hinweis:** Diese Folie ist defensiv, aber wichtig. Sie zeigt, dass das "Sokrates-Argument" die Situation nicht entschärft.
:::

### Slide: Warum Experten profitieren, Lernende nicht

::: {.callout-tip}
## Sprechernotizen
**Die zwei Spalten zusammenfassen:**

*Experten können:*
- **Routine-Aufgaben sicher auslagern:** Sie wissen, welche Aufgaben "Routine" sind
- **Höheres Denken aufrechterhalten:** Die eingesparte kognitive Kapazität fliesst in komplexere Arbeit
- **KI-Outputs bewerten:** Sie haben die Domänenexpertise zur kritischen Evaluation
- **Haben Grundfähigkeiten, die nicht verkümmern:** Die Expertise ist schon da

*Lernenden fehlt:*
- **Wissen zur Bewertung:** Sie können nicht einschätzen, ob die KI richtig liegt
- **Etablierte Grundfähigkeiten:** Was sie nicht haben, kann nicht verkümmern — aber es entsteht auch nicht
- **Metakognitive Kontrolle:** Sie wissen nicht, wann KI-Nutzung schadet
- **"Fliessende Inkompetenz":** Sie können anspruchsvoll wirkende Outputs produzieren, ohne das Thema zu verstehen

**Der Begriff "Fliessende Inkompetenz":**
- Englisch: "Fluent incompetence"
- Beschreibt die Situation, in der Studierende professionell klingende Texte einreichen, ohne das Thema verstanden zu haben
- Das KI-Output sieht kompetent aus; das Wissen fehlt

**Kernbotschaft:** "Dasselbe Werkzeug, fundamental unterschiedliche Auswirkungen."
:::

### Slide: Diskussion Think-Pair-Share (15 Min)

::: {.callout-tip}
## Sprechernotizen
**Timing:** 15 Minuten — die längste Diskussion. Hier soll das Publikum das Gelernte auf den eigenen Kontext anwenden.

**Die Fragen:**
1. "Wo könnte KI-Unterstützung in deinem Fach die produktive Anstrengung eliminieren, die Lernen ermöglicht?"
2. "Welche Grundfähigkeiten könnten bei KI-Nutzung verkümmern?"

**Moderationshinweise:**
- Bei grossen Gruppen: Kleingruppen von 3-4 Personen
- Nach der Pair-Phase: Kurzes Brainstorming in Kleingruppen
- Share: 4-5 Beiträge aus verschiedenen Fächern sammeln

**Typische Antworten nach Fach:**
- **Medizin:** Differentialdiagnose erstellen, klinisches Reasoning
- **Recht:** Argumentation entwickeln, Präzedenzfälle finden
- **STEM:** Problem modellieren, Lösungsansätze generieren
- **Geisteswissenschaften:** Quellenkritik, eigene Thesen entwickeln
- **Sprachen:** Formulieren, Grammatik verinnerlichen

**Überleitung:** "Ihr habt konkrete Bereiche identifiziert, wo KI-Nutzung problematisch sein könnte. Im letzten Teil schauen wir uns an, was das für die Hochschullehre bedeutet — und was wir noch nicht wissen."
:::

---

## Teil 5: Implikationen und Synthese (~30 Min)

::: {.callout-note}
## Meta: Funktion von Teil 5
Dieser Teil zieht die Konsequenzen, ohne konkrete Rezepte zu geben. Die Argumentation ist: (1) Es gibt ein Problem, (2) das Problem ist theoretisch fundiert, (3) aber die Lösung ist kontextabhängig und die Evidenz unvollständig. Die Haltung ist "epistemische Bescheidenheit bei begründeter Sorge".
:::

### Slide: Die unbequeme Wahrheit

::: {.callout-tip}
## Sprechernotizen
**Die Callout-Box ist die zentrale These:**

"Was KI für Produktivität nützlich macht, macht sie für Lernen schädlich."

**Die drei Sätze auseinandernehmen:**

1. **"Was KI für Produktivität nützlich macht..."**
   - Sofortige Antworten
   - Kognitive Entlastung
   - Automatisierung von Denkarbeit

2. **"...macht sie für Lernen schädlich."**
   - Weil Lernen Anstrengung erfordert
   - Weil desirable difficulties eliminiert werden
   - Weil der Generierungseffekt wegfällt

3. **"Dies ist kein Mangel aktueller KI. Es folgt aus etablierten Prinzipien der Kognitionswissenschaft."**
   - Bessere KI wird das Problem nicht lösen
   - Das Problem liegt in der Natur des Lernens
   - **Aber:** "wobei die direkte Evidenz für KI noch begrenzt ist" — epistemische Bescheidenheit

**Rhetorischer Hinweis:** Diese Folie ist der Kulminationspunkt. Alles Vorherige führt hierhin. Lass sie wirken.
:::

### Slide: Mind-extending vs. Mind-replacing

::: {.callout-tip}
## Sprechernotizen
**Hintergrund zu Andy Clark:**
- Philosoph, bekannt für die "Extended Mind Thesis"
- Argument: Der Geist endet nicht an der Schädeldecke; Werkzeuge können Teil der Kognition sein
- 2025 hat er explizit zu generativer KI Stellung genommen

**Die Unterscheidung:**

*Kognition erweitern:*
- Der Mensch bleibt kognitiv engagiert
- Werkzeug verstärkt, ersetzt nicht
- Beispiel: Taschenrechner für einen Mathematiker (beschleunigt, aber der Mathematiker denkt)
- Fähigkeiten bleiben erhalten und werden ausgebaut

*Kognition ersetzen:*
- Der Mensch wird passiv
- Werkzeug übernimmt das Denken
- Beispiel: KI schreibt den Essay, Studierender submittet
- Abhängigkeit entsteht, Fähigkeiten verkümmern

**Kernbotschaft:** "Dasselbe Werkzeug kann beides sein, abhängig von der Nutzung."

**Praktische Implikation:** Die Frage ist nicht "KI ja oder nein?", sondern "Wie wird KI genutzt?"
:::

### Slide: Die Sequenzierungsfrage

::: {.callout-tip}
## Sprechernotizen
**Die vier Punkte:**

1. **"Grundwissen BEVOR KI vorteilhaft wird"**
   - Der Expertise-Umkehr-Effekt legt nahe: Erst Grundlagen, dann Tools
   - Aber: Ab wann hat jemand "genug" Grundwissen?

2. **"Dynamische Policies"**
   - Keine statischen Regeln ("KI verboten" oder "KI erlaubt")
   - Policies sollten sich mit dem Lernfortschritt ändern
   - Früh im Studium: restriktiver; später: offener

3. **"Ab welchem Punkt wechselt KI von schädlich zu hilfreich?"**
   - Das ist die Schlüsselfrage
   - Wir wissen es nicht genau
   - Es hängt von Domäne, Aufgabe und Person ab

4. **"Domänen- und studentenspezifisch"**
   - Keine universelle Antwort
   - Lehrende müssen für ihre Kontexte entscheiden

**Rhetorischer Hinweis:** Hier keine falschen Gewissheiten. Die Fragen sind offen. Das ist intellektuell ehrlich und respektiert die Komplexität.
:::

### Slide: Die Entwicklungsfrage

::: {.callout-tip}
## Sprechernotizen
**Neurowissenschaftlicher Hintergrund:**
- Präfrontaler Kortex: zuständig für exekutive Funktionen, Planung, Impulskontrolle
- Entwicklung dauert bis Mitte 20 (Giedd, 2004; Casey et al., 2008)
- Studierende im Bachelorstudium sind neurologisch noch in Entwicklung

**Die drei Punkte:**

1. **Präfrontaler Kortex entwickelt sich bis Mitte 20**
   - Die Gehirne von 18-Jährigen sind nicht "fertig"
   - Genau die Funktionen, die für Selbstregulation nötig sind, sind noch unreif

2. **Exekutive Funktionen, Metakognition, Selbstregulation noch in Entwicklung**
   - Die Fähigkeit zu entscheiden "Wann nutze ich KI?" erfordert Metakognition
   - Diese ist bei jungen Erwachsenen noch in Entwicklung

3. **Das Paradox:**
   - Jene, die KI-Nutzung am wenigsten regulieren können, sind am verletzlichsten
   - Die Gruppe, die am meisten Anleitung braucht, ist auch die, die am meisten KI nutzt

**Die Callout-Box (Kohortenfrage):**
- Die aktuelle Studierendengeneration könnte die erste sein, die komplett mit KI aufwächst
- Wir führen ein Experiment durch — ohne Kontrollgruppe
- Wenn wir in 20 Jahren Daten haben, ist es zu spät, etwas zu ändern

**Rhetorischer Hinweis:** Diese Folie kann Unbehagen auslösen. Das ist beabsichtigt. Es geht um eine ernste Frage.
:::

### Slide: Die Equity-Dimension

::: {.callout-tip}
## Sprechernotizen
**Hintergrund (Trucano, 2024):**
- "Third Digital Divide" — Begriff aus der Bildungstechnologie-Debatte
- Geht über Zugang (1. Kluft) und Nutzungskompetenz (2. Kluft) hinaus

**Die drei Klüfte:**

| Erste Kluft | Zweite Kluft | Dritte Kluft |
|-------------|--------------|--------------|
| Zugang zu Geräten | Fähigkeit zur sinnvollen Nutzung | Qualität der pädagogischen Integration |

**Die Ironie:**
- "Demokratisierung" durch KI könnte Ungleichheit verstärken
- Gutausgestattete Studierende: ausgeklügelte pädagogische Unterstützung, informierte Eltern, strukturierte KI-Nutzung
- Unterversorgte Studierende: KI als unbeaufsichtigte Abkürzung, niemand erklärt die Risiken

**Konkret:**
- Eliteschulen werden KI-Nutzung sorgfältig steuern
- Unterfinanzierte Schulen könnten KI als "Ersatz" für fehlende Lehrkräfte sehen
- Das Ergebnis: Ungleichheit wächst

**Rhetorischer Hinweis:** Diese Folie ist wichtig für ein Publikum, das sich für Bildungsgerechtigkeit interessiert. Sie zeigt, dass die KI-Frage nicht nur individuell, sondern auch gesellschaftlich ist.
:::

### Slide: Der stärkste Gegeneinwand

::: {.callout-tip}
## Sprechernotizen
**Der Einwand:** "Wenn KI immer verfügbar ist, müssen Fähigkeiten nicht internalisiert werden."

**Warum das der stärkste Einwand ist:**
- Er akzeptiert die Prämisse (KI ersetzt Fähigkeiten)
- Er zieht eine andere Schlussfolgerung (Das ist okay)
- Er ist nicht einfach zu widerlegen

**Die vier Antworten:**

1. **Permanenzannahme:**
   - Setzt voraus, dass KI immer da ist
   - Aber: Stromausfall, Serverprobleme, Kosten, politische Entscheidungen
   - KI-abhängige Menschen wären in solchen Situationen hilflos

2. **Rekursionsproblem:**
   - Wer erkennt, wenn KI falsch liegt?
   - Wer trainiert die nächste KI-Generation?
   - Wer erweitert das menschliche Wissen über das hinaus, was KI schon weiss?
   - Irgendwer muss die Domänenexpertise haben

3. **Autonomie-Argument:**
   - Eigenständiges Denken hat intrinsischen Wert
   - Für Selbstbestimmung, Würde, das Gefühl des Verstehens
   - Nicht alles lässt sich in Produktivität messen

4. **Unbekannte Unbekannte:**
   - Komplexe Systeme haben Kaskadeneffekte
   - Wir wissen nicht, was wir verlieren könnten
   - Vorsicht ist angebracht

**Rhetorischer Hinweis:** Diese Folie zeigt, dass die Argumentation die Gegenposition ernst nimmt. Das stärkt die Glaubwürdigkeit.
:::

### Slide: Was wir noch nicht wissen

::: {.callout-tip}
## Sprechernotizen
**Die fünf Punkte — epistemische Bescheidenheit:**

1. **Längsschnittstudien über Jahre:** Praktisch nicht vorhanden
   - Die meisten Studien sind kurzfristig (Wochen)
   - Langfristige Effekte (Jahre, Karrieren) sind unerforscht

2. **Transfer auf neue Kontexte:** Unerforscht
   - Können Studierende, die mit KI gelernt haben, in KI-freien Kontexten arbeiten?
   - Keine Daten

3. **Optimale Scaffolding-Bedingungen:** Unbekannt
   - Wann sollte KI eingeführt werden? Wie viel? In welcher Form?
   - Wir raten

4. **Disziplinspezifische Effekte:** Untererforscht
   - Ist Mathematik anders als Schreiben anders als Medizin?
   - Wahrscheinlich ja, aber Details fehlen

5. **Publikationsbias:** Wahrscheinlich vorhanden
   - Positive Ergebnisse werden eher publiziert
   - Die wahre Effektgrösse ist unsicher

**Kernbotschaft:** "Epistemische Bescheidenheit ist angebracht."

**Rhetorischer Hinweis:** Diese Folie ist wichtig für die Glaubwürdigkeit. Sie zeigt, dass die Präsentation nicht übertreibt.
:::

### Slide: Abschliessende Provokationen

::: {.callout-tip}
## Sprechernotizen
**Die vier Zitate — steigern sich:**

1. **"If AI assistance during education impairs independent capability..."**
   - Fokus: Was Studierende können, wenn sie graduieren
   - KI-freie Kontexte werden existieren

2. **"The productivity gains during education would come at the cost of capability thereafter."**
   - Fokus: Der Tradeoff
   - Kurzfristige Gewinne vs. langfristige Kosten

3. **"Whether this tradeoff is acceptable depends on assumptions about the future that educators cannot verify."**
   - Fokus: Unsicherheit
   - Wir wissen nicht, wie die Zukunft aussieht
   - Die Entscheidung basiert auf Annahmen

4. **"Wenn wir uns bei den Risiken irren..."** (auf Deutsch)
   - Fokus: Asymmetrie der Fehler
   - Wenn wir zu vorsichtig sind: langsame Technologieadoption
   - Wenn wir zu sorglos sind: geschädigte Generation
   - Das zweite ist schlimmer

**Rhetorischer Hinweis:** Diese Zitate sind bewusst provokant. Sie sollen zum Nachdenken anregen, nicht abschliessen.
:::

### Slide: Offene Diskussion (15 Min)

::: {.callout-tip}
## Sprechernotizen
**Ziel:** Freie Diskussion, nicht mehr strukturiert. Das Publikum soll eigene Schlüsse ziehen.

**Die drei Fragen:**
1. "Was bedeutet das für deine Lehre?"
2. "Wo siehst du die Experten-Lernenden-Unterscheidung in der Praxis?"
3. "Was sind die schwierigsten Fragen, die das aufwirft?"

**Moderationshinweise:**
- Frage 3 ist oft die fruchtbarste
- Zulassen, dass das Gespräch sich entwickelt
- Nicht alle Fragen beantworten müssen — Unsicherheit ist okay

**Mögliche Themen:**
- Prüfungsformen
- Plagiatserkennung vs. KI-Nutzungsrichtlinien
- Fairness (wenn manche KI nutzen, andere nicht)
- Die eigene Nutzung von KI als Lehrende

**Abschluss:** "Wir haben heute nicht alle Antworten gefunden — und das war auch nicht das Ziel. Das Ziel war, die richtigen Fragen zu stellen und ein theoretisches Fundament zu legen. Was ihr in euren Kontexten daraus macht, ist eure Entscheidung."
:::

---

## Anhang: Häufige Fragen und Antworten

::: {.callout-note}
## Meta: Über diesen Anhang
Dieser Anhang sammelt häufige Fragen, die während oder nach der Präsentation aufkommen können, mit möglichen Antworten.
:::

::: {.callout-tip}
## Sprechernotizen: FAQ

**F: "Sollten wir KI einfach verbieten?"**
A: Das ist weder praktikabel noch sinnvoll. Die Frage ist nicht ob, sondern wie und wann. Pauschalverbote ignorieren die Nuancen.

**F: "Ist die Bastani-Studie nicht nur eine Studie?"**
A: Ja, und das wird in der Präsentation erwähnt. Die Studie illustriert ein theoretisch gut begründetes Muster, aber Replikation ist nötig.

**F: "Was sollen wir denn konkret tun?"**
A: Die Präsentation gibt bewusst keine Rezepte, weil die Evidenz fehlt und die Kontexte verschieden sind. Aber: Grundlagen zuerst, KI später; Prozess bewerten, nicht nur Produkt; Reflexion über KI-Nutzung fördern.

**F: "Ist das nicht einfach Technikfeindlichkeit?"**
A: Nein. Die Argumentation basiert auf Kognitionswissenschaft, nicht auf Technologieangst. Es geht um die spezifische Frage, wie KI-Nutzung während des Lernens Lernen beeinflusst.

**F: "Aber KI kann doch auch als Tutor dienen?"**
A: Ja, und das wird in der Präsentation thematisiert (Bastani's "GPT Tutor"). Pädagogisch gestaltete KI ist etwas anderes als unstrukturierter Zugang. Die Unterscheidung ist wichtig.

**F: "Werden Studierende nicht sowieso KI nutzen, egal was wir sagen?"**
A: Wahrscheinlich. Aber das entbindet uns nicht von der Pflicht, über optimale Nutzung nachzudenken und Kontexte zu schaffen, in denen Lernen stattfindet.
:::

---

## Literaturhinweise zur Vertiefung

::: {.callout-tip}
## Sprechernotizen: Weiterführende Literatur

**Für Teilnehmende, die vertiefen wollen:**

*Zur Experten-Novizen-Forschung:*
- Chi, M. T. H., Feltovich, P. J., & Glaser, R. (1981). Categorization and representation of physics problems by experts and novices.

*Zu Cognitive Load Theory:*
- Sweller, J., Ayres, P., & Kalyuga, S. (2011). Cognitive Load Theory. Springer.

*Zu Desirable Difficulties:*
- Bjork, R. A., & Bjork, E. L. (2011). Making things hard on yourself, but in a good way.

*Zu kritischem Denken:*
- Willingham, D. T. (2008). Critical thinking: Why is it so hard to teach?

*Zur KI-Lern-Debatte:*
- Bastani, H., et al. (2024). Generative AI Can Harm Learning.
- Jose, A., et al. (2025). The Cognitive Paradox of AI Assistance.
:::
