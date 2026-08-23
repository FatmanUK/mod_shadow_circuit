# Pattern06 — "Breakdown"

The held breath. Kick, hi-hat, and DeepBass drop out completely; only the atmosphere remains. Sweep holds a quiet sustained drone (Ch2), and NightMare (Ch4) is fully exposed, opening slightly above its usual register and then slowly sinking for almost the entire pattern — dread deepening rather than resolving.

New effect: **`2xx` — Portamento Down**. The mirror of `1xx` — continuously *lowers* pitch (raises the period) by `x` per tick, no destination note. Used here as the exact inverse of the Siren's rise in Pattern04: where that one climbed, this one sinks.

New effect: **`4xy` — Vibrato**. Oscillates the pitch back and forth around the current note at speed `x`, depth `y`, cycling continuously while active — exactly what a static pad needs to feel alive instead of static.Landing at period 512 — close to A-3, roughly a fourth below where Pattern02 left it. Comfortable, not a dive.

New effect for Sweep: **`7xy` — Tremolo**. Same mechanism as vibrato but modulates *volume* instead of pitch — a slow "breathing" swell rather than a pitch wobble. NightMare keeps a much gentler vibrato; Sweep switches to tremolo. That gives them distinct characters instead of both buzzing the same way.

```
Row | Ch1        | Ch2        | Ch3        | Ch4
------------------------------------------------------
00  | ... .. ... | ... .. ... | ... .. ... | ... .. 201
01  | ... .. ... | ... .. ... | ... .. ... | ... .. 200
02  | ... .. ... | ... .. ... | ... .. ... | ... .. 200
03  | ... .. ... | C-4 09 ... | ... .. ... | ... .. 200
04  | ... .. ... | ... .. 712 | ... .. ... | ... .. 200
05  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
06  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
07  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
08  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
09  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
0A  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
0B  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
0C  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
0D  | ... .. ... | ... .. 700 | ... .. ... | ... .. 200
0E  | ... .. ... | ... .. 700 | ... .. ... | ... .. 412
0F  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
10  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
11  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
12  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
13  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
14  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
15  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
16  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
17  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
18  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
19  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1A  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1B  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1C  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1D  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1E  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
1F  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
20  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
21  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
22  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
23  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
24  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
25  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
26  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
27  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
28  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
29  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2A  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2B  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2C  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2D  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2E  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
2F  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
30  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
31  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
32  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
33  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
34  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
35  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
36  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
37  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
38  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
39  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3A  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3B  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3C  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3D  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3E  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
3F  | ... .. ... | ... .. 700 | ... .. ... | ... .. 400
```

**Audition criteria:**
1. Does the sudden absence of kick/hi-hat/bass feel like a genuine held-breath moment, not a mistake or dropout?
2. Does NightMare's descent read as continuous and unbroken — audibly still moving even near the end, not stuck or clamped?
3. Does Sweep's drone sit low enough in the mix to support without competing with NightMare for attention?
4. Overall: does this feel like the calm-before-the-rebuild moment the order list needs here (it sits before Return Pulse and Loop Bridge), rather than just an empty gap?

Let me know how it plays before Pattern07 ("Return Pulse").
