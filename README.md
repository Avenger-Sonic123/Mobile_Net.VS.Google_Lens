# MobileNet vs. Google Lens

A static case-study page comparing reported image-recognition results.

**Repository created:** 2022-07-21  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-07-21

## Features and implementation

- HTML comparison layout.
- Test-image and result sections.
- Qualitative conclusion recorded on the page.

## Technologies

HTML, CSS, Bootstrap, jQuery, p5.js, ml5.js.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`style.css`](style.css) | Page styling |

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Mobile_Net.VS.Google_Lens.git
cd Mobile_Net.VS.Google_Lens
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Open the page to read the recorded comparison.

## Current status and limitations

The repository does not run either model or contain a reproducible evaluation pipeline; the conclusion is a page observation, not a general accuracy benchmark.

---

Source reference: [`ae8daae2`](https://github.com/Avenger-Sonic123/Mobile_Net.VS.Google_Lens/tree/ae8daae28c7f3ad209e40c400de443ecbe53236d) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
