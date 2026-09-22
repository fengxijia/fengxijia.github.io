# fengxijia.github.io

Personal site of Xijia Feng (冯茜嘉). Static, single page, no build step.

Everything the page needs ships in this repository: fonts under `assets/fonts/`,
three.js under `assets/js/`, images under `assets/img/`. Nothing is fetched from
a third-party CDN at runtime, so the page renders the same from mainland China.

The 3D parts run in the visitor's browser (WebGL via three.js). If WebGL is not
available, the paintings fall back to plain images and the page stays readable.
