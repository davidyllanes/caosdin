# Figures of "Temperature chaos is present in off-equilibrium spin-glass dynamics"

The scripts and the data needed to reproduce the figures on the article "Temperature chaos is present in off-equilibrium spin-glass dynamics" (https://arxiv.org/abs/2011.09419) are provided.

Each directory corresponds to one figure. Inside each directory you can find:

A gnuplot (.gpt) script of the figure.
A directory "data" with all the needed data for the figure.
A "data_information.txt" where the data files are explained.
A .pdf with the produced figure.
For running the scripts you need the Version 5.2 of Gnuplot and the pdflatex compiler. Inside the directory of any figure you can simply do

gnuplot fig1.gpt ; pdflatex fig1.tex

The corresponding fig1.pdf will be produced in that directory.
