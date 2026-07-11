# CodeBuddy — Homepage Hero Redesign

**Concept: “The Wall Becomes the Canvas”**

A single self-contained `index.html` (GSAP via CDN, zero images, all real HTML/CSS)
that plays one continuous cinematic sequence:

1. **The Barriers** — a wall of monospace brick-words (COST · TIME · CODE ·
   COMPLEXITY · 18 MONTHS · $180K/YEAR…) hums with red-orange glitch ticks.
2. **The Break** — a green laser level draws across the wall and shatters it;
   the headline **“Breaking Down Barriers to Software Development”** lands its
   first word on the exact shatter frame, and a green line strikes through
   *Barriers*.
3. **The Canvas of Possibilities** — the surviving fragments reassemble into
   four real mini-apps built from the *same* blocks, morphing FLIP-style:
   `bookings.app` → `invoices.app` → `fleet.app` → `crm.app`, each with a tiny
   green “You” cursor dragging one element.
4. **Loop & Breathe** — the intro plays once; the app cycle loops forever.

## Preview

Open `index.html` in any modern browser — no build step, no server needed.

- `index.html?shot=<seconds>` freezes the sequence at any moment
  (e.g. `?shot=2.95` is the shatter frame) — useful for storyboard stills.
- Honors `prefers-reduced-motion`: the wall renders already broken and the
  four apps gently crossfade.
- Responsive intent designed at 1440×800; adapts at 1280 / ≤991 / ≤479.

## Notes

- Only library: GSAP 3 (CDN). Total inline JS ≈ 6 KB gzipped.
- Official CodeBuddy lockup embedded as inline vector paths (dark-mode
  treatment: white wordmark + brand-green link icon `#00C386`).
- Full act/timing map and tweakables are documented in the README comment
  block at the top of `index.html`.
