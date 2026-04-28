# lucide-admonitions

A LaTeX package for rendering visually consistent admonition boxes with Lucide
icons and multilingual support.

## Features

- Customizable icons, colors, and titles
- Automatic translation of titles into multiple languages
- Compatible with standard LaTeX and KOMA-Script classes

## Installation

Install using your TeX distribution:

- TeX Live: `tlmgr install lucide-admonitions`
- MiKTeX: use the package manager

Or download the files and place them either:

- in your document directory, or
- in your local or user `texmf` tree

Then update the filename database if needed (`texhash` or `mktexlsr`).

## Usage

Load the package in your preamble:

```latex
\usepackage[<options>]{lucide-admonitions}
```

Use any of the predefined environments:

```latex
\begin{AdmonitionNote}[Custom title]
  ...
\end{AdmonitionNote}
```

## Options

- `titles` -- display the box type as a title
- `breakable` -- allow boxes to break across pages

Example:

```latex
\usepackage[titles,breakable]{lucide-admonitions}
```

## Predefined types

- Note
- Attention
- Caution
- Warning
- Danger
- Error
- Hint
- Important
- Tip
- Abstract
- Info
- Success
- Question
- Failure
- Bug
- Example
- Quote

## Customization

See the package documentation for details on modifying existing admonition
types or add your own ones.

## Acknowledgements

- Inspired by Zensical: https://zensical.org/docs/authoring/admonitions/
- Lucide icons: https://lucide.dev
- `lucide-icons` LaTeX package by Cédric Pierquet
- `tcolorbox` by Thomas F. Sturm
- `translations` by Clemens Niederberger
- `xcolor` by Uwe Kern
