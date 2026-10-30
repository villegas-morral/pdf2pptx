# pdf2pptx

**Utility to convert a PDF slideshow to Powerpoint PPTX. Fork of [pdf2pptx](https://github.com/kevinmcguinness/pdf2pptx)**

Renders each page as a PNG image and creates a Powerpoint 
slideshow from these images, which can also be edited using LibreOffice, Keynote, etc. You can then
use the presentation capabilities of your chosen app (videos, drawings, diagrams...) with slides created in LaTeX/Beamer.

Uses [PyMuPDF](https://github.com/pymupdf/PyMuPDF) and 
[python-pptx](https://github.com/scanny/python-pptx) to do the hard work.

## Usage

Open up a terminal in the folder containing the .pdf file. Running the following will create the .pptx file in the same folder.

```bash
pdf2pptx slides.pdf
```

Resolution is set to 300 dpi by default, and can be changed using adding ``-r n_dpi`` after ``pdf2pptx`` (where ``n_dpi`` is an integer).

Run `pdf2pptx --help` for more info on the command line interface.


## Installation

Make sure Python and pipx are installed. Then, run

```bash
pipx install git+https://github.com/villegas-morral/pdf2pptx
```
