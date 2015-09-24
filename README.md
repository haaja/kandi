Kandidaatintutkielma
====================

A work in progress.

tktltiki2 LaTeX class
======================

This is a thesis and course report LaTeX class following the conventions at the Computer Science Department of the University of Helsinki. The class is intended to be used for the bachelor's thesis, master's thesis and various course and seminar reports.

The tktltiki2 class is appearance-wise largely based on the older tktltiki class, but nearly all features have been rewritten to make it less likely to break. Some of the features, most notably the automatic appendix page counting, are not included at least in the current version. The tktltiki-specifix bibtex style has been dropped in favour of babelbib package included in most recent LaTeX installations.

Compiling
---------

Re-compile everything as needed:

    rubber -Wall template-en.tex

Clean up everything:

    rubber --clean template-en.tex
