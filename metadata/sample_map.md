Thanks — that's real, useful data. I can confirm the eight sample picks now without needing lengths. I measured each sample's envelope (RMS across five equal segments) rather than guessing.

For a suspenseful, thumping, Norrish/Brimble-style loader loop, I'd go with:

| Slot | Sample | Role | Recorded peak | Volume (0–64) | Why | Envelope behavior | Loop? |
|---|---|---|---|---|---|---|---|
| 1 | ST-01/BassDrum4 | Thump — the driving kick | 128 (full) | **64** | Anchor of the track — full weight | Decay cleanly to near-silence by the end (e.g. BassDrum4 goes 94→6, CloseHiHat 12→0.2) | **No loop** — natural one-shots |
| 2 | ST-01/Snare3 | Backbeat snare | 128 (full) | **58** | Strong backbeat, just under the kick | Decay cleanly to near-silence by the end (e.g. BassDrum4 goes 94→6, CloseHiHat 12→0.2) | **No loop** — natural one-shots |
| 3 | ST-01/CloseHiHat | Rhythmic hi-hat pulse | 34 (quiet recording) | **44** | Naturally recorded far quieter than the others — needs a boost just to register as a texture, but stays a background element | Decay cleanly to near-silence by the end (e.g. BassDrum4 goes 94→6, CloseHiHat 12→0.2) | **No loop** — natural one-shots |
| 4 | ST-01/DeepBass | Sub-bass throb / bassline | 127 (full) | **56** | Present but sits under the kick | Decay cleanly to near-silence by the end (e.g. BassDrum4 goes 94→6, CloseHiHat 12→0.2) | **No loop** — natural one-shots |
| 5 | ST-01/NightMare | Dark atmospheric pad — suspense layer | 127, sustains rather than decaying | **40** | Meant to sit underneath as atmosphere, not compete | Doesn't decay — stays in a 33–46 RMS band the whole way through | **Yes, forward loop** — it's a pad, and letting it ring past its natural end (instead of retriggering) is what will make the atmosphere feel continuous rather than choppy |
| 6 | ST-01/Mechanic2 | Industrial/mechanical stab — tension accent | 128, has its own internal swell | **50** | Accent-level, lets its shape read without dominating | Has its own internal swell (35→47→**80**→60→36) then settles, doesn't fully decay | **Optional** — no loop needed for a stab; only loop it if we later want it as a sustained mechanical drone |
| 7 | ST-02/Perc-Timpani | Low dramatic percussion hit | 127 (full) | **56** | Dramatic but not overpowering | Decay cleanly to near-silence by the end (e.g. BassDrum4 goes 94→6, CloseHiHat 12→0.2) | **No loop** — natural one-shots |
| 8 | ST-02/Siren | Tension riser / alarm sweep | 125 (full) | **46** | Tension accent, not a lead | Decays to near-zero (48→4.7) on its own | **Yes, forward loop** — not because of its natural envelope, but because its *function* is a held tension riser across several bars; without a loop it'll just thud out |

That gives kick/snare/hat for the thumping groove, DeepBass for the pulse, and NightMare/Mechanic2/Timpani/Siren for the suspenseful, moody texture layer typical of that sound.
