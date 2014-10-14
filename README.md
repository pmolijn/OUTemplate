OUTemplate
==========

Open Universiteit Latex Template

Using the template
------------------

This is the OU LaTeX template provided by Patrick Molijn. 
It is designed to work with all versions of LaTeX, but is primarily used with pdflatex and biber.
The document can be compiled with

  pdflatex report
  biber report
  makeglossaries report
  pdflatex report
  pdflatex report

This is equivalent to selecting 'pdfLaTeX+Biber+makeglossaries' or similar in your preferred  TeX
editing program.

A separate example document is available which generates a cover image (front,
back and spine). This document can be generated with

  pdflatex cover
  pdflatex cover

or simply with the 'pdfLaTeX' option in the TeX editing program.


Installation on Windows
-----------------------

The template has been tested to work with the most recent version
of MiKTeX at the time of this writing (2.9). The following packages are required
on top of a basic MiKTeX installation to make full use of the template:

  caption, fancyhdr, filehook, footmisc, fourier, l3kernel, l3packages,
  metalogo, mptopdf, ms, natbib, pgf, realscripts, tipa, titlesec, tocbibind,
  unicode-math, url, xcolor, xetex-def

Note that MiKTeX will generally automatically install these packages if they are
missing from your installation.



Installation on Linux (Debian/Ubuntu)
-------------------------------------

Recent versions of Debian, and derived distributions such as Ubuntu, use the TeX
Live system. Install the following packages to make full use of the this
template:

  texlive, texlive-fonts-extra, texlive-math-extra, texlive-lang-dutch
  (or texlive-lang-european), texlive-lang-english, texlive-latex-extra,
  texlive-xetex

