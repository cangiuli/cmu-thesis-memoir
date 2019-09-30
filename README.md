# CMU thesis template for `memoir`

This is a LaTeX template for a thesis in Computer Science at CMU, for use with the excellent
[`memoir`](https://ctan.org/pkg/memoir) package. It began life as the [class
file](http://www.cs.cmu.edu/~dkoes/research/cmuthesis.cls) and
[template](http://www.cs.cmu.edu/~dkoes/research/cmuthesis_template.tex) hosted on David Koes's
website, but it seems that a Ship-of-Theseus situation occurred at some point during my hacking.

The included `cmutr.sty` was written by Matt Zekauskas, and produces a "CMU tech report"-compliant
title page. The font choices (Libertine and Inconsolata) are those of `acmart.sty`.

## Benefits

The `book` document class, like `article`, is intentionally simple. In contrast, `memoir` includes
bells and whistles you may find useful when writing a book (or thesis), including features found in
the `fancyhdr`, `subfigure`, `geometry`, and `epigraph` packages, among others.

I also include (and recommend) the `biblatex`, `microtype`, and `cleveref` packages. All of these,
especially `memoir`, have extensive documentation available on CTAN or via `texdoc`.
