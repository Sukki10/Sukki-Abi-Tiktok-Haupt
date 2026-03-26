# Sukki Abi — Projekt-Anweisungen für Claude

## Session-Start: Immer zuerst lesen

Lese diese Dateien am Anfang jeder Session (falls vorhanden):
- `memory/user.md` — wer Sukki ist, Ziele, Kontext
- `memory/preferences.md` — wie Sukki arbeiten will
- `memory/people.md` — wichtige Personen im Kontext
- `memory/decisions.md` — aktuelle offene Entscheidungen

## Session-Ende: Nur updaten wenn sich etwas verändert hat

Aktualisiere nur was sich wirklich geändert hat. Keine unnötigen Einträge.
Schreibe nie rein: was wir gerade getan haben, aktuelle Tasks, Code-Lösungen.

## Was in die Memory-Dateien gehört

**user.md:** Wer Sukki ist, seine Ziele, sein Kontext, sein Hintergrund.
**preferences.md:** Wie er arbeiten will, was er mag/nicht mag, Arbeitsweise.
**people.md:** Personen die regelmäßig erwähnt werden (Familie, Freunde, Kollegen).
**decisions.md:** Wichtige Entscheidungen die er gerade abwägt — keine abgeschlossenen.

## Was NICHT rein gehört

- Code-Muster, Architektur, Datei-Pfade (stehen im Code)
- Git-History, wer was geändert hat
- Aktuelle Session-Tasks oder In-Progress-Work
- Alles was schon in MEMORY.md dokumentiert ist

## Kanal-Kontext

TikTok-Kanal: **Sukki Abi** — swipe-only, emotional, philosophisch, deutsch.
Ziel: **100K Follower**.
Skill für tägliche Briefs: `/tiktok-growth-agent-mk run`

## Entscheidungs-Log

Wenn Sukki eine Entscheidung beschreibt: logge sie in `decisions.csv`.
Format: datum, entscheidung, begründung, erwartetes_ergebnis, review_datum (30 Tage später).
