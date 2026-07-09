# 🏛️ Elegant Classic Thesis Template

<div align="center">

![Template](https://img.shields.io/badge/TEMPLATE-THESIS-8E44AD?style=for-the-badge)
![Engine](https://img.shields.io/badge/ENGINE-XELATEX-34495E?style=for-the-badge)
![Layout](https://img.shields.io/badge/LAYOUT-TWO__SIDES-D35400?style=for-the-badge)
![Style](https://img.shields.io/badge/STYLE-CLASSIC__ELEGANT-27AE60?style=for-the-badge)

</div>

Do you care in the slightest about what your readers think about your document, and by proxy about you and your competence level? If yes, then this classy, typographically professional layout and structured, clear, and revealing content can only help. This template tries to aid you in both of these endeavors.

---

## ✨ Template Features

* 🔤 **Full XeLaTeX Support:** Native support for professional system fonts and complex typography.
* 📖 **Classic Two-Sided Layout:** Balanced margins and symmetric grids tailored for elegant, high-quality printing.
* 📌 **Clean Code Structure:** Well-organized files with plenty of comments to help you easily customize the template to your needs.
* 📜 **Refined Page Numbering:** Page numbers and running headers perfectly positioned for an academic look.

---

## 📦 Software Dependencies

> [!WARNING]
> To properly build the document, the template requires a modern **TeX Live** or **MiKTeX** distribution to avoid missing package errors.

### LaTeX build tools:
* `xelatex` - The core compiler used for handling modern fonts and layouts.
* `latexmk` - Automated build tool to handle references, indexes, and glossaries seamlessly.
* `biber` - Bibliography processing engine utilized by `biblatex`.

---

## 🚀 Getting Started

To compile the document, ensure all dependencies are installed, then run the following command in the root directory:

```bash
latexmk -xelatex main.tex
