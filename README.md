# Ahmed Zaafouri — Portfolio

Personal portfolio of Ahmed Zaafouri, Networks & Telecommunications engineering student at INSAT Tunis.

- `index.html` — the site (FR/EN, light/dark theme, no build step)
- `cv/cv.html` — source of the CV; `cv/Ahmed-Zaafouri-CV.pdf` — exported PDF
- `assets/` — images

Live: https://ahmedzaafouri.github.io

To regenerate the PDF after editing `cv/cv.html`:

```bash
chrome --headless=new --no-pdf-header-footer --print-to-pdf=cv/Ahmed-Zaafouri-CV.pdf cv/cv.html
```
