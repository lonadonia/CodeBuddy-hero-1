# CodeBuddy — Homepage Hero Redesign

**Concept: “The Wall Becomes the Canvas”**

A single self-contained `index.html` (GSAP via CDN, zero images, all real HTML/CSS)
that plays one continuous cinematic sequence:

1. **The Barriers** — a wall of monospace brick-words (COST · TIME · CODE ·
   COMPLEXITY · 18 MONTHS · $180K/YEAR…) hums with red-orange glitch ticks.
2. **The Break** — the **CodeBuddy link icon draws itself**, rides the green
   laser level as its head and shatters the wall; the headline **“Breaking
   Down Barriers to Software Development”** lands its first word on the exact
   shatter frame, and a green line strikes through *Barriers*.
3. **The Brand Beat** — the 40 surviving fragments first **assemble the
   CodeBuddy link mark** in glowing brand green and pulse, while the icon
   that broke the wall **flies into the nav**, lands on the logo slot, and
   the `codebuddy` wordmark writes on with a sheen sweep.
4. **The CodeBuddy Dashboard** — the same blocks then disperse and build one
   **branded product shell**: a sidebar carrying the brand mark and module
   icons, a topbar with the real logo, workspace breadcrumb, search and
   avatar. The content morphs FLIP-style through its four modules —
   **Bookings → Invoices → Dispatch → Pipeline** — while the sidebar’s active
   pill glides and the breadcrumb re-types, so every switch reads as real
   product navigation. A green “You” cursor drags one element per module.
5. **Loop & Breathe** — the intro plays once; the module cycle loops forever.

## Preview

Open `index.html` in any modern browser — no build step, no server needed.

- `index.html?shot=<seconds>` freezes the sequence at any moment
  (e.g. `?shot=2.95` is the shatter frame) — useful for storyboard stills.
- Honors `prefers-reduced-motion`: the wall renders already broken and the
  four apps gently crossfade.
- Responsive intent designed at 1440×800; adapts at 1280 / ≤991 / ≤479.

## Notes

- Only library: GSAP 3 (CDN). Everything else is hand-built DOM/CSS.
- Nav logo is **`Primary Logo.png` exactly as provided** (base64-embedded,
  never redrawn or restyled — reveal/sheen effects are clips and masks over
  the untouched image).
- Every app scene is narrated: a value caption (`// invoices — get paid
  faster`), scene progress dots, and a quiet `✓ synced` toast reinforce
  what customers can build and how reliably it ships.
- Full act/timing map and tweakables are documented in the README comment
  block at the top of `index.html`.
