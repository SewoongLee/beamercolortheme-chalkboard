# Chalkboard color theme for Beamer

Version 0.1.0 (2026-10-15)

A chalkboard-inspired dark green color theme for Beamer, with warm off-white
text and yellow, blue, and pink accents. It styles titles, palettes, blocks,
and projected items, and disables shadows on blocks and the title page.

## Quick start

Copy `beamercolorthemechalkboard.sty` beside your presentation and compile:

```latex
\documentclass{beamer}
\usetheme{Madrid}
\usecolortheme{chalkboard}
\begin{document}
\begin{frame}{Hello}
  Normal text, \alert{an alert}, and $E=mc^2$.
\end{frame}
\end{document}
```

Load the color theme after the main theme. No theme options are provided.
Beamer is required; no extra fonts or external graphics are needed. The
package uses the color facilities supplied by Beamer. For a persistent local
installation, place the style file in
`TEXMFHOME/tex/latex/beamercolorthemechalkboard/` (find TEXMFHOME with
`kpsewhich -var-value=TEXMFHOME`). Overleaf users can upload the style file
beside their main `.tex` file.

## Documentation and example

Read `beamercolorthemechalkboard-doc.pdf` and `chalkboard-example.pdf`.
Build each PDF by running pdfLaTeX twice on its corresponding `.tex` file
from this directory. The example uses Madrid; the theme also works with
the default Beamer theme. Other themes may override particular settings.

This is primarily a color theme, but it also makes projected item labels
bold, selects rounded blocks without shadows, and selects the default
rounded title page without shadows. It does not select ball-shaped list
markers; those are chosen by the main or inner theme. Load your own template
or font customizations after the color theme to override these choices.
Dark backgrounds also apply in handout mode; there is no light/print option.
Test readability on the projector and in the lighting used for your talk.

## Author and support

Sewoong Lee <samuel27@illinois.edu>  
Author profile: https://github.com/SewoongLee

## License

Copyright 2026 Sewoong Lee. Distributed under the LaTeX Project Public
License version 1.3c or, at your option, any later version.
Maintenance status: maintained. Current Maintainer: Sewoong Lee.
See `LICENSE` for the work's file list and license URL.

## Changes

- 0.1.0 (2026-10-15): Initial packaged release of the Chalkboard color theme.
