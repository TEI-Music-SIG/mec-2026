# First Example: Reger

An example to display TEI files with a section of **musical notation** and **formula-like functional chord notation**.

Live Demo: https://tei-music-sig.github.io/mec-2026/example-reger/

### How it works

- see https://github.com/TEI-Music-SIG/examples/
- a little JavaScript function manages the document selection
- MathJax is triggered when a `<formula>` element in TEI contains `@rend="tex"`.
