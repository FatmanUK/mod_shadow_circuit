# Pattern03 — "Diagnostic Chime"

This is the pause. Kick pulls back to just marking each bar, hi-hat and snare drop out entirely, and DeepBass gives one low sustained note that's simply allowed to decay away rather than being retriggered. All the activity moves to **Mechanic2**, playing a syncopated "scanning" motif.

New effect introduced: **`0xy` — Arpeggio**. Within a single row, the engine rapidly cycles the note between its own pitch, pitch+`x` semitones, and pitch+`y` semitones (one per tick, repeating) — a classic trick for a fast, buzzy, chord-like "warble" out of a single sample, which is exactly the electronic-chime texture we want here. Using `037` (root, +3 semitones, +7 semitones — a minor triad shape) on every Mechanic2 hit.

```
Row | Ch1        | Ch2        | Ch3        | Ch4
------------------------------------------------------
00  | C-4 01 ... | ... .. ... | ... .. ... | C-4 06 037
01  | ... .. ... | C-4 09 ... | ... .. ... | ... .. ...
06  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
0A  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
10  | C-4 01 ... | ... .. ... | ... .. ... | C-4 06 037
16  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
1A  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
20  | C-4 01 ... | ... .. ... | ... .. ... | C-4 06 037
26  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
2A  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
30  | C-4 01 ... | ... .. ... | ... .. ... | C-4 06 037
36  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
3A  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
3E  | ... .. ... | ... .. ... | ... .. ... | C-4 06 037
```

Every row not listed has no events in any channel. The Mechanic2 motif is deliberately syncopated (hit-hit-gap-hit rather than evenly spaced) within each bar — a "scan, scan, ping" rhythm — with one extra hit at the very end (`3E`) to build a little anticipation before Pattern01 returns in the order list.

Sweep replaces DeepBass in Ch2: triggered once (offset from the kick/chime attack, same reasoning as before) and, since it actually loops, left to sustain across the whole pattern rather than needing to be retriggered every bar. One trigger, one loop, sustained the whole 4 bars — much simpler than the retrigger workaround, and it should actually hold as a drone this time. Let me know how it plays.

**Audition criteria:**
1. Does the contrast with Pattern02 feel immediate and stark — genuinely "pulled back," not just quieter?
2. Does the arpeggio (`037`) on Mechanic2 read as a chiming/warbling texture rather than a wrong note or glitch?
3. Does the syncopated hit-hit-gap-hit rhythm feel like a "system check" pattern rather than random noise?
4. Does the lone decaying DeepBass note register as a grounding drone underneath, without drawing attention to itself?
5. Does the extra hit at the end create a sense of "something's about to happen" heading into Pattern01?

Let me know how it plays before Pattern04 ("Rising Tension").
