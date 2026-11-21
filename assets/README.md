# Assets

Images used by the profile [README](../README.md). They are loaded by relative path, so **renaming or moving one breaks it on the profile**.

| File | Used for |
|---|---|
| `intro.webp` | Top intro: a white 3D cat pops onto a stage, dances, then steps aside and waves while "Hi there, I'm Guru Charan" appears. An 8-second looping animated WebP (960×480, 15 fps), rendered from a three.js scene. |
| `work-perfume.jpg`, `work-lays.jpg`, `work-movade.jpg`, `work-arena.jpg` | Screenshots on the "Immersive web" cards (480×300). |
| `banner.svg` | The old typing-line banner. No longer shown; kept in case it is wanted back. |

GitHub only shows images in a README (no scripts or video players), which is why the intro is an animated WebP rather than a live 3D scene. To change the intro, re-render the scene and replace `intro.webp` with a file of the same name.

## Related folders

- `../profile-3d-contrib/` holds 3D contribution graphs generated daily by the *GitHub-Profile-3D-Contrib* workflow. The README shows `profile-night-rainbow.svg`.
- The *Generate Snake* workflow publishes a snake animation to the `output` branch every 12 hours. The README shows `github-snake-dark.svg` from that branch.
