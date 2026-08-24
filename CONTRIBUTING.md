# Contributing

This repository contains my personal CV - external contributions are not expected.

If you want to reuse the structure or adapt the template for your own CV, feel free to **fork** the repository and modify it freely under the [MIT License](LICENSE).

---

## 🔧 Local development

### Prerequisites

- LaTeX distribution: [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)
- Required packages: `fontawesome5`, `paracol`, `tikz`, `tcolorbox`, `latexmk`

### Build

```sh
latexmk -pdf -auxdir=/tmp/latex-build -outdir=. src/en/cv-dmytro-palahin-en-d.tex
```

---

## 🚀 Release workflow

```sh
# 1. Edit your .tex file(s)
# 2. Commit
git add .
git commit -m "feat: <description>"
git push

# 3. When ready to publish - create a tag
git tag v1.4.0
git push origin v1.4.0
# -> GitHub Actions builds all PDFs and creates a Release automatically
```

---

## 📐 Naming conventions

| Suffix | Meaning |
| :--------: | :---------: |
| `-d` | Data Engineer / MLOps focus |
| `-q` | Quantitative Researcher focus |
| `-tr` | Trading focus |
| `-simple` | Simplified single-column version |
