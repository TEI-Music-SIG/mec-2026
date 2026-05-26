# First Example: Reger

A minimal example to display TEI files with multiple sections of musical notation and **formulas** within. Similar to [ceteicean-verovio](../ceteicean-verovio), but with additional TeX support using MathJax.

Live Demo: https://tei-music-sig.github.io/mec-2026/example-reger/

### How it works

- see https://github.com/TEI-Music-SIG/examples/
- a little JavaScript function manages the document selection
- MathJax is triggered when a `<formula>` element in TEI contains `@rend="tex"`.
