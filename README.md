# CleanEasy Beamer Theme

A clean and minimalist Beamer theme designed for professional and academic presentations.  
This theme separates style components into modular `.sty` files for flexibility and clarity.

---

## 🚀 How to Use

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

## 💡 Features

- ✅ Clean design suitable for scientific and professional presentations
- 🎨 Separated color/font definitions for easy customization
- 🔌 Modular components (title page, configuration settings)
- 🖼️ Ready-to-use logos

---

## 📚 Demo

The `sample.tex` file showcases how to use the theme. Modify title, sections, logos, and colors as needed.

---

## ✨ Credits

Designed and maintained by Jose P. Marchezi

---

## 📝 License

Free for academic and non-commercial use.
