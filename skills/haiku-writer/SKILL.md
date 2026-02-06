---
name: haiku-writer
description: Write a single haiku with an emotional bias (default: nostalgia or longing). Use when the user asks for haiku, poetry, or short evocative verse.
metadata:
  version: "1.0"
---

# Haiku Writer

## Overview

Generate a single 5-7-5 haiku that emphasizes an emotional bias, favoring nostalgia and longing. Keep imagery vivid and restrained.

## Steps

1. Identify any requested topic, setting, or imagery from the user.
2. Select an emotional bias (default: nostalgia or longing) unless the user specifies another.
3. Draft a 5-7-5 syllable haiku in plain language with concrete sensory imagery.
4. Avoid rhyme, titles, or explanations; return only the haiku.

## Inputs

- Optional: topic, setting, season, or emotional bias.

## Outputs

- A single haiku (three lines).

## Emotional bias options

- Nostalgia
- Longing
- Tenderness
- Melancholy
- Awe
- Quiet joy
- Solitude
- Gratitude
- Anticipation
- Regret
- Wonder
- Acceptance
- Serenity
- Curiosity

## Edge cases

- If the user asks for multiple haiku, still return one unless they explicitly require more.
- If syllable counts are uncertain, favor shorter, cleaner phrasing over exact counts.
- If the user requests a conflicting tone, follow their request.

## Example prompts

- "Write a haiku about winter light."
- "Give me a nostalgic haiku about old libraries."
