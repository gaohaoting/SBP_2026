SBP-BRiMS 2026 / Springer LNCS camera-ready source bundle
Paper: Visual Attention is Not Memoryless (mTEAM_HON)

Contents
--------
mTEAM_HON.tex       Main LaTeX source
mTEAM_HON.bib       Bibliography
mTEAM_HON.pdf       Compiled PDF (pdflatex + bibtex)
llncs.cls           Springer LNCS document class
splncs04.bst        Bibliography style
Figures/            PNG figures referenced by \includegraphics

Build (from this folder)
------------------------
pdflatex -shell-escape mTEAM_HON
bibtex mTEAM_HON
pdflatex -shell-escape mTEAM_HON
pdflatex -shell-escape mTEAM_HON

Or run `make` from HON_paper/ if Makefile is kept alongside.

EasyChair
---------
Upload this zip if the system asks for source; upload mTEAM_HON.pdf separately if a PDF-only field is required.

Note: PDF built on 2026-07-26 is 12 pages including references.
