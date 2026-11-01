Ball Game AI Lab v4.0 — startup dependency fix

This package adds the missing local jQuery dependency required by gamelab-api.js.
The index.html now loads jquery.min.js before gamelab-api.js.

For GitHub Pages:
- Upload the CONTENTS of this ZIP into the repository root (not the ZIP itself).
- Preserve the assets/ folder and its contents. Do not upload the individual images into the repository root.
- The repository root should contain index.html, jquery.min.js, gamelab-api.js, p5.js, p5.play.js, code.js, gamelab.css, and the assets/ folder.
- In Settings > Pages, deploy from the intended branch and /(root).

This fixes the specific "$ is not defined" startup error. It does not establish that the full game or AI training has been tested in the older computer's browser.
