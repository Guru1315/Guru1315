# Assets

The images used by the profile [README](../README.md). They are all SVG files and are loaded from this folder using their `raw.githubusercontent.com` addresses, so **renaming or moving a file breaks the matching image on the profile**.

| File | Used for |
|---|---|
| `hero.svg` | Banner at the top of the profile |
| `divider.svg` | The line between sections (used 7 times) |
| `h-projects.svg` | "Projects" section heading |
| `card-1.svg` to `card-7.svg` | Project cards, in order: AI Voice Customer Support, AI Health Agent, AI Fraud Investigation, AI Personal Agent, Saveetha Foodie Bot, Image Caption Generator, Resume Screening System |
| `h-stack.svg` | "Tech Stack" heading |
| `h-focus.svg` | "Focus Areas" heading |
| `focus.svg` | Panel listing the focus areas (NLP, computer vision, voice AI, fraud and safety) |
| `h-graph.svg` | "3D Activity" heading |
| `h-stats.svg` | "GitHub Stats" heading |
| `h-contact.svg` | "Let's Connect" heading |
| `h-about.svg` | "About Me" heading |
| `devcard.svg` | The developer card under "About Me" |
| `footer.svg` | Closing image at the bottom |

## Related folders

- `../profile-3d-contrib/` holds the 3D contribution graphs. They are generated automatically by the *GitHub-Profile-3D-Contrib* workflow every day, so do not edit them by hand. The profile uses `profile-night-rainbow.svg`.
- The snake animation is not stored on the `main` branch. The *Generate Snake* workflow builds it every 12 hours and publishes it to the `output` branch.

## Changing a project card

Each card is a picture, so the text on it cannot be edited in the README. To change one, replace the matching `card-N.svg` file and keep the same file name. The link that opens when someone clicks a card is set in the main README.
