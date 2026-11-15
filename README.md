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
| Patterns | A–D pro Idee, kopieren, leeren, „Kette“ spielt alle gefüllten Patterns nacheinander |
| Kick-Designer | Pitch-Start, Grundton, Pitch-Sweep, Länge, Klick, Verzerrung, Höhen |
| Rumble | Hall auf der Kick, verzerrt und tiefpassgefiltert, mit Ducking |
| Bass / Lead | Piano-Roll nur mit Tönen der Tonart; Lead mit Supersaw, Akkord-Modus, Hall und Delay |
| Export | ZIP mit Mix, Stems, MIDI (Drum-Rack-Belegung C1/D#1/F#1/A#1), `idee.json` und Anleitung |

Leertaste startet und stoppt die Wiedergabe.

## Was nicht ins Repo gehört

Audio-Dateien und Exporte sind per `.gitignore` ausgeschlossen. Ins Repo kommen Code, Notizen und Ideen als kleine JSON-Dateien (z. B. unter `ideas/`).
