# Sukki Abi — Hook Memory System
*Zuletzt aktualisiert: 2026-03-26 22:15 CET | V007 Live-Update integriert*

---

## Hook-Typ Performance Tabelle

| Hook-Typ | Trigger-Code | Ø Completion | Ø Shares | Ø Saves | Sample-Größe | Status |
|----------|-------------|-------------|----------|---------|--------------|--------|
| VERLUST + ZEITDRUCK | [C]+[D] | 47% | 2.432 | 4.761 | 2 | ✅ TOP-PATTERN |
| IDENTITÄT + DIREKTE ANSPRACHE | [E]+[A] | 37.6% | 860 | 1.940 | 2 | ✅ STARK |
| VERLUST + DIREKTE ANSPRACHE | [C]+[A] | 30.3% | 2.108 | 2.145 | 1 | ✅ STARK |
| IDENTITÄT + KONFLIKT | [E]+[B] | 19.2% | 1.387 | 1.934 | 1 | ⚠️ MITTEL |
| VERLUST + IDENTITÄT | [C]+[E] | 17.5% | 1.362 | 2.275 | 1 | ⚠️ MITTEL |
| DIREKTE ANSPRACHE + KONFLIKT | [A]+[B] | 16.4% | 2.904 | 1.026 | 1 | ⚠️ MITTEL (hohe Shares, low Completion) |
| ZEITDRUCK allein | [D] | — | — | — | 0 | 🔬 UNGETESTET |
| KONFLIKT + ZEITDRUCK | [B]+[D] | — | — | — | 0 | 🔬 UNGETESTET |

---

## Top-Pattern (priorisieren)

**RANG 1 — VERLUST + ZEITDRUCK [C]+[D]**
- Ø Completion: 47% (V004: Vater/Zeit + V000 Benchmark: Nostalgie)
- Ø Shares: 2.432 | Ø Saves: 4.761
- Beste Themen: Vater, Zeit, Nostalgie, Vergänglichkeit
- Empfohlene Sounds: distorted memories, 3 am walk

**RANG 2 — IDENTITÄT + DIREKTE ANSPRACHE [E]+[A]**
- Ø Completion: 35.1% (V003: Gedanken)
- Ø Shares: 860 | Ø Saves: 1.940
- Beste Themen: Selbstbild, innere Wahrheit, Charakter
- Empfohlene Sounds: Riff 2

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

| Datum | Hook-Text (Auszug) | Typ-Codes | Completion | Shares | Saves | Neue Follower |
|-------|--------------------|-----------|-----------|--------|-------|---------------|
| 19.02.2026 | Gier-Thema Ramadan | [C]+[A] | 30.3% | 2.108 | 2.145 | 200 |
| 03.12.2025 | Mama-Thema | [C]+[E] | 17.5% | 1.362 | 2.275 | 158 |
| 02.12.2025 | Vater/Zeit | [C]+[D] | 47% | 1.960 | 1.588 | 133 |
| 04.10.2025 | Ich bin noch nicht... | [E]+[A] | 35.1% | 860 | 1.940 | 80 |
| 29.11.2025 | Pass auf was du sagst | [E]+[B] | 19.2% | 1.387 | 1.934 | 156 |
| 21.05.2025 | Kindheit/Nostalgie | [A]+[B] | 16.4% | 2.904 | 1.026 | 55 |
| 15.01.2023 | Nostalgie Benchmark | [C]+[D] | — (640K Views) | 8.446 | 7.934 | 1.300 |

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
