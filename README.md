# Poster: Generative Design of Control Pulses for Magic State Preparation via Neural Quantum States

This repository contains the LaTeX source for an academic poster presented at the Isaac Newton Institute in October 2025.

**Author:** Alberto Berni, University of Southampton



## Project Overview

The poster presents a novel computational framework that leverages Neural Quantum States (NQS) and differentiable programming to automate Quantum Optimal Control (QOC). The central goal is to systematically discover high-fidelity control pulses required for preparing non-Clifford "magic states," a critical bottleneck in the development of fault-tolerant quantum computers.

The framework reframes the heuristic search for optimal control pulses as a systematic, gradient-based optimization problem, aiming to transform pulse engineering from a heuristic art into an automated science.

---

## Original Theme Documentation (Gemini)

This poster was created using the **Gemini** theme, a modern LaTeX beamerposter theme developed by Anish Athalye. The original documentation, including instructions for dependencies, usage, and customization, is preserved below for users who wish to adapt this template for their own work.

### Acknowledgements

We gratefully acknowledge Anish Athalye for creating and distributing the Gemini theme under the MIT License. The original project can be found on [GitHub](https://github.com/anishathalye/gemini).

### Gemini Theme README

Gemini is a modern LaTeX [beamerposter] theme.

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini-small.png">
</a>
</p>

If you're looking for a beamer presentation theme, take a look at [Auriga].

#### Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

#### Usage

1.  Copy the files in this repository (or clone the repository)
2.  In `poster.tex`, set up your paper size, column layout, and scale the content as necessary
3.  Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme` line in `poster.tex`, and theme the poster to your liking (optional, but highly recommended)
4.  Run `make` to build your poster

#### FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how to add an institution logo to the poster.

#### Themes

Gemini currently includes three color themes:

* `gemini` (default)
* `mit`
* `labsix`

The alternative themes are intended to be inspiration for you to make your own color theme. You're highly recommended to make your own color theme (it's really easy!) or use the default Gemini theme.

#### License

Copyright (c) 2018-2022 Anish Athalye. Released under the MIT License. See [LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ