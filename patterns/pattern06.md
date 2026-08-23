[Claude got very stuck on this one. I accepted it for the sake of momentum and revisited later.]

# Pattern06 — "Breakdown"

The held breath. Kick, hi-hat, and DeepBass drop out completely; only the atmosphere remains. Sweep holds a quiet sustained drone (Ch2), and NightMare (Ch4) is fully exposed, opening slightly above its usual register and then slowly sinking for almost the entire pattern — dread deepening rather than resolving.

New effect: **`2xx` — Portamento Down**. The mirror of `1xx` — continuously *lowers* pitch (raises the period) by `x` per tick, no destination note. Used here as the exact inverse of the Siren's rise in Pattern04: where that one climbed, this one sinks.

New effect: **`4xy` — Vibrato**. Oscillates the pitch back and forth around the current note at speed `x`, depth `y`, cycling continuously while active — exactly what a static pad needs to feel alive instead of static.Landing at period 512 — close to A-3, roughly a fourth below where Pattern02 left it. Comfortable, not a dive.

New effect for Sweep: **`7xy` — Tremolo**. Same mechanism as vibrato but modulates *volume* instead of pitch — a slow "breathing" swell rather than a pitch wobble. NightMare keeps a much gentler vibrato; Sweep switches to tremolo. That gives them distinct characters instead of both buzzing the same way.

```
Row | Ch1        | Ch2        | Ch3        | Ch4
------------------------------------------------------
00  | C-4 01 C20 | ... .. ... | ... .. ... | ... .. ...
10  | C-4 01 C20 | C-4 09 ... | ... .. ... | C-4 05 ...
20  | C-4 01 C20 | C#4 09 ... | C-3 07 ... | C-4 05 ...
30  | C-4 01 C20 | C-4 09 ... | ... .. ... | C-4 05 ...
```

**Audition criteria:**
1. Does the sudden absence of kick/hi-hat/bass feel like a genuine held-breath moment, not a mistake or dropout?
2. Does NightMare's descent read as continuous and unbroken — audibly still moving even near the end, not stuck or clamped?
3. Does Sweep's drone sit low enough in the mix to support without competing with NightMare for attention?
4. Overall: does this feel like the calm-before-the-rebuild moment the order list needs here (it sits before Return Pulse and Loop Bridge), rather than just an empty gap?

Let me know how it plays before Pattern07 ("Return Pulse").
