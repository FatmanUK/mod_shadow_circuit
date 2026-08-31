# Pattern04 — "Rising Tension"

The groove returns to the Main Thump B feel (steady kick, driving 8th-note hi-hat, the familiar 3-note DeepBass pulse-cell), but Siren now takes over channel 4 for the whole pattern — since it's a continuous rising element, the snare backbeat steps aside for this one (it comes back in force for the climax).

New effect: **`1xx` — Portamento Up**. Unlike `3xx`, there's no destination note — it just continuously raises the pitch (lowers the period) by `x` per tick, for as long as the effect is active. That's the actual mechanism behind a classic alarm/tension riser: it just keeps climbing.That table is mostly one repeating line (Ch4 = `... .. 101` on every single row from `02` to `3F`, continuous) — here's the compact version:

**Pattern04 — "Rising Tension"**

- **Ch1 (kick):** unchanged — steady quarter-note thump, rows `00,04,08,0C,10,...,3C`.
- **Ch2 (DeepBass):** the same 3-note pulse-cell from Pattern00/01 (not the Dark Variation chromatic run) — keeps this pattern feeling like a continuation of the groove, not another variation.
- **Ch3 (hi-hat):** unchanged — straight 8ths, `C38`/`C20` alternating accents.
- **Ch4 (Siren):** row `01` triggers `C-3 08 ...` (its starting pitch); **every row from `02` through `3F`** carries `... .. 101` — a continuous portamento-up, no exceptions, no destination note. Snare sits out this pattern entirely to give Siren the channel.

I calculated the rate rather than guessing: at `01`/tick across the full pattern, Siren climbs from C-3 up to roughly A#3 by the end — a clear, audible rise, but deliberately not reaching the top of the valid range. That headroom is intentional: Pattern05 ("Peak Thump") is the actual climax, so this shouldn't already max out.

**Audition criteria:**
1. Does the Siren read as a single continuous, gradually rising pitch across all 4 bars — not stepped, not stuck?
2. Does dropping the snare (to give Siren the channel) feel like a deliberate trade-off — tension replacing backbeat — rather than the groove feeling incomplete?
3. Does the pitch, by the end of the pattern, feel like it's "still climbing" / leaving room for more, rather than already peaking?
4. Does the familiar kick/hihat/bass groove underneath keep this feeling grounded, so the rising Siren reads as tension being added rather than the whole track spiraling?

Let me know how it plays before Pattern05 ("Peak Thump").

Understood — here's the full table, unabbreviated:

```
Row | Ch1        | Ch2        | Ch3        | Ch4
------------------------------------------------------
00  | C-4 01 ... | ... .. ... | C-4 03 C38 | C-3 08 ...
01  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
02  | ... .. ... | E-4 04 ... | C-4 03 C20 | ... .. 101
03  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
04  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
05  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
06  | ... .. ... | D-4 04 ... | C-4 03 C20 | ... .. 101
07  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
08  | C-4 01 ... | C-4 04 ... | C-4 03 C38 | ... .. 101
09  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
0A  | ... .. ... | ... .. ... | C-4 03 C20 | ... .. 101
0B  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
0C  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
0D  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
0E  | ... .. ... | C-4 04 ... | C-4 03 C20 | ... .. 101
0F  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
10  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
11  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
12  | ... .. ... | E-4 04 ... | C-4 03 C20 | ... .. 101
13  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
14  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
15  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
16  | ... .. ... | D-4 04 ... | C-4 03 C20 | ... .. 101
17  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
18  | C-4 01 ... | D#4 04 ... | C-4 03 C38 | ... .. 101
19  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
1A  | ... .. ... | ... .. ... | C-4 03 C20 | ... .. 101
1B  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
1C  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
1D  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
1E  | ... .. ... | C-4 04 ... | C-4 03 C20 | ... .. 101
1F  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
20  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
21  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
22  | ... .. ... | E-4 04 ... | C-4 03 C20 | ... .. 101
23  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
24  | C-4 01 ... | E-4 04 ... | C-4 03 C38 | ... .. 101
25  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
26  | ... .. ... | D-4 04 ... | C-4 03 C20 | ... .. 101
27  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
28  | C-4 01 ... | C-4 04 ... | C-4 03 C38 | ... .. 101
29  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
2A  | ... .. ... | ... .. ... | C-4 03 C20 | ... .. 101
2B  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
2C  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
2D  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
2E  | ... .. ... | C-4 04 ... | C-4 03 C20 | ... .. 101
2F  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
30  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
31  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
32  | ... .. ... | E-4 04 ... | C-4 03 C20 | ... .. 101
33  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
34  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
35  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
36  | ... .. ... | D-4 04 ... | C-4 03 C20 | ... .. 101
37  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
38  | C-4 01 ... | C#4 04 ... | C-4 03 C38 | ... .. 101
39  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
3A  | ... .. ... | ... .. ... | C-4 03 C20 | ... .. 101
3B  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
3C  | C-4 01 ... | ... .. ... | C-4 03 C38 | ... .. 101
3D  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
3E  | ... .. ... | C-4 04 ... | C-4 03 C20 | ... .. 101
3F  | ... .. ... | ... .. ... | ... .. ... | ... .. 101
```
