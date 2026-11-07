# "One Beat" — 60s Health Film · Storyboard v1 (awaiting approval)

**Format:** 1920×1080 (16:9) · 60 fps · 3600 frames · 120 BPM
**Grid:** 1 beat = 30 f (0.5 s) · 1 bar = 120 f (2 s) · 30 bars total
**Notation:** `B9.3` = bar 9, beat 3 · bar *n* starts at frame `(n−1)×120`
**Palette:** BG #F8F9FA · Teal #00A896 (primary) · Slate #2B2D42 (type/structure) · Coral #FF6B6B (highlight/warning, used sparingly)
**Type:** Inter only — Label 600 / 22px / +12% tracking · Headline 700 / 72px · Body 500 / 34px · line-height ≥ 1.6
**Motion:** entrances `cubic-bezier(.16,1,.3,1)` 20 f · exits `cubic-bezier(.7,0,.84,0)` 8 f, timed to *end* on the next downbeat · springs stiffness 100 / damping 16
**Camera:** one `<Camera>` container wraps the whole film; it moves only during holds (scale 1.00→1.04, linear-ish ease) and snaps back on a section downbeat.

**Visual motif:** the heartbeat. A single teal dot → an ECG line → a heart → a 4-part ring (four habits) → back to the ECG line that carries the tagline. Every scene is born from the previous shape; no cuts, only transformations.

---

## ACT I — THE PULSE · Bars 1–4 · 0:00–0:08 (f0–479)

| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B1.1 | 0:00.0 | 0 | Clean white. A 24px teal dot springs in at centre. | Soft tick + low heartbeat "lub" |
| B1.3, B2.1, B2.3 | 0:01.0 / 0:02.0 / 0:03.0 | 60 / 120 / 180 | Dot pulses (spring 1.0→1.3→1.0); a faint teal ring ripples out and fades each time. | Heartbeat lub-dub, pad fades in |
| B3.1 | 0:04.0 | 240 | Dot stretches horizontally into a 3px slate baseline spanning 80% width. | Tick |
| B3.3 | 0:05.0 | 300 | Copy rises in above the line: **"Every beat tells a story."** | Tick |
| B4.1 | 0:06.0 | 360 | Baseline fires one ECG complex (P-QRS-T); the R-peak draws in **coral**. | **Warm chime** |
| B4.4 (exit) | 0:07.87 | 472 | Copy exits (8 f). Line holds. | — |

## ACT II — THE HEART · Bars 5–8 · 0:08–0:16 (f480–959)

| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B5.1 | 0:08.0 | 480 | The ECG peak folds up into a flat geometric **teal heart** (two circles + rotated rounded square). Line retracts into it. | **Warm chime** + kick enters |
| every B.1 / B.3 | — | — | Heart beats lub-dub (spring scale 1.00→1.08). | Heartbeat locked to the visual |
| B6.1 | 0:10.0 | 600 | Large counter appears under heart: **0** → rolls to **100,000** by B7.4 (eased, digits tabular). | Soft ticks on each beat while counting |
| B6.3 | 0:11.0 | 660 | Sub-line: **"beats every day, without being asked."** | Tick |
| B7.1–B7.4 | 0:12–0:14 | 720–839 | **Hold** — camera breathes 1.00→1.04. | — |
| B8.1 | 0:14.0 | 840 | Counter swaps (exit 8 f before) for headline **"Let's keep it strong."** | Tick |
| B8.4 (exit) | 0:15.87 | 952 | Copy exits; heart shrinks back toward centre. | — |

## ACT III — FOUR HABITS · Bars 9–20 · 0:16–0:40 (f960–2399)

Shared layout (centered): a thin slate ring (360px) split into 4 quadrants sits top-centre; the habit icon lives inside the ring. Text stack below: label (teal), headline (slate), stat (slate 70%). Each habit fills **its quadrant in teal** — the ring is the film's progress bar.

### Habit 1 — MOVE · Bars 9–11 · 0:16–0:22
| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B9.1 | 0:16.0 | 960 | Quadrant 1 sweeps teal. Icon: flat figure in stride (circle head + capsule limbs); legs swing on each beat. | **Warm chime** · marimba arp enters |
| B9.3 | 0:17.0 | 1020 | Label **"01 · Move"** | Tick |
| B10.1 | 0:18.0 | 1080 | Headline **"Move a little, every day."** | Tick |
| B10.3 | 0:19.0 | 1140 | Stat **"Aim for 150 minutes of activity a week."** A slim teal bar fills 0→150 by B11.2. | Tick |
| B11.4 (exit) | 0:21.87 | 1312 | Text exits, icon morphs → plate. | — |

### Habit 2 — NOURISH · Bars 12–14 · 0:22–0:28
| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B12.1 | 0:22.0 | 1320 | Quadrant 2 sweeps teal. Icon: flat plate (circle) — empty outline. | **Warm chime** |
| B12.3 | 0:23.0 | 1380 | Label **"02 · Nourish"** | Tick |
| B13.1 | 0:24.0 | 1440 | Headline **"Eat for energy."** Plate's left half pops in teal. | Tick |
| B13.3 / B13.4 | 0:25.0 / 0:25.5 | 1500 / 1530 | Stat **"Fill half your plate with vegetables and fruit."** Remaining quarters pop in slate, then coral. | Tick, tick |
| B14.4 (exit) | 0:27.87 | 1672 | Exit; plate morphs → crescent. | — |

### Habit 3 — REST · Bars 15–17 · 0:28–0:34 (the "breath")
| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B15.1 | 0:28.0 | 1680 | Quadrant 3 sweeps teal. Icon: flat crescent moon; three small dots twinkle one per bar. Icon pulse slows to half-time. | **Warm chime** · drums drop out, pad only |
| B15.3 | 0:29.0 | 1740 | Label **"03 · Rest"** | Tick (quieter) |
| B16.1 | 0:30.0 | 1800 | Headline **"Recovery is part of the work."** | Tick |
| B16.3 | 0:31.0 | 1860 | Stat **"Most adults need 7–9 hours of sleep."** | Tick |
| B16.3–B17.4 | 0:31–0:34 | 1860–2039 | **Hold** — camera breathes 1.00→1.04. | Pad swell |
| B17.4 (exit) | 0:33.87 | 2032 | Exit; moon morphs → gauge. | — |

### Habit 4 — CHECK IN · Bars 18–20 · 0:34–0:40
| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B18.1 | 0:34.0 | 2040 | Quadrant 4 sweeps teal → **ring complete**. Icon: flat half-circle gauge (teal zone, narrow coral zone at the right edge); needle springs into teal. | **Warm chime** · drums return |
| B18.3 | 0:35.0 | 2100 | Label **"04 · Check in"** | Tick |
| B19.1 | 0:36.0 | 2160 | Headline **"Know your numbers."** | Tick |
| B19.3 / B19.4 / B20.1 | 0:37.0 / 0:37.5 / 0:38.0 | 2220 / 2250 / 2280 | Three pill chips pop in, one per hit: **"Blood pressure" · "Cholesterol" · "Blood sugar"** | Tick ×3 |
| B20.2 | 0:38.5 | 2310 | Needle flicks into **coral**; coral line: **"Notice a change? Talk to your doctor."** Needle settles back to teal on B20.3. | Single low coral "alert" tone (soft, not alarming) |
| B20.4 (exit) | 0:39.87 | 2392 | All text exits. | — |

## ACT IV — RHYTHM · Bars 21–24 · 0:40–0:48 (f2400–2879)

| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B21.1 | 0:40.0 | 2400 | Ring scales up to centre; the four icons (small) settle at 12/3/6/9 o'clock around it. Full teal ring glows once. | **Big warm chime** (full mix) |
| B21.3 | 0:41.0 | 2460 | The heart reappears at the ring's centre, beating; icons orbit slowly (one quarter-turn per 2 bars). | Heartbeat |
| B22.1 | 0:42.0 | 2520 | Copy line 1: **"Small habits."** | Tick |
| B22.3 | 0:43.0 | 2580 | Copy line 2: **"Steady rhythm."** | Tick |
| B23.1 | 0:44.0 | 2640 | Copy line 3: **"Stronger you."** ("you" in teal) | Chime (small) |
| B23.1–B24.3 | 0:44–0:47.5 | 2640–2849 | **Hold** — camera breathes. | — |
| B24.4 (exit) | 0:47.87 | 2872 | Copy exits; icons collapse into heart; heart flattens into the baseline. | Riser (filtered noise, 8 f) |

## ACT V — THE TAGLINE · Bars 25–29 · 0:48–0:58 (f2880–3479)

| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B25.1 | 0:48.0 | 2880 | Baseline draws across the full width; at centre the R-peak fires in **coral**. | **Biggest warm chime** (tonic) |
| B25.3 | 0:49.0 | 2940 | Line 1 rises in above the ECG: **"Empowering Your Health,"** | Tick |
| B26.1 | 0:50.0 | 3000 | Line 2 below, first half: **"One Beat"** ("Beat" in teal) | Heartbeat |
| B26.3 | 0:51.0 | 3060 | Line 2 completes: **"at a Time"** | Tick |
| B27.1–B29.3 | 0:52–0:57.5 | 3120–3449 | **Hold** — camera breathes 1.00→1.04 over 6 s. A soft coral ECG blip on each downbeat. | Pad + heartbeat, music thinning |
| B29.4 (exit) | 0:57.87 | 3472 | Tagline + line exit (8 f). | — |

## OUTRO · Bar 30 · 0:58–1:00 (f3480–3599)

| Hit | Time | Frame | Visual | Sound |
|---|---|---|---|---|
| B30.1 | 0:58.0 | 3480 | Single teal dot at centre — the film's first frame, returned. One final beat. | Final lub-dub + chime on tonic |
| B30.3–end | 0:59–1:00 | 3540–3599 | Dot holds on clean white. | Reverb tail decays to silence by f3599 |

---

## Music & sound plan (all synthesized in code, no samples)
- **Score:** 120 BPM, D major. 2-bar chord cycle: Dmaj9 → Bm11 → Gmaj7 → A6sus4. Warm detuned sine/triangle pad (low-passed), heartbeat kick (sine 60→40 Hz pitch drop: "lub" on the beat, "dub" softer a 16th later), marimba-like pluck arpeggio in Acts III–IV.
- **Dynamics:** Act I sparse (pad + pulse) → Act II kick enters → Act III marimba; *Rest* drops to pad only → *Check in* drums return → Act IV full mix → Act V thins to pad + heartbeat → silence.
- **Ticks:** 2.4 kHz sine, 12 ms decay, −24 dBFS, on every UI element (labels, chips, counter steps).
- **Warm chimes:** FM bell (D/F♯/A partials) on every section downbeat: B4.1, B5.1, B9.1, B12.1, B15.1, B18.1, B21.1, B25.1, B30.1.
- **Sync rule:** every sound attack is placed at the exact frame of its visual hit (sample offset = frame / 60 × 48000).

## Build plan (after both approvals)
- Remotion 4 + React + TypeScript; all visuals are SVG primitives (circles, paths, rects).
- Audio rendered by a deterministic Node synth script → `public/score.wav`, muxed by Remotion.
- Inter loaded via `FontFace` + `delayRender`; `cancelRender` (fail the render) if any weight fails to load.
- `dir="ltr" lang="en"` on every text block.
- Pre-render lint: ESLint + `tsc --noEmit` + a copy-lint script (spelling, punctuation, copy matches the approved list, line-height ≥ 1.6).

---

## On-screen copy (complete list for approval)

| # | Bar | Copy | Style |
|---|---|---|---|
| 1 | B3.3 | Every beat tells a story. | Headline |
| 2 | B6.1 | 100,000 | Counter (numeric) |
| 3 | B6.3 | beats every day, without being asked. | Body |
| 4 | B8.1 | Let's keep it strong. | Headline |
| 5 | B9.3 | 01 · Move | Label |
| 6 | B10.1 | Move a little, every day. | Headline |
| 7 | B10.3 | Aim for 150 minutes of activity a week. | Body |
| 8 | B12.3 | 02 · Nourish | Label |
| 9 | B13.1 | Eat for energy. | Headline |
| 10 | B13.3 | Fill half your plate with vegetables and fruit. | Body |
| 11 | B15.3 | 03 · Rest | Label |
| 12 | B16.1 | Recovery is part of the work. | Headline |
| 13 | B16.3 | Most adults need 7–9 hours of sleep. | Body |
| 14 | B18.3 | 04 · Check in | Label |
| 15 | B19.1 | Know your numbers. | Headline |
| 16 | B19.3 | Blood pressure | Chip |
| 17 | B19.4 | Cholesterol | Chip |
| 18 | B20.1 | Blood sugar | Chip |
| 19 | B20.2 | Notice a change? Talk to your doctor. | Body (coral) |
| 20 | B22.1 | Small habits. | Headline |
| 21 | B22.3 | Steady rhythm. | Headline |
| 22 | B23.1 | Stronger you. | Headline |
| 23 | B25.3 | Empowering Your Health, | Tagline line 1 |
| 24 | B26.1–26.3 | One Beat at a Time | Tagline line 2 |

Fact basis: ~100,000 beats/day ≈ 70 bpm × 1,440 min; 150 min/week moderate activity (WHO, NHS); half plate vegetables & fruit (NHS Eatwell Guide); 7–9 h sleep for adults (NHS, US National Sleep Foundation).
