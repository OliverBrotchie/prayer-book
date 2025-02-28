<div align="center">

  <h1><code>Prayer Book</code></h1>

<strong>
This repository contains the LaTeX source code for the new edition of Holy Archdiocese of Thyateira and Great Britain's prayer book.</strong>

</div>

 The transaltions used are primarly sourced from the late Fr Ephrem Lash.

## Project Structure

- `book.tex` The main LaTeX file that compiles the prayer book.
- `/sections/` Contains all the different services included in the book.
- `/commands/prayers.tex` Contains prayers that are commonly repeated or used in more than one service.

## How to Compile

To compile the LaTeX document, follow these steps:

1. Install LaTeX (see installation guide below).
2. Clone this repository:
   ```sh
   git clone https://github.com/OliverBrotchie/prayer-book
   cd prayer-book
   ```
3. Compile the document using `pdflatex`:
   ```sh
   pdflatex -halt-on-error book.tex
   ```
   Alternatively, you can use an editor like Overleaf, TeXworks, or TeXShop.

## Installing LaTeX

To use this project, you need to install a LaTeX distribution:

- **Download LaTeX**: [https://www.latex-project.org/get/](https://www.latex-project.org/get/)
- Recommended distributions:
  - **TeX Live** (Windows/Linux/macOS)
  - **MiKTeX** (Windows)
  - **MacTeX** (macOS)

## Learning LaTeX

If you're new to LaTeX, here are some great resources to get started:

- **Overleaf's Introduction to LaTeX**: [https://www.overleaf.com/learn/latex/Learn\_LaTeX\_in\_30\_minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
- **LaTeX Wikibook**: [https://en.wikibooks.org/wiki/LaTeX](https://en.wikibooks.org/wiki/LaTeX)