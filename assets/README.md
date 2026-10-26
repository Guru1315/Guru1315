# Assets

The images used by the profile [README](../README.md). They are all hand-built animated pixel-art SVG files (8-bit game theme), loaded through their `raw.githubusercontent.com` addresses, so **renaming or moving a file breaks the matching image on the profile**.

| File | Used for |
|---|---|
| `px-hero.svg` | Title screen: night city, moon, coins, walking robot, blinking "PRESS START" |
| `px-divider.svg` | Pac-Man eating dots between sections |
| `px-stage-status.svg`, `px-stage-inventory.svg`, `px-stage-quests.svg`, `px-stage-classes.svg`, `px-stage-map.svg`, `px-stage-scores.svg`, `px-stage-contact.svg` | Stage headers |
| `px-status.svg` | Player status screen with loading bars (MLOps, LLM apps) and motto |
| `px-inventory.svg` | Tools grid with a moving selection cursor |
| `px-quest-1.svg` to `px-quest-7.svg` | Project quests, in order: AI Voice Customer Support, AI Health Agent, AI Fraud Investigation, AI Personal Agent, Saveetha Foodie Bot, Image Caption Generator, Resume Screening System |
| `px-quest-8.svg` | Bonus stage linking to the repositories tab |
| `px-classes.svg` | Four class cards: NLP, Vision, Voice AI, Fraud |
| `px-btn-linkedin.svg`, `px-btn-email.svg`, `px-btn-github.svg` | Contact buttons (links are set in the README) |
| `px-footer.svg` | Closing scene with a walking robot and falling coin |

## Related folders

- `../profile-3d-contrib/` holds the 3D contribution graphs, generated daily by the *GitHub-Profile-3D-Contrib* workflow. Do not edit them by hand. The profile uses `profile-gitblock.svg`.
- The snake animation is not stored on `main`. The *Generate Snake* workflow builds it every 12 hours and publishes it to the `output` branch.

## Changing a quest

Each quest is a picture, so its text cannot be edited in the README. Replace the matching `px-quest-N.svg` and keep the same file name. The link that opens when someone clicks a quest is set in the README.
