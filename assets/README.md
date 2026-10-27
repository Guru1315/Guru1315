# Assets

The images used by the profile [README](../README.md). They are hand-built animated SVG files in a light editorial style (paper background, serif headlines, one red accent). They load through their `raw.githubusercontent.com` addresses, so **renaming or moving a file breaks the matching image on the profile**.

| File | Used for |
|---|---|
| `ed-hero.svg` | Top banner: big "Guru." title, rotating badge, cycling words (listens, sees, investigates, helps) |
| `ed-h-work.svg`, `ed-h-toolbox.svg`, `ed-h-focus.svg`, `ed-h-activity.svg`, `ed-h-stats.svg`, `ed-h-contact.svg` | Numbered section headings |
| `ed-work-1.svg` to `ed-work-7.svg` | Project rows, in order: AI Voice Customer Support, AI Health Agent, AI Fraud Investigation, AI Personal Agent, Saveetha Foodie Bot, Image Caption Generator, Resume Screening System |
| `ed-work-8.svg` | "See everything else" row linking to the repositories tab |
| `ed-marquee.svg` | Two rows of scrolling tool names |
| `ed-skills.svg` | Machine learning, data and tools lists, plus the "now learning" strip |
| `ed-focus.svg` | Four focus areas with small animated glyphs |
| `ed-statement.svg` | Quote with animated highlighter and the 7+ / 4 numbers |
| `ed-contact-linkedin.svg`, `ed-contact-email.svg`, `ed-contact-github.svg` | Contact rows (links are set in the README) |
| `ed-footer.svg` | Closing banner with scrolling outlined text |

## Related folders

- `../profile-3d-contrib/` holds the 3D contribution graphs, generated daily by the *GitHub-Profile-3D-Contrib* workflow. Do not edit them by hand. The profile uses `profile-green.svg` (light mode) and `profile-night-green.svg` (dark mode).
- The snake animation is not stored on `main`. The *Generate Snake* workflow builds it every 12 hours and publishes it to the `output` branch.

## Changing a project row

Each row is a picture, so its text cannot be edited in the README. Replace the matching `ed-work-N.svg` and keep the same file name. The link that opens when someone clicks a row is set in the README.
