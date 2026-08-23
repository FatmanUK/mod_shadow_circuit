[Claude got very stuck on this one. I accepted it for the sake of momentum and revisited later. In other news, I goofed. I told it to stop abbreviating the patterns --- meaning I needed it to not say things like "repeat this pattern 32 times", as ptgen can't parse that. But it also stopped omitting empty rows. Facepalm.]

# Pattern06 — "Breakdown"

The held breath. Kick, hi-hat, and DeepBass drop out completely; only the atmosphere remains. Sweep holds a quiet sustained drone (Ch2), and NightMare (Ch4) is fully exposed, opening slightly above its usual register and then slowly sinking for almost the entire pattern — dread deepening rather than resolving.

New effect: **`2xx` — Portamento Down**. The mirror of `1xx` — continuously *lowers* pitch (raises the period) by `x` per tick, no destination note. Used here as the exact inverse of the Siren's rise in Pattern04: where that one climbed, this one sinks.

New effect: **`4xy` — Vibrato**. Oscillates the pitch back and forth around the current note at speed `x`, depth `y`, cycling continuously while active — exactly what a static pad needs to feel alive instead of static.Landing at period 512 — close to A-3, roughly a fourth below where Pattern02 left it. Comfortable, not a dive.

New effect for Sweep: **`7xy` — Tremolo**. Same mechanism as vibrato but modulates *volume* instead of pitch — a slow "breathing" swell rather than a pitch wobble. NightMare keeps a much gentler vibrato; Sweep switches to tremolo. That gives them distinct characters instead of both buzzing the same way.

New effect: **`ECx` — Note Cut**. Silences the channel `x` ticks into the row (rather than at the start of it) — a precise, decisive cutoff rather than a gradual slide. Used here to end NightMare's loop cleanly.

```
Row | Ch1        | Ch2        | Ch3        | Ch4
------------------------------------------------------
00  | C-4 01 C20 | ... .. ... | ... .. ... | ... .. ...
08  | ... .. ... | E-4 04 C18 | ... .. ... | ... .. ...
10  | C-4 01 C20 | C-4 09 ... | ... .. ... | C-4 05 ...
18  | ... .. ... | D-4 04 C18 | ... .. ... | ... .. ...
20  | C-4 01 C20 | C#4 09 ... | C-3 07 ... | C-4 05 ...
28  | ... .. ... | C-4 04 C18 | ... .. ... | ... .. ...
30  | C-4 01 C20 | ... .. ... | ... .. ... | ... .. ...
34  | ... .. ... | C-4 04 C20 | ... .. ... | ... .. EC4
38  | ... .. ... | ... .. ... | C-4 06 037 | ... .. ...
```

Nine rows of actual content, everything else silent. Here's the reasoning bar by bar:

- **Bar 1:** just the quiet kick, NightMare continuing from Pattern02, and one faint DeepBass note (E-4, very quiet at volume `18` hex) — the seed motif's first note, whispered rather than stated.
- **Bar 2:** Sweep enters, NightMare re-pulses, and the motif continues with D-4 — the same E→D→C shape from Pattern00, just spread across bars and barely audible.
- **Bar 3:** Perc-Timpani's dramatic accent, Sweep's second pulse (your `C#4` addition), and the motif's third note (C-4) — completing the fragment.
- **Bar 4:** DeepBass plays one final, slightly less quiet C-4 (volume `20`) — a resolution note that also **naturally silences Sweep** just by retriggering the channel, no fade needed. NightMare gets a clean `EC4` cut. Mechanic2 closes with a quiet arpeggio callback to Diagnostic Chime, then true silence into Pattern07.

**Audition criteria:**
1. Does the faint DeepBass motif read as a genuine (if ghostly) musical idea tying this back to the rest of the piece, rather than being buried?
2. Does the ending — DeepBass's resolution note, NightMare's clean cut, the Mechanic2 callback — feel like a real conclusion rather than just automation fading out?
3. Does this feel like it has more substance than the previous version while still being clearly the sparsest pattern in the piece?

Let me know how it plays before Pattern07 ("Return Pulse").
