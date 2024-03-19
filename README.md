Certainly, I can help you adjust the template for Ludwig Maximilian University of Munich (LMU Munich). Here's an adaptation:

---

# Gemini LMU Munich Version [![Build Status](https://github.com/anishathalye/gemini/workflows/CI/badge.svg)](https://github.com/anishathalye/gemini/actions?query=workflow%3ACI)

This is an unofficial adaptation of the modern LaTeX [beamerposter] theme, Gemini, tailored for Ludwig Maximilian University of Munich (LMU Munich).

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/maxmlang/assets/master/lmu-poster.png">
</a>
</p>

For a general-purpose beamer presentation theme, see [Auriga].

## LMU Munich Customizations

* Integrated LMU Munich branding guidelines
* Example templates featuring the LMU Munich color scheme and logo placement
* Additional font support to match LMU Munich's branding (where applicable)

## Dependencies

* A TeX installation that includes [LuaTeX]
    * `latexmk` is needed for using the provided `Makefile`
* LaTeX package dependencies including beamerposter (typically part of your TeX installation, available on [CTAN] if not)
* Fonts recommended by LMU Munich's branding guidelines, available under Open Font License

## Usage

1. Copy or clone the files from this repository

1. Configure `poster.tex` with your desired paper size, column layout, and scale adjustments as needed

1. Customize `beamercolorthemegemini.sty` by copying it and modifying the `\usecolortheme` line in `poster.tex` to theme your poster to LMU Munich's branding (optional but recommended for university-related presentations)

1. Use `make` to compile your poster

## FAQ

For common questions, such as adding an institution logo or customizing the color theme further, consult the [FAQ] in the Wiki.

## Themes

The LMU Munich version includes several color themes suitable for various types of presentations:

* `gemini` (default)
* `lmu` (customized for LMU Munich branding)
* `mit`
* `labsix`

You're encouraged to create your own color theme or use the `lmu` theme for presentations associated with the University.

## Design Goals

* **Minimal**: Focuses on readability and simplicity.
* **Batteries Included**: Ready to use with minimal setup.
* **Easy Theming**: Simplified process to create or modify themes.

## Contributing

Contributions such as bug reports, new themes, and enhancements are welcome! Design is subjective, so early feedback through issues or pull requests is encouraged.

## Disclaimer
This version of the Gemini LaTeX beamerposter theme, adapted for Ludwig Maximilian University of Munich (LMU Munich), is an unofficial modification and not endorsed by or affiliated with LMU Munich. It has been created to assist students, faculty, and researchers in creating presentations that align with the visual identity of LMU Munich. Users should ensure compliance with LMU Munich's branding guidelines when using this theme. The creators of this theme are not responsible for any misuse or violations of LMU Munich's branding policies.

## License

Copyright (c) 2018-2022 Anish Athalye. This unofficial LMU Munich version is released under the MIT License. See [LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ

