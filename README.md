# 🏛️ The Sovereign Thesis Template

<div align="center">

![Engine](https://img.shields.io/badge/Engine-XeLaTeX-8E44AD?style=for-the-badge&logo=latex&logoColor=white)
![Layout](https://img.shields.io/badge/Layout-Two--Sides-D35400?style=for-the-badge)
![Typography](https://img.shields.io/badge/Typography-Classic__Elegant-27AE60?style=for-the-badge)
![Design](https://img.shields.io/badge/Design-Premium__Academic-2C3E50?style=for-the-badge)

</div>

An academic masterpiece deserves more than just standard margins and generic layouts. **The Sovereign** is a premium, professionally engineered XeLaTeX template crafted specifically for rigorous academic research, dissertations, and high-end book printing. 

Built on a timeless, symmetric **Two-Sides** layout, this template revives the golden ratio of classic book-binding while embracing modern typesetting power.

---

## 🎨 Design Philosophy & Features

* **📜 The Golden Ratio Layout:** Perfectly calculated asymmetric margins on single pages that seamlessly align into a gorgeous, balanced spread when printed and bound (Two-Sides).
* **🔤 Typographical Excellence via XeLaTeX:** Zero limitations on fonts. It is pre-configured to leverage advanced OpenType system fonts, ligatures, and pristine micro-typography.
* **🖋️ Academic Sophistication:** From running headers that adapt dynamically to chapters, to meticulously spaced footnotes, every element is designed to minimize visual clutter and maximize readability.
* **🧩 Modular Architecture:** No monolithic code. Your front matter, chapters, and bibliography are cleanly separated for an effortless writing experience.

---

## 📦 System Requirements

> [!WARNING]
> Because this template heavily relies on native system font loading and advanced modern packages, compiling it with standard `pdfLaTeX` will fail. You **must** use the **XeLaTeX** engine.

### Recommended Toolchain:
* **`xelatex`** — Core compiler for modern font mapping and rendering.
* **`biber`** — Next-generation bibliography processor for flawless citation management via `biblatex`.
* **`latexmk`** — Highly recommended to automate multiple compilation passes (Table of Contents, Cross-references, and Citations).

---

## 🚀 Quick Start Guide

To compile your thesis with its full index, glossary, and bibliography layout, simply run this command in your terminal:

```bash
latexmk -xelatex main.tex
