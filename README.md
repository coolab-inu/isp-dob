# ISP DOB Validation

Hardware validation page for a disturbance observer (DOB) on a single-axis inertially stabilized platform: tracked rig videos, logged signals and a 3D replay, observer off against on.

- English: https://coolab-inu.github.io/isp-dob/
- 한국어: https://coolab-inu.github.io/isp-dob/ko/

The page is static. `index.html` (English by default) and `ko/index.html` (Korean by default) are the same page and share every other file: the two logged runs (`data.js`), per-frame video tracking of the two clips (`track.js`), the CAD model (`model.js`, the same bytes as `media/isp.glb`), the copy in both languages (`i18n.js`) and the clips and posters in `media/`. The language switch in the page works in place; `#ko` or `#en` in the address overrides the default.
