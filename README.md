# Starfall — Neon Survival

A tiny, self-contained arcade game for start.ng. Steer your character through a meteor shower, scoop up mint sparks, and try to beat your best run.

## Play

- **Steer:** Left/Right arrows or A/D. Touch buttons appear on small screens.
- **Objective:** Avoid falling rocks and collect sparks.
- **Best runs:** Stored locally for guests and submitted to the shared start.ng leaderboard for signed-in players.

## Publish

This repository is a static site. `index.html` is ready to serve from the repository root; there is no build step or dependency install. The game uses start.ng's `/connect` frame for player identity, character appearance, score saving, and leaderboard reads.
