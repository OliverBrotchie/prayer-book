<div align="center">

  <h1><code>Prayer Book</code></h1>

<strong>A new edition of the prayer book for Archdiocese of Thyateira and Great Britan.</strong>

</div>

## Project Structure 📋

- `book.tex` The main LaTeX file that compiles the prayer book.
- `sections` Contains the different services included in the book.
- `commands/prayers.tex` Contains prayers that are commonly repeated or used in more than one service.

## How to Compile 💻

To compile the prayer book:

1. Install LaTeX.
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

## Installing LaTeX 💡

To use this project, you need to [install a LaTeX distribution](https://www.latex-project.org/get/).

## Learning LaTeX 📖

If you're new to LaTeX, here are some great resources to get started:

- [Overleaf's Introduction to LaTeX](https://www.overleaf.com/learn/latex/Learn\_LaTeX\_in\_30\_minutes)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)