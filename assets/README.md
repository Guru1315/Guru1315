# Assets

The images used by the profile [README](../README.md). They are all hand-built animated SVG files, loaded through their `raw.githubusercontent.com` addresses, so **renaming or moving a file breaks the matching image on the profile**.

| File | Used for |
|---|---|
| `hero.svg` | Top banner: aurora background, neural network, typing roles |
| `divider.svg` | Animated line between sections |
| `title-projects.svg`, `title-stack.svg`, `title-focus.svg`, `title-now.svg`, `title-activity.svg`, `title-stats.svg`, `title-connect.svg` | Numbered section headings |
| `card-1.svg` to `card-7.svg` | Project cards, in order: AI Voice Customer Support, AI Health Agent, AI Fraud Investigation, AI Personal Agent, Saveetha Foodie Bot, Image Caption Generator, Resume Screening System |
| `card-8.svg` | "More on GitHub" card linking to the repositories tab |
| `marquee.svg` | Two rows of scrolling tool pills |
| `focus.svg` | Four animated tiles: NLP, Computer Vision, Voice AI, Fraud & Safety |
| `now.svg` | Building / Learning / Studying panel and motto |
| `quote.svg` | Quote banner |
| `contact-linkedin.svg`, `contact-email.svg`, `contact-github.svg` | Contact buttons (links are set in the README) |
| `footer.svg` | Animated wave footer |

## Related folders

- `../profile-3d-contrib/` holds the 3D contribution graphs, generated daily by the *GitHub-Profile-3D-Contrib* workflow. Do not edit them by hand. The profile uses `profile-night-green.svg`.
- The snake animation is not stored on `main`. The *Generate Snake* workflow builds it every 12 hours and publishes it to the `output` branch.

## Changing a project card

Each card is a picture, so its text cannot be edited in the README. Replace the matching `card-N.svg` and keep the same file name. The link that opens when someone clicks a card is set in the README.
