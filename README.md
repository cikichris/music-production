# music-production

Privates Repo für eigene Hardbounce- und Hardtechno-Produktionen.

## Workflow

1. **Ideen skizzieren** im Rave-Skizzenblock (`sketchpad/index.html`): Beats, Kick, Rumble, Bass und Stabs im Browser bauen.
2. **Exportieren** als ZIP: Mix, Einzelspuren (48 kHz / 24 Bit, nahtlos loopbar), MIDI und `idee.json`.
3. **In Ableton fertig produzieren:** Sounds nachbauen oder layern, arrangieren, mischen, mastern.
4. **Veröffentlichen** als Free Download. Nur selbst erzeugte Sounds oder lizenzfreie Samples verwenden, keine ungeklärten Vocals oder Pop-Edits.

## Rave-Skizzenblock

Läuft komplett im Browser, ohne Installation und ohne Samples. Alle Sounds werden per Web Audio synthetisiert.

- **Lokal:** `sketchpad/index.html` per Doppelklick im Browser öffnen (Chrome oder Firefox). Ideen werden im Browser gespeichert. Nur hier gibt es den Knopf „Aufnehmen“ fürs Mikrofon.
- **In claude.ai:** als private Seite. Dort werden Ideen und Vocals in der Cloud gespeichert, und Claude kann die Ideen lesen und weiterverarbeiten. Mikrofonzugriff gibt es dort nicht, Vocals kommen über „Aufnahme laden“.

| Bereich | Was es kann |
| --- | --- |
| Step-Sequencer | Kick, Clap, Hi-Hat, Open Hat, Perc, Ride (Klick: an, Akzent, aus), Bass, Lead und Pluck mit Notennamen |
| Polymeter | Jede Spur hat eine eigene Loop-Länge (1–16 Steps). Ungerade Längen laufen gegen den Takt, typisch für Hypnotic Techno |
| Patterns | A–H pro Idee, kopieren, leeren |
| Ideen-Generator | „Hypnotic würfeln“ (Rumble, rollender Bass, Polymeter-Perc, Dub-Stab, kreisende Sequenz) und „Bounce würfeln“ in zwei Richtungen (dunkel und treibend, oder hell und melodisch): jedes Mal eine neue Idee mit Akkordfolge, Bass, Stabs, Melodie und fertigem Arrangement |
| Song | Abschnitte mit Pattern-Folge, Länge, Spuren an/aus und Übergängen (Crash, Riser, Clap-Roll, Kick-Pause, Filterfahrt) |
| Kick-Designer | Pitch-Start, Grundton, Pitch-Sweep, Länge, Klick, Verzerrung, Höhen |
| Rumble | Hall auf der Kick, verzerrt und tiefpassgefiltert, mit Ducking |
| Bass / Lead / Pluck | Piano-Roll nur mit Tönen der Tonart; Lead mit Supersaw und Akkord-Modus, Pluck für Melodien |
| Vocals | Eigene Aufnahmen laden (z. B. aus „Sprachmemos“) oder lokal am Rechner direkt einsingen; Ausschnitt, Tonhöhe, Verzerrung, Filter, Zerhacker, Hall und Delay; pro Song-Abschnitt platzierbar |
| Live | DJ-Filter, Delay-Wurf, Hall-Fahne, Kick raus (halten) und „Variation“ für neue Hat-, Perc- und Notenmuster |
| Mastering | Lautheit nach ITU-R BS.1770 auf ein Ziel bringen (−14 bis −6,5 LUFS), Limiter mit True-Peak-Grenze −1 dBTP, Bericht mit Lautheitskurve |
| Export | Ganzer Song oder Pattern-Loop als ZIP mit Mix, Stems, MIDI (Drum-Rack-Belegung C1/D#1/F#1/A#1), `idee.json` und Anleitung |

Leertaste startet und stoppt die Wiedergabe.

### Auf dem iPhone

Unter 760 px Breite schaltet der Skizzenblock in eine Handy-Ansicht: feste Leiste unten mit Play in der Mitte und den Bereichen Beat, Klang, Song und Ideen. Oben bleiben Patterns und Tempo stehen; ein Tipp auf „BPM“ klappt Swing, Tonart und Pattern-Werkzeuge aus. Ein Tipp auf einen Spurnamen öffnet dessen Klang-Einstellungen.

## Was nicht ins Repo gehört

Audio-Dateien und Exporte sind per `.gitignore` ausgeschlossen. Ins Repo kommen Code, Notizen und Ideen als kleine JSON-Dateien (z. B. unter `ideas/`).

## Projekte

| Projekt | Stil | Tempo / Tonart | Datei |
| --- | --- | --- | --- |
| Projekt 01 – Überholspur | Melodischer Bounce mit Hardtechno-Kante, 136 Takte, ca. 3:27 | 158 BPM, F-Moll | `ideas/projekt-01-ueberholspur.json` |
| Projekt 02 – Sperrstunde | Dunkler, treibender Bounce: rollender Bass, mehr Rumble, kurzer Hook, 136 Takte, ca. 3:35 | 152 BPM, F-Moll | `ideas/projekt-02-sperrstunde.json` |
| Projekt 03 – Spirale | Hypnotic Groove: Perc 13 Steps, Stab und Sequenz 7 Steps gegen den Takt, 136 Takte, ca. 3:57 | 138 BPM, A-Moll | `ideas/projekt-03-spirale.json` |
