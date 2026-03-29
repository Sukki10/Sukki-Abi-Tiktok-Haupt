# Sukki Abi — Hook Memory System
*Zuletzt aktualisiert: 2026-03-28 CET | V008 PRELIMINARY eingetragen — [C]+[D] neuer moderner Sample*

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
| IDENTITÄT + DIREKTE ANSPRACHE | [E]+[A] | 39.8% | 431 | 975 | 2 | BELASTBAR | ✅ STARK |
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

**RANG 2 — IDENTITÄT + DIREKTE ANSPRACHE [E]+[A]** ✅ BELASTBAR
- Ø Completion: 39.8% (V003: 35.1% + V007: 44.4%) — 2 bestätigte Samples
- Ø Shares: 431 | Ø Saves: 975
- Beste Themen: Mama/Familie, Selbstbild, innere Wahrheit, Charakter
- Empfohlene Sounds: campxfire, Riff 2
- ⚠️ Follower/1K Views V007 = 0.0 — Follow-Trigger auf Slide 7 stärken
- KRITISCH: Für Mama-Thema [E]+[A] immer über [C]+[E] (40% vs 17.5%)

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
| 28.03.2026 | Deine Mama braucht dich — aber fragt nie danach. | [E]+[A] | 42.5% | 3 | 7 | 1 | PRELIMINARY (~16h) → CONFIRMED ab 29.03 21:00 |
| 27.03.2026 | Deine Mama wird älter — du merkst es zu spät | [C]+[D] | 46.25% | 5 | 20 | 0 | CONFIRMED |
| 26.03.2026 | Deine Mama fragt immer. Du antwortest seltener. | [E]+[A] | 44.4% | 2 | 11 | 0 | CONFIRMED |
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
