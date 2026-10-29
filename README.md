# LSN-ACCESS Access control systems: interactives

Interactive simulations for LSN-ACCESS (CBT Technology Institute, lesson). Each lesson has self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Canvas pages link to them through GitHub Pages.

Live site: https://luisleon-cbt.github.io/lsn-access/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| lesson1 | Access control systems | credential-path.html | design-the-door.html | wiring-trainer.html | ivms-programming.html |

## Publishing

1. Push this folder to the `main` branch of `luisleon-cbt/lsn-access`.
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://luisleon-cbt.github.io/lsn-access/lessonN/<file>.html`.

The pages load the CBT logo from `luisleon-cbt/items`, and GSAP, Three.js, and fonts from public CDNs. They still work if a CDN fails (a 2D view replaces the 3D one) and need no build step.
