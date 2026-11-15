# music-production

Privates Repo für eigene Hardbounce- und Hardtechno-Produktionen.

## Workflow

1. **Ideen skizzieren** im Rave-Skizzenblock (`sketchpad/index.html`): Beats, Kick, Rumble, Bass und Stabs im Browser bauen.
2. **Exportieren** als ZIP: Mix, Einzelspuren (48 kHz / 24 Bit, nahtlos loopbar), MIDI und `idee.json`.
3. **In Ableton fertig produzieren:** Sounds nachbauen oder layern, arrangieren, mischen, mastern.
4. **Veröffentlichen** als Free Download. Nur selbst erzeugte Sounds oder lizenzfreie Samples verwenden, keine ungeklärten Vocals oder Pop-Edits.

## Rave-Skizzenblock

Läuft komplett im Browser, ohne Installation und ohne Samples. Alle Sounds werden per Web Audio synthetisiert.

- **Lokal:** `sketchpad/index.html` per Doppelklick im Browser öffnen (Chrome oder Firefox). Ideen werden im Browser gespeichert.
- **In claude.ai:** als private Seite. Dort werden Ideen in der Cloud gespeichert, und Claude kann sie lesen und weiterverarbeiten.

| Bereich | Was es kann |
| --- | --- |
| Step-Sequencer | Kick, Clap, Hi-Hat, Open Hat (Klick: an, Akzent, aus), Bass und Lead mit Notennamen |
| Patterns | A–H pro Idee, kopieren, leeren |
| Ideen-Generator | „Bounce-Track würfeln“ erzeugt jedes Mal eine neue melodische Bounce-Idee mit Akkordfolge, Bass, Stabs, Melodie und fertigem Arrangement |
| Song | Abschnitte mit Pattern-Folge, Länge, Spuren an/aus und Übergängen (Crash, Riser, Clap-Roll, Kick-Pause, Filterfahrt) |
| Kick-Designer | Pitch-Start, Grundton, Pitch-Sweep, Länge, Klick, Verzerrung, Höhen |
| Rumble | Hall auf der Kick, verzerrt und tiefpassgefiltert, mit Ducking |
| Bass / Lead / Pluck | Piano-Roll nur mit Tönen der Tonart; Lead mit Supersaw und Akkord-Modus, Pluck für Melodien |
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
