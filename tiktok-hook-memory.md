# Sukki Abi — Hook Memory System
*Zuletzt aktualisiert: 2026-03-27 | V007 finale Stats ausstehend — RANG 2 noch PRELIMINARY*

---

## Hook-Typ Performance Tabelle

**WICHTIG: Sample-Größe + Confidence beachten.**
- EARLY SIGNAL (<12h) = KEIN Datenpunkt — nicht in Durchschnitt einrechnen
- PRELIMINARY (1 bestätigter Sample) = vorsichtig verwenden
- BELASTBAR (2+ bestätigte Samples, alle >24h) = verlässlich
- V000 (2023) = historischer Benchmark — kein gleichwertiger Sample für aktuelle Algo-Logik

| Hook-Typ | Trigger-Code | Ø Completion | Ø Shares | Ø Saves | Sample-Größe | Zuverlässigkeit | Status |
|----------|-------------|-------------|----------|---------|--------------|-----------------|--------|
| VERLUST + ZEITDRUCK | [C]+[D] | 47% | 2.432 | 4.761 | 2 | BELASTBAR | ✅ TOP-PATTERN |
| IDENTITÄT + DIREKTE ANSPRACHE | [E]+[A] | 35.1%* | 860 | 1.940 | 1 bestätigt + 1 EARLY | PRELIMINARY | ⚠️ STARK (wird BELASTBAR nach V007 Bestätigung) |
| VERLUST + DIREKTE ANSPRACHE | [C]+[A] | 30.3% | 2.108 | 2.145 | 1 | PRELIMINARY | ✅ STARK |
| IDENTITÄT + KONFLIKT | [E]+[B] | 19.2% | 1.387 | 1.934 | 1 | PRELIMINARY | ⚠️ MITTEL |
| VERLUST + IDENTITÄT | [C]+[E] | 17.5% | 1.362 | 2.275 | 1 | PRELIMINARY | ⚠️ MITTEL |
| DIREKTE ANSPRACHE + KONFLIKT | [A]+[B] | 16.4% | 2.904 | 1.026 | 1 | PRELIMINARY | ⚠️ MITTEL (hohe Shares, low Completion) |
| ZEITDRUCK allein | [D] | — | — | — | 0 | UNGETESTET | 🔬 |
| KONFLIKT + ZEITDRUCK | [B]+[D] | — | — | — | 0 | UNGETESTET | 🔬 |

---

## Top-Pattern (priorisieren)

**RANG 1 — VERLUST + ZEITDRUCK [C]+[D]**
- Ø Completion: 47% (V004: Vater/Zeit + V000 Benchmark: Nostalgie)
- Ø Shares: 2.432 | Ø Saves: 4.761
- Beste Themen: Vater, Zeit, Nostalgie, Vergänglichkeit
- Empfohlene Sounds: distorted memories, 3 am walk

**RANG 2 — IDENTITÄT + DIREKTE ANSPRACHE [E]+[A]** ⚠️ PRELIMINARY
- Bestätigt: 35.1% (V003) | EARLY SIGNAL: 40% (V007 — noch nicht in Durchschnitt)
- Ø Completion BESTÄTIGT: 35.1% | Nach V007 Bestätigung: ~37.6%
- Ø Shares: 860 | Ø Saves: 1.940
- Beste Themen: Selbstbild, innere Wahrheit, Charakter, Mama/Familie
- Empfohlene Sounds: Riff 2, campxfire
- ⚠️ WIRD BELASTBAR sobald V007 finale Stats >24h bestätigt sind

**RANG 3 — VERLUST + DIREKTE ANSPRACHE [C]+[A]**
- Ø Completion: 30.3% (V006: Ramadan/Gier)
- Ø Shares: 2.108 | Ø Saves: 2.145
- Beste Themen: Gier, moralische Konflikte, Ramadan
- Empfohlene Sounds: thematisch

---

## Schwach-Pattern (reduzieren oder anpassen)

- **DIREKTE ANSPRACHE + KONFLIKT [A]+[B]** → hohe Shares aber Completion 16.4% → Hook-Problem (Abbruch bei 0:01)
- **IDENTITÄT + KONFLIKT [E]+[B]** → Completion 19.2% — nur empfehlen wenn Thema stark

---

## Ungetestete Kombinationen (für Tests)

- [B]+[D] KONFLIKT + ZEITDRUCK — noch ungetestet, theoretisch stark
- [D] allein — nie isoliert getestet
- [C]+[B] VERLUST + KONFLIKT — noch ungetestet

---

## Hook-Test-Log
*(Wird nach jedem analyze-Modus erweitert)*

| Datum | Hook-Text (Auszug) | Typ-Codes | Completion | Shares | Saves | Neue Follower | Confidence |
|-------|--------------------|-----------|-----------|--------|-------|---------------|------------|
| 26.03.2026 | Deine Mama fragt immer. Du antwortest seltener. | [E]+[A] | 40% | — | 1 | 0 | EARLY SIGNAL (<12h) — finale Stats ausstehend |
| 19.02.2026 | Gier-Thema Ramadan | [C]+[A] | 30.3% | 2.108 | 2.145 | 200 | CONFIRMED |
| 03.12.2025 | Mama-Thema | [C]+[E] | 17.5% | 1.362 | 2.275 | 158 | CONFIRMED |
| 02.12.2025 | Vater/Zeit | [C]+[D] | 47% | 1.960 | 1.588 | 133 | CONFIRMED |
| 04.10.2025 | Ich bin noch nicht... | [E]+[A] | 35.1% | 860 | 1.940 | 80 | CONFIRMED |
| 29.11.2025 | Pass auf was du sagst | [E]+[B] | 19.2% | 1.387 | 1.934 | 156 | CONFIRMED |
| 21.05.2025 | Kindheit/Nostalgie | [A]+[B] | 16.4% | 2.904 | 1.026 | 55 | CONFIRMED |
| 15.01.2023 | Nostalgie Benchmark | [C]+[D] | — (640K Views) | 8.446 | 7.934 | 1.300 | CONFIRMED |

---

## WINNER-CONFIDENCE-LAYER (für alle Agenten)

**Unterscheide immer:**
- EARLY SIGNAL = < 12h Daten → KEIN harter Winner-Modus. Nur als Hinweis nutzen.
- PRELIMINARY WINNER = 12h bis < 24h → Vorsichtige Winner-Tendenz erlaubt
- CONFIRMED WINNER = >= 24h + Completion >35% → Winner-Modus aktivieren

**Im Output immer anzeigen:**
`WINNER-STATUS: [EARLY SIGNAL / PRELIMINARY / CONFIRMED / KEIN WINNER]`

---

## DATA-FRESHNESS-REGELN (für alle Agenten)

**Pruefe Datum des letzten Eintrags in tiktok-log.md:**
- AKTUELL = <= 48h → normaler Betrieb, Winner-Check erlaubt
- STALE = > 48h bis 7 Tage → Warnung anzeigen, Winner-Status als unsicher markieren, Trends hoeher gewichten
- KRITISCH VERALTET = > 7 Tage → Winner-Check deaktiviert, kein falsches Vertrauen, User-Reminder: "analyze + git push ausfuehren"

**Wenn STALE oder KRITISCH VERALTET:**
Erste Zeile des Outputs: `⚠️ DATEN [X TAGE ALT] — bitte analyze ausfuehren + git push`

---

## Ablese-Regeln für Agenten

**Completion-Priorität:**
- >35% = TOP-PATTERN → sofort priorisieren
- 25–35% = STARK → bevorzugt einsetzen
- 15–25% = MITTEL → nur mit starkem Thema
- <15% = SCHWACH → vermeiden oder Hook neu schreiben

**Pattern-Label im Output:**
- `[TOP-PATTERN: C+D]` → wenn Completion >35% bestätigt
- `[STARK-PATTERN: E+A]` → wenn Completion 25–35% bestätigt
- `[UNGETESTET]` → wenn kein Datenpunkt vorhanden

---

*Dieses Dokument wird automatisch durch Agent 8 (Learning Agent) nach jedem `analyze`-Modus aktualisiert.*
