# latex-tikz-beamer-linkedlists

Example slides diagraming linked list data structures using tikz in beamer latex.

The `linkedlist.tex` file contains a number examples of referring to
code in beamer slides and drawing linked list data structures using
tikz. A
[custom listing file](https://github.com/markroyer/latex-listings-eclipse)
was used for syntax markup.

The latex
[tikz-uml package](http://perso.ensta-paristech.fr/~kielbasi/tikzuml/var/files/html/web-tikz-uml-userguide.html)
was used to display a simple class diagram on a slide.

## Screenshots

The document shows a few techniques for displaying linked list data
scructures in latex documents using tikz.  Code listing markup and the
tikz-uml package is also shown on some slides.  A few of the diagrams
are shown below.

![Linkedlist](https://raw.githubusercontent.com/wiki/markroyer/latex-tikz-beamer-linkedlists/linkedlist1.png
"Linked list data structure")

![Linkedlist](https://raw.githubusercontent.com/wiki/markroyer/latex-tikz-beamer-linkedlists/linkedlistInsert1.png
"Linked list insert before")

![Linkedlist](https://raw.githubusercontent.com/wiki/markroyer/latex-tikz-beamer-linkedlists/linkedlistInsert2.png
"Linked list insert after")

![Linkedlist](https://raw.githubusercontent.com/wiki/markroyer/latex-tikz-beamer-linkedlists/linkedlistRemoveAt1.png
"Linked list remove at before")

![Linkedlist](https://raw.githubusercontent.com/wiki/markroyer/latex-tikz-beamer-linkedlists/linkedlistRemoveAt2.png
"Linked list remove at after")


## Setup

Make sure that you have the Debian `texlive` package installed.

## Usage

You can build the PDF document by typing

```
make
```

in the root of the repository. The file `linkedlist.pdf` is the
generated output.

Typing

```
make clean
```

will remove all generated files.

## License

The project is licensed under the terms of the
[GPL3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.
