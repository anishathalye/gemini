# Gemini [![Build Status](https://github.com/anishathalye/gemini/actions/workflows/ci.yml/badge.svg)](https://github.com/anishathalye/gemini/actions/workflows/ci.yml)

Gemini is a modern LaTeX [beamerposter] theme.

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-gemini-small.png">
</a>
</p>

If you're looking for a beamer presentation theme, take a look at [Auriga].

## Dependencies

- A TeX installation that includes [LuaTeX]
    - You also need `latexmk` if you want to use the provided `Makefile`
- LaTeX package dependencies including beamerposter (these usually come with your TeX installation, but if not, you can get them from [CTAN])
- [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme` line in `poster.tex`, and theme the poster to your liking (optional, but highly recommended)

1. Run `make` to build your poster

## FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how to add an institution logo to the poster.

## Themes

Gemini includes several color themes, and it's also easy to make your own. Gemini has three built-in themes:

- `gemini`, default
- `mit` ([Massachusetts Institute of Technology](https://mit.edu))
- `labsix` ([LabSix](https://www.labsix.org/))

The community has also contributed a number of themes:

- `dart` ([Dartmouth College](https://dartmouth.edu))
- `umich` ([University of Michigan](https://umich.edu/))
- `bristol` ([University of Bristol](https://www.bristol.ac.uk/))
- `warwick` ([University of Warwick](https://warwick.ac.uk/))

If you create a Gemini theme, feel free to send a pull request to add it here!

### MIT theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-mit.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-mit-small.png">
</a>
</p>

### LabSix theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-labsix.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/assets/master/gemini/poster-labsix-small.png">
</a>
</p>

## Design goals

- **Minimal**: clean and easy to read, so that the emphasis is on the content
- **Batteries included**: works and looks good out of the box
- **Easy theming**: easy to create and use a new color theme

## Contributing

Contributions to Gemini such as bug reports, new themes, and new poster components are greatly appreciated! Given the subjective nature of design, you're encouraged to open an issue or pull request early to get feedback before investing a lot of time in implementing a new feature.

## License

Copyright (c) Anish Athalye. Released under the MIT License. See [LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Auriga]: https://github.com/anishathalye/auriga
[LuaTeX]: http://www.luatex.org/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
