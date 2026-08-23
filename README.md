# 📄 cv-latex-simple-en

> Personal CV of **Dmytro Palahin** — Data Engineer & MLOps student  
> 🎓 Sup Galilée School of Engineering, Paris, France

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Built with LaTeX](https://img.shields.io/badge/Built%20with-LaTeX-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 🖼️ Preview

![CV Preview](img/cv-dmytro-palahin-en-q.png)

![CV Preview](img/cv-dmytro-palahin-en-d.png)

---

## ⚙️ Build

Make sure you have a LaTeX distribution installed (e.g. [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/)) with `fontawesome5`, `paracol`, and `latexmk`.

```sh
latexmk -pdf -auxdir=/tmp/latex-build -outdir=. cv-dmytro-palahin-en-q.tex

latexmk -pdf -auxdir=/tmp/latex-build -outdir=. cv-dmytro-palahin-en-d.tex
```

## 🤝 Contributing

This is a personal CV repository — external contributions are not expected.
Feel free to fork and adapt the template for your own use.
See CONTRIBUTING.md for details.

## 📋 Changelog

See [CHANGELOG.md](CHANGELOG.md) for all notable changes.

## 📜 License

This project is licensed under the MIT License.
