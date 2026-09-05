---
name: seeded-design
description: Design a landing page or web prototype whose visual direction — color, layout, typography — is derived from a random seed generated at run time. Use when the user wants a page built but leaves the creative direction to you, asks to be surprised or for a random/fresh look, or wants a different result each attempt.
---

# Seeded design

Build a landing page whose whole creative direction grows from a random **seed** — a long alphanumeric string generated fresh each run. The seed is private inspiration: it shapes every visual choice and never appears in the output.

## Why a seed

Told to invent "a random look," a model reaches for the same safe defaults every time. A seed from real entropy breaks that: each run starts from a different pattern, so the directions genuinely diverge instead of converging on the same blue-gradient hero.

## Steps

1. **Generate the seed.** Run a shell script for real randomness — don't invent the string yourself:
   ```sh
   LC_ALL=C tr -dc 'A-Za-z0-9' < /dev/urandom | head -c 64; echo
   ```
   Done when you have the string in hand.

2. **Read the seed for a direction.** Look past the surface. Scan for digit runs and "special" numbers (dates, primes, round or repeated figures), hex-like segments that could seed a color, repeated substrings or characters, clusters that read like initials or words, the balance of letters to digits, and where things sit in the string. Turn what you notice into concrete decisions: a full palette (not a single color), a layout structure, a type pairing with a scale, and at least one distinctive detail (motion, texture, shape, or an unusual grid). Done when every one of those is decided and each traces back to something you saw in the seed — a vague vibe is not done.

3. **Build it well.** Bring the direction to life as a self-contained landing page, held to real craft: deliberate spacing and hierarchy, readable type, coherent color, responsive across widths, accessible contrast. Use your judgment to make it genuinely good, not just on-brief.

4. **Keep the seed private.** The output shows only the design the seed inspired. The string stays behind the scenes — never printed in the page, its comments, or your reply.
