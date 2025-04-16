# CleanEasy Beamer Theme

A clean and minimalist Beamer theme designed for professional and academic presentations.  
This theme separates style components into modular `.sty` files for flexibility and clarity.

---

## �� Project Structure

```
CleanEasy_BeamerTheme/
├── beamercolorthemeCleanEasy.sty        # Custom color definitions
├── beamerfontthemeCleanEasy.sty         # Font settings
├── beamerinnerthemeCleanEasy.sty        # Inner theme elements
├── beamerthemeCleanEasy.sty             # Main theme file (includes the others)
├── configs/
│   ├── configs.tex                       # Global configurations (colors, layout options)
│   └── title_page.tex                   # Modular title page setup
├── logos/
│   ├── logo1.png                        # Logos for customization
│   ├── logo2.png
│   ├── logo3.png
│   └── logo4.png
├── reference.bib                        # Sample bibliography file
├── sample.tex                           # Demo presentation
└── README.md
```

---

## �� How to Use

1. Place all files in your working directory (or install to a local LaTeX path).
2. In your LaTeX document, load the theme with:

```latex
\documentclass{beamer}
\usetheme{CleanEasy}
```

3. (Optional) Include modular configurations:

```latex
\input{configs/configs.tex}
\input{configs/title_page.tex}
```

4. Compile with `pdflatex` or `latexmk`:

```bash
pdflatex sample.tex
```

---

## �� Features

- ✅ Clean design suitable for scientific and professional presentations
- �� Separated color/font definitions for easy customization
- �� Modular components (title page, configuration settings)
- ��️ Ready-to-use logos

---

## �� Demo

The `sample.tex` file showcases how to use the theme. Modify title, sections, logos, and colors as needed.

---

## ✨ Credits

Designed and maintained by [Your Name].  
Structure improved and documentation generated with assistance from ChatGPT.

---
## License

This project is released under the **Unlicense License**, granting you complete freedom to use, modify, and distribute the template. For more details, see the [LICENSE](./LICENSE) file.