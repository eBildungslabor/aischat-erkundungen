# AIS.chat in der Praxis — Über die Schulter geschaut

**Was Kolleg:innen ausprobiert haben.** Fünf fiktive Porträts von Lehrkräften, die AIS.chat in ihrem Unterricht erprobt haben.

➡️ **[Zur Website](https://ebildungslabor.github.io/aischat-erkundungen/)**

## Worum es geht

Am Niedersächsischen Landesinstitut für schulische Qualitätsentwicklung (NLQ) entsteht gerade ein Selbstlernangebot zu AIS.chat. Darin finden sich fiktive Porträts von Kolleginnen und Kollegen und ihrer Nutzung.

In diesem Repository liegt der **erste Entwurf dieser Inhalte** zum Anschauen und Erkunden: Suche dir das Porträt aus, das dir spannend erscheint. Lies es dir durch. Halte Schlussfolgerungen für dich fest. Teile sie mit Kolleginnen und Kollegen.

## Die fünf Porträts

| Porträt | Kontext | Anwendungssituation |
| --- | --- | --- |
| [Britta H.](britta.html) | Grundschule, 4. Klasse, ländlicher Raum | differenzierte Lernmaterialien erstellen |
| [Dr. Ralf B.](ralf.html) | Chemie und Physik, Gymnasium | Übungsmaterialien erstellen, über die eigene KI-Nutzung sprechen |
| [Anne S.](anne.html) | Geschichte, gymnasiale Oberstufe an einer IGS | einen Dialogpartner bauen, historisches Lernen und Quellenkritik |
| [Ilja P.](ilja.html) | Mathematik, Oberschule, 8. Schuljahrgang | Lernprozesse dialogisch begleiten |
| [Markus D.](markus.html) | Klassen- und Beratungslehrer, KGS | sensible Gespräche vorbereiten, Datenschutz |

Jedes Porträt folgt demselben Aufbau: Kontext · Pädagogisches Ziel · Vorgehen · Qualitätscheck · Einsatz und Ergebnis · Chancen, Risiken und Grenzen · Reflexion und Feedback · Konsequenzen · Zum Weiternutzen · Jetzt bist du dran.

## Status

Dies ist ein **Entwurf in Erarbeitung**, kein fertiges Kursangebot. Inhalte, Formulierungen und Struktur können sich noch ändern. Rückmeldungen sind willkommen, gerne als [Issue](../../issues).

Die dargestellten Personen sind frei erfunden. Sie bilden typische Situationen ab, keine realen Lehrkräfte.

## Technisches

Statische Website ohne Build-Schritt, ohne Tracking und ohne externe Ressourcen zur Laufzeit.

```
index.html              Startseite mit den fünf Kacheln
britta|ralf|anne|ilja|markus.html   die Porträtseiten
css/pico.min.css        CSS-Framework (lokal eingebunden)
css/custom.css          eigene Anpassungen
bilder/                 Illustrationen zu den Porträts
```

Lokal anschauen: `python -m http.server` im Projektordner starten und <http://localhost:8000> öffnen.

## Credits

Danke an alle, deren offene Arbeit hier weitergenutzt wird:

- [Pico CSS](https://picocss.com) — leichtgewichtiges CSS-Framework, MIT-Lizenz

## Auftrag und Lizenz

Die Inhalte entstehen im Auftrag des [NLQ](https://www.nlq.niedersachsen.de) und werden vom [eBildungslabor](https://ebildungslabor.de) erarbeitet.

Sie stehen unter der Lizenz [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de). Nachnutzung ist also ausdrücklich erwünscht, auch verändert und auch kommerziell, solange die Herkunft angegeben wird. Empfohlene Namensnennung:

> "AIS.chat in der Praxis — Über die Schulter geschaut" von NLQ, Lizenz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)

Ausgenommen ist das enthaltene CSS-Framework Pico CSS, das unter der MIT-Lizenz steht.
