# CV Repository

My (Matthias Hutter) repository contains two LaTeX CV variants:

- `cv-global.tex` / `cv-global.pdf`  
  ATS-friendly international version (no photo, minimal personal data).
- `cv-dach.tex` / `cv-dach.pdf`  
  DACH version (photo + local personal details format).

## Build

```bash
pdflatex -interaction=nonstopmode -halt-on-error cv-global.tex
pdflatex -interaction=nonstopmode -halt-on-error cv-dach.tex
```

## Assets

- `crop.jpg`: current profile image used in `cv-dach.tex`
- `crop-original.jpg`: backup of the uncropped source image
